# CampusAI — College Timetable Generator

A browser-based timetable generator prototype for college class sections. It creates a weekly schedule while checking teacher and room availability.

## Features

- Configure class sections, working days, periods per day, rooms, subjects, teachers, and weekly lecture counts.
- Generate a timetable with checks for teacher and room clashes.
- Avoid scheduling the same subject more than once per day for a section.
- Switch between class-section timetable views.
- Export scheduled sessions as a CSV file.
- Print the timetable.
- Responsive layout with light/dark theme support based on the browser.

## Requirements

- A modern web browser (such as Chrome, Edge, Firefox, or Safari).
- No installation or server is required; the prototype runs locally in the browser.

## Run the project

1. Extract the project ZIP file.
2. Open `index.html` in your web browser.
3. Edit the sample sections, rooms, and subject data as needed.
4. Select **Generate schedule** to create a timetable.
5. Use **Export CSV** to download the generated sessions or **Print** to print the timetable.

## Subject input format

Enter one subject per line using this format:

`Subject name | Teacher name | periods per week`

Example:

```text
Mathematics | Prof. Kulkarni | 4
Data Structures | Prof. Patil | 4
DBMS | Prof. Joshi | 4
```

Separate class section names and room names with commas.

## Notes and limitations

- This is a front-end prototype; scheduling runs in the browser and does not use a remote AI service or database.
- The generator reports an error if it cannot find a clash-free schedule for the supplied constraints.
- Periods are displayed as 50-minute sessions, starting at 09:00 with one-hour spacing between period start times.
- The example configuration is included by default and can be restored with **Reset**.

## Project files

- `index.html` — application UI, styles, and scheduling logic.
- `README.md` — project overview and usage instructions.
