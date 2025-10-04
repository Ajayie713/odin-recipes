# Copilot Instructions for odin-recipes

## Project Overview
This is a simple static website project for sharing recipes. The codebase consists of HTML files and images, organized by recipe type. There are no build steps, tests, or external dependencies; all content is served as static files.

## Directory Structure
- `index.html`: Main landing page listing recipes.
- `Recipes/`: Contains individual recipe pages and images.
  - `chickencurry.html`, `friedrice.html`, `spaghetti.html`: Recipe detail pages.
  - Corresponding `.jpeg` images for each recipe.

## Key Patterns & Conventions
- All recipe pages follow a similar HTML structure: title, image, ingredients, and instructions.
- Images are stored alongside their respective HTML files in the `Recipes/` directory.
- Navigation between pages is handled via standard HTML `<a>` links.
- No JavaScript, CSS, or frameworks are used; styling and interactivity are minimal.
- All file and directory names use lowercase and are descriptive of their contents.

## How to Contribute
- To add a new recipe, create a new HTML file and image in the `Recipes/` directory, following the structure of existing files.
- Update `index.html` to include a link to the new recipe page.
- Keep markup simple and consistent with existing pages.

## Example: Adding a Recipe
1. Copy an existing recipe HTML file (e.g., `friedrice.html`) and update the content for the new recipe.
2. Add a corresponding image file (e.g., `newrecipe.jpeg`) to the `Recipes/` directory.
3. Edit `index.html` to add a link to the new recipe page.

## No Build or Test Workflows
- There are no build scripts, test suites, or package managers in use.
- All changes are immediately reflected by opening the HTML files in a browser.

## Summary
This project is a static HTML site with a clear, simple structure. Focus on consistency, clarity, and minimalism when making changes. Reference existing files for patterns and structure.
