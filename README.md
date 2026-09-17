# Syncfusion Blazor Server DataGrid - Row Drag and Drop with CustomAdaptor

## Overview

This sample demonstrates row drag-and-drop functionality within a Syncfusion Blazor DataGrid using a CustomAdaptor as the data source layer. The implementation is designed to support reordering records inside the same Grid and processing the updated record positions through the adaptor's batch update workflow. When a row is moved, the Grid sends the reordered record information to the CustomAdaptor, enabling the underlying collection to be updated and synchronized with the new order. This sample is useful for applications that require user-controlled row sequencing while maintaining custom server-side or in-memory data processing logic.

## Key Features

- Demonstrates row drag-and-drop operations within a single Syncfusion Blazor DataGrid.
- Uses a CustomAdaptor implementation as the Grid data source.
- Processes reordered records through the CustomAdaptor batch update workflow.
- Demonstrates handling of the inserted record position after a drag-and-drop operation.
- Uses project assets contained within the `Pages` and `Data` folders to support Grid rendering and data processing.

## Prerequisites

* Visual Studio 2022 or Visual Studio Code
* .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download the repository.
2. Open the solution file: `DragandDropWithCustomAdaptor.sln`
3. Restore NuGet packages.
4. Set the startup project to: `DragandDropWithCustomAdaptor` 
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the folder containing `DragandDropWithCustomAdaptor.csproj`.

```bash
dotnet restore
```

```bash
dotnet run
```
4. Open the URL displayed by the ASP.NET Core host in your browser.

## Project Structure

`Pages/` — contains the Blazor page that hosts the DataGrid row drag-and-drop sample implementation.
`Data/` — contains the CustomAdaptor implementation, sample data source logic, and supporting data models used during row reordering.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official Syncfusion DataGrid row drag-and-drop documentation: https://help.syncfusion.com/grid-sdk/blazor/data-grid/row-drag-and-drop

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.