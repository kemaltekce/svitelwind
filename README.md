# svitelwind - A Svelte-Electron-Vite-Tailwind template 🍱

This is a simple template which combines Svelte, Electron, Vite and Tailwind.

This template supports **hot reload** 🔥 during development via Vite.

Right now it only supports creating Mac dmg files. But you can always extend the simple functionality of the template.

## 🚀 Development

First install all packages via `npm i`.

Start the dev environment via `npm run dev`.

## 🎨 Customization

You can change the icons and background images used for the app. They are all located inside the `icons` folder:

- dmg_background.png: background image of dmg installer
- icon.icns: icon of app
- tray.png and tray@2x.png: icon displayed in tray

## 🍱 Building the app

Building your app only takes too steps:

1. Build the svelte app into `dist` folder via `npm run build`
2. Create the electron app into the `out` folder via `npm run forge:make`
   `After that you will find the dmg install file inside the`out` folder.
