# College-Attendance-Shortage-Predictor.
A command-line Python application that helps students track subject-wise attendance and stay above the minimum 75% requirement. Instead of discovering a shortage just before exams, students can check their standing at any time and plan ahead.

## Overview

Students enter each subject with the total classes held and classes attended. The program calculates the current attendance percentage and gives clear guidance:

- **Below 75%:** shows how many consecutive classes must be attended to reach the required level.
- **Safe:** shows how many more classes can be missed while staying above 75%.

## Features

- Add subjects with input validation
- View attendance records with percentages
- Predict shortage status for a single subject
- Simulate missing classes before skipping them
- Generate a report of subjects with a shortage

## How It Works

Attendance % = (Classes Attended x 100) / Classes Held

- **Shortage:** the number of classes needed is rounded up, so the student is guaranteed to reach 75%.
- **Safe:** the number of classes that can be missed is rounded down, so the student never drops below 75%.

## Technologies Used

- Python 3 (no external libraries)

## Social Impact

Built for our *Compassion in Action* project, this tool reduces the stress of attendance shortages. It helps students avoid being barred from exams and especially supports those who miss classes due to illness or personal circumstances by showing exactly how much they need to recover.

