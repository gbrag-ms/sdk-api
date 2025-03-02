---
UID: NF:directxmath.XMQuaternionSlerp
title: XMQuaternionSlerp function (directxmath.h)
description: Interpolates between two unit quaternions, using spherical linear interpolation.
helpviewer_keywords: ["Use DirectX..XMQuaternionSlerp","XMQuaternionSlerp","XMQuaternionSlerp method [DirectX Math Support APIs]","dxmath.xmquaternionslerp"]
old-location: dxmath\xmquaternionslerp.htm
tech.root: dxmath
ms.assetid: M:Microsoft.directx_sdk.quaternion.XMQuaternionSlerp(XMVECTOR,XMVECTOR,float)
ms.date: 12/05/2018
ms.keywords: Use DirectX..XMQuaternionSlerp, XMQuaternionSlerp, XMQuaternionSlerp method [DirectX Math Support APIs], dxmath.xmquaternionslerp
req.header: directxmath.h
req.include-header: 
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
 - XMQuaternionSlerp
 - directxmath/XMQuaternionSlerp
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - DirectXMath.h
api_name:
 - XMQuaternionSlerp
---

# XMQuaternionSlerp function


## -description

Interpolates between two unit quaternions, using spherical linear interpolation.

## -parameters

### -param Q0 [in]

Unit quaternion to interpolate from.

### -param Q1 [in]

Unit quaternion to interpolate to.

### -param t [in]

Interpolation control factor.

## -returns

Returns the interpolated quaternion. If <i>Q0</i> and <i>Q1</i> are not unit quaternions, the resulting
       interpolation is undefined.

## -remarks

The DirectXMath quaternion functions use an XMVECTOR 4-vector to represent quaternions, 
    where the X, Y, and Z components are the vector part and the W component is the scalar part.

When <i>t</i> is 0.0f, the function returns <i>Q0</i>. When <i>t</i> is 1.0f, the function returns
   <i>Q1</i>.

<h3><a id="Platform_Requirements"></a><a id="platform_requirements"></a><a id="PLATFORM_REQUIREMENTS"></a>Platform Requirements</h3>
Microsoft Visual Studio 2010 or Microsoft Visual Studio 2012 with the Windows SDK for Windows 8. Supported for Win32 desktop apps, Windows Store apps, and Windows Phone 8 apps.

## -see-also

<a href="https://docs.microsoft.com/windows/desktop/dxmath/ovw-xnamath-reference-functions-quaternion">DirectXMath Library Quaternion Functions</a>



<a href="https://docs.microsoft.com/windows/desktop/api/directxmath/nf-directxmath-xmquaternionslerpv">XMQuaternionSlerpV</a>

