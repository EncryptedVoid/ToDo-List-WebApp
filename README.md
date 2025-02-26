# Tasks Manager

![Tasks Manager Preview](https://via.placeholder.com/800x400?text=Tasks+Manager+Preview)

## Overview

Tasks Manager is a sleek, modern web-based kanban board application for task management. It provides a visually appealing interface to track and organize tasks across four different stages of completion.

## Features

- **Four-Stage Workflow**: Organize tasks into Backlog, In Progress, Completed, and Upcoming categories
- **Task Cards**: Each task has a title, description, deadline, and difficulty level
- **Visual Status Indicators**: Color-coded sections provide quick visual cues about task status
- **Hover Effects**: Subtle animations enhance user experience and highlight interactive elements
- **Edit Functionality**: Built-in editing options for task titles and descriptions
- **Task Counter**: Each section displays the number of tasks it contains
- **Responsive Design**: Adapts to different screen sizes for optimal viewing

## Technologies Used

- **HTML5**: Semantic structure for the application
- **CSS3**: Modern styling with flexbox layout and transitions
- **Google Fonts**: "Raleway" for clean, legible typography
- **Material Icons**: Rounded style icons for visual enhancement

## Visual Design

The application features a dark-themed interface with:

- Blurred background image for depth
- Distinct color schemes for each task stage:
  - **Backlog**: Blue gradient
  - **In Progress**: Yellow/Gold gradient
  - **Completed**: Green gradient
  - **Upcoming**: Purple gradient
- Card-based layout with subtle hover animations
- Dashed borders around sections for clear visual separation
- Consistent iconography for improved user experience
- Smooth transitions for interactive elements

## Project Structure

```
tasks-manager/
├── central.html        # Main application HTML
├── styling.css         # CSS styling
└── assets/             # Background images
    ├── central_background.png
    ├── backlog_list_background.png
    ├── active_tasks_background.png
    ├── completed_tasks_background.png
    └── upcoming_tasks_background.png
```

## Usage

1. Open `central.html` in a modern web browser
2. Tasks are automatically organized into their respective categories
3. Hover over task titles or descriptions to reveal edit buttons
4. View task details including deadlines and difficulty levels

## CSS Features

The application uses several modern CSS techniques:

- **Flexbox Layout**: For responsive arrangement of tasks and sections
- **CSS Transitions**: Smooth animations when interacting with elements
- **Linear Gradients**: Visually distinct section headers
- **Backdrop Filter**: Blur effects for depth and visual hierarchy
- **Custom Properties**: For consistent styling throughout
- **Hover States**: Interactive elements respond to user actions

## Browser Compatibility

The application is designed to work in modern browsers that support:
- CSS Flexbox
- CSS Transitions
- Backdrop filters
- Linear gradients

For best experience, use the latest versions of Chrome, Firefox, Safari, or Edge.

## Future Enhancements

Potential improvements for future versions:

- **Drag-and-Drop**: Allow moving tasks between different stages
- **LocalStorage Integration**: Save tasks between sessions
- **Task Filtering**: Search and filter by various criteria
- **Dark/Light Mode Toggle**: Additional theme options
- **Mobile Optimization**: Enhanced experience on smaller screens
- **Task Details Expansion**: Ability to add comments, attachments, or subtasks
- **User Authentication**: Multi-user support with personalized boards
- **Data Export**: Options to export task data in various formats

## Credits

- Material Design Icons by Google
- Raleway font by Matt McInerney, Pablo Impallari, and Rodrigo Fuenzalida