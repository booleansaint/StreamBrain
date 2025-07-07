# StreamBrain: To Do and Notes Application
# Project Description
# StreamBrain is a mobile application designed to help users more effectively establish, track, and accomplish tasks and take related notes. It aims to do this through the use of user-specified time requirements for each individual step towards a goal. The application will make use of color-changing text to assist the user in understanding the proximity to specified deadlines for overall goals and individual steps, proactively engaging the user with note-taking strategies and methods. Users will generate inputs via a keyboard, with future updates supporting microphone and camera use, and associated data and file types. The community may support additional features and extensions with a library of rated, personalized additions. In short, StreamBrain will serve as a goal-oriented note-taking platform, allowing users to accurately and proactively prioritize steps with features like color-changing text and user-set notification intervals.

# Problem Addressing
# Current note-taking applications often compartmentalize notes and to-do lists into separate entities and are generally passive in nature. StreamBrain seeks to foster workflow and positive step tracking through the use of timelines for To-do's within a note. This allows for the seamless integration of necessary elements that can be tailored based on user preference. The application addresses the need for a more proactive and integrated approach to task management and note-taking. Potential use of visualization aids to track progress, such as tables, icons, or bar charts, may be included.

# Platform
# The current platform will be Android-based, utilizing the latest or most available version according to application requirements, with potential for cross-platform support. This selection was made due to the availability of open-source resources and supportive development resources like tutorials.

# Front/Back End Support
# Front End:
# Utilizing the Android platform, primary languages will include Kotlin, and XML layouts will be used. The user interface (UI) will focus on responsive design to accommodate different Android device screen sizes. The progress of various notes and to-dos will be represented with color-changing text as a key UI element.
# Back End:
# Local data storage for this application is ideally handled through the use of the Room Persistent Library. This library will integrate with Kotlin. Future considerations include a cloud-based backend and the necessary authentication for remote access and storage.

# Functionality
# Users can create main goals and specify the number of steps.
# Every goal/task will have an overall deadline.
# Within each goal, each step can have its own deadline/time requirement.
# Notes are generally associated with goals and steps.
# Text will dynamically change color based on proximity to deadlines.
# An example color scheme is green for ample time, yellow for approaching, and red for critical or overdue.
# Users will set customizable thresholds for these color changes.
# Users will also specify notification intervals for goals and individual steps.

# Design (Wireframes)
# The following describes the planned screens and their key elements:

# Main Screen:
# Top Bar: Application Title “StreamBrain,” Search Icon, Settings Icon
# Main Area: A list of active Goals with title, overall deadline, a visual indicator (such as a progress bar or color-changing background), and a "+" symbol for quick adding of new goals/tasks
# Bottom Navigation Bar: Icons include “Goals,” “Notes,” Calendar timeline view

# Goal Detail Screen:
# Top Bar: Edit, Share, and Delete icons
# Goal Overview: Provides the goal description
# Steps Section: A scrollable list of individual steps. Each step has a user-specified title, deadline, a checkbox for completion, and a small icon to expand notes. A "+" for adding new steps.
# Notes for Goal Section: Provides a dedicated area for general notes.

# Step Detail Screen:
# Top Bar: Step title, related goal, and a back button
# Main Area: Includes notes for the step and an option to link to existing notes.
# Notification Settings: Provides fields for intervals for specific steps/goals.

# New Goal Screen: Includes input fields for title, description, deadline, and additional notes.

# Settings Screen: Provides general application settings, sound, theme, color-coding thresholds customization, and help/about settings.
