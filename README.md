# Project Name

This project is a React-based application with organized components, pages, and utilities. The following document outlines the file structure and key components of the project.

## File Structure

### `src/`
This is the main source directory containing all application code.

- `components/`: Shared components used across the application.
  - Layout.tsx: Defines the layout structure for the application.

- `pages/`: Contains the main pages of the application, each representing a feature or section.
  - `Calendar/`: Handles the calendar view and related functionality.
    - CalendarDay.tsx: Represents a single day in the calendar.
    - CalendarGrid.tsx: Manages the grid view of the calendar.
    - CommunicationList.tsx: Lists communications for a selected date.
    - CommunicationModal.tsx: Modal for viewing or editing a communication.
    - NotificationPanel.tsx: Displays notifications related to the calendar.
    - utils.ts: Utility functions for the calendar page.
    - index.tsx: Entry point for the calendar page.
  - `Companies/`: Manages company-related functionality.
    - AddCompanyButton.tsx: Button to add a new company.
    - CompanyList.tsx: Displays a list of companies.
    - CompanyModal.tsx: Modal for viewing or editing a company.
    - CompanyRow.tsx: Represents a single company in a list.
    - index.tsx: Entry point for the companies page.
  - `Reports/`: Handles report generation and display.
    - `components/`: Contains subcomponents for reports.
      - CompanySelect.tsx: Dropdown to select a company.
      - DateRangePicker.tsx: Date range picker for filtering reports.
    - ActivityLog.tsx: Displays activity logs.
    - CommunicationFrequency.tsx: Shows frequency of communications.
    - Dashboard.tsx: Main dashboard for reports.
    - EngagementEffectiveness.tsx: Displays engagement metrics.
    - OverdueTrends.tsx: Highlights overdue trends.
    - utils.ts: Utility functions for the reports page.
    - index.tsx: Entry point for the reports page.
  - Dashboard.tsx: Main dashboard page.

- `store/`: Manages application state.
  - useStore.ts: Custom hooks for state management.

- `types/`: Contains type definitions for the application.
  - index.ts: Centralized type definitions.

- Root Files:
  - App.tsx: Main application component.
  - index.css: Global styles for the application.
  - main.tsx: Application entry point.
  - vite-env.d.ts: TypeScript environment declarations for Vite.
## Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <project-directory>
