# Design Guidelines

We're having fun here, and we don't need to care about universal or industrial rules; but certain practices for good user experience and accessibility are still required. The design guidelines provided by [Material Design](https://material.io/) system is very helpful. We can take advantage of the principles of hierarchy and naming in terms of colors, fonts and layouts. Note that it's not the styles we're looking for in the guidelines, but the principles and design patterns.

---

## Website main sections

Adjacent website typically consists of three main sections that require designers attention: landing page, article page and menu. Always keep article page and menu in mind as designing landing page, making sure everything is going to be consistent.

<div>
<img style="width: 30%;" alt="screenshot from issue 6 article page" src="./assets/design-guidelines/issue-6_article.png">
<img style="width: 30%;" alt="screenshot from issue 6 landing page" src="./assets/design-guidelines/issue-6_landing.png">
<img style="width: 30%;" alt="screenshot from issue 6 menu" src="./assets/design-guidelines/issue-6_menu.png">
</div>

---

## Design systems

For consistency of the website and efficient communication between dev team members, sets of elements in following aspects are suggested to be considered during the design process.

### Typography

It's suggested to use up to **two types of fonts** in Adjacent website.

- **Font family**
	- Main font - Major font used across the website.
	- Sub font - Minor font choice for long paragraph or secondary information.

- **Font weight**
	- If required, each font family should have according variations of font weight.

- **Type scale**
	- It's suggested to organize a system of font size usage, following the naming and spec [Material Design](https://material.io/design/typography/the-type-system.html#) provides.

[![Type Scale provided by Material Design](https://storage.googleapis.com/spec-host/mio-staging%2Fmio-design%2F1579302979877%2Fassets%2F1W8kyGVruuG_O8psvyiOaCf1lLFIMzB-N%2Ftypesystem-typescale.png)](https://material.io/design/typography/the-type-system.html#)

- **Type color**
	- Following the website [color system](https://material.io/design/color/the-color-system.html#color-theme-creation), it's also suggested to think of colors of fonts on other colors.
	- Making sure the contrast between font color and background color is accessible.

	[![Typography and iconography colors provided by Material Design](https://storage.googleapis.com/spec-host/mio-staging%2Fmio-design%2F1579302979877%2Fassets%2F1jTwR_tLfYC3x-B1bD8hN7Nza9x2y1Kny%2Ftheming-color-oncolors.png)](https://material.io/design/color/the-color-system.html#color-theme-creation)

### Color

Though [Material Design](https://material.io/design/color/the-color-system.html#color-theme-creation) provides a comprehensive setting of color theme, we don't need to follow every details but at least following settings:

1. Primary color
2. Secondary color
3. Background color

[![The baseline Material color theme](https://storage.googleapis.com/spec-host/mio-staging%2Fmio-design%2F1579302979877%2Fassets%2F1hg4iTKzTMMgtJRx7bhaE2kSYR5BRYz1g%2Fcolor-colorsystem-schemecreation-theme.png)](https://material.io/design/color/the-color-system.html#color-theme-creation)

### Layout

Constraint of grid system is unnecessary here, but the **margins on two sides** of the website is required. These two vertical bars is the negative space of the **safe and comfortable reading zone** of the website. Very important.

![Issue 6 safe zone in article page](./assets/design-guidelines/issue-6_article-margin.png)

[![Responsive layout grid provided by Material Design](https://storage.googleapis.com/spec-host/mio-staging%2Fmio-design%2F1579302979877%2Fassets%2F1P_b7NIZ5_IBvs9VraJx7tu8KO-dUZXJW%2Flayout-responsive-columns-margins-gutters.png)](https://material.io/design/layout/responsive-layout-grid.html#)

---

## For front-end development
### Responsive design
### Deliverables (UI files) for developers