# RoutineReminder - ADHD-Friendly iOS App

An iOS application designed to help 13-year-old users with ADHD stay organized with daily routines and exam preparations.

## Features

### 1. Daily Routine Reminders
- Full-screen alerts for scheduled daily routines
- Simple "Done" button confirmation
- Visual emoji icons for better engagement
- Reward animation and sound upon completion
- Persistent notifications that require action

### 2. Exam Countdown Alerts
- Automated countdown notifications for upcoming exams
- Starts reminding user 7 days before exam date
- Daily notifications with dynamic messaging based on days remaining
- Easy exam input through simple interface

### 3. ADHD-Friendly Design
- Clean, distraction-free interface
- Large text and buttons for easy reading and interaction
- Colorful icons and visual cues
- Minimal steps required to complete tasks
- Calming color scheme with blues and greens

### 4. Task Logging
- Records when routines are completed
- Timestamps stored for future reference
- Designed to help build consistent habits

## Technical Implementation

### Data Structure
- Core Data for persistent storage
- Simple models for routines and exams
- JSON-compatible structure for easy data sharing/backup

### Notifications
- UNUserNotificationCenter for local notifications
- Background support for triggering alerts at scheduled times
- Custom notification content and actions

### User Interface
- UIKit with programmatic layout
- Animations for engagement and positive reinforcement
- Full-screen, focused interface for routine alerts

## App Screens

1. **Main Dashboard** - Overview of today's routines and upcoming exams
2. **Routine Alert** - Full-screen reminder with confirmation button
3. **Exam List** - List of upcoming exams with countdown days
4. **Add Exam** - Simple form to add new exam reminders
5. **Settings** - Configure app settings and notification permissions

## Getting Started

To run this app:

1. Open the project in Xcode
2. Build and run on iOS simulator or device (iOS 16.0+)
3. Allow notification permissions when prompted
4. Default routines and sample exams will be created on first launch

## Future Enhancements

- Parent dashboard to edit routines remotely
- Google Sheets or Firebase integration for remote data updates
- Reward points system for consistent routine completion
- Custom sound selection for notifications
- Multiple user profiles for siblings

## Requirements

- iOS 16.0+
- iPhone (optimized for iPhone 13/14)
- Notification permissions enabled