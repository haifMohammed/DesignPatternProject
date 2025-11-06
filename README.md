DesignPatternProject - Space Invaders Java GUI (Structural Patterns)
This version extends the refactored Space Invaders game by implementing Structural Design Patterns to enhance system organization, reduce complexity, and improve performance. The project demonstrates how Facade and Flyweight patterns can simplify communication between components and optimize memory usage within the game. Design Patterns Applied
Facade Pattern
Provides a simplified interface to manage multiple subsystems of the game such as sprite loading, rendering, and updates.
Makes the game easier to use and maintain by hiding the complexity of internal operations behind one unified access point.
Flyweight Pattern
Applied to game objects such as Aliens.
Reduces memory usage by sharing common image data among multiple instances instead of creating duplicates.
Improves performance when rendering large numbers of similar objects.
