Library Management -- WPF Styles
Project Overview
This project demonstrates four levels of styling in a C# WPF application
using a simple Library Management interface.
Technologies
- C#
- WPF (Windows Presentation Foundation)
- XAML
- Visual Studio
Style Levels Used
1. Control-Level Style
A style defined inside a particular control's resources. In this
project, the Book Name TextBox has its own style with a light-yellow
background and blue border.
2. Layout-Level Style
A style defined inside StackPanel.Resources. It is applied to matching
controls inside that StackPanel. In this project, TextBoxes receive a
common height, font size, margin, and padding.
3. Window-Level Style
Styles defined inside Window.Resources. In this project, button styles
are defined for Add Book, Update, and Delete buttons.
4. Application-Level Style
A style defined inside Application.Resources in App.xaml. In this
project, it applies common formatting to Labels throughout the
application.
User Interface
The Library Management window contains: - Book Name - Author Name - Book
ID - Add Book button - Update button - Delete button
Project Structure
LibraryManagement/
├── App.xaml
├── App.xaml.cs
├── MainWindow.xaml
└── MainWindow.xaml.cs
How to Run
1. Open Visual Studio.
2. Create or open a WPF project named LibraryManagement.
3. Add the Application-Level style to App.xaml.
4. Add the Control-Level, Layout-Level, and Window-Level styles to
   MainWindow.xaml.
5. Ensure the XAML namespace matches your project namespace.
6. Build and run the project.
Note
This project is a styling demonstration. The Add Book, Update, and
Delete buttons are visual controls only; database or book-management
functionality has not been implemented.
