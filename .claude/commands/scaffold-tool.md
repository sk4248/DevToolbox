Create a new developer tool for DevToolBox

Tool name: $ARGUMENTS

 ## Requirements:
  - Create a folder under `src/tools/` with the tool name in kebab-case
  - Include these files:
    - `index.tsx` — main component (named export)
    - `utils.ts` — pure logic functions
    - `styles.module.css` — component styles
  - Follow all conventions from CLAUDE.md
  - Add the tool to the router in App.tsx
  - Make the UI clean and functional with proper input/output areas