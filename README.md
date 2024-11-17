# Financial Management Application

## Introduction
Welcome to the repository for the Financial Management Tracking Application. This repository is a sample project used for exploring Blazor and, eventually, MAUI.

## Description
The Financial Management Tracker is an application that allows us to track financial events related to various accounts and services.

## Requirements
The Financial Management Tracker application should be able to:
- Allow users to track various financial accounts, transactions, and balances
- Allow users to set up recurring debits/credits
- Display information about financial events
- Provide analysis on spending habits
- Display futures in charts and data table formats

At the moment, we are not planning on giving the application direct access to the financial accounts. The application should have its own user store setup on the machine the application is running on. Eventually, we may add functionality for the user to use a cloud service to store their data.

## Choices
Below are some choices we made for starting the project. Please note that these are subject to change as we dive into the project.
- **Database**: SQL (most likely SQLite) using EntityFrameworkCore as the ORM
- **Language and SDK**: C# and Razor using the latest .NET SDK (.NET 8 at the time of this writing)
- **Web Technology/Project Type**: Blazor Server and Blazor WASM with a Shared UI and Server Services, and separate Client-side service implementations
- **UI Frameworks**: We decided to remove all third-party CSS libraries and are planning on not using third-party Blazor Component Libraries