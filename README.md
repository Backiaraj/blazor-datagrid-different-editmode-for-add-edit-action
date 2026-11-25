# Blazor DataGrid — Different Edit Modes for Add and Edit Actions

A sample Blazor application demonstrating how to dynamically switch between different edit modes (Dialog vs Inline) when adding or editing records in the [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) component.

## Overview

This project illustrates a common use case where different edit modes improve usability. When users create a new record, a Dialog provides a clean, dedicated form experience. When editing existing records, inline editing allows quick modifications without context switching.

The sample includes:
- Event-driven edit mode switching
- Dialog mode for adding new records
- Inline mode for editing existing records
- Grid row validation
- Sample data with Orders information

## Features

- **Dynamic Edit Mode Switching** - Automatically switches between Dialog mode for new records and Inline mode for editing existing records based on user action
- **Full CRUD Operations** - Add, Edit, and Delete records with complete toolbar integration and batch action support
- **Event-Driven Logic** - Uses `RowCreating` and `RowEditing` events for seamless control of edit behavior
- **Specialized Editors** - DatePicker for dates, NumericEdit for numbers, and DropDown for selections
- **Data Validation** - Required field validation with built-in error handling on form submission
- **Formatted Display** - Currency formatting and date formatting for professional data presentation
- **Responsive Paging** - 15 rows per page with automatic paging controls for efficient data browsing
- **Accessible Toolbar** - Built-in toolbar with standard CRUD actions readily accessible

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2026](https://visualstudio.microsoft.com/downloads/) or [Visual Studio Code](https://code.visualstudio.com/)

## Run with Visual Studio

**Visual Studio 2026**:

* Checkout this project to a location in your disk.
* Open the project (`Grid_EditMode.csproj`) file.
* Restore the NuGet packages.
* Run the project.

**Visual Studio Code**:

* Checkout this project to a location in your disk.
* Open the repository folder in Visual Studio Code.
* Open the integrated terminal.
* Navigate to the repository root.

```bash
cd blazor-datagrid-different-editmode-for-add-edit-action
dotnet restore
dotnet run
```

Open the URL displayed in the terminal after the application starts.

## References

**Documentation**: https://help.syncfusion.com/grid-sdk/blazor/data-grid/dialog-editing

**Online example**: https://blazor.syncfusion.com/demos/datagrid/dialog-editing?theme=fluent2
