# Xamarin.MikePenz.MaterialDrawer [![NuGet Badge](https://buildstats.info/nuget/Xamarin.MikePenz.MaterialDrawer)](https://www.nuget.org/packages/Xamarin.MikePenz.MaterialDrawer/) 

Port of https://github.com/mikepenz/MaterialDrawer to Xamarin.

## How to use

Have a look at [README.md](https://github.com/mikepenz/MaterialDrawer/blob/develop/README.md)

## How to install

### Android

Add [Nuget](https://www.nuget.org/packages/Xamarin.MikePenz.MaterialDrawer)

        PM> Install-Package Xamarin.MikePenz.MaterialDrawer -Version 6.0.8

## How to build

    msbuild Xamarin.MikePenz.MaterialDrawer.sln /t:Xamarin.MikePenz.MaterialDrawer /p:Configuration="Release" /p:BuildProjectReferences=false

## How to publish nupkg

E.g.: to [https://www.nuget.org/](https://www.nuget.org/) using [myApiKey](https://www.nuget.org/account/apikeys)

    nuget push Xamarin.MarkdownView/bin/Release/*.nupkg -Source https://api.nuget.org/v3/index.json -ApiKey myApiKey

## Contributors

[Jan Rabe](jan.rabe@kibotu.net)

### License
<pre>
Copyright 2018 Jan Rabe

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
</pre>
