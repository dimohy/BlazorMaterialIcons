# BlazorMaterialIcons

BlazorMaterialIcons is a library that helps you easily use Google's Material Icons in Blazor.


## Install package

Install BlazorMaterialIcons via NuGet in your project.

```ps
Install-Package BlazorMaterialIcons -ProjectName YourProject
```

Next, add the following to the head tag in **wwwroot/index.html** for Blazor Webassembly and **_Host.cshtml** for Blazor Server.
BlazorMaterialIcons is needed to access the Material icon in the font provided by Google.

```html
<head>
...
<link href="https://fonts.googleapis.com/css?family=Material+Icons|Material+Icons+Outlined|Material+Icons+Sharp|Material+Icons+Round|Material+Icons+Two+Tone" rel="stylesheet">
</head>
```


## Summary

BlazorMaterialIcons is designed to make it easy to use Material icons in the Blazor. There is also a purpose to see what a simple Blazor library looks like. (My first Blazor library.)

As you can see from the source code, this library is so simple that you can easily understand the Razor or Blazor environment.

## Usage

`<MaterialIcon>`
