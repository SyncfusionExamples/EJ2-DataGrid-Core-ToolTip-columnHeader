# ASP.NET CORE DataGrid - ToolTip ColumnHeader

## Repository Description

This repository contains an ASP.NET Core sample application that demonstrates the EJ2 DataGrid with remote data binding and tooltip integration for grid column headers using Syncfusion EJ2 components.

## Project Overview

The application renders an EJ2 DataGrid inside an EJ2 Tooltip component to display contextual information for grid headers. A tooltip is dynamically updated during mouse interactions and displays the header text when the pointer moves over specific columns. The sample focuses on combining grid rendering, remote data binding, and client-side event handling within an ASP.NET Core MVC environment.

## Features

- EJ2 DataGrid integration with ASP.NET Core 
- Remote data binding using server-provided data
- Tooltip rendering for grid header columns
- Dynamic tooltip content update on mouse interaction
- Clean Razor and JavaScript integration

## Prerequisites

- .NET Core SDK 8.x
- Visual Studio 2019 or later
- ASP.NET Core MVC knowledge
- Syncfusion EJ2 packages referenced in the project

## Running the application

1. Clone the repository to the local machine.
    ```
    git clone <repo_link>
    ```
2. Open the solution file in Visual Studio.
3. Restore all NuGet packages.
4. Run the application using the following commands:
    ```
    dotnet build
    dotnet run
    ```

## Usage

When the application loads, the grid retrieves data from the server and renders it. Moving the mouse over configured header columns displays a tooltip showing the corresponding header text.

### Reference

- [Getting started with ASP.NET CORE Grid](https://ej2.syncfusion.com/aspnetcore/documentation/grid/getting-started-core) 
- [Databinding](https://ej2.syncfusion.com/aspnetcore/documentation/grid/data-binding/data-binding)
- [Tooltip](https://ej2.syncfusion.com/aspnetcore/documentation/tooltip/getting-started)
- [API Reference](https://help.syncfusion.com/cr/aspnetcore-js2/syncfusion.ej2.grids.grid.html) 