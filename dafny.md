---
layout: page
title: Set up Dafny
description: How to set up Dafny
---

# Installing Dafny on Visual Studio Code

To install Dafny in Visual Studio Code, you need first to download and install Visual Studio Code if you do not have it already. On Linux and Mac Os you will also need the latest version of Mono.

Once you have Visual Studio Code, you can install the Dafny extension for Visual
Studio Code following [these
instructions](https://marketplace.visualstudio.com/items?itemName=dafny-lang.ide-vscode). This
extension contains everything you need, including its own copy of Dafny.

**Note**: you need to have .NET installed. Only the runtime one is necessary. If you want to install it on Ubuntu, for example, you can follow [these instructions](https://docs.microsoft.com/en-us/dotnet/core/install/linux-ubuntu), or likewise look for similar instructions for your environment. To install on Windows, you can download the SDK (preferably version >= 6) and install, then you must configure the executable path of the dotnet.exe file when prompted in Visual Studio Code.

# Using Dafny

Opening a Dafny file (with a `.dfy` extension) with Visual Studio or Visual Studio Code will allow you to see syntax highlighting as well as any errors, as underlined text, in the code or specification. Dafny is reinvoked automatically as you edit the text.
