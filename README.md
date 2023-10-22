# LEGO Figure

**LEGO Figure** is a creative project crafted entirely with HTML and CSS, designed to resemble a classic LEGO minifigure.

The figure is fully scalable and customizable with variables, allowing you to easily adjust its size and colors.

## How to view

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/lego-figure.git
   ```

2. Open the `lego-figure.html` file in your web browser.

## Customisation

**Color adjustment:**
All shadows and highlights are automatically calculated from color variables. To modify the colors of the figure's skin and clothes, make changes to the defined color variables in the `:root` tag:

```css
:root {
  --color-skin: #fdcc24;
  --color-sweater: #e1181c;
  --color-pants: #0858a8;
  ...;
}
```

**Size adjustment:**
The size of all elements is computed relative to the `--width` variable set in the `:root` tag. To maintain the figure's proportions, adjust this variable only:

```css
  :root {
    ...
    --width: 500px;
  }
```

## Contributing

Feel free to add an issue or submit a pull request if you have any suggestions or encounter any issues.

If you have any questions or feedback about this project, please reach out.

<br></br>

---

## Disclaimer

**This project is not affiliated with or endorsed by the LEGO Group.**

This project, is an independent creation and is not associated with or endorsed by the LEGO Group. LEGO®, the LEGO logo, and related terms are trademarks of the LEGO Group. The LEGO Group has not reviewed or approved this project.

Please note that this project is intended for creative and educational purposes. The use of the term "LEGO" and any related terminology in this project is for descriptive purposes to indicate the design aesthetic or inspiration, and it does not imply any official connection with or endorsement by the LEGO Group.
