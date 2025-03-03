---
UID: NE:cfapi.CF_CREATE_FLAGS
title: CF_CREATE_FLAGS (cfapi.h)
description: Flags for creating a placeholder file or directory.
old-location: cloudapi\cf_create_flags.htm
tech.root: cfApi
ms.assetid: F70ECFDB-8542-4395-9EDD-7DABC2E5225D
ms.date: 12/05/2018
ms.keywords: CF_CREATE_FLAGS, CF_CREATE_FLAGS enumeration, CF_CREATE_FLAG_NONE, CF_CREATE_FLAG_STOP_ON_ERROR, PCF_CREATE_FLAGS, PCF_CREATE_FLAGS enumeration pointer, cfapi/CF_CREATE_FLAGS, cfapi/CF_CREATE_FLAG_NONE, cfapi/CF_CREATE_FLAG_STOP_ON_ERROR, cfapi/PCF_CREATE_FLAGS, cloudApi.cf_create_flags
f1_keywords:
- cfapi/CF_CREATE_FLAGS
dev_langs:
- c++
req.header: cfapi.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 10, version 1709 [desktop apps only]
req.target-min-winversvr: Windows Server 2016 [desktop apps only]
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
- HeaderDef
api_location:
- CfApi.h
api_name:
- CF_CREATE_FLAGS
targetos: Windows
req.typenames: CF_CREATE_FLAGS
req.redist: 
ms.custom: 19H1
---

# CF_CREATE_FLAGS enumeration


## -description


Flags for creating a placeholder file or directory.


## -enum-fields




### -field CF_CREATE_FLAG_NONE

Default mode. All entries are processed.


### -field CF_CREATE_FLAG_STOP_ON_ERROR

Causes the API to return immediately if placeholder creation fails. If creation fails, the error code will be returned by the API.

