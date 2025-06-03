Interactive Flutter App
Project Overview
This is a Flutter-based mobile app designed to help students manage their academic activities with ease. It provides an intuitive and colourful interface to keep track of upcoming tests, view scores across subjects, and ask subject-related questions interactively. The app is optimized for smooth transitions and a pleasant user experience, making study management engaging and straightforward.

Features
•	Upcoming Tests: 
Displays a list of scheduled tests with dates and subject-specific icons and colours.
•	Scores: 
Shows scores for different subjects with colour coding to indicate performance levels.
•	Subjects & Q&A: 
Allows users to select a subject, ask questions related to it, and receive predefined answers to enhance learning.
•	Smooth UI Transitions: 
Animated page switching for a modern app feel.
•	Colourful and Responsive Design: Uses gradients, icons, and rounded cards for an appealing visual experience.

Tools and Technologies Used
•	Flutter: 
UI toolkit for building natively compiled applications for mobile.
•	Dart: 
Programming language used with Flutter.
•	Material3 Design: 
Utilizes Flutter’s latest Material You design components.
•	IDE Compatibility: 
Compatible with Project IDX, VSCode, Android Studio, and other Flutter-supported IDEs.

Code Structure and Design Pattern
The app follows a simplified MVVM (Model-View-ViewModel) inspired structure:
•	Model: 
The data is represented by simple Dart collections and maps (e.g., lists of tests, scores, and Q&A data).
•	View: 
The UI widgets (UpcomingTestsPage, ScoresPage, SubjectsPage) represent the views, responsible for rendering data and user interaction.
•	ViewModel: 
The HomePage widget manages the navigation state and orchestrates which view to display, effectively separating UI logic from presentation.

This separation improves code maintainability, readability, and scalability, making it easy to extend the app with new features or change the UI without affecting data logic.
