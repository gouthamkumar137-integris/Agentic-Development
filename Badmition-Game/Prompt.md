## MY PROMPT

<role> expert prompt engineering</role>
<goal> create an web page for badmitton game with realastic time sync play </goal>
<input>it should contain to play two player and no login or signup user freiendly must support desktop and mobile versions be realastic ball and bat movents background of people sitting and cheering and the image of two players playing.</input>
<layout> ther realastic sync game play which support smooth flow and contains initail pages of the app name ans start play and guide etc.. on next page the game should play </layout>
<output> it should be amazingly designed and  should not look like generic card generatior should include beetter  and layout</output>
<rule> 1. it should be user friendly and no login or signup required.
2. must follow  well designed layout structure
3.the realastic sync game play which support smooth flow and contains initail pages of the app name ans start play and guide etc.. on next page the game should play 
4.zero fluff.</rule>
<task> generate prompt which tells ai to follow the above instructions and give me the better output</task>


## META PROMPT

Role: Senior Web Game Developer & Creative UI/UX Designer

Goal: Build a fully functional, highly polished, browser-based 2-Player Badminton Game using single-file HTML5 Canvas, CSS3, and JavaScript (ES6+).

Key Technical & Visual Specifications:

1. Application Flow & Screen Navigation:
   - Screen 1: Welcome & Main Menu (App Name, "Start Play" button, "How to Play / Guide" modal, and Control Settings).
   - Screen 2: Game Arena (Canvas view, active scoreboard, match pause/resume overlay, and match result screen with restart options).

2. Game Mechanics & Physics (Realistic Motion):
   - Local 2-Player Mode (Player 1: Keyboard WASD + Space to Swing; Player 2: Arrow Keys + Enter to Swing).
   - Realistic Shuttlecock (Ball) Physics: Drag coefficient, gravity deceleration, parabolic arc, and speed adjustments based on shot strength/timing (Smash vs. Clear vs. Drop shot).
   - Racket (Bat) Movement & Hitbox: Smooth character physics with acceleration, jumping, hit detection based on timing and racket angle, and visual swing animations.

3. Visual Design & Asset Rendering (Canvas Graphics):
   - Court Background: Detailed 2D perspective vector court (lines, net, posts).
   - Background Elements: Dynamic ambient crowd in the background sitting in bleachers with subtle cheering/bounce animations.
   - Player Sprites: Custom vector-drawn players (distinct colored jerseys/rackets) with directional stance changes and swing animations.
   - UI/UX Styling: Premium modern dark-theme UI overlay (glassmorphism buttons, vibrant typography, fluid animations). NO generic card-generator components or basic Bootstrap-style default layouts.

4. Responsiveness & Device Support:
   - Universal Layout: Responsive HTML5 canvas scaling maintaining aspect ratio (16:9 preferred).
   - Touch Controls: Dynamic touch-screen directional pad and action buttons for mobile devices, automatically toggled on touch input detection.

5. Rules & Execution Constraints:
   - Zero login or signup requirement.
   - Self-contained implementation (HTML/CSS/JS in a single cohesive snippet or standard modular file structure).
   - Zero external assets requiring external URL loading (render all graphics, sprites, and background effects programmatically via Canvas API or embedded inline SVGs).