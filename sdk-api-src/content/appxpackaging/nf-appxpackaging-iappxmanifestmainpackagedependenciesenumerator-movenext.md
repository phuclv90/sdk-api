---
UID: NF:appxpackaging.IAppxManifestMainPackageDependenciesEnumerator.MoveNext
title: IAppxManifestMainPackageDependenciesEnumerator::MoveNext (appxpackaging.h)
description: Advances the position of the enumerator to the next &lt;MainPackageDependency&gt; element.
old-location: appxpkg\iappxmanifestmainpackagedependenciesenumerator_movenext.htm
tech.root: appxpkg
ms.assetid: C9E34671-5B56-4A6D-B728-C074F9BDB6D6
ms.date: 12/05/2018
ms.keywords: IAppxManifestMainPackageDependenciesEnumerator interface [App packaging and management],MoveNext method, IAppxManifestMainPackageDependenciesEnumerator.MoveNext, IAppxManifestMainPackageDependenciesEnumerator::MoveNext, MoveNext, MoveNext method [App packaging and management], MoveNext method [App packaging and management],IAppxManifestMainPackageDependenciesEnumerator interface, appxpackaging/IAppxManifestMainPackageDependenciesEnumerator::MoveNext, appxpkg.iappxmanifestmainpackagedependenciesenumerator_movenext
f1_keywords:
- appxpackaging/IAppxManifestMainPackageDependenciesEnumerator.MoveNext
dev_langs:
- c++
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
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- AppxPackaging.h
api_name:
- IAppxManifestMainPackageDependenciesEnumerator.MoveNext
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IAppxManifestMainPackageDependenciesEnumerator::MoveNext


## -description


Advances the position of the enumerator to the next &lt;MainPackageDependency&gt; element.


## -parameters




### -param hasNext [out, retval]

Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types">BOOL</a>*</b>

<b>TRUE</b> if the enumerator successfully advances

<b>FALSE</b> if the enumerator has passed the end of the collection.


## -returns



Type: <b>HRESULT</b>

If the method succeeds, it returns <b>S_OK</b>. Otherwise, it returns an error code.

<div class="alert"><b>Note</b>  When the enumerator passes the end of the collection for the first time, <i>hasNext</i> = <b>FALSE</b>,  but the method succeeds and returns <b>S_OK</b>. However, the method returns <b>E_BOUNDS</b> if you subsequently call another MoveNext after you have already passed the end of the collection, and you have previously received  <i>hasNext</i> = <b>FALSE</b>.</div>
<div> </div>



## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/appxpackaging/nn-appxpackaging-iappxmanifestmainpackagedependenciesenumerator">IAppxManifestMainPackageDependenciesEnumerator</a>
 

 

