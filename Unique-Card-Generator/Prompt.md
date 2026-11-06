## Step1: MY PROMPT

<role> expert prompt engineering</role>
<goal> create an web page generates multiple cards with fantastic quotes with color grading</goal>
<input> it ask the multiple input from the user end for example name, age, hobbies, favourite things etc.... and ask them questions so it should feel for them personalized to them </input>
<layout> don't keep generic layout and ai color gradings, use the welcome quote at top which changes with time and in the left bar ask's them to input the needs and in right bar generate card and option to alter, personalize and copyable must has , contain footer section </layout>
<output> it should be amazingly designed and multiple options availablity to alter and copy, should not look like generic card generatior should include beetter font styles and layout</output>
<rule> 1. it should be user friendly and no login or signup required.
2. must follow  well designed layout structure
3. must genereate unique and mutiple cards.
4.zero fluff.</rule>
<task> generate prompt which tells ai to follow the above instructions and give me the better output</task>


## Step2: META PROMPT 

<role>
You are an expert Senior Frontend Developer and UI/UX Designer specializing in modern, glassmorphic, and dynamic web applications.
</role>

<task>
Build a fully functional, highly responsive single-page web application (HTML, CSS/Tailwind CSS, and JavaScript) that generates personalized, beautifully styled quote cards based on interactive user inputs.
</task>

<requirements>
1. User Onboarding & Interactive Questionnaire:

   - Left Sidebar / Panel: A multi-step interactive input area asking for details (e.g., Name, Age, Hobbies, Favorite Themes, Current Mood, Life Goals).
   - Dynamic Questions: Ask progressive, tailored questions so the experience feels personal and engaging.
   - Zero Friction: No login, signup, or backend authentication required. Store state locally in JS.

2. Dynamic Top Header:
   - Displays a dynamic welcome greeting/quote that changes based on the user's local time of day (Morning, Afternoon, Evening, Night).

3. Card Generation & Customization Engine:
   - Right Main Canvas: Displays real-time generated quote cards based on user responses.
   - Distinct Layouts: Provide multiple non-generic layout choices (e.g., Editorial Magazine, Minimalist Swiss Typography, Neon Cyberpunk, Soft Glassmorphism).
   - Deep Personalization Controls: Allow users to customize fonts (Google Fonts integration like Playfair Display, Inter, Space Grotesk), custom color gradients, text size, alignment, and backdrop filters.
   - Copy & Export Options: Include functional controls to copy text to clipboard, copy HTML/CSS snippet, or download/export card as an image.

4. UI/UX & Visual Aesthetics:
   - Avoid plain or cliché AI aesthetic templates.
   - Use vibrant color grading (mesh gradients, dual-tone shifts, glassmorphism overlays).
   - Smooth micro-interactions, hover states, and transitions.
   - Include a sleek, modern footer.

5. Code Quality:
   - Provide complete, ready-to-run, bug-free code in a single HTML file (or cleanly structured React/Tailwind component if applicable).
   - Zero placeholding commentary—deliver full implementation logic for quote generation and customization toggles.
</requirements>

<output_format>
Output only the clean, complete source code along with brief setup instructions. No conversational fluff.
</output_format>


### TOOL: @google gemini