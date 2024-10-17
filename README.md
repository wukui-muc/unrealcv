# UnrealCV

[![Join the chat at https://gitter.im/unrealcv/unrealcv](https://badges.gitter.im/unrealcv/unrealcv.svg)](https://gitter.im/unrealcv/unrealcv?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Docs Status](https://readthedocs.org/projects/unrealcv/badge/?version=latest
)](http://docs.unrealcv.org)

<!-- [![Build Status](https://travis-ci.org/unrealcv/unrealcv.svg?branch=master)](https://travis-ci.org/unrealcv/unrealcv) -->

UnrealCV is a project to help computer vision researchers build virtual worlds using Unreal Engine (UE). It extends UE with a plugin by providing:

1. A set of UnrealCV commands to interact with the virtual world.
2. Communication between UE and an external program, such as Caffe.

UnrealCV can be used in two ways. The first one is using a compiled game binary with UnrealCV embedded. This is as simple as running a game, no knowledge of Unreal Engine is required. The second is installing the UnrealCV plugin into Unreal Engine and using the editor to build a new virtual world.


Please read [Tutorial: Getting Started](http://unrealcv.github.io/tutorial/getting_started.html) to learn using UnrealCV.

<center>
<img src="http://unrealcv.github.io/images/homepage_teaser.png" alt="annotation"/>
Images generated from the technical demo <a href="http://docs.unrealcv.org/en/master/reference/model_zoo.html#realisticrendering">RealisticRendering</a><br>
</center>

## New Features
 - Call any Blueprint function from Python by `vbp [obj_name] [func_name] [arg1] [arg2] ...` command.
 - Support RPC communication between Server and Client in Linux, higher FPS and more reliable.
 - A set of new commands for camera control and object manipulation, please refer to [command system](https://docs.unrealcv.org/en/latest/reference/commands.html) for more details.

## How to install UnrealCV
To install the UnrealCV Server, you need:
1. Download the source code and place it on the ``Plugin`` folder of a C++ UE project.
2. launch the C++ project with Visual Studio 2019, UnrealCV will be compiled at the same time.
3. To check the success installation of UnrealCV, you can run ``vget /unrealcv/status`` in the console (Press **`** to display the console).

To install the UnrealCV Client, just run:
``pip install unrealcv``


