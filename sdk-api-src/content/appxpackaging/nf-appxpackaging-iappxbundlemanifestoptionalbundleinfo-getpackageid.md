---
UID: NF:appxpackaging.IAppxBundleManifestOptionalBundleInfo.GetPackageId
title: IAppxBundleManifestOptionalBundleInfo::GetPackageId (appxpackaging.h)
description: Retrieves an object that represents the identity of the &lt;OptionalBundle&gt;.
helpviewer_keywords: ["GetPackageId","GetPackageId method [App packaging and management]","GetPackageId method [App packaging and management]","IAppxBundleManifestOptionalBundleInfo interface","IAppxBundleManifestOptionalBundleInfo interface [App packaging and management]","GetPackageId method","IAppxBundleManifestOptionalBundleInfo.GetPackageId","IAppxBundleManifestOptionalBundleInfo::GetPackageId","appxpackaging/IAppxBundleManifestOptionalBundleInfo::GetPackageId","appxpkg.iappxbundlemanifestoptionalbundleinfo_getpackageid"]
old-location: appxpkg\iappxbundlemanifestoptionalbundleinfo_getpackageid.htm
tech.root: appxpkg
ms.assetid: 57C8FB41-0218-4768-8E84-4ABF63EB94E8
ms.date: 12/05/2018
ms.keywords: GetPackageId, GetPackageId method [App packaging and management], GetPackageId method [App packaging and management],IAppxBundleManifestOptionalBundleInfo interface, IAppxBundleManifestOptionalBundleInfo interface [App packaging and management],GetPackageId method, IAppxBundleManifestOptionalBundleInfo.GetPackageId, IAppxBundleManifestOptionalBundleInfo::GetPackageId, appxpackaging/IAppxBundleManifestOptionalBundleInfo::GetPackageId, appxpkg.iappxbundlemanifestoptionalbundleinfo_getpackageid
req.header: appxpackaging.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 10 [desktop apps only]
req.target-min-winversvr: Windows Server 2016 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: AppxPackaging.idl
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
 - IAppxBundleManifestOptionalBundleInfo::GetPackageId
 - appxpackaging/IAppxBundleManifestOptionalBundleInfo::GetPackageId
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - AppxPackaging.h
api_name:
 - IAppxBundleManifestOptionalBundleInfo.GetPackageId
---

# IAppxBundleManifestOptionalBundleInfo::GetPackageId


## -description

Retrieves an object that represents the identity of the &lt;OptionalBundle&gt;.

## -parameters

### -param packageId [out, retval]

The package identifier.

## -returns

If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.

## -see-also

<a href="https://docs.microsoft.com/windows/desktop/api/appxpackaging/nn-appxpackaging-iappxbundlemanifestoptionalbundleinfo">IAppxBundleManifestOptionalBundleInfo</a>

