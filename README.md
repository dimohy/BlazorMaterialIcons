# BlazorMaterialIcons

BlazorMaterialIcons is a library that helps you easily use Google's Material Icons in Blazor.
You can see a list of all icons in [Google's Material Icons](https://material.io/resources/icons/?style=baseline)


## Summary

BlazorMaterialIcons is designed to make it easy to use Material icons in the Blazor. There is also a purpose to see what a simple Blazor library looks like. (My first Blazor library.)

As you can see from the source code, this library is so simple that you can easily understand the Razor or Blazor environment.


## Install package

Install BlazorMaterialIcons via NuGet in your project.

```ps
dotnet add package BlazorMaterialIcons
```

Next, add the following to the head tag in **wwwroot/index.html** for Blazor Webassembly or **_Host.cshtml** for Blazor Server.
BlazorMaterialIcons is needed to access the Material icon in the font provided by Google.

```html
<head>
...
<link href="https://fonts.googleapis.com/css?family=Material+Icons|Material+Icons+Outlined|Material+Icons+Sharp|Material+Icons+Round|Material+Icons+Two+Tone" rel="stylesheet">
</head>
```


## Usage

The icon can be displayed via the `<MaterialIcon>` tag.
Specify the icon name with the `Kind` attribute. Alternatively, you can assign an icon name directly to the contents of the tag.
The Google Material icon can display icons with five themes. Themes are accessed via the `Theme` property.
You can resize the icon through the `Size` property. (Default size is 24px)

Please refer to the following usage

```html
<MaterialIcon Kind="face" />

<MaterialIcon>face</MaterialIcon>

<MaterialIcon Theme="@MaterialIcon.Themes.Filled" Size="12">cast_connected</MaterialIcon>
<MaterialIcon Theme="@MaterialIcon.Themes.Outlined" Size="24">cast_connected</MaterialIcon>
<MaterialIcon Theme="@MaterialIcon.Themes.Rounded" Size="48">cast_connected</MaterialIcon>
<MaterialIcon Theme="@MaterialIcon.Themes.Sharp" Size="64">cast_connected</MaterialIcon>
<MaterialIcon Theme="@MaterialIcon.Themes.TwoTone" Size="128">cast_connected</MaterialIcon>
```
