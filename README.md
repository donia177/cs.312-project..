# Inventory Management System

**CS312 – Modern Development Tools | GUI Design Stage**
Misr University for Science and Technology (MUST) – Group 54

## Project Overview

A desktop application built with **C# and Windows Forms (.NET 8)** that helps a business track products, manage suppliers, record stock movements and view reports.

> **Submission note:** this repository contains the **GUI Design stage** submission as `CS312_54_200041181_GUI.zip` (the complete Visual Studio solution). All screens are designed and open in the Visual Studio Designer.

## Technologies

- C# / Windows Forms (.NET 8, `net8.0-windows`)
- SQLite via `Microsoft.Data.Sqlite` (NuGet, restored automatically)
- Visual Studio 2022

## Main Features

1. **Dashboard** – KPI cards, donut chart, bar chart and low-stock alerts (custom GDI+ controls).
2. **Products** – add, edit, delete, live search, low/out-of-stock filter.
3. **Suppliers** – add, edit, delete and search suppliers.
4. **Stock Movements** – stock-in / stock-out with a searchable history.
5. **Reports** – five inventory reports with statistics and CSV export.
6. **Settings** – SMTP configuration for low-stock e-mail alerts.
7. **Authentication** – first-run admin setup, login, change password, user management.

## How to Open the Project

1. Download and extract `CS312_54_200041181_GUI.zip`.
2. Open `InventoryManager.sln` in Visual Studio 2022 (".NET desktop development" workload + .NET 8 SDK).
3. Wait for NuGet restore, then choose **Build → Rebuild Solution**.
4. Right-click any `.cs` file (e.g. `MainForm.cs`, `ProductsPanel.cs`) → **View Designer**.
5. Press **F5** to run. On first run the app asks you to create the administrator account.

## Team Members

| Name | Student ID |
|------|-----------|
| Donia Ashraf | 200041181 |
| Fares Ahmed | 200042841 |
| Nada Osama | 200043782 |
| Ziad Amr | 200054096 |
| Mohamed Amr | 200053998 |
| Mark John | 200036305 |

## License

Developed for academic purposes as part of the CS312 – Modern Development Tools course.
