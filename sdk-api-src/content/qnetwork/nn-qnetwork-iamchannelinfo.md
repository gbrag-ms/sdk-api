---
UID: NN:qnetwork.IAMChannelInfo
title: IAMChannelInfo (qnetwork.h)
description: The IAMChannelInfo interface gets and sets channel information for Windows Media Station (.nsc) files.This interface is exposed by the Windows Media Source filter only when the filter is reading Windows Media Station (.nsc) files.
helpviewer_keywords: ["IAMChannelInfo","IAMChannelInfo interface [DirectShow]","IAMChannelInfo interface [DirectShow]","described","IAMChannelInfoInterface","dshow.iamchannelinfo","qnetwork/IAMChannelInfo"]
old-location: dshow\iamchannelinfo.htm
tech.root: dshow
ms.assetid: 779d1c0a-f838-4d02-8254-d66916d3b790
ms.date: 12/05/2018
ms.keywords: IAMChannelInfo, IAMChannelInfo interface [DirectShow], IAMChannelInfo interface [DirectShow],described, IAMChannelInfoInterface, dshow.iamchannelinfo, qnetwork/IAMChannelInfo
req.header: qnetwork.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
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
 - IAMChannelInfo
 - qnetwork/IAMChannelInfo
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Qnetwork.h
api_name:
 - IAMChannelInfo
---

# IAMChannelInfo interface


## -description

The <b>IAMChannelInfo</b> interface gets and sets channel information for Windows Media Station (.nsc) files.

This interface is exposed by the <a href="https://docs.microsoft.com/windows/desktop/DirectShow/windows-media-source-filter">Windows Media Source</a> filter only when the filter is reading Windows Media Station (.nsc) files. The Windows Media Source filter uses .nsc files to get the information it needs to receive multicast content over the Internet. These files contain information such as stream location and rollover URL, as well as descriptive information about the station.

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IAMChannelInfo</b> interface inherits from the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/oaidl/nn-oaidl-idispatch">IDispatch</a> interface. <b>IAMChannelInfo</b> also has these types of members:
<ul>
<li><a href="https://docs.microsoft.com/">Methods</a></li>
</ul>

## -members

The <b>IAMChannelInfo</b> interface has these methods.
<table class="members" id="memberListMethods">
<tr>
<th align="left" width="37%">Method</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/qnetwork/nf-qnetwork-iamchannelinfo-get_channeldescription">get_ChannelDescription</a>
</td>
<td align="left" width="63%">
Gets the description of the channel.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/qnetwork/nf-qnetwork-iamchannelinfo-get_channelname">get_ChannelName</a>
</td>
<td align="left" width="63%">
Gets the channel name.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/qnetwork/nf-qnetwork-iamchannelinfo-get_channelurl">get_ChannelURL</a>
</td>
<td align="left" width="63%">
Gets the channel URL.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/qnetwork/nf-qnetwork-iamchannelinfo-get_contactaddress">get_ContactAddress</a>
</td>
<td align="left" width="63%">
Gets the contact address.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/qnetwork/nf-qnetwork-iamchannelinfo-get_contactemail">get_ContactEmail</a>
</td>
<td align="left" width="63%">
Gets the contact email address.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/qnetwork/nf-qnetwork-iamchannelinfo-get_contactphone">get_ContactPhone</a>
</td>
<td align="left" width="63%">
Gets the contact phone number.

</td>
</tr>
</table>

## -remarks

To define the interface identifier, include the header file Initguid.h before Qnetwork.h, but after Dshow.h and other header files:

<pre class="syntax" xml:space="preserve"><code>#include &lt;dshow.h&gt;
#include &lt;initguid.h&gt;
#include &lt;qnetwork.h&gt;
</code></pre>
<div class="alert"><b>Note</b>  Make sure that Initguid.h is included only once in your project. Otherwise, you will receive linker errors for duplicate GUID values.</div>
<div> </div>

## -see-also

<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/oaidl/nn-oaidl-idispatch">IDispatch</a>



<a href="https://docs.microsoft.com/windows/desktop/DirectShow/interfaces">Interfaces</a>

