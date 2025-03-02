---
UID: NF:directxmath.XMVectorSwizzle
title: XMVectorSwizzle function (directxmath.h)
description: Swizzles a vector.
helpviewer_keywords: ["Use DirectX..XMVectorSwizzle","XMVectorSwizzle","XMVectorSwizzle method [DirectX Math Support APIs]","dxmath.xmvectorswizzle"]
old-location: dxmath\xmvectorswizzle.htm
tech.root: dxmath
ms.assetid: M:Microsoft.directx_sdk.component-wise.XMVectorSwizzle(XMVECTOR,uint32_t,uint32_t,uint32_t,uint32_t)
ms.date: 12/05/2018
ms.keywords: Use DirectX..XMVectorSwizzle, XMVectorSwizzle, XMVectorSwizzle method [DirectX Math Support APIs], dxmath.xmvectorswizzle
req.header: directxmath.h
req.include-header: DirectXMath.h
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: Use DirectX.
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - XMVectorSwizzle
 - directxmath/XMVectorSwizzle
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - directxmathvector.inl
api_name:
 - XMVectorSwizzle
---

# XMVectorSwizzle function


## -description

Swizzles a vector.

## -parameters

### -param V [in]

Vector to swizzle.

### -param E0 [in]

Index that describes which component of <i>V</i> to place in the x-component of the swizzled vector. A value of 0
        selects the x-component, 1 selects the y-component, 2 selects the z-component, and 3 selects the w-component.

### -param E1 [in]

Index that describes which component of <i>V</i> to place in the y-component of the swizzled vector. A value of 0
        selects the x-component, 1 selects the y-component, 2 selects the z-component, and 3 selects the w-component.

### -param E2 [in]

Index that describes which component of <i>V</i> to place in the z-component of the swizzled vector. A value of 0
        selects the x-component, 1 selects the y-component, 2 selects the z-component, and 3 selects the w-component.

### -param E3 [in]

Index that describes which component of <i>V</i> to place in the w-component of the swizzled vector. A value of 0
        selects the x-component, 1 selects the y-component, 2 selects the z-component, and 3 selects the w-component.

## -returns

Returns the swizzled <a href="https://docs.microsoft.com/windows/desktop/dxmath/xmvector-data-type">XMVECTOR</a>.

## -remarks

The following code demonstrates how this function might be used.


```
XMVECTOR v = XMVectorSet( 10.0f, 20.0f, 30.0f, 40.0f );
XMVECTOR result = XMVectorSwizzle(v, 3, 3, 0, 2 );
```


The swizzled vector (<i>result</i>) will be &lt;40.0f, 40.0f, 10.0f, 30.0f&gt;.

<code>XM_SWIZZLE_X</code>, <code>XM_SWIZZLE_Y</code>, <code>XM_SWIZZLE_Z</code>, and <code>XM_SWIZZLE_W</code> are constants which 
   evaluate to 0, 1, 2, and 3 respectively for use with <b>XMVectorSwizzle</b>. 
   This is identical to <code>XM_PERMUTE_0X</code>, <code>XM_PERMUTE_0Y</code>, <code>XM_PERMUTE_0Z</code>, and <code>XM_PERMUTE_0W</code>.

For the case of constant indices (E0, E1, E2, E3), it is much more efficent to use the template form of <a href="https://docs.microsoft.com/windows/desktop/dxmath/xmvectorswizzle-template">XMVectorSwizzle</a>:


```

template<uint32_t SwizzleX, uint32_t SwizzleY, uint32_t SwizzleZ, uint32_t SwizzleW>
    XMVECTOR XMVectorSwizzle(FXMVECTOR V)

Example: XMVectorSwizzle< 3, 3, 0, 2>(v);
   
```


<h3><a id="Platform_Requirements"></a><a id="platform_requirements"></a><a id="PLATFORM_REQUIREMENTS"></a>Platform Requirements</h3>
Microsoft Visual Studio 2010 or Microsoft Visual Studio 2012 with the Windows SDK for Windows 8. Supported for Win32 desktop apps, Windows Store apps, and Windows Phone 8 apps.

## -see-also

<a href="https://docs.microsoft.com/windows/desktop/dxmath/ovw-xnamath-reference-functions-vector-component-wise">Component-Wise Vector Functions</a>



<a href="https://docs.microsoft.com/windows/desktop/api/directxmath/nf-directxmath-xmvectorpermute">XMVectorPermute</a>

