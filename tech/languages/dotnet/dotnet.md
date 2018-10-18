---
title: .NET Core
subsection: dotnet
section: tech-languages
order: 1
version: 7.8.4
description: ".NET Core and Mono open source frameworks, and available IDEs."
---

[.NET Core](https://docs.microsoft.com/en-us/dotnet/core/) is a general-purpose, modular, cross-platform and open-source development Platform.

## .NET Core Installation

Enable the .NET SIG's copr repository:
```
$ sudo dnf copr enable @dotnet-sig/dotnet
```

Install the latest SDK:
```
$ sudo dnf install dotnet
```

Or a specific version:
```
$ sudo dnf install dotnet-sdk-2.1
```

To install runtime only, for example to merely deploy already prebuilt applications, where _x_ stands for major and _y_ stands for minor version:
```
$ sudo dnf install dotnet-runtime-x.y
```

## Getting Started

You can create your first console app following instructions in [this official guide](https://www.microsoft.com/net/learn/get-started-with-dotnet-tutorial#create).