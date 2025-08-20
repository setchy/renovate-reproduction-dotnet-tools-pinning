**Current behavior**
Updates in both `*.csproj` and `dotnet-tools.json` when pinning is enabled wraps versions in `[` and `]`

**Expected behavior**

- package reference inside `*.csproj` should be pinned (ie: [15.1.7]
- tools version inside `dotnet-tools.json` should not have `[` or `]` - breaks sdk

