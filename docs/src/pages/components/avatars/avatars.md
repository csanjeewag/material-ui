---
title: Avatar React component
components: Avatar
---

# Avatar

<p class="description">Avatars are found throughout material design with uses in everything from tables to dialog menus.</p>

## Image avatars

Image avatars can be created by passing standard `img` props `src` or `srcSet` into the component.

{{"demo": "pages/components/avatars/ImageAvatars.js"}}

## Letter avatars

Avatars containing simple characters can be created by passing your string as `children`.

{{"demo": "pages/components/avatars/LetterAvatars.js"}}

## Icon avatars

Icon avatars are created by passing an icon as `children`.

{{"demo": "pages/components/avatars/IconAvatars.js"}}

## Variants

If you need square or rounded avatars, use the `variant` prop.

{{"demo": "pages/components/avatars/VariantAvatars.js"}}

## Fallbacks

The component fallbacks if there is an error loading the avatar image, in this order, to:

- the provided children
- the first letter of tha `alt` text
- a generic avatar icon

{{"demo": "pages/components/avatars/FallbackAvatars.js"}}
