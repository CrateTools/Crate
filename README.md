# CRATE V2.0 under contruction

Crate is the first 3D browser for Nuke that generates thumbnails from geometry and gaussian splats automatically for you without intervention.

Note: Crate V2.0 is a major update both for it´s interface, functions, engines and code. It works very different compared to V1.1., a clean install is needed.

Will be compatible with PySide2 to PySide6 across Nuke 15 16 17

New studio professional tools, Curators vs Visitors access, user read and write privileges, user interface privileges according to role. 

Library objects vs storage tiers it allows to have the thumbnails and animated previews on a separate cache. You might choose to locate the cache over ssd/nvme disk and the raw elements on an array or high capacity disks.

We´re are working to build a first long term solid foundation and allow studios and users to update their Crate versions easily in the future.

#

No more guesswork, just thumbnails, making it easier than ever to find, organize, and access your 2D and 3D resources.
Double-click and the asset will instantly appear in the nodegraph.
Forget about creating cache images in your OS explorer, Crate does everything for you in the background right inside Nuke.

Crate uses F3D, OpenImageIO, FFmpeg, ImageMagik and MediaInfo as splat, geo, metadata, video and images for fast ingest, still and animated thumbs done automatically on the fly with professional color management.

The engines will continue to allow Crate to grow into new and more professional features, many of them already on new V2.0

#
Official Crate youtube playlist: https://www.youtube.com/playlist?list=PLPqEIUVfnnz6pt2Bg8_i-BTS6PeyLD2nX

#

Some of the supported formarts covering image, geometry and gaussian splats:

abc, avi, bmp, dae, dds, dnxhd, dpx, exr, fbx, gif, glb, gltf, hdr, ico, jpeg, jpg, m2v, m4v, mkv, mov, mp4, mpeg, mpg, mxf,
obj, off, pbm, pfm, pgm, pic, ply, png, ppm, prores, psd, pts, splat, spz, stl, tga, tif, tiff, usd, usda, usdc, usdz, vrml, 
vtp, vtu, webm, webp, wmv, wrl, xyz, y4m, yuv and more...


# Licenses

Crate is under Apache License.

F3D, which Crate depends on, is licensed under the BSD 3-Clause License.

ImageMagik, which Crate depends on, is licensed under the ImageMagick License (the "License").

FFmpeg, which Crate depends on, is under the GNU Lesser General Public License version 2.1 or later (LGPL v2.1+), most files in FFmpeg, not all, support this license.

MediaInfo, which Crate depends on, is under the BSD 2-Clause License

OpenImageIO, which Crate depends on, is under Apache License.


# Crate engines

https://github.com/ImageMagick

https://github.com/f3d-app

https://github.com/AcademySoftwareFoundation

https://github.com/pitvfx/OpenImageIO

https://github.com/MediaArea/MediaInfo

https://github.com/FFmpeg


# Credits & Acknowledgments


## Splat

WebGL 3D Gaussian Splat Viewer

[https://github.com/francescofugazzi/3dgsconverter](https://github.com/antimatter15/splat)

Used as ply to splat converter

## Camera Database

Crate's Camera module ships with a reference database of digital cinema, broadcast, drone, mobile, and film camera sensor specifications. This data is derived in part from **[VFXCamDB.com](https://vfxcamdb.com)**, maintained by **Tony D'Agostino**.

We are genuinely grateful and the Camera module would not exist in its current form without his work. If you find this data useful, please consider [supporting VFXCamDB](https://vfxcamdb.com) directly.

Any inaccuracies in Crate's database are ours, not VFXCamDB's; corrections are welcome via the issue tracker, and significant ones will be reported back to VFXCamDB as well.

# Recommended Apps that you can link to Crate´s right click "Open With" available on Crate Settings

  Open RV
    https://github.com/AcademySoftwareFoundation/OpenRV
    Licence: Apache-2.0
    Use: media review and playback for image sequences and video.
    Get installers for windows and linux below thanks to kimda90
    https://github.com/kimda90/OpenRV-Releases

  DJV
    https://github.com/grizzlypeak3d/DJV
    Licence: BSD-3-Clause
    Use: high-bit-depth image sequence and video player.

  VLC media player
    https://www.videolan.org/vlc
    Licence: GNU General Public License v2 or later (GPLv2+).
    libVLC core is LGPL-2.1+; the VLC application as a whole is GPLv2+.
    Use: general-purpose video and audio playback.

  XnView MP (xnviewmp_Portable)
    https://www.xnview.com/en/xnviewmp/
    Licence: Proprietary freeware. Free for private, public-entity, and
    educational use, including non-profit organisations. Commercial use
    requires a paid licence from XnSoft. Studios using XnView MP in
    paid production work are responsible for obtaining the appropriate
    XnView licence directly from XnSoft.
    Use: image and texture browsing and conversion.

  Notepad++
    https://notepad-plus-plus.org
    Licence: GNU General Public License v3 or later (GPLv3+)
    Use: editing text-based asset descriptors, configuration files,
    and shader/script files.

  Bulk Rename Utility (Bulk Rename_Portable)
    https://www.bulkrenameutility.co.uk
    Licence: Proprietary freeware. Free for personal/home use.
    Commercial use requires a paid licence from TGRMN Software.
    Studios using Bulk Rename Utility in paid production work are
    responsible for obtaining the appropriate licence directly from
    TGRMN Software.
    Use: batch-renaming asset files.

  LizardQ Spherical Pano Viewer
    https://www.lizardq.com
    Licence: Proprietary freeware (vendor-supplied viewer).
    Use: 360° panorama playback.

  tev — The HDR/EDR Viewer
    https://github.com/Tom94/tev
    Licence: GNU General Public License v3 (GPLv3) for current versions
    (v1.31 and later). Older versions (v1.30 and earlier) were
    BSD-3-Clause.
    Use: HDR / OpenEXR inspection, false-colour comparison, pixel
    peeping.


