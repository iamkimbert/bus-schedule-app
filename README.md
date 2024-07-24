# Bus Schedule App

**Bus Schedule App**: A C# application to manage and display bus routes and schedules. Includes `BusRoute` for route details, `BusRouteRepository` for managing routes and finding connections, and `BusTimes` for scheduling. Demonstrates route and timing handling via console output.

## Overview

This project provides a simple implementation for handling bus routes and their schedules. It includes:

- **`BusRoute` Class**: Represents a bus route with details such as route number, origin, destination, and places served.
- **`BusRouteRepository` Class**: Manages a collection of bus routes and provides methods to find routes serving specific locations or connections between locations. Includes sample scheduling data for a specific route.
- **`BusTimes` Class**: Stores and manages bus schedule timings for a given route.
- **`Program` Class**: Demonstrates how to use the above classes to print bus route details and timings to the console.

## Getting Started

### Prerequisites

- .NET Framework or .NET Core (depending on the version used)
- Visual Studio or any C# compatible IDE

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/bus-schedule-app.git
