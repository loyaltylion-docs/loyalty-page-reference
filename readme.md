# LoyaltyLion on-page program reference

This repository contains a reference Shopify theme with LoyaltyLion's on-page interface integrated. It can be used as a reference when adding LoyaltyLion to your own Shopify theme.

## Live reference store

https://loyaltylion-reference-8b64.myshopify.com

* access the rewards page from the "Rewards" menu in the top

## Adding a loyalty page to your theme

### 1. Create a loyalty page template

Setting up a loyalty page involves adding a few HTML elements -- it's usually easiest to do this using a page template in your theme.

The page template used for the reference store can be found in `templates/page.rewards.liquid`

### 2. Create a dedicated page for the program

Common choices are `/pages/rewards` or `/pages/loyalty`. This page is where you'll send shoppers to access their rewards, and also to introduce new people to the program.

For the page template, select the one you created in step 1. There's no need to add any content to the page as that'll all be in the template.

### 3. Add the LoyaltyLion UI components to your page template

The page template should consist of:

* your own markup, e.g. images, headings, etc
* individually placed LoyaltyLion UI components, such as a list of rewards

The components available, and how to add them, are detailed in the (component reference)[https://github.com/loyaltylion-docs/loyalty-page-reference/blob/master/docs/component-reference.md]

### 4. Style the LoyaltyLion UI components as needed

The LoyaltyLion SDK includes some basic styles for all of its components, but they're also designed to be easy to adjust to match your store's look and feel.

The intended way to add your own styles for LoyaltyLion components is with your theme's normal CSS editing workflow, e.g. `/assets/theme.scss.liquid`.

All our class names start with `lion-` and adopt [BEM](https://en.bem.info) methodology.
