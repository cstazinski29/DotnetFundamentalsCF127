# dotnet build

Builds a project and all of its dependencies.

The dotnet build command builds the project and its dependencies into a set of binaries. The binaries include the project's code in Intermediate Language (IL) files with a .dll extension. Depending on the project type and settings, other files may be included, such as:

- An executable that can be used to run the application, if the project type is an executable targeting .NET Core 3.0 or later.
- Symbol files used for debugging with a .pdb extension.
- A .deps.json file, which lists the dependencies of the application or library.
- A .runtimeconfig.json file, which specifies the shared runtime and its version for an application.
- Other libraries that the project depends on (via project references or NuGet package references).

## Resources

- [Dotnet Build Documentation](https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-build)

---

[Back to home](../README.md)