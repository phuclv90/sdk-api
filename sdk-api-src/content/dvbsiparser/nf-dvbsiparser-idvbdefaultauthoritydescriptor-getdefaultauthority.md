---
UID: NF:dvbsiparser.IDvbDefaultAuthorityDescriptor.GetDefaultAuthority
title: IDvbDefaultAuthorityDescriptor::GetDefaultAuthority (dvbsiparser.h)
description: Gets the string identifying the default authority from a Digital Video Broadcast (DVB) content reference identifier (CRID).
old-location: mstv\idvbdefaultauthoritydescriptor_getdefaultauthority.htm
tech.root: mstv
ms.assetid: dd615bd1-3db7-4577-aa10-d68ad61b068c
ms.date: 12/05/2018
ms.keywords: GetDefaultAuthority, GetDefaultAuthority method [Microsoft TV Technologies], GetDefaultAuthority method [Microsoft TV Technologies],IDvbDefaultAuthorityDescriptor interface, IDvbDefaultAuthorityDescriptor interface [Microsoft TV Technologies],GetDefaultAuthority method, IDvbDefaultAuthorityDescriptor.GetDefaultAuthority, IDvbDefaultAuthorityDescriptor::GetDefaultAuthority, dvbsiparser/IDvbDefaultAuthorityDescriptor::GetDefaultAuthority, mstv.idvbdefaultauthoritydescriptor_getdefaultauthority
f1_keywords:
- dvbsiparser/IDvbDefaultAuthorityDescriptor.GetDefaultAuthority
dev_langs:
- c++
req.header: dvbsiparser.h
req.include-header: Dvbsiparser.idl
req.target-type: Windows
req.target-min-winverclnt: Windows 7 [desktop apps only]
req.target-min-winversvr: None supported
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
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- dvbsiparser.h
api_name:
- IDvbDefaultAuthorityDescriptor.GetDefaultAuthority
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IDvbDefaultAuthorityDescriptor::GetDefaultAuthority


## -description


Gets the string identifying the default authority from a Digital Video Broadcast (DVB)
content reference identifier (CRID). 


## -parameters




### -param pbLength [out]

Receives the length of the default authority string in bytes.


### -param ppbBytes [out]

Pointer to a buffer that receives the default authority string. The caller is responsible for releasing this memory.


## -returns



If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -see-also




<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/dvbsiparser/nn-dvbsiparser-idvbdefaultauthoritydescriptor">IDvbDefaultAuthorityDescriptor</a>
 

 

