FSharp.Configuration
===========================

The FSharp.Configuration project contains type providers for the configuration of .NET projects.

* [AppSettings](http://fsprojects.github.io/FSharp.Configuration/AppSettingsProvider.html)
* [ResX](http://fsprojects.github.io/FSharp.Configuration/ResXProvider.html)
* [Yaml](http://fsprojects.github.io/FSharp.Configuration/YamlProvider.html)
* [Ini](http://fsprojects.github.io/FSharp.Configuration/IniTypeProvider.html)

<a href="http://fsprojects.github.io/FSharp.Configuration" target="_blank">Documentation available here.</a>

## Build status

|  |  BuildScript | Status of last build |
| :------ | :------: | :------: |
| **Mono** | [build.sh](https://github.com/fsprojects/FSharp.Configuration/blob/master/build.sh) | [![Travis build status](https://travis-ci.org/fsprojects/FSharp.Configuration.png)](https://travis-ci.org/fsprojects/FSharp.Configuration) |
| **Windows** | [build.cmd](https://github.com/fsprojects/FSharp.Configuration/blob/master/build.cmd) | [![AppVeyor Build status](https://ci.appveyor.com/api/projects/status/eljpus4w1t7b0jic)](https://ci.appveyor.com/project/vasily-kirichenko/fsharp-configuration) |

## Testing

* Start FSharp.Configuration.sln and configure the project's debug mode to run `[YOURPATH]\FSharp.Configuration\FSharp.Configuration.Tests.sln` with `C:\Program Files (x86)\Microsoft Visual Studio 12.0\Common7\IDE\devenv.exe`.