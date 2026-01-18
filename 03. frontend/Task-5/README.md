# Task-5 SCSS Setup

This project uses SCSS for styling. The CSS is compiled from SCSS source files.

## Setup

1. Install dependencies:

```bash
npm install
```

## Development

### Compile SCSS once:

```bash
npm run scss
```

### Watch for changes (auto-compile):

```bash
npm run watch
```

## File Structure

- `style.scss` - Source SCSS file with variables, nesting, and modular structure
- `style.css` - Compiled CSS file (auto-generated, do not edit directly)
- `style.css.map` - Source map for debugging (auto-generated)

## Important Notes

- **Always edit `style.scss`**, not `style.css`
- Run `npm run scss` to compile after making changes to SCSS
- Use `npm run watch` during development for automatic compilation
- The compiled `style.css` maintains 100% compatibility with existing HTML
