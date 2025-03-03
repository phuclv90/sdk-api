---
UID: NF:tuner.ITuningSpace.put_DefaultPreferredComponentTypes
title: ITuningSpace::put_DefaultPreferredComponentTypes (tuner.h)
description: The put_DefaultPreferredComponentTypes method specifies the default preferred component types for this tuning space.
old-location: mstv\ituningspace_put_defaultpreferredcomponenttypes.htm
tech.root: mstv
ms.assetid: 11ab6f15-1f16-42f9-9d7f-f0e51c83cba3
ms.date: 12/05/2018
ms.keywords: ITuningSpace interface [Microsoft TV Technologies],put_DefaultPreferredComponentTypes method, ITuningSpace.put_DefaultPreferredComponentTypes, ITuningSpace::put_DefaultPreferredComponentTypes, ITuningSpaceput_DefaultPreferredComponentTypes, mstv.ituningspace_put_defaultpreferredcomponenttypes, put_DefaultPreferredComponentTypes, put_DefaultPreferredComponentTypes method [Microsoft TV Technologies], put_DefaultPreferredComponentTypes method [Microsoft TV Technologies],ITuningSpace interface, tuner/ITuningSpace::put_DefaultPreferredComponentTypes
f1_keywords:
- tuner/ITuningSpace.put_DefaultPreferredComponentTypes
dev_langs:
- c++
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
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- tuner.h
api_name:
- ITuningSpace.put_DefaultPreferredComponentTypes
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# ITuningSpace::put_DefaultPreferredComponentTypes


## -description



The <b>put_DefaultPreferredComponentTypes</b> method specifies the default preferred component types for this tuning space.




## -parameters




### -param NewComponentTypes [in]

Pointer to the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/tuner/nn-tuner-icomponenttypes">IComponentTypes</a> interface of the component types collection.


## -returns



Returns S_OK if successful. If the method fails, error information can be retrieved using the standard COM <b>IErrorInfo</b> interface.




## -see-also




<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/tuner/nn-tuner-ituningspace">ITuningSpace Interface</a>
 

 

