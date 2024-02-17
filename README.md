# SUDOKU-SOLVER

## Sudoku Intro:

1. This is the introductory section of project Sudoku Solver.
2. The project is a game that allows the user to solve Sudoku puzzle.
3. The aim of the project is to recreate the experience of solving Sudoku puzzles that people used to do in newspapers.
4. The game consists of a 9x9 grid of boxes that can be filled with digits from 1 to 9.
5. The game has a reset button, an exit button, a solution button, and a check moves button.
6. The reset button empties the whole grid, the exit button closes the execution, the solution button fills the grid with expected solutions, and the check moves button checks whether the move is correct or not.
7. The game grid consists of 9 rows and 9 columns, which are buttons that can be clicked to fill the digit in the box.
8. The game is built from scratch, and it will be a combination of a 9x9 matrix of buttons.

## Technologies used:

1. The project has primarily used Java language for coding.
2. Java Swing will also be used to build the GUI application.
3. Java Swing is a part of JFC (Java Foundation Classes) which is used to create window-based applications.
4. AWT (Abstract Windowing Toolkit) is the base for Java Swing.
5. Java Swing is used to build lightweight GUI applications.
6. Java Swing provides a lot of styling components such as buttons, labels, text fields, etc. for building the GUI.
7. JFrames are top-level containers provided by Java Swing which provide a playground for designing components.
8. JFrames are also known as base windows on which other components such as menu bars, panels, labels, text fields, buttons, etc.
9. Almost every Java Swing application starts with the JFrame window.

## javaSwing Library:

Java Swing is a set of GUI (Graphical User Interface) components for building desktop applications in Java. It provides a rich set of tools and components that allow developers to create interactive and visually appealing user interfaces.Here are some key functionalities of the Java.

### Swing library:

* Components: Swing provides a comprehensive set of GUI components such as buttons, text fields, labels, panels, dialogs, and more. These components are used to create the various elements of a user interface.

* Lightweight Architecture: Swing is built on top of the Java Standard Widget Toolkit (SWT) and is known for its lightweight nature. It doesn't rely on the native platform's GUI components, making Swing applications platform-independent.

* Customization: Developers can extensively customize the appearance and behavior of Swing components. This includes setting colors, fonts, and other visual properties, as well as handling events to define how components respond to user interactions.

* Layout Managers: Swing provides layout managers that help arrange components within a container in a consistent and flexible manner. Layout managers automatically adjust the position and size of components based on the size of the container.

* Event Handling: Swing supports event-driven programming. Developers can define event listeners to handle user actions such as button clicks, mouse events, and key presses. This allows for creating responsive and interactive applications.

* Double Buffering: Swing uses double buffering to reduce flickering in graphical updates. This technique involves drawing graphics off-screen before displaying them on the screen, providing a smoother visual experience.

* Concurrency Support: Swing components are not thread-safe by default, but Swing provides utilities for handling concurrency in GUI applications, such as the SwingWorker class for background tasks.

* Internationalization (I18N): Swing supports internationalization and localization, allowing developers to create applications that can be easily adapted to different languages and regions.

* Drag-and-Drop: Swing includes built-in support for drag-and-drop functionality, making it easier for users to interact with data in a graphical interface.

* Accessibility: Swing provides features to enhance accessibility for users with disabilities, such as support for screen readers and keyboard navigation.

* Java Swing has been widely used for developing desktop applications, although in recent years, JavaFX has gained popularity as an alternative framework for building rich and modern user interfaces in Java.

## javaSwing components used in SUDOKU-SOLVER:

* JFrame: JFrame is a class in the Java Swing library that represents a top-level container for creating and managing a windowed GUI application. It provides the outer frame or window that holds and organizes other Swing components.

* JPanel: In Java Swing, JPanel is a container class that provides an area for organizing and grouping components. It is a lightweight container that can be used to hold and organize other Swing components. 

* JButton: In Java Swing, JButton is a part of the Swing GUI toolkit and is used to create a clickable button component. It extends the AbstractButton class and provides a variety of methods to customize its appearance and behavior. 

## ActionListener interface:

* ActionListener is an interface in Java used for handling action events, which are generated by components such as buttons, menu items, and other interactive elements in a graphical user interface (GUI). When the user interacts with a component that generates action events, the registered ActionListener is notified, and the actionPerformed(ActionEvent e) method is called. This method contains the code that responds to the user's action.

### Here are key points about the ActionListener interface:

* Interface Definition: The ActionListener interface is part of the java.awt.event package in Java. It defines a single method: 
-> void actionPerformed(ActionEvent e);
This method is called when an action event occurs.

* Event Source: Components that generate action events must implement the ActionListener interface or have a mechanism to register objects that implement this interface.

* Registration: To handle action events, you need to register an object (often a class that implements ActionListener) with the component that generates the events. This is typically done using the addActionListener(ActionListener listener) method provided by the component.

* ActionEvent: The ActionEvent class encapsulates information about the event, such as the source of the event and any command string associated with the action. The getSource() method of ActionEvent returns the object that fired the event.
