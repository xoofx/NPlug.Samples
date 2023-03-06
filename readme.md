# NPlug.Samples [![Build Status](https://github.com/xoofx/NPlug.Samples/workflows/ci/badge.svg?branch=main)](https://github.com/xoofx/NPlug.Samples/actions)

<img align="right" width="160px" height="160px" src="https://raw.githubusercontent.com/xoofx/NPlug/main/img/NPlug.png">

This repository provides samples for creating VST3 audio native plugins with [NPlug](https://github.com/xoofx/NPlug/) and .NET7+/NativeAOT.

## Samples

You need to have installed [.NET 7 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/7.0).

Then you can build native plugins by running the following command:

```
dotnet publish -c Release -r win-x64 -p:PublishAot=true
```

### NPlug.SimpleDelay

This is a port of C/C++ adelay sample from https://github.com/steinbergmedia/vst3_public_sdk/tree/master/samples/vst/adelay/source

### NPlug.SimpleProgramChange

This is a port of C/C++ program change sample from https://github.com/steinbergmedia/vst3_public_sdk/tree/master/samples/vst/programchange/source

## Documentation

You can find more information from NPlug [documentation here](https://github.com/xoofx/NPlug/blob/main/doc/readme.md).

## License

The core part of this software is released under the [BSD-2-Clause license](https://opensource.org/licenses/BSD-2-Clause) but you have also to follow the following VST3 license:

> **NOTICE**
> 
> When you are developing a plugin with NPlug, your plugin needs to comply with the [VST 3 Licensing](https://steinbergmedia.github.io/vst3_dev_portal/pages/VST+3+Licensing/Index.html). If your plugin is distributed, it needs to either be published under:
> - The [Proprietary Steinberg VST 3 license](https://steinbergmedia.github.io/vst3_dev_portal/pages/VST+3+Licensing/What+are+the+licensing+options.html#proprietary-steinberg-vst-3-license) if you want to keep your plugin closed source.
> - The [Open-source GPLv3 license](https://steinbergmedia.github.io/vst3_dev_portal/pages/VST+3+Licensing/What+are+the+licensing+options.html#open-source-gplv3-license) if you want to make your plugin OSS.

What it means is that you are allowed to modify and redistribute NPlug (according to the `BSD-2-Clause` license) but you need to publish your plugin under the VST3 dual-license.

## Author

Alexandre Mutel aka [xoofx](https://xoofx.com).

