# GOSIM AI Paris 2025

## How to add Schedule
1. Add data to JSON file at `src/json/Schedule.json`
2. If you add speaker images, add only the file name, such as `speaker-name.jpg`
3. Add potential speaker images as PNG or JPG files to `public/images/speakers/`

## How to add Sponsors
1. Add data to JSON file at `src/json/Sponsors.json`
2. Add sponsor file name, such as `sponsor-name.png`
3. Add sponsor images as PNG / JPG / SVG files to `public/images/sponsors/`

## How to add Speakers
1. Add data to JSON file at `src/json/Speakers.json`
2. Add speaker file name, such as `speaker-name.png`
3. Add speaker images as PNG / JPG files to `public/images/speakers/`

## How to add FAQ
1. Add data to JSON file at `src/json/FAQ.json`

## How to edit Markdown pages (Code of Conduct, Privacy, Workshop)
1. Edit the Markdown file at `src/markdown/`

## 🚀 Project Structure

```text
/
├── public/
│   └── fonts
│   └── icons
│   └── images
│       └── speakers
│       └── sponsors
│   └── js
│   └── videos
├── src/
│   ├── layouts/
│   ├── components/
│   └── pages/
│   └── styles/
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [guide on project structure](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## Want to learn more?

Feel free to check [the Astro documentation](https://docs.astro.build).
