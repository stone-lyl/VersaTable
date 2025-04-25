# VersaTable

A Next.js friendly project built with React, TypeScript, and data-table-filters for creating versatile data tables.

## Project Overview

VersaTable is a comprehensive data management system that provides powerful data visualization and analysis capabilities. The project is built using Next.js, React, TypeScript, and leverages [data-table-filters](https://github.com/openstatusHQ/data-table-filters) for advanced table functionality.

## Features

- **Data Analysis System**: A dedicated page for analyzing and visualizing data with interactive charts and tables
- **Logging System**: A comprehensive logging interface for monitoring system activities
- **Reusable Table Component**: A shared table component that can be customized for different use cases

## Tech Stack

- Next.js for server-side rendering and routing
- React for building user interfaces
- TypeScript for type safety
- data-table-filters for advanced table filtering capabilities


## Run tasks

To run the dev server for your app, use:

```sh
npx nx dev VersaTable
```

To create a production bundle:

```sh
npx nx build VersaTable
```

To see all available targets to run for a project, run:

```sh
npx nx show project VersaTable
```

These targets are either [inferred automatically](https://nx.dev/concepts/inferred-tasks?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects) or defined in the `project.json` or `package.json` files.

[More about running tasks in the docs &raquo;](https://nx.dev/features/run-tasks?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects)

## Project Structure

```
├── apps/
│   └── VersaTable/        # Main Next.js application
│       ├── app/
│       │   ├── analysis/   # Data Analysis System page
│       │   └── logs/       # Logging System page
│       └── components/
│           └── ui/
│               └── Table/  # Shared Table component
└── packages/              # Shared libraries
```

## Getting Started

1. Clone the repository
2. Install dependencies: `npm install`
3. Start the development server: `npx nx dev VersaTable`
4. Open your browser and navigate to `http://localhost:3000`

## Pages

### Data Analysis System

The Data Analysis System page provides a comprehensive interface for analyzing and visualizing data. It includes:

- Interactive data tables with advanced filtering
- Data visualization components
- Export functionality

### Logging System

The Logging System page offers a detailed view of system logs with features such as:

- Real-time log monitoring
- Log filtering and search
- Log level management

## Components

### Shared Table Component

The shared Table component is a versatile and reusable component that provides:

- Advanced filtering using data-table-filters
- Sorting and pagination
- Customizable columns and cell renderers
- Responsive design
