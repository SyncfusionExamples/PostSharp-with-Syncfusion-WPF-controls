# PostSharp-with-Syncfusion-WPF-controls

This sample demonstrates how to use PostSharp with Syncfusion WPF controls, specifically the WPF Data Grid control. It shows how to apply PostSharp's attribute-based features, such as dependency properties and commands, while integrating them with Syncfusion's data grid features.

## Overview

PostSharp is an aspect-oriented programming (AOP) framework for .NET that helps reduce repetitive code and separate cross-cutting concerns such as validation, logging, and property management. This sample highlights how those features can be used together with a Syncfusion WPF Data Grid in a practical WPF application.

## Features

- PostSharp integration in a WPF application
- Syncfusion WPF Data Grid data binding and customization
- Dependency property and attached property examples
- Command-based behavior on loaded events
- Simple employee data model for grid demonstration

## Project details

The sample application includes:

- MainWindow.xaml — defines the WPF UI and binds the grid to the view model
- EmployeeViewModel.cs — contains employee data and grid load command logic
- CustomGrid.cs — custom grid class inheriting from WPF Data Grid with PostSharp dependency properties

The custom grid demonstrates the use of PostSharp's [DependencyProperty] and [AttachedProperty] attributes to create reusable properties with validation logic.

## Prerequisites

- Visual Studio 2019 or later
- .NET Framework 4.6+ or a supported .NET version for your project setup
- Syncfusion WPF assemblies
- PostSharp installed via NuGet
- Windows operating system

## Getting started

1. Clone this repository.
2. Open the solution file in Sample/SyncfusionPostSharp.sln.
3. Restore the NuGet packages.
4. Build the project in Visual Studio.
5. Run the application to see the grid and PostSharp integration in action.

## Project structure

- Sample/SyncfusionPostSharp — WPF sample project
- Sample/SyncfusionPostSharp.sln — Visual Studio solution file
- Sample/SyncfusionPostSharp/ViewModel — view models and commands
- Sample/SyncfusionPostSharp/DependencyProperty — custom grid and PostSharp property examples

## Resources

- [PostSharp Documentation](https://www.postsharp.net/)
- [Syncfusion WPF Controls](https://www.syncfusion.com/wpf-controls)
- [Syncfusion SfDataGrid Documentation](https://help.syncfusion.com/wpf/datagrid/overview)
