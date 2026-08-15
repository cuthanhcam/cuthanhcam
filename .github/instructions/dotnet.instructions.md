---
applyTo: "**/*.cs,**/*.csproj,**/*.sln,**/*.slnx,**/Directory.Build.*"
---

# .NET instructions

- Follow the SDK version in `global.json` and the repository-wide build properties.
- Keep nullable reference types and analyzers enabled; fix warnings introduced by the change.
- Prefer async APIs end to end and pass `CancellationToken` through I/O and request boundaries.
- Preserve project layering and dependency direction. Add packages only when the platform or existing dependencies cannot solve the problem cleanly.
- Format touched code with `dotnet format` when available, then build and run the relevant tests from the repository root.
