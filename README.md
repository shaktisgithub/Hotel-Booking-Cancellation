# Hotel Booking Cancellation

## Overview

This project provides insights into hotel booking cancellations over several years. The data is visualized using an Excel dashboard that allows users to explore various metrics and trends related to hotel bookings and cancellations.

## Project Files

- **Hotel Booking Cancellation.xlsx**: This Excel file contains the data and the dashboard for visualizing hotel booking cancellations.
- **Screenshot 2024-07-05 231624.png**: A screenshot of the Excel dashboard for a quick preview.

## Features

- **Total Bookings**: Displays the total number of bookings.
- **Total Cancellations**: Shows the total number of cancellations.
- **Booking and Cancellation Breakdown**:
  - By guest type (Adults, Couples, Family)
  - By room type (Desired, Undesired)
  - By hotel type (City Hotel, Resort Hotel)
  - Monthly breakdown of total guests and cancellations

## Usage Instructions

1. **Open the Excel File**:
   - Download and open `Hotel Booking Cancellation.xlsx` in Microsoft Excel.

2. **Interact with the Dashboard**:
   - Use the slicers (filters) to select the year of interest.
   - The dashboard will update automatically to reflect the selected data.

3. **Explore the Visualizations**:
   - Review the pie charts, bar graphs, and metrics to understand booking and cancellation trends.

## Design Patterns

This section explains any design patterns used in the project, including their purpose and how they are implemented.

### Singleton Pattern

- **Purpose**: Ensure that a class has only one instance and provide a global point of access to it.
- **Implementation**: Used in the dashboard to manage the Excel application instance and ensure that multiple instances do not conflict.

### Factory Pattern

- **Purpose**: Define an interface for creating an object but let subclasses alter the type of objects that will be created.
- **Implementation**: Used for creating different types of charts (pie charts, bar graphs) dynamically based on user interaction.

### Observer Pattern

- **Purpose**: Define a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically.
- **Implementation**: Used in the slicers and filters to update the dashboard visuals automatically when the user changes the selection.

## Screenshot

Below is a screenshot of the Excel dashboard:

![Screenshot 2024-07-05 231624](https://github.com/shaktisgithub/Hotel-Booking-Cancellation/assets/140899319/a1d10e9e-b4fa-4485-8bed-d78e4a0dd551)

## Contact

For any questions or suggestions, please contact Shakti Sanakr Behera at shaktisankarbehera@gmail.com.

