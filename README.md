
This projet is UNO/WinUI3 Version of MaterialIcon control 

of project https://github.com/SKProCH/Material.Icons

Special thanks to https://github.com/SKProCH

#Packages 

[icons-nuget]: https://www.nuget.org/packages/Material.Icons/
[UNO/WinUi3-nuget]: https://www.nuget.org/packages/Material.Icons.UNO/

# Material.Icons
Parsed icons set from [materialdesignicons.com](https://materialdesignicons.com/) and display control implementations for different GUI frameworks.  
- All icons are **always up-to-date** because automatically updated every 6 hours.
- **Small package size** because icons are graphically encoded via SVG Path.
- Icon types are **strongly typed** enum, so your **IDE will suggest available variants**:  
![895428ad-6010-4ffd-bd88-61aecd50f5e1](https://user-images.githubusercontent.com/29896317/213889827-ca4f7673-115a-433e-9fde-305d55d36772.gif)

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

```
xmlns:icons="using:Material.Icons.UNO"
```

```
    <icons:MaterialIcon Width="24" Height="24" Margin="4" HorizontalAlignment="Left" VerticalAlignment="Bottom" Foreground="Black" Kind="PersonTie" />
```
