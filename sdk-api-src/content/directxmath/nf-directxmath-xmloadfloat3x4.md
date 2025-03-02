---
UID: NF:directxmath.XMLoadFloat3x4
title: XMLoadFloat3x4
ms.date: 04/23/2020
description: Loads an [**XMFLOAT3X4**](/windows/win32/api/directxmath/ns-directxmath-xmfloat3x4) into an [**XMMATRIX**](/windows/win32/api/directxmath/ns-directxmath-xmmatrix).
tech.root: dxmath
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
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
f1_keywords:
 - XMLoadFloat3x4
 - directxmath/XMLoadFloat3x4
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
 - XMLoadFloat3x4
---

## -description

Loads an [**XMFLOAT3X4**](/windows/win32/api/directxmath/ns-directxmath-xmfloat3x4) into an [**XMMATRIX**](/windows/win32/api/directxmath/ns-directxmath-xmmatrix).

## -parameters

### -param pSource

Type: **const [XMFLOAT3X4](/windows/win32/api/directxmath/ns-directxmath-xmfloat3x4) \*** 

Pointer to the constant [**XMFLOAT3X4**](/windows/win32/api/directxmath/ns-directxmath-xmfloat3x4) structure to load. This argument must point to cached memory.

## -returns

Type: **[XMMATRIX](/windows/win32/api/directxmath/ns-directxmath-xmmatrix)**

An [**XMMATRIX**](/windows/win32/api/directxmath/ns-directxmath-xmmatrix) loaded with the data from the *pSource* argument.

This function performs a partial load of the returned **XMMATRIX**. For more info, see [Getting started (DirectXMath)](/windows/win32/dxmath/pg-xnamath-getting-started).

## -remarks

[**XMFLOAT3X4**](/windows/win32/api/directxmath/ns-directxmath-xmfloat3x4) is a row-major form of the matrix. **XMLoadFloat3x4** could be used to read column-major data, but that would then need to be transposed with [XMMatrixTranspose](/windows/win32/api/directxmath/nf-directxmath-xmmatrixtranspose) before use in other [**XMMATRIX**](/windows/win32/api/directxmath/ns-directxmath-xmmatrix) functions.

## -see-also

[DirectXMath Library vector load functions](/windows/desktop/dxmath/ovw-xnamath-reference-functions-load)

