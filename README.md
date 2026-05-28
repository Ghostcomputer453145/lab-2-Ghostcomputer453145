# WEB102 Lab 2 – *Samosa Selector*

Submitted by: **Yumin Jang**  
Z Number: **Z23655899**

**Samosa Selector** is a React web app that allows users to click a samosa to increase their count and purchase upgrades that multiply how many samosas are earned per click.

Time spent: **3-5** hours spent in total

## Required Features

The following **required** functionality is completed:

* [X] A large samosa that the user can click to harvest one samosa at a time
* [X] A counter displaying the number of samosas the user currently has 
* [X] Three upgrades that increase the effectiveness of the user’s cursor at certain point thresholds


## Stretch Features

The following **stretch** functionality is implemented:

* [x] When purchasing an upgrade, the user loses samosas from their total count
* [x] Decrease the scale of the large samosa when the user clicks the samosa to create a pulse effect

## Video Walkthrough

Here's a walkthrough of the fully completed Timetabled calendar:

<img src="samosa-selector.gif" title="Video Walkthrough" alt="Video Walkthrough" />

GIF created with **Snipping Tool**

## What I've done and learned

In this lab, I built a React app that tracks a samosa count and a multiplier using useState. I connected clicks on the samosa image and the upgrade buttons to event handlers that update the state and automatically refresh the UI. I added logic so upgrades only work when enough samosas are available and subtract the correct amount after purchase. I also learned how to properly import images from the src folder and used CSS Flexbox and hover/click effects to center the layout and improve the user experience.

## License

    Copyright 2026 Yumin Jang

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
