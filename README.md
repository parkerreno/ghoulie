# Ghoulie Docs
This is the docfx repo used to power the Ghoulie Docs.

## Getting Started
Once you have the repo cloned, here are the steps to get it up and running!

1. Install .NET - as of writing 8 is the latest release and LTS, 6 or higher is required
    ```
    winget install Microsoft.DotNet.SDK.8
    ```
2. Install docfx
    ```
    dotnet tool install -g docfx
    ```
3. Run docfx
    ```
    docfx --serve
    ```

For more information on docfx, see https://dotnet.github.io/docfx/