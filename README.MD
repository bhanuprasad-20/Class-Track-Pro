# ClassTrack Pro (AttendanceWiz)

ClassTrack Pro, shown in the UI as **AttendanceWiz**, is a student-friendly attendance calculator built with HTML, CSS, and JavaScript. It helps students track their current attendance, understand how many classes they can skip, and how many they must attend to reach a target percentage.

## Features
- Calculates current attendance percentage from total and attended classes.
- Automatically derives the number of classes absent.
- Lets you set a desired attendance threshold (default 75%).
- Shows how many classes you can safely skip while staying above the threshold.
- Shows how many consecutive classes you must attend to reach the threshold if you are below it.
- Simple, responsive interface with a clear, motivational design.

## Getting Started

1. Clone the repository:
   ```bash
   git clone(https://github.com/harivamsikandregula-lab/Attendance_Tracker.git)
Go into the project directory:

bash
cd Attendance_Tracker
Open index.html in your browser.

**Project Structure**
   text
   Project_one/
   ├── index.html        # Main app page
   ├── style.css         # Styles and layout
   ├── script.js         # Attendance logic and interactions
   ├── students.jpg      # Background image
   └── quirky-classtrack-logo.png  # App logo


**Tech Stack**
   HTML
   CSS
   JavaScript

*Notes: *
   Total classes must be greater than 0.
   Classes attended cannot be more than total classes.
   If you leave the default threshold, it uses 75%.
