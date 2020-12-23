| README.md |
|:---|

<h1 align="center">Cake.Extensions</h1>
<div align="center">

(Proof-of-concept) Provides a default set of APIs for building [Cake](https://cakebuild.net) extensions such as add-ins and modules.

[![NuGet Version](http://img.shields.io/nuget/v/Cake.Extensions.PoC.svg?style=flat-square)](https://www.nuget.org/packages/Cake.Extensions.PoC/) [![Stack Overflow](https://img.shields.io/badge/stack%20overflow-cakebuild-orange.svg?style=flat-square)](http://stackoverflow.com/questions/tagged/cakebuild)

</div>

## Getting started :rocket:

```xml
<Project Sdk="Microsoft.NET.Sdk">

  <PropertyGroup>
    <TargetFrameworks>net5.0;netstandard2.0;net461</TargetFrameworks>
  </PropertyGroup>

  <ItemGroup>
    <PackageReference Include="Cake.Extensions.PoC" Version="0.0.2-preview" PrivateAssets="All" />
  </ItemGroup>

</Project>
```

See the [Cake.Addins.Sample](https://github.com/augustoproiete/cake-addins-sample) source code for a full example.

---

_Copyright &copy; 2020 C. Augusto Proiete & Contributors - Provided under the [MIT License](LICENSE)._
