---
UID: NN:netfw.INetFwAuthorizedApplication
title: INetFwAuthorizedApplication (netfw.h)
description: The INetFwAuthorizedApplication interface provides access to the properties of an application that has been authorized have openings in the firewall.
helpviewer_keywords: ["INetFwAuthorizedApplication","INetFwAuthorizedApplication interface [ICS/ICF]","INetFwAuthorizedApplication interface [ICS/ICF]","described","ics.inetfwauthorizedapplication","netfw/INetFwAuthorizedApplication"]
old-location: ics\inetfwauthorizedapplication.htm
tech.root: ics
ms.assetid: 1ddeeab8-b81b-4d34-9ca6-103147fb3426
ms.date: 12/05/2018
ms.keywords: INetFwAuthorizedApplication, INetFwAuthorizedApplication interface [ICS/ICF], INetFwAuthorizedApplication interface [ICS/ICF],described, ics.inetfwauthorizedapplication, netfw/INetFwAuthorizedApplication
req.header: netfw.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista, Windows XP with SP2 [desktop apps only]
req.target-min-winversvr: Windows Server 2003 with SP1 [desktop apps only]
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
req.dll: FirewallAPI.dll; Hnetcfg.dll on Windows XP with SP2
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - INetFwAuthorizedApplication
 - netfw/INetFwAuthorizedApplication
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - FirewallAPI.dll
 - Hnetcfg.dll
api_name:
 - INetFwAuthorizedApplication
---

# INetFwAuthorizedApplication interface


## -description

<p class="CCE_Message">[The Windows Firewall API is available for use in the operating systems specified in the Requirements section. It may be altered or unavailable in subsequent versions. For Windows Vista and later, use of the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/ics/windows-firewall-advanced-security-start-page">Windows Firewall with Advanced Security</a> API is recommended.]

The <b>INetFwAuthorizedApplication</b> interface provides access to the properties of an application that has been authorized have openings in the firewall.

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">INetFwAuthorizedApplication</b> interface inherits from the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/oaidl/nn-oaidl-idispatch">IDispatch</a> interface. <b>INetFwAuthorizedApplication</b> also has these types of members:
<ul>
<li><a href="https://docs.microsoft.com/">Methods</a></li>
<li><a href="https://docs.microsoft.com/">Properties</a></li>
</ul>

## -members

The <b>INetFwAuthorizedApplication</b> interface has these methods.
<table class="members" id="memberListMethods">
<tr>
<th align="left" width="37%">Method</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/netfw/nf-netfw-inetfwauthorizedapplication-get_enabled">get_Enabled</a>
</td>
<td align="left" width="63%">
Retrieves the contents of the     Enabled property for this application.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/netfw/nf-netfw-inetfwauthorizedapplication-get_ipversion">get_IpVersion</a>
</td>
<td align="left" width="63%">
Retrieves the contents of the    IpVersion property for this application.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/netfw/nf-netfw-inetfwauthorizedapplication-get_name">get_Name</a>
</td>
<td align="left" width="63%">
Retrieves the contents of the  Name property for this application.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/netfw/nf-netfw-inetfwauthorizedapplication-get_processimagefilename">get_ProcessImageFileName</a>
</td>
<td align="left" width="63%">
Retrieves the contents of the ProcessImageFileName property for this application.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/netfw/nf-netfw-inetfwauthorizedapplication-get_remoteaddresses">get_RemoteAddresses</a>
</td>
<td align="left" width="63%">
Retrieves the contents of the RemoteAddresses property for this  application.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/netfw/nf-netfw-inetfwremoteadminsettings-get_scope">get_Scope</a>
</td>
<td align="left" width="63%">
Retrieves the contents of the Scope property.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/netfw/nf-netfw-inetfwauthorizedapplication-get_enabled">put_Enabled</a>
</td>
<td align="left" width="63%">
Sets the contents of the     Enabled property for this application.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/netfw/nf-netfw-inetfwauthorizedapplication-get_ipversion">put_IpVersion</a>
</td>
<td align="left" width="63%">
Sets the contents of the    IpVersion property for this application.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/netfw/nf-netfw-inetfwauthorizedapplication-get_name">put_Name</a>
</td>
<td align="left" width="63%">
Sets the contents of the  Name property for this application.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/netfw/nf-netfw-inetfwauthorizedapplication-get_processimagefilename">put_ProcessImageFileName</a>
</td>
<td align="left" width="63%">
Sets the contents of the ProcessImageFileName property for this application.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/netfw/nf-netfw-inetfwauthorizedapplication-get_remoteaddresses">put_RemoteAddresses</a>
</td>
<td align="left" width="63%">
Sets the contents of the RemoteAddresses property for this  application.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/netfw/nf-netfw-inetfwremoteadminsettings-get_scope">put_Scope</a>
</td>
<td align="left" width="63%">
Sets the contents of the Scope property.

</td>
</tr>
</table> 
<h3><a id="properties"></a>Properties</h3>The <b xmlns:loc="http://microsoft.com/wdcml/l10n">INetFwAuthorizedApplication</b> interface has these properties.
<table class="members" id="memberListProperties">
<tr>
<th align="left" width="27%">Property</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="27%" xml:space="preserve">

<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/netfw/nf-netfw-inetfwauthorizedapplication-get_enabled">Enabled</a>


</td>
<td align="left" width="63%">
Accesses the  Enabled property for this application.

</td>
</tr>
<tr data="declared;">
<td align="left" width="27%" xml:space="preserve">

<a href="https://docs.microsoft.com/windows/desktop/api/netfw/nf-netfw-inetfwauthorizedapplication-get_ipversion">IpVersion</a>


</td>
<td align="left" width="63%">
Accesses the IpVersion property for this application.

</td>
</tr>
<tr data="declared;">
<td align="left" width="27%" xml:space="preserve">

<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/netfw/nf-netfw-inetfwauthorizedapplication-get_name">Name</a>


</td>
<td align="left" width="63%">
Accesses the Name property for this application.

</td>
</tr>
<tr data="declared;">
<td align="left" width="27%" xml:space="preserve">

<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/netfw/nf-netfw-inetfwauthorizedapplication-get_processimagefilename">ProcessImageFileName</a>


</td>
<td align="left" width="63%">
Accesses the ProcessImageFileName property for this application.

</td>
</tr>
<tr data="declared;">
<td align="left" width="27%" xml:space="preserve">

<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/netfw/nf-netfw-inetfwauthorizedapplication-get_remoteaddresses">RemoteAddresses</a>


</td>
<td align="left" width="63%">
Accesses the RemoteAddresses property for this application.

</td>
</tr>
<tr data="declared;">
<td align="left" width="27%" xml:space="preserve">

<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/netfw/nf-netfw-inetfwremoteadminsettings-get_scope">Scope</a>


</td>
<td align="left" width="63%">
Accesses the contents of the Scope property.

</td>
</tr>
</table>

## -remarks

When creating new applications, this interface is supported by the HNetCfg.FwAuthorizedApplication COM object.  

For reading or modifying existing applications, instances of this interface are retrieved through the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/netfw/nn-netfw-inetfwauthorizedapplications">INetFwAuthorizedApplications</a> collection.

All configuration changes take effect immediately.

## -see-also

<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/oaidl/nn-oaidl-idispatch">IDispatch</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/netfw/nn-netfw-inetfwauthorizedapplications">INetFwAuthorizedApplications</a>



<a href="https://docs.microsoft.com/windows/desktop/api/unknwn/nn-unknwn-iunknown">IUnknown</a>

