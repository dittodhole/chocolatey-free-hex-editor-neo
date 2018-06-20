![](assets/icon-256x256-hex-editor-neo.png)

#  chocolatey-free-hex-editor-neo

> Free Hex Editor Neo is the fastest large files optimized binary file editor for Windows platform developed by HHD Software Ltd.

## Installing

### [myget.org][1]

[![](https://img.shields.io/appveyor/ci/dittodhole/chocolatey-free-hex-editor-neo/develop.svg)][2]
[![](https://img.shields.io/myget/dittodhole/vpre/free-hex-editor-neo.svg)][1]

```cmd
choco install free-hex-editor-neo --pre --source https://www.myget.org/F/dittodhole/api/v2
```

### [chocolatey.org][3]

[![](https://img.shields.io/appveyor/ci/dittodhole/chocolatey-free-hex-editor-neo/master.svg)][4]
[![](https://img.shields.io/chocolatey/v/free-hex-editor-neo.svg)][3]

```cmd
choco install free-hex-editor-neo
```

## Developing & Building

```cmd
> git clone https://github.com/dittodhole/chocolatey-free-hex-editor-neo.git
> cd chocolatey-free-hex-editor-neo/
chocolatey-free-hex-editor-neo> cd build
chocolatey-free-hex-editor-neo/build> npm install
chocolatey-free-hex-editor-neo/build> npm run-script build
```

This will create the following artifacts:

- `artifacts/free-hex-editor-neo.{version}.nupkg`

## License

chocolatey-free-hex-editor-neo is published under [WTFNMFPLv3](https://github.com/dittodhole/WTFNMFPLv3).

[1]: https://www.myget.org/feed/dittodhole/package/nuget/free-hex-editor-neo
[2]: https://ci.appveyor.com/project/dittodhole/chocolatey-free-hex-editor-neo/branch/develop
[3]: https://chocolatey.org/packages/free-hex-editor-neo
[4]: https://ci.appveyor.com/project/dittodhole/chocolatey-free-hex-editor-neo/branch/master