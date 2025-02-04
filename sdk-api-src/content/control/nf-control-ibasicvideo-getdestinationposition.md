---
UID: NF:control.IBasicVideo.GetDestinationPosition
title: IBasicVideo::GetDestinationPosition (control.h)
description: The GetDestinationPosition method retrieves the position of the destination rectangle.
helpviewer_keywords: ["GetDestinationPosition","GetDestinationPosition method [DirectShow]","GetDestinationPosition method [DirectShow]","IBasicVideo interface","IBasicVideo interface [DirectShow]","GetDestinationPosition method","IBasicVideo.GetDestinationPosition","IBasicVideo::GetDestinationPosition","IBasicVideoGetDestinationPosition","control/IBasicVideo::GetDestinationPosition","dshow.ibasicvideo_getdestinationposition"]
old-location: dshow\ibasicvideo_getdestinationposition.htm
tech.root: dshow
ms.assetid: ee2abf52-edc2-471e-bf9b-eda04f2eabe4
ms.date: 4/26/2023
ms.keywords: GetDestinationPosition, GetDestinationPosition method [DirectShow], GetDestinationPosition method [DirectShow],IBasicVideo interface, IBasicVideo interface [DirectShow],GetDestinationPosition method, IBasicVideo.GetDestinationPosition, IBasicVideo::GetDestinationPosition, IBasicVideoGetDestinationPosition, control/IBasicVideo::GetDestinationPosition, dshow.ibasicvideo_getdestinationposition
req.header: control.h
req.include-header: Dshow.h
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
req.lib: Strmiids.lib
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - IBasicVideo::GetDestinationPosition
 - control/IBasicVideo::GetDestinationPosition
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Strmiids.lib
 - Strmiids.dll
api_name:
 - IBasicVideo.GetDestinationPosition
---

# IBasicVideo::GetDestinationPosition


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

The <code>GetDestinationPosition</code> method retrieves the position of the destination rectangle.

## -parameters

### -param pLeft [out]

Pointer to a variable that receives the x-coordinate, in pixels.

### -param pTop [out]

Pointer to a variable that receives the y-coordinate, in pixels.

### -param pWidth [out]

Pointer to a variable that receives the width, in pixels.

### -param pHeight [out]

Pointer to a variable that receives the height, in pixels.

## -returns

Returns an <b>HRESULT</b> value.

## -remarks

This method has the same effect as individually calling the <a href="/windows/desktop/api/control/nf-control-ibasicvideo-get_destinationleft">IBasicVideo::get_DestinationLeft</a>, <a href="/windows/desktop/api/control/nf-control-ibasicvideo-get_destinationtop">IBasicVideo::get_DestinationTop</a>, <a href="/windows/desktop/api/control/nf-control-ibasicvideo-get_destinationwidth">IBasicVideo::get_DestinationWidth</a>, and <a href="/windows/desktop/api/control/nf-control-ibasicvideo-get_destinationheight">IBasicVideo::get_DestinationHeight</a> methods.

## -see-also

<a href="/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="/windows/desktop/api/control/nn-control-ibasicvideo">IBasicVideo Interface</a>