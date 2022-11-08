# lume-figma-tokens

**Lume Figma Tokens**

This is a POC project with the goal of creating and testing a design tokens workflow for use with Figma.

This workflow is comprised of the following:
1. Figma
2. Figma Tokens plugin - for the creation and management of design tokens
3. Style Dictionary - for converting the Figma Tokens JSON format to a usable CSS or CSS custom properties format
4. Github - for version control and keeping tokens in sync between multiple team members
5. Github Actions - 2 actions are used:
    * **Create Figma Tokens PR** - creates a PR each time the Figma Tokens are updated
    * **Process Figma Tokens PR** - processes the new PR and runs the Style Dictionary build command
6. [Backlight](https://backlight.dev) - Backlight empowers front-end teams to build and ship great design systems. A unique, all-in-one design system solution. For developers, loved by designers.
