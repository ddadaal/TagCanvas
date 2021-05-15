# TagCanvas

NJUSE 2018年软件构造课程第一次作业，一个使用WPF的画图工具，支持识别画出来的形状。

## Features

- WPF (Windows Presentation Foundation) 
  - Targeting .NET Framework 4.5.2
- Dependency Management with [Autofac](https://autofac.org/)
  - Autofac is the ONLY dependency
- Complete MVVM Pattern
- Save and load graphs
  - Serialization and deserialization with good-old System.IO.Stream, Serializable and BinaryFormatter stuff
  - No JSON involved!

## Installation

Prebuilt binary is ready on `./TagCanvas/publish`. 

Run `setup.exe` to install the application on your machine. 

You can uninstall it anytime via Control Panel.

## Development

Visual Studio 2017 and "Windows Desktop Development" installation are required.