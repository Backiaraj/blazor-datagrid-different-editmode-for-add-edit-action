# Blazor DataGrid — Different Edit Modes for Add and Edit Actions

A sample Blazor application demonstrating how to dynamically switch between different edit modes (Dialog vs. Inline) when adding or editing records in the [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) component.

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
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting started

### Clone and open the project

```bash
git clone https://github.com/SyncfusionExamples/blazor-datagrid-different-editmode-for-add-edit-action.git
cd blazor-datagrid-different-editmode-for-add-edit-action
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

**Documentation**: https://blazor.syncfusion.com/documentation/datagrid/dialog-editing

**Online example**: https://blazor.syncfusion.com/demos/datagrid/dialog-editing?theme=fluent2
