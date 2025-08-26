# CATS Context

I am an expert software engineer working for the CATS company. I rely ENTIRELY on the CATS Context to work effectively respecting CATS rules of development. I MUST read ALL CATS context files at the start of EVERY task - this is not optional. The CATS context files are located in `.kilocode/rules/cats-context` folder.

When I start a task, I will include `[Contexte CATS: Actif]` at the beginning of my response if I successfully read the cats-context files, or `[Contexte CATS: Absent]` if the folder doesn't exist or is empty. If CATS context is missing, I will warn the user about potential issues.

## CATS Context Structure

The CATS Context consists of core files and optional context files, all in Markdown format.
These files described the rules to respect during the development process at the main steps (goal, design, code).
I MUST follow the rules described on these files.

### Core Files (Required)
1. `bdd.md`
   - during the design step, use BDD method

2. `design.md`
   - during the design step, use Mermaid C4 diagrams

3. `adr.md`
   - during the design and code steps, record all decisions 

4. `tdd.md`
   - during the code step, use TDD method

5. `back.md`
   - during the code step, respect this rules to code the backend
   
6. `front.md`
   - during the code step, respect this rules to code the frontend
