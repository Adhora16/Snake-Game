### Snake Game

The **Snake Game** project implemented in Python with OpenGL provides an engaging graphical experience with interactive gameplay and visually appealing features. Below are its features and highlights:

---

#### **Gameplay Features**
1. **Dynamic Snake Movement**:
   - The snake grows with each food item consumed.
   - Movement controlled via keyboard arrow keys (`Up`, `Down`, `Left`, `Right`) or `u`, `d`, `l`, `r`.

2. **Food Mechanics**:
   - Two types of food:
     - **Circle**: Adds 10 points.
     - **Square**: Adds 30 points.
   - Food spawns randomly within the play area.

3. **Game States**:
   - **Play**: Continuously animates and updates gameplay.
   - **Pause**: Allows resuming without resetting progress.
   - **Restart**: Resets the game, including score and snake length.
   - **Exit**: Ends the session with a goodbye message and score display.

4. **Game Over**:
   - Triggered by collisions with the snake’s body.
   - Displays final score and halts gameplay.

---

#### **Interactive Graphics**
1. **Buttons**:
   - **Pause Button**: Appears during gameplay to halt animation.
   - **Play Button**: Resumes from a paused state.
   - **Restart Button**: Resets the game to initial conditions.
   - **Exit Button**: Ends the game session.

2. **Dynamic Background Modes**:
   - **Light Mode**: White background (`m` key).
   - **Dark Mode**: Black background (`n` key).

3. **Snake and Food Design**:
   - Snake segments are rendered as colorful shapes:
     - **Head**: Circular.
     - **Body**: Square segments.
   - Food shapes dynamically switch between circular and square styles with unique colors.

4. **Smooth Animation**:
   - Frame updates every 150 milliseconds ensure fluid gameplay.

---

#### **Technical Implementation Highlights**
1. **OpenGL Rendering**:
   - Real-time graphics powered by OpenGL.
   - Efficient algorithms for drawing lines, circles, and squares.

2. **Midpoint Algorithms**:
   - **Circle Drawing**: Uses midpoint circle algorithm for precise rendering.
   - **Line Drawing**: Employs midpoint line algorithm for sharp edges.

3. **Collision Detection**:
   - Detects collisions between the snake and itself or food.

4. **Responsive Controls**:
   - Keyboard listeners (`keyboardListener` and `specialKeyListener`) handle movement and gameplay states.
   - Mouse listener enables button-based interactivity.

5. **Viewport Management**:
   - Ensures a consistent view with proper scaling and projection using OpenGL’s `glOrtho`.

---

This project is an excellent demonstration of game design fundamentals, advanced graphics algorithms, and interactive UI implementation using Python and OpenGL.
