# Boardgames Management System with Entity Framework Core

## Overview

This repository contains a Boardgames Management System developed with Entity Framework Core following a Code First approach. Designed to facilitate the management of board game collections, it allows users to track board games, publishers, and related gameplay statistics.

## Project Structure 

- `Data`: Contains the `DbContext` and configuration classes for Entity Framework.
- `Models`: Includes domain model classes for BoardGame, Publisher, and PlayerStats.
- `Configuration`: Holds settings such as the database connection string.
- `Services`: Business logic for managing board game data operations.
- `Datasets`: Sample datasets for seeding the database with initial data.
- `Utilities`: Helper functions and utilities for data import/export and other operations.

## Model Definition

The models represent different aspects of board games, such as `BoardGame`, `Publisher`, and `PlayerStats`. Each class is defined with properties like `GameTitle`, `ReleaseDate`, `PublisherName`, etc., and includes data annotations for entity relationships and validation.

## Data Management

- `Import`: Capability to import board game data from external sources.
- `Export`: Functionality to export data for reporting or analysis.

## Usage

1. Fork or clone the repository to your local environment.
2. Make sure you have .NET Core SDK installed (preferably version 3.1 or later).
3. Open the terminal, navigate to the project directory, and run `dotnet restore`.
4. Execute `dotnet run` to launch the system.

## Contribution

Contributors are welcome! If you have suggestions or improvements, please fork the repository, commit your updates, and open a pull request with your changes.

## License

This project is open-sourced under the MIT License. See the LICENSE file for full details.
