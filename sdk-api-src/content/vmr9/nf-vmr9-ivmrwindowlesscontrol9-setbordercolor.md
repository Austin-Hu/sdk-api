---
UID: NF:vmr9.IVMRWindowlessControl9.SetBorderColor
title: IVMRWindowlessControl9::SetBorderColor (vmr9.h)
description: The SetBorderColor method sets the border color to be used by the VMR.
helpviewer_keywords: ["IVMRWindowlessControl9 interface [DirectShow]","SetBorderColor method","IVMRWindowlessControl9.SetBorderColor","IVMRWindowlessControl9::SetBorderColor","IVMRWindowlessControl9SetBorderColor","SetBorderColor","SetBorderColor method [DirectShow]","SetBorderColor method [DirectShow]","IVMRWindowlessControl9 interface","dshow.ivmrwindowlesscontrol9_setbordercolor","vmr9/IVMRWindowlessControl9::SetBorderColor"]
old-location: dshow\ivmrwindowlesscontrol9_setbordercolor.htm
tech.root: dshow
ms.assetid: 462b264d-1b4c-482a-b154-382748abaf92
ms.date: 4/26/2023
ms.keywords: IVMRWindowlessControl9 interface [DirectShow],SetBorderColor method, IVMRWindowlessControl9.SetBorderColor, IVMRWindowlessControl9::SetBorderColor, IVMRWindowlessControl9SetBorderColor, SetBorderColor, SetBorderColor method [DirectShow], SetBorderColor method [DirectShow],IVMRWindowlessControl9 interface, dshow.ivmrwindowlesscontrol9_setbordercolor, vmr9/IVMRWindowlessControl9::SetBorderColor
req.header: vmr9.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP with SP2 [desktop apps only]
req.target-min-winversvr: Windows Server 2003 R2 [desktop apps only]
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
 - IVMRWindowlessControl9::SetBorderColor
 - vmr9/IVMRWindowlessControl9::SetBorderColor
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
 - IVMRWindowlessControl9.SetBorderColor
---

# IVMRWindowlessControl9::SetBorderColor


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

The <code>SetBorderColor</code> method sets the border color to be used by the VMR.

## -parameters

### -param Clr [in]

Specifies the color as a <b>COLORREF</b> value.

## -returns

The method returns an <b>HRESULT</b>. Possible values include those in the following table.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
The method succeeded.

</td>
</tr>
</table>

## -remarks

The border color is used to fill any area of the destination rectangle that does not contain video. It is typically used in two situations:

<ul>
<li>When the video straddles two monitors</li>
<li>When the VMR is trying to maintain the aspect ratio of the movies by letter-boxing the video to fit within the specified destination rectangle. See <b>SetAspectRatioMode</b>.</li>
</ul>
Include DShow.h and D3d9.h before Vmr9.h.

## -see-also

<a href="/previous-versions/ms787155(v=vs.85)">IVMRWindowlessControl9 Interface</a>



<a href="/windows/desktop/DirectShow/using-the-video-mixing-renderer">Using the Video Mixing Renderer</a>