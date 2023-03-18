# Mythic Plus Score Calculator for World of Warcraft

This is a simple app that takes data on your Mythic+ runs from Raider.io and calculates how much rating you will gain from timing a certain key

The calculator is built in Javascript, pulling data from the Raider.io API and uses the same calculations as the WoW UI to predict gains

The character pages are built dynamically using the Astro 🚀 Framework, with basic styling using Tailwind

It's deployed and hosted on Netlify

[![Netlify Status](https://api.netlify.com/api/v1/badges/5ebcca9e-bc6b-476d-9d7c-19d8bf16c695/deploy-status)](https://app.netlify.com/sites/mythic-plus-calculator/deploys)

Feel free to contribute or fork for your own projects, as long as you attribute me!

# TODO

- Better overall styling
- Catch error responses from raider.io API
- Validate character details input and handle errors
- Add reactive element to calculator page that accepts a key level and updates the calcs in the right-hand columns (Note: Svelte framework is enabled ready for this)
- Refactoring and tidying up pretty much everything
