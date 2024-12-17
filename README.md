# FLOWBITE-BLAZOR-DESKTOP-STARTER

**⚠️ Flowbite Blazor Desktop is currently in early development and APIs and packages are likely to change quite often.**

## Application Shell Examples

| Feature                     | Implemented | Docs |
| --------------------------- | ----------- | ---- |
| EmptyLayout                 |             |      |
| MainLayout                  |             |      |
| StackedLayout               |             |      |
| Sidebar                     |             |      |
| Footer                      |             |      |
| ApplicationVersion          |             |      |
| Counter Example Page        |             |      |
| Fetch Data Example Page     |             |      |
| Run Executable Example Page |             |      |
| Authentication Example Page |             |      |
| Icon Example Page           |             |      |
| Component Example Page      |             |      |

## Building and Publishing the Installer

To build and publish the application, and optionally create an installer, use the `build.ps1` script located in the root directory of the project.

### Usage

The `build.ps1` script supports the following options:

- **Build the project:**

    ```powershell
    .\build.ps1
    ```

- **Build the project and create the installer:**

    ```powershell
    .\build.ps1 -dist
    ```

- **Display help information:**

    ```powershell
    .\build.ps1 -Help
    ```

### Prerequisites

- Ensure you have the .NET SDK installed.
- Ensure you have Inno Setup installed if you want to create an installer.

### Steps

1. Open a PowerShell window in the root directory of the project.
2. Run the `build.ps1` script with the desired options.
3. If creating an installer, the installer executable will be located in the `dist` directory in the project root.
