---
UID: NF:immdev.ImmGetStatusWindowPos
title: ImmGetStatusWindowPos function (immdev.h)
description: Retrieves the position of the status window.
helpviewer_keywords: ["ImmGetStatusWindowPos","ImmGetStatusWindowPos function [Internationalization for Windows Applications]","_win32_ImmGetStatusWindowPos","imm/ImmGetStatusWindowPos","intl.immgetstatuswindowpos"]
old-location: intl\immgetstatuswindowpos.htm
tech.root: Intl
ms.assetid: 785d8523-14a7-4443-8326-34ca197b1cff
ms.date: 12/05/2018
ms.keywords: ImmGetStatusWindowPos, ImmGetStatusWindowPos function [Internationalization for Windows Applications], _win32_ImmGetStatusWindowPos, imm/ImmGetStatusWindowPos, intl.immgetstatuswindowpos
req.header: immdev.h
req.include-header: Immdev.h, Windows.h
req.target-type: Windows
req.target-min-winverclnt: Windows XP [desktop apps only],East Asian language support installed.
req.target-min-winversvr: Windows Server 2003 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Imm32.lib
req.dll: Imm32.dll
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - ImmGetStatusWindowPos
 - immdev/ImmGetStatusWindowPos
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - DllExport
api_location:
 - Imm32.dll
api_name:
 - ImmGetStatusWindowPos
---

# ImmGetStatusWindowPos function


## -description

Retrieves the position of the status window.

## -parameters

### -param HIMC [in]

Handle to the input context.

### -param lpptPos [out]

Pointer to a <a href="https://docs.microsoft.com/previous-versions/dd162805(v=vs.85)">POINT</a> structure in which the function retrieves the position coordinates. These are screen coordinates, relative to the upper left corner of the screen.

## -returns

Returns a nonzero value if successful, or 0 otherwise.

## -see-also

<a href="https://docs.microsoft.com/windows/desktop/Intl/input-method-manager">Input Method Manager</a>



<a href="https://docs.microsoft.com/windows/desktop/Intl/input-method-manager-functions">Input Method Manager Functions</a>

