# Cofoundry.Plugins.Imaging.ImageSharp

[![Build status](https://ci.appveyor.com/api/projects/status/neoc6yy7ed64td14?svg=true)](https://ci.appveyor.com/project/Cofoundry/cofoundry-plugins-imaging-imagesharp)
[![NuGet](https://img.shields.io/nuget/v/Cofoundry.Plugins.Imaging.ImageSharp.svg)](https://www.nuget.org/packages/Cofoundry.Plugins.Imaging.ImageSharp/)
[![Gitter](https://img.shields.io/gitter/room/cofoundry-cms/cofoundry.svg)](https://gitter.im/cofoundry-cms/cofoundry)


This library is a plugin for [Cofoundry](https://www.cofoundry.org). For more information on getting started with Cofoundry check out the [Cofoundry repository](https://github.com/cofoundry-cms/cofoundry).

## Overview

Cofoundry does not have a default image resizing implementation and relies on plugins to add this functionality. For more info on image resizing in Cofoundry check out the [imaging documentation](https://github.com/cofoundry-cms/cofoundry/wiki/Images). 

This plugin uses the cross platform [ImageSharp](https://github.com/JimBobSquarePants/ImageSharp) package to resize images dynamically. 

***NB:** ImageSharp is still in pre-release so this is a quick rough solution to cross platform imaging. The ImageSharp package should be picked up automatically, but if not you can find it in the MyGet feed stored in the NuGet.config file.*

The services register themselves automatically so no other configuration is required.