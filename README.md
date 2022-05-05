# Cobalt Native UI Framework

Cobalt [an extension of the Netease-IM Duilib Fork] is a native C++ UI Framework containing a complete set of components for developing native Win32 UI that expands upon the original NIM Duilib fork architecture on top of the original Duilib fork.

![GitHub](https://img.shields.io/badge/license-MIT-green.svg)
[![Build status](https://ci.appveyor.com/api/projects/status/u29yl0j7pasopm3h?svg=true)](https://ci.appveyor.com/project/nmgwddj/nim-duilib-framework)

[Introduction in Chinese](README_ch-Mandarin.md)

## Features

 - Multi language support
 - Global style support
 - DPI scaling support
 - GIF animation support
 - CEF control support（based on CEF 2623, support XP）
 - Touch device support（surface, wacom）
 - Abstract rendering interface (support for other rendering engines)

## Preview

![preview](docs/PREVIEW.gif)

## Start

Clone the repo into your disk.

```bash
git clone https://github.com/3rdGen-Media/Cobalt
```

Enter the `Cobalt/examples` directory，Open `examples.sln` with Visual Studio 2019 or higher ，press `F7` to compile all projects.

## Documentation

 - [Getting Started](docs/GETTING-STARTED.md)
 - [Docs](docs/SUMMARY.md)
    
## Structure

├─`base` Base libraries.  
├─`bin` Examples output directories，include skin and language files and CEF dependencies.  
├─`docs` Documentation of Duilib.  
├─`duilib` Duilib core, depend on base project.  
├─`libs` Static library output directories, include CEF static library.  
├─`examples` Examples of Duilib.  
├─`third_party` Third party for CEF.  
├─`ui_components` UI components based on Duilib, such as `msgbox`,`toast`,`cef_control`  

## Communication

 - Question: Read the [Documentation](docs/SUMMARY.md) and [Examples code](examples/README.md) to help you.
 - Report: File a bug in GitHub issues.
 - Suggestion: Request a new feature in Github issues.
