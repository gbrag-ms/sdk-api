---
UID: NF:infotech.IITWordWheel.Lookup(LONG,IITResultSet,LONG)
title: IITWordWheel::Lookup(LONG,IITResultSet,LONG) (infotech.h)
description: Looks up an entry and returns contents in a buffer.
helpviewer_keywords: ["IITWordWheel interface [HTML Help Workshop]","Lookup method","IITWordWheel.Lookup","IITWordWheel.Lookup(LONG","IITResultSet","LONG)","IITWordWheel::Lookup","IITWordWheel::Lookup(LONG","IITResultSet","LONG)","IITWordWheel::Lookup(LONG","LPVOID","DWORD)","Lookup","Lookup method [HTML Help Workshop]","Lookup method [HTML Help Workshop]","IITWordWheel interface","htmlhelp.iitwordwheel_lookup1","infotech/IITWordWheel::Lookup","refIITWordWheelLookupBuffer"]
old-location: htmlhelp\iitwordwheel_lookup1.htm
tech.root: htmlhelp
ms.assetid: VS|htmlhelp|~\html\refiitwordwheellookupbuffer.htm
ms.date: 12/05/2018
ms.keywords: IITWordWheel interface [HTML Help Workshop],Lookup method, IITWordWheel.Lookup, IITWordWheel.Lookup(LONG,IITResultSet,LONG), IITWordWheel::Lookup, IITWordWheel::Lookup(LONG,IITResultSet,LONG), IITWordWheel::Lookup(LONG,LPVOID,DWORD), Lookup, Lookup method [HTML Help Workshop], Lookup method [HTML Help Workshop],IITWordWheel interface, htmlhelp.iitwordwheel_lookup1, infotech/IITWordWheel::Lookup, refIITWordWheelLookupBuffer
req.header: infotech.h
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
 - IITWordWheel::Lookup
 - infotech/IITWordWheel::Lookup
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Infotech.h
api_name:
 - IITWordWheel.Lookup
---

# IITWordWheel::Lookup(LONG,IITResultSet,LONG)


## -description

Looks up an entry and returns contents in a buffer.

## -parameters

### -param lEntry

TBD

### -param lpITResult

TBD

### -param cEntries

TBD




#### - fExactMatch [out]

Buffer to return entry.




#### - lpcvPrefix [in]

Entry to look up.




#### - plEntry [in]

Buffer size in number of bytes.

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
The word wheel entry was successfully returned.



</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_OUTOFRANGE</b></dt>
</dl>
</td>
<td width="60%">
Entry number is out of range.



</td>
</tr>
</table>

## -see-also

<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/infotech/nn-infotech-iitwordwheel">IITWordWheel</a>

