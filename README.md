# Blazor Server DataGrid with Row Drag and Drop

A demonstration project showcasing how to implement row drag and drop functionality in a [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) using a custom data adaptor. This example provides a complete, production-ready implementation with sorting, filtering, paging, and data management capabilities.

## Overview

This project demonstrates advanced row drag and drop interactions with the Blazor DataGrid component. By implementing a custom adaptor, the application automatically triggers batch update operations when users reorder rows, enabling sophisticated data manipulation without complex client-server communication patterns.

The sample includes:
- Real-time row reordering with visual feedback
- Custom data adaptor implementation with full CRUD operations
- Batch update handling for multiple row changes
- Data virtualization for efficient rendering of large datasets
- Integrated sorting, filtering, and paging capabilities

## Key Features

- **Row Drag and Drop**: Drag rows to reorder them within the grid
- **Custom Data Adaptor**: Full control over data operations with Read, Insert, Update, Remove, and BatchUpdate methods
- **Sorting & Filtering**: Built-in capabilities for data organization
- **Paging**: Efficient data loading with configurable page sizes
- **Data Virtualization**: Fast rendering of large datasets
- **Reactive Updates**: Automatic UI synchronization with data changes

## Getting Started

### Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

### Clone the Repository

```bash
git clone https://github.com/SyncfusionExamples/EJ2-DataGrid-BlazorServer-Drag-and-Drop-CustomAdaptor.git
cd DragandDropWithCustomAdaptor
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References

**Documentation**: 
* https://blazor.syncfusion.com/documentation/datagrid/row-drag-and-drop
* https://blazor.syncfusion.com/documentation/datagrid/connecting-to-adaptors/custom-adaptor

**Online example**: https://blazor.syncfusion.com/demos/datagrid/row-drag-and-drop?theme=bootstrap5