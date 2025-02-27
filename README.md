<!-- ## Print-friendly portfolio CV

![preview](https://github.com/user-attachments/assets/44c47034-06e4-412a-b9dd-014593b32215)

![Astro Badge](https://img.shields.io/badge/Astro-BC52EE?logo=astro&logoColor=fff&style=flat)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-0F172A?&logo=tailwindcss)
![GitHub stars](https://img.shields.io/github/stars/Smilesharks/dev-portfolio)
![GitHub issues](https://img.shields.io/github/issues/Smilesharks/dev-portfolio)
![GitHub forks](https://img.shields.io/github/forks/Smilesharks/dev-portfolio)
![GitHub PRs](https://img.shields.io/github/issues-pr/Smilesharks/dev-portfolio) -->
# Joko Liber Portfolio

## Technologies used

- [**Astro**](https://astro.build/) - The next-gen web framework.
- [**Typescript**](https://www.typescriptlang.org/) - JavaScript with type syntax.
- [**Ninja Keys**](https://github.com/ssleptsov/ninja-keys) - Dropdown menu with keyboard shortcuts made in pure JavaScript.

---
> Kickstart your portfolio with ease! 🚀 Follow these simple steps to set up your own stunning site using similar template. Let’s turn your vision into reality—no hassle, just results.
## Getting Started

### 1. Use this Repo as an Astro Project Template

- I use [pnpm](https://pnpm.io/installation) as my package manager.

```bash
# Enable pnpm on MacOS, WSL & Linux:
corepack enable
corepack prepare pnpm@latest --activate
```

# Initialize the project
```bash
# choose one
pnpm create astro@latest -- --template Smilesharks/dev-portfolio
or
pnpm create astro@latest --template MiraHikari/portfolio
```

### 2. Add data:

Edit the `cv.json` file to create your own printable Portfolio/CV.

### 3. Test on local server:

```bash
# Enjoy
pnpm dev
```
1. Open [**http://localhost:4321**](http://localhost:4321/) in your browser to view the result.

### 4. Custum the theme colours:
Change the data-theme of `cv.json` and choose one of the colour themes defined in theme.css, red, blue, green, cyber and default, with its variants in dark mode, or create your own.

## Commands to remember

|     | Command         | Action                                                                       |
| :-- | :-------------- | :--------------------------------------------------------------------------- |
| ⚙️  | `dev` o `start` | Launches a local development server at `localhost:4321`.                   |
| ⚙️  | `build`         | Checks for errors and creates a production build in `./dist/`. |
| ⚙️  | `preview`       | Local preview at `localhost:4321`                                       |

---
## Inspirations
This project was inspired by several outstanding portfolios. Here are some that served as references:
- [Bartosz Jarocki - Print-friendly, minimalist CV page](https://github.com/BartoszJarocki/cv) 
- [Miguel Ángel Durán - minimalist-portfolio-json](https://github.com/midudev/minimalist-portfolio-json)
- [Mira Hikari - portfolio](https://github.com/MiraHikari/portfolio)
- [John Doe - dev-portfolio](https://github.com/Smilesharks/dev-portfolio)

## License
This project is [MIT](https://opensource.org/license/mit) licensed.

CV JSON schema from [**jsonresume.org**](https://jsonresume.org/schema/)