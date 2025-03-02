---
UID: NF:dvbsiparser.IDVB_BAT.RegisterForNextTable
title: IDVB_BAT::RegisterForNextTable (dvbsiparser.h)
description: This topic applies to Update Rollup 2 for Microsoft Windows XP Media Center Edition 2005 and later.
helpviewer_keywords: ["IDVB_BAT interface [Microsoft TV Technologies]","RegisterForNextTable method","IDVB_BAT.RegisterForNextTable","IDVB_BAT::RegisterForNextTable","IDVB_BATRegisterForNextTable","RegisterForNextTable","RegisterForNextTable method [Microsoft TV Technologies]","RegisterForNextTable method [Microsoft TV Technologies]","IDVB_BAT interface","dvbsiparser/IDVB_BAT::RegisterForNextTable","mstv.idvb_bat_registerfornexttable"]
old-location: mstv\idvb_bat_registerfornexttable.htm
tech.root: mstv
ms.assetid: 77c2d270-72ab-4ae6-84dd-c28c231094ad
ms.date: 12/05/2018
ms.keywords: IDVB_BAT interface [Microsoft TV Technologies],RegisterForNextTable method, IDVB_BAT.RegisterForNextTable, IDVB_BAT::RegisterForNextTable, IDVB_BATRegisterForNextTable, RegisterForNextTable, RegisterForNextTable method [Microsoft TV Technologies], RegisterForNextTable method [Microsoft TV Technologies],IDVB_BAT interface, dvbsiparser/IDVB_BAT::RegisterForNextTable, mstv.idvb_bat_registerfornexttable
req.header: dvbsiparser.h
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
ms.custom: 19H1
f1_keywords:
 - IDVB_BAT::RegisterForNextTable
 - dvbsiparser/IDVB_BAT::RegisterForNextTable
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - dvbsiparser.h
api_name:
 - IDVB_BAT.RegisterForNextTable
---

# IDVB_BAT::RegisterForNextTable


## -description

This topic applies to Update Rollup 2 for Microsoft Windows XP Media Center Edition 2005 and later.
        



The <b>RegisterForNextTable</b> method registers the client to be notified when a <i>next</i> table arrives that will replace the current table.

## -parameters

### -param hNextTableAvailable [in]

Handle to an event created by the caller. The object signals the event when the next table arrives. When the event is signaled, call the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/dvbsiparser/nf-dvbsiparser-idvb_bat-getnexttable">IDVB_BAT::GetNextTable</a> method to retrieve the table.

## -returns

The method returns an <b>HRESULT</b>. Possible values include those in the following table.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_ACCESSDENIED</b></dt>
</dl>
</td>
<td width="60%">
This table is already a <i>next</i> table.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_INVALIDARG</b></dt>
</dl>
</td>
<td width="60%">
Invalid argument; <i>hNextTableAvailable</i> cannot be <b>NULL</b>.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>MPEG2_E_ALREADY_INITIALIZED</b></dt>
</dl>
</td>
<td width="60%">
The method has already been called.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
The method succeeded.

</td>
</tr>
</table>

## -remarks

This method applies only to <i>current</i> tables. Otherwise, the method returns E_ACCESSDENIED.

## -see-also

<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/dvbsiparser/nn-dvbsiparser-idvb_bat">IDVB_BAT Interface</a>

