---
UID: NF:tapi3if.ITTAPI.SetAssistedTelephonyPriority
title: ITTAPI::SetAssistedTelephonyPriority (tapi3if.h)
description: The SetAssistedTelephonyPriority method sets the application priority to handle assisted telephony requests.
helpviewer_keywords: ["ITTAPI interface [TAPI 2.2]","SetAssistedTelephonyPriority method","ITTAPI.SetAssistedTelephonyPriority","ITTAPI::SetAssistedTelephonyPriority","SetAssistedTelephonyPriority","SetAssistedTelephonyPriority method [TAPI 2.2]","SetAssistedTelephonyPriority method [TAPI 2.2]","ITTAPI interface","_tapi3_ittapi_setassistedtelephonypriority","tapi3.ittapi_setassistedtelephonypriority","tapi3if/ITTAPI::SetAssistedTelephonyPriority"]
old-location: tapi3\ittapi_setassistedtelephonypriority.htm
tech.root: tapi3
ms.assetid: 446fd541-30af-45de-85fa-d6655317362c
ms.date: 12/05/2018
ms.keywords: ITTAPI interface [TAPI 2.2],SetAssistedTelephonyPriority method, ITTAPI.SetAssistedTelephonyPriority, ITTAPI::SetAssistedTelephonyPriority, SetAssistedTelephonyPriority, SetAssistedTelephonyPriority method [TAPI 2.2], SetAssistedTelephonyPriority method [TAPI 2.2],ITTAPI interface, _tapi3_ittapi_setassistedtelephonypriority, tapi3.ittapi_setassistedtelephonypriority, tapi3if/ITTAPI::SetAssistedTelephonyPriority
req.header: tapi3if.h
req.include-header: Tapi3.h
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
req.lib: Uuid.lib
req.dll: Tapi3.dll
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - ITTAPI::SetAssistedTelephonyPriority
 - tapi3if/ITTAPI::SetAssistedTelephonyPriority
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Tapi3.dll
api_name:
 - ITTAPI.SetAssistedTelephonyPriority
---

# ITTAPI::SetAssistedTelephonyPriority


## -description

The 
<b>SetAssistedTelephonyPriority</b> method sets the application priority to handle assisted telephony requests.

## -parameters

### -param pAppFilename [in]

Pointer to a <b>BSTR</b> containing the name of the application.

### -param fPriority [in]

Set to VARIANT_FALSE to disable, VARIANT_TRUE to enable.

## -returns

This method can return one of these values.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
Method succeeded.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_OUTOFMEMORY</b></dt>
</dl>
</td>
<td width="60%">
Insufficient memory exists to perform the operation.

</td>
</tr>
</table>

## -remarks

The application must use 
<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/oleauto/nf-oleauto-sysallocstring">SysAllocString</a> to allocate memory for the <i>pAppFilename</i> parameter and use 
<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/oleauto/nf-oleauto-sysfreestring">SysFreeString</a> to free the memory when the variable is no longer needed.

## -see-also

<a href="https://docs.microsoft.com/windows/desktop/api/tapi3if/nf-tapi3if-itbasiccallcontrol-handoffindirect">ITBasicCallControl::HandoffIndirect</a>



<a href="https://docs.microsoft.com/windows/desktop/api/tapi3if/nn-tapi3if-ittapi">ITTAPI</a>



<a href="https://docs.microsoft.com/windows/desktop/Tapi/tapi-object">TAPI Object</a>

