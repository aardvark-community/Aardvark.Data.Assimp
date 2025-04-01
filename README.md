# Aardvark.Data.Assimp

![Publish](https://github.com/aardvark-community/aardvark.data.assimp/workflows/Publish/badge.svg)


[![NuGet](https://badgen.net/nuget/v/Aardvark.Data.Assimp)](https://www.nuget.org/packages/Aardvark.Data.Assimp/)
[![NuGet](https://badgen.net/nuget/dt/Aardvark.Data.Assimp)](https://www.nuget.org/packages/Aardvark.Data.Assimp/)

[Assimp](https://github.com/assimp/assimp) wrapper for the Aardvark Platform based on [AssimpNet](https://bitbucket.org/Starnick/assimpnet) and [AssimpNetter](https://github.com/Saalvage/AssimpNetter).

Supported platforms:
- Windows (x64)
- Linux (x64)
- MacOS (x64, ARM64)

## Updating native binaries
Native binaries are built using Github CI and [vcpkg](https://vcpkg.io/). Modify the version specified in `vcpkg/vcpkg.json` and manually trigger the workflow.