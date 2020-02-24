
Content of this folder is intended for the manual deployment of CS-Script when for whatever reason you cannot use the recommended distribution mechanisms, which are:

- Chocolatey (https://chocolatey.org/)
  For standalone script engine (_cscs.exe_)

- NuGet (https://www.nuget.org/)
  For CS-Script class library (_CSScriptLibrary.dll_).

====================================================================

Directories content
-------------------
cs-script:
  cscs.exe - 4.5 build
  csws.exe - 4.5 build

cs-script\Lib:
  CSScriptLibrary.dll - 4.5 build
  CSScriptLibrary.v1.1.dll - 1.3.1 build

cs-script\Lib\Bin\Net 1.1:
  CSScriptLibrary.v1.1.dll - 1.1 build
  CSSCodeProvider.v1.1.dll - 1.1 build

cs-script\Lib\Bin\Net 3.5:
  CSScriptLibrary.dll - 3.5 build
  CSScriptLibrary.dll.unsigned - 3.5 unsigned build (just rename the file before usage)
  cscs.exe - 3.5 build
  csws.exe - 3.5 build

cs-script\Lib\Bin\Net 4.0:
  CSScriptLibrary.dll - 4.0 build

cs-script\Lib\Bin\Net 4.5:
  CSScriptLibrary.dll - 4.5 build
  CSScriptLibrary.dll.unsigned - 4.5 unsigned build (just rename the file before usage)
  cscs.exe - 4.5 build
  csws.exe - 4.5 build
  x86\cscs32.exe - 4.5 build for x86 CPU architecture
  x86\csws32.exe - 4.5 build for x86 CPU architecture

Linux
  Minimalistic distribution for Linux (see https://github.com/oleg-shilo/cs-script/wiki/CS-Script-on-Linux)

Roslyn
  Roslyn binaries that can be used as a custom (alternative) compiler for scripts written  in C# 6+ (https://github.com/oleg-shilo/cs-script/wiki/C%23-7-support-%28hosted%29).

Note:
- CS-Script build for .NET 4.5 is to be used on all .NET versions higher than v4.5 as all these versions are based on the same CLR and exhibit identical API that is used by CS-Script at runtime.
- CS-Script for .NET Core is managed under the dedicated GitHub project https://github.com/oleg-shilo/cs-script.core

