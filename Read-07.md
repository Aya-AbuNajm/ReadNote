# Introducing CSS
web pages more **attractive , controlling** the design .

## Thinking Inside the Box
> The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.

## Foreground Color
You can specify any color in CSS in one of three ways:
* **rgb values**
These express colors in terms  of how much red, green and blue are used to make it up. For example: rgb(100,100,90)   

* **hex codes**
These are six-digit codes that represent the amount of red,
green and blue in a color,
preceded by a pound or hash #sign. For example: #ee3e80
* **color names**
There are 147 predefined color names that are recognized
by browsers.
* **DarkCyan**
We look at these three different ways of specifying colors on the next double-page spread.
![img21](https://i.pinimg.com/originals/22/dd/64/22dd6419f9773617a80e3c763a79db2f.png)


## Background Color
CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box.

You can specify your choice of background color in the same
three ways you can specify foreground colors: RGB values,
hex codes, and color names (covered on the next page).
If you do not specify a background color, then the
background is transparent.

By default, most browser windows have a white background, but browser users can set a background color for
their windows, so if you want to be sure that the background
is white you can use the background-color property on the <body> elemen

## Understanding Color
Every color on a computer screen is created by mixing amounts of red, green, and blue. To find the color you want, you can use a color picker.
![im45](https://res.cloudinary.com/dno0vkynk/image/upload/v1475392871/RGBvsCMYKvsPANTONE.png)

### opacity
CSS3 introduces the opacity property which allows you to
specify the opacity of an element and any of its child  lements.
The value is a number between 0.0 and 1.0 (so a value of 0.5
is 50% opacity and 0.15 is 15% opacity).

The CSS3 rgba property allows you to specify a color, just like you would with an RGB value, but adds a fourth value to
indicate opacity. This value is known as an alpha value and is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity). The rgba value will only affect the element on which it is applied (not child  lements).

### HSL Colors

**hue**
Hue is the colloquial idea of color. In HSL colors, hue is often represented as a color circle where the angle represents the color, although it may also be
shown as a slider with values from 0 to 360.

**saturation**
Saturation is the amount of gray in a color. Saturation is
represented as a percentage.
100% is full saturation and 0% is a shade of gray.

**lightness**
Lightness is the amount of white (lightness) or black
(darkness) in a color. Lightness is represented as a percentage.
0% lightness is black, 100% lightness is white, and 50%
lightness is normal. Lightness is sometimes referred to as
luminosity

