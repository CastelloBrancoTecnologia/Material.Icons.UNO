[icons-nuget]: https://www.nuget.org/packages/Material.Icons/
[wpf-nuget]: https://www.nuget.org/packages/Material.Icons.WPF/
[avalonia-nuget]: https://www.nuget.org/packages/Material.Icons.Avalonia/
[UNO/WinUi3-nuget]: https://www.nuget.org/packages/Material.Icons.UNO/


# Material.Icons
Parsed icons set from [materialdesignicons.com](https://materialdesignicons.com/) and display control implementations for different GUI frameworks.  
- All icons are **always up-to-date** because automatically updated every 6 hours.
- **Small package size** because icons are graphically encoded via SVG Path.
- Icon types are **strongly typed** enum, so your **IDE will suggest available variants**:  
![895428ad-6010-4ffd-bd88-61aecd50f5e1](https://user-images.githubusercontent.com/29896317/213889827-ca4f7673-115a-433e-9fde-305d55d36772.gif)

## Structure
This project consists of 3 parts:
- [![](https://img.shields.io/nuget/dt/Material.Icons?label=Material.Icons&style=flat-square)](#meta) contains info about the icons
- [![](https://img.shields.io/nuget/dt/Material.Icons.Avalonia?color=blue&label=Material.Icons.Avalonia&style=flat-square)](#avalonia) contains controls for **AvaloniaUI**
- [![](https://img.shields.io/nuget/dt/Material.Icons.WPF?color=blue&label=Material.Icons.WPF&style=flat-square)](#wpf) contains controls for **WPF**


- [FAQ](#faq) - frequently asked questions


## Meta
#### Getting started
Install [Material.Icons nuget package](https://www.nuget.org/packages/Material.Icons/):
```shell
dotnet add package Material.Icons
```
[![icons-nuget](https://img.shields.io/nuget/v/Material.Icons?label=Material.Icons&style=flat-square)][icons-nuget]
[![icons-nuget](https://img.shields.io/nuget/dt/Material.Icons?color=blue&label=Downloads&style=flat-square)][icons-nuget]

#### Using
Icon types stored in `Material.Icons.MaterialIconKind` enum.  

We can resolve an icon path by using `Material.Icons.MaterialIconDataProvider.GetData()`.  

In XAML use control MaterialIcon to show icon

...
    xmlns:icons="using:Material.Icons.WinUI"

....

    <icons:MaterialIcon Width="24" Height="24" Margin="4" HorizontalAlignment="Left" VerticalAlignment="Bottom" Foreground="Black" Kind="PersonTie" />

