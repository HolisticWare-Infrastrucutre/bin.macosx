# Release v3.30.0
----------------
- Issue #25: Feature request to support conditional directives
* Merge pull request #159 from HugoRoss/patch-3
- Issue #160: Compatibility with old script syntax
- Issue #161: Assembly is (tried to be) loaded from GAC instead of local dir
- Triggered by issue #172: CsvHelper loads the wrong ValueTuple version in CSScript?
- Issue #173: C# script installation on Window10 / WSL linux does not work
- Added support for _gitignore_ syntax in `//css_` directives (e.g. `//css_ref .\**\Release\*.dll`)
- Added processing precompilers output for `-proj` option
- Added debugVS2019.cs
- Improved version info output
- Fixed all urls pointing to the old web hosting
- Added support for PreferredRuntime of the dependency packages when resolving them.
- Added VB samples for NuGet package (partial solution for #155)
- Added syntax help output info