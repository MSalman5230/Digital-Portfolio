## Print-friendly portfolio CV

![preview](https://github.com/user-attachments/assets/44c47034-06e4-412a-b9dd-014593b32215)

## 📄 About

This project is refactored from the original [**dev-portfolio**](https://github.com/Smilesharks/dev-portfolio) project, thanks for his work.

I use iconify instead of SVG icons for better dev experience.


## 🛠️ Stack

- [**Astro**](https://astro.build/) - The next-gen web framework.
- [**Typescript**](https://www.typescriptlang.org/) - JavaScript with type syntax.
- [**TailwindCSS**](https://tailwindcss.com/) - Utility-first CSS framework.
- [**Iconify**](https://iconify.design/) - Icon library.
- [**FancyBox**](https://fancyapps.com/fancybox/3/) - Image viewer.
- [**Ninja Keys**](https://github.com/ssleptsov/ninja-keys) - Dropdown menu with keyboard shortcuts made in pure JavaScript.

## 🚀 Getting Started


Modify the `cv.json` file to create your own printable Portfolio/CV.

### 1. Use this Repo as an Astro Project Template

- I use [npm](https://www.npmjs.com/) as my package manager.



### 1-1. Clone the repo
If you don't want to use the template command, you can clone this repo and install the dependencies.

```bash
git clone https://github.com/MSalman5230/Digital-Portfolio.git
cd Digital-Portfolio
npm install
```

### 2. Add Your Content:

Edit the `cv.json` file to create your own printable Portfolio/CV.

### 3. Launch the Development Server:

```bash
# Enjoy the results
npm run dev
```
1. Open [**http://localhost:4321**](http://localhost:4321/) in your browser to view the result 🚀

### 4. Customisable colours:
Change the data-theme of `cv.json` and choose one of the colour themes defined in theme.css, red, blue, green, cyber, pink and default, with its variants in dark mode, or create your own.

## 🧞 Commands
npm run

|     | Command         | Action                                                                       |
| :-- | :-------------- | :--------------------------------------------------------------------------- |
| ⚙️  | `dev` or `start` | Launches a local development server at `localhost:4321`.                   |
| ⚙️  | `build`         | Checks for errors and creates a production build in `./dist/`. |
| ⚙️  | `preview`       | Local preview at `localhost:4321`                                       |
| 📦  | `deploy:vercel`         | Deploy on Vercel.                           |
| 📦 | `deploy:cloudflare`       | Deploy on Cloudflare, please run `wrangler login` first.                                           |                                |

## 📝 License

This project is [MIT](./LICENSE) licensed.

CV JSON schema from [**jsonresume.org**](https://jsonresume.org/schema/)
