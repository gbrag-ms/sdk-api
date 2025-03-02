---
UID: NN:tuner.IATSCLocator
title: IATSCLocator (tuner.h)
description: The IATSCLocator interface is implemented on the ATSCLocator object and contains methods that enable the network provider to determine the physical channel and transport stream ID of an ATSC transmission.
helpviewer_keywords: ["IATSCLocator","IATSCLocator interface [Microsoft TV Technologies]","IATSCLocator interface [Microsoft TV Technologies]","described","IATSCLocatorInterface","mstv.iatsclocator","tuner/IATSCLocator"]
old-location: mstv\iatsclocator.htm
tech.root: mstv
ms.assetid: 8ca7d50f-e7cc-4938-a2ed-fce5278b73fd
ms.date: 12/05/2018
ms.keywords: IATSCLocator, IATSCLocator interface [Microsoft TV Technologies], IATSCLocator interface [Microsoft TV Technologies],described, IATSCLocatorInterface, mstv.iatsclocator, tuner/IATSCLocator
req.header: tuner.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP [desktop apps only]
req.target-min-winversvr: None supported
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Tuner.idl
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
 - IATSCLocator
 - tuner/IATSCLocator
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - tuner.h
api_name:
 - IATSCLocator
---

# IATSCLocator interface


## -description

The <b>IATSCLocator</b> interface is implemented on the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/mstv/atsclocator-object">ATSCLocator</a> object and contains methods that enable the network provider to determine the physical channel and transport stream ID of an ATSC transmission. Applications do not use Locator interfaces except possibly for debugging purposes. All Locator objects also support <b>IPersistPropertyBag</b>.

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IATSCLocator</b> interface inherits from <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/tuner/nn-tuner-idigitallocator~r1">IDigitalLocator</a>. <b>IATSCLocator</b> also has these types of members:
<ul>
<li><a href="https://docs.microsoft.com/">Methods</a></li>
</ul>

## -members

The <b>IATSCLocator</b> interface has these methods.
<table class="members" id="memberListMethods">
<tr>
<th align="left" width="37%">Method</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/tuner/nf-tuner-iatsclocator-get_physicalchannel">get_PhysicalChannel</a>
</td>
<td align="left" width="63%">
Retrieves the physical channel.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/tuner/nf-tuner-iatsclocator-get_tsid">get_TSID</a>
</td>
<td align="left" width="63%">
Retrieves the transport stream ID.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/tuner/nf-tuner-iatsclocator-put_physicalchannel">put_PhysicalChannel</a>
</td>
<td align="left" width="63%">
Sets the physical channel.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/tuner/nf-tuner-iatsclocator-put_tsid">put_TSID</a>
</td>
<td align="left" width="63%">
Sets the transport stream ID.

</td>
</tr>
</table>

## -remarks

To declare the interface identifier (IID) for this interface, use the <b>__uuidof</b> operator: <code>__uuidof(IATSCLocator)</code>.

## -see-also

<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/tuner/nn-tuner-idigitallocator~r1">IDigitalLocator</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/mstv/tuning-model-interfaces">Tuning Model Interfaces</a>

