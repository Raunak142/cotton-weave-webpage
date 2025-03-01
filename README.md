# cotton-weave-webpage


# Responsive Layout with CSS Flexbox and Positioning

This project demonstrates a responsive layout built with HTML and CSS. It features a split-screen design with a left section containing text and color options, and a right section displaying an image with an overlay and rotated text.

## Features
- **Responsive Layout**: The layout adjusts based on the screen size.
- **Flexbox for Layout**: The main container and left section use Flexbox for alignment and distribution of space.
- **Dynamic Font Sizing**: The font sizes in the layout are responsive, using `vw` (viewport width) units to scale based on the screen size.
- **Image and Overlay**: The right section contains an image with an overlay circle displaying text.
- **Rotated Text**: The text in the right section is rotated for a unique effect.

## Installation

To view or modify this project on your local machine, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/repository-name.git
   ```

2. Navigate to the project directory:

   ```bash
   cd repository-name
   ```

3. Open the `index.html` file in your browser to see the layout in action.

## Folder Structure

```
/repository-name
│
├── index.html    # The main HTML file
└── style.css     # The main CSS file for styling the layout
```

## Code Breakdown

### Global Styles (`*` selector)
- Resets margin, padding, and sets the box-sizing to `border-box` for all elements.
- Applies the font family globally (`Arial, Helvetica, sans-serif`).

### HTML & Body
- Ensures the HTML and body elements take up 100% of the height and width of the viewport.

### Main Section (`#main`)
- A flex container that divides the screen into two sections: left and right.
- The left section (`#left`) contains dynamic text and a color picker.
- The right section (`#right`) holds an image and an overlay circle with text.

### Left Section (`#left`)
- Contains a header (`h1`), subheader (`h2`), and a color palette section.
- Uses Flexbox for vertical alignment and spacing.
- The text is responsive and adjusts in size based on viewport width using `vw` units.

### Right Section (`#right`)
- Displays an image with `object-fit: cover` to ensure it covers the available space.
- Includes a circular overlay (`#black`) with text centered inside.
- The right section also features rotated text (`#rotated`) positioned at the bottom.

## Customization
You can customize the following:

- **Colors**: Modify the background colors in the `#color1` and `#color2` divs.
- **Image**: Replace the image in the `#right` section with your own by modifying the `img` tag's `src` attribute.
- **Fonts**: Adjust font sizes and families by modifying the `font-size` and `font-family` properties in the CSS.

