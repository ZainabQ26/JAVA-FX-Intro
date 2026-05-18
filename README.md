#  JavaFX Application

A collection of four desktop applications built with JavaFX to demonstrate GUI development skills and object-oriented programming principles.

##  Applications

### 1.  Calculator
- Simple JavaFX calculator with: +, −, ×, ÷, percent, square root, reciprocal (1/x), sign toggle, decimal point, memory keys (MC/MR/MS/M+), backspace, CE/C.
- Computes on =; basic error handling for invalid input or divide‑by‑zero.

### 2.  Minesweeper
- Fixed 10×10 grid with 10 randomly placed mines.
- Left‑click to reveal, right‑click to toggle flag. Shows adjacent mine counts. Reveals all cells on game over and offers a reset button.
- No timer, mine counter, win detection, or recursive zero‑cell expansion. Grid size and mine count are not configurable.

### 3.  Notepad
- Minimal text editor with New, Open, Save, and Save As for .txt files.
- Single document, no text formatting or search features. Basic error dialogs.

### 4.  Snowflakes Animation
- Koch snowflake fractal renderer on a Canvas.
- Adjustable iteration level (1–9) with optional auto‑redraw. Static rendering (no animation/particle system).

##  Technologies
- **Language:** Java
- **UI Toolkit:** JavaFX
- **IDE:** IntelliJ IDEA

##  Running the Applications

### From an IDE (recommended):
Run the main method of any of these classes:
- CALC.CALC
- MINESWEEP.MINESWEEP
- NOTEPAD.NOTEPAD
- SnowFlakes.SNOWFLAKES

Ensure JavaFX SDK is configured and added to the VM options with the required modules.

### From command line (example outline; adjust paths):

Compile with JavaFX on the module path.

Run one main class with JavaFX modules enabled, e.g.:
```
java --module-path <path-to-javafx-lib> --add-modules javafx.controls,javafx.fxml \
  -cp <compiled-output> CALC.CALC
```


##  Key Concepts Demonstrated
- JavaFX scene graph and layouts: BorderPane, GridPane, VBox, HBox, StackPane.
- Event handling: button actions and mouse clicks; basic text field events.
- Basic styling: inline -fx- styles applied to some controls.
- File I/O: reading/writing .txt files (Notepad).
- Elementary game logic: mine placement and neighbor counting (Minesweeper).
- Recursive drawing: Koch snowflake fractal via recursive subdivision.

##  Learning Outcomes
- Build and run simple modular JavaFX applications.
- Use event‑driven programming with UI controls and mouse events.
- Organize basic UI layouts and manage simple application state (calculator memory, current file, game over flag).
- Implement straightforward algorithms (neighbor counting; recursive fractal drawing).
- Handle basic error scenarios (I/O errors, invalid numeric input) with simple alerts or messages.

##  Contact
**Zainab Qazi** - [GitHub](https://github.com/ZainabQ26) - [LinkedIn](https://www.linkedin.com/in/zainab--qazi/)
