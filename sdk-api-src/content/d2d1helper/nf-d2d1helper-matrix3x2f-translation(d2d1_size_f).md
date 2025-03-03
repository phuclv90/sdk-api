---
UID: NF:d2d1helper.Matrix3x2F.Translation(D2D1_SIZE_F)
title: Matrix3x2F::Translation (d2d1helper.h)
description: Creates a translation transformation that has the specified x and y displacements.
old-location: direct2d\matrix3x2f_translation.htm
tech.root: Direct2D
ms.assetid: eb289287-4f33-42cf-a306-120adda70371
ms.date: 12/05/2018
ms.keywords: D2D1.Matrix3x2F.Translation, D2D1::Matrix3x2F::Translation, Matrix3x2F class [Direct2D],Translation method, Matrix3x2F.Translation, Matrix3x2F::Translation, Matrix3x2F::Translation(D2D1_SIZE_F), Translation, Translation method [Direct2D], Translation method [Direct2D],Matrix3x2F class, d2d1helper/Matrix3x2F::Translation, direct2d.matrix3x2f_translation
f1_keywords:
- d2d1helper/Matrix3x2F.Translation
dev_langs:
- c++
req.header: d2d1helper.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 7, Windows Vista with SP2 and Platform Update for Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2008 R2, Windows Server 2008 with SP2 and Platform Update for Windows Server 2008 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: D2D1
req.assembly: 
req.type-library: 
req.lib: D2d1.lib
req.dll: D2d1.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- D2d1.dll
api_name:
- Matrix3x2F.Translation
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# Matrix3x2F::Translation


## -description


Creates a translation transformation that has the specified x and y displacements.


## -parameters




### -param size

Type: <b><a href="https://docs.microsoft.com/windows/desktop/Direct2D/d2d1-size-f">D2D1_SIZE_F</a></b>

The distance to translate along the x-axis and the y-axis.


## -returns



Type: <b><a href="https://docs.microsoft.com/windows/desktop/api/d2d1helper/nl-d2d1helper-matrix3x2f">Matrix3x2F</a></b>

A transformation matrix that translates an object the specified horizontal and vertical distance.




## -remarks



 Translation  is an affine transformation, which moves every point by a fixed distance in the same direction. It is similar to shifting the origin of the coordinate space. You can translate an object along the x-axis, the y-axis, or both. 

When calling this method, specify the x and y displacements and create  a <a href="https://docs.microsoft.com/windows/desktop/Direct2D/d2d1-size-f">D2D1_SIZE_F</a> structure for storing the displacements.   If you prefer to specify each displacement as a parameter, call the  other <a href="https://docs.microsoft.com/windows/desktop/api/d2d1helper/nf-d2d1helper-matrix3x2f-translation(float_float)">Translation</a> method. The following illustration shows a square moved 20 pixels to the right along the x-axis, and 10 pixels downward along the y-axis.

<img alt="Illustration of a square moved to the right and down from its original position" src="images/translation_ovw.png"/>
 For an example, see <a href="https://docs.microsoft.com/windows/desktop/Direct2D/how-to-translate">How to Translate an Object</a>.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/d2d1helper/nl-d2d1helper-matrix3x2f">Matrix3x2F</a>
 

 

