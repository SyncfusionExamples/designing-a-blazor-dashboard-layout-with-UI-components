# Designing a Blazor Dashboard Layout with UI Components

## Project Overview

This sample demonstrates how to design a dashboard with the Syncfusion [Blazor Dashboard Layout](https://www.syncfusion.com/blazor-components/blazor-dashboard) component and host other UI components inside its panels. The application arranges income, expense, balance, and transaction panels with `CellSpacing`, styles the panels, and places a spline-area chart, an accumulation chart, and a data grid in the panel content. The layout also uses a media query so the panels adapt to smaller screens.

## Features

- Uses the Syncfusion Blazor `SfDashboardLayout` component to arrange dashboard panels.
- Sets `Columns` to `8`, `CellSpacing` to `10`, and `MediaQuery` to `max-width:700px`.
- Defines each panel with `HeaderTemplate` and `ContentTemplate`.
- Shows income, expenses, balance, and transactions in the first row of panels.
- Renders an `SfChart` spline-area series for income and expense values.
- Renders an `SfAccumulationChart` for total expenses with custom palettes.
- Renders an `SfGrid` of recent transactions with category and amount templates.
- Styles panel headers, amounts, and category icons in `Pages/Index.razor`.
- Loads panel images from `wwwroot`.

## Prerequisites

Ensure the following requirements are met before running this project:

- Visual Studio 2022 or Visual Studio Code
- [.NET 10 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later

## Installation

### Clone the Repository

Clone the repository and navigate to the project directory:

```shell
git clone https://github.com/SyncfusionExamples/designing-a-blazor-dashboard-layout-with-UI-components.git
```

### Run the Application

**Visual Studio 2022**

1. Open the cloned repository folder.
2. Open the project file:

`BlazorApp__DashBoard.csproj`

3. Restore the NuGet packages by rebuilding the project.
4. Set the startup project to:

`BlazorApp__DashBoard`

5. Build the project.
6. Run the application using `Ctrl+F5`.
7. Open the application URL displayed by Visual Studio after launch.
8. Verify that the dashboard panels, charts, and transaction grid are displayed.

**Visual Studio Code**

1. Open the cloned repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory:

```shell
cd designing-a-blazor-dashboard-layout-with-UI-components
```

4. Restore the NuGet packages:

```shell
dotnet restore
```

5. Run the project:

```shell
dotnet run
```

6. Open the local URL displayed in the terminal after the application starts.
7. Verify that the dashboard panels, charts, and transaction grid are displayed.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation: [Blazor Dashboard Layout getting started](https://help.syncfusion.com/chart-sdk/blazor/dashboard-layout/getting-started)

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
