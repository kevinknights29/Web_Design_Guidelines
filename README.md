# Web_Design_Guidelines

This project contains guidelines on how to design beautiful websites.

## Table of Contents

1. [Typography](#typography)
2. [Color](#color)
3. [Images](#images)
4. [Icons](#icons)

## Guidelines

### Typography

1. Use a font size between 15 and 25 pixels (Body).

2. Use (really) big font size for headlines.
    - EXAMPLE: 60px.
    - NOTE: The more you increase the font size, the more you need to decrease the font weight.

3. Use line spacing between 120 and 150% of font size.

4. Maintain 45 to 90 characters per line.

5. Use good fonts (a bit subjective)
    - Sans-serif
        - More Neutral
        - Clean
        - Simple
        - Modern websites
    - Serif
        - Traditional purposes
        - Storytelling
        - Long reading

    - EXAMPLE:
        - Sans-serif
            - Open Sans
            - Lato
            - Raleway
            - Montserrat
            - PT Sans
        - Serif
            - Cardo
            - Merriweather
            - PT Serif

#### How to choose a Font?

1. Choose a font that reflects the look and feel you want for your website.

2. Decide: sans-serif or serif typeface?

3. Use a good font.

4. Use only that one typeface.

### Color

1. Use only one base color.
    - A list of base colors can be found [here](https://flatuicolors.com/palette/defo).

2. Select a darker a lighter version of that color for your palette.
    - A tool to achieve this can be found [here](https://0to255.com/)

3. Use color to draw attention.
    - NOTE: You can use a color wheel tool to mix colors.
        An example of such a tool can be found [here](https://www.canva.com/colors/color-wheel/).

4. Never use black in your design.

5. Choose colors wisely

    Color makes a difference. This happens because there are psychological effects behind each color.

    - `Red`: power, passion, strength, and excitement.
    - `Orange`: cheerfulness, creativity, friendliness, confidence, and courage.
    - `Yellow`: happiness, liveliness, curiosity, intelligence, brightness.
    - `Green`: harmony, nature, life, money, and health.
    - `Blue`: patience, peace, trustworthiness, stability, professionalism, trust, and honor.
    - `Purple`: wisdom royalty, nobility, luxury, and mystery.
    - `Pink`: romance, passivity, care, peace, and affection.
    - `Brown`: relaxation, confidence, earthiness, nature, durability, comfort, and reliability.

    NOTE: Brighter tones are more energetic, while darker tones are more powerful and elegant.

### Images

#### Techniques when working with images

1. Put text directly on the image.

    NOTE: This only works if the image is quite dark and your text is white.

2. Overlay the image with a color.

    NOTE: The simplest way to do this, is by using the color `black`.

3. Put text in a box.

    NOTE: The box should be opaque.

4. Blur the image.

5. Floor fade.

    NOTE: This works when you are planning to put the text at the bottom of the image.

#### Applying techniques with CSS

Here is a list of example CSS code for some of the effects.
Please change it according to your needs.

- **Overlay the image**

```css
    .darken {
        background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(YOUR IMAGE HERE);
    }
```

[Example](http://jsfiddle.net/drpak8vy/1/)

- **Put text in a box**

```css
    .text-box {
        background-color: rgba(0, 0, 0, 0.5);
        color: #fff;
        display: inline;
        padding: 10px;
    }
```

[Example](http://jsfiddle.net/qg83m36p/)

- **Floor fade**

```css
    .floor-fade {
        background: linear-gradient(to bottom, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.6) ), url(YOUR IMAGE HERE);
    }
```

[Example](http://jsfiddle.net/gRzPF/409/)

### Icons

1. Use icons to list features/steps.

2. Use icons for actions/links.

    NOTE: Here are some rules to follow when applying this concept.

    - Icons should be recognizable.
    - Label your icons.

3. Icons should not take center stage.

4. Use icon fonts whenever possible.

    NOTE: icon fonts use smooth vector images instead of raster images to display icons.
