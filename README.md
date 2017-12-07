# SampleProjectForNuget
Reproduce steps:
1. build project
2. `cd .\ClassLibrary1\`
3. `nuget.exe pack`

check the result packages, the content files is included.
When we remove the `file` tag in nuspec, the content files is excluded.
