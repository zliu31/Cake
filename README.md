# 🎂 Make a Cake! Interactive Website

An interactive, step-by-step cake designer where users can create their dream cake and see it visualized in real-time.

## 🌐 Live Demo

Once GitHub Pages is enabled, visit: **https://zliu31.github.io/Cake/**

> **Not live yet?** See [GITHUB_PAGES_SETUP.md](GITHUB_PAGES_SETUP.md) for setup instructions.

## Features

### Interactive Step-by-Step Flow
1. **Choose Base Flavor**: Matcha, Vanilla, Chocolate, or Red Velvet
2. **Choose Cake Type**: Birthday Cake or Cupcake
   - Birthday Cake: Select 1, 2, or 3 layers
   - Cupcake: Automatically proceeds to frosting
3. **Choose Frosting Color**: White, Pink, Yellow, Purple, or Brown
4. **Choose Fruit Topping**: Strawberry, Mango, or Peach
5. **Add Sprinkles**: Yes or No

### Visual Design
- **Playful & Colorful**: Gradient backgrounds and colorful buttons
- **Smooth Transitions**: Fade-in animations between steps
- **Progress Tracker**: Visual dots showing current progress
- **Responsive Design**: Works on desktop and mobile devices
- **Centered Layout**: Clean, modern interface

### Cake Visualization
- **Dynamic Canvas Drawing**: Cakes are drawn in real-time based on selections
- **Birthday Cake**: Shows multiple layers with frosting, candle, and toppings
- **Cupcake**: Shows wrapper, swirl frosting, and toppings
- **Sprinkles**: Randomly distributed colorful sprinkles when selected
- **Fruit Details**: Different fruit styles (strawberry with seeds and leaf)

## How to Use

1. Open `index.html` in any modern web browser
2. Follow the step-by-step instructions
3. Click on your preferred options for each step
4. View your completed cake design with a summary description
5. Click "Start Over" to create a new cake

## Technical Details

- **Pure HTML/CSS/JavaScript**: No external dependencies or backend required
- **Canvas API**: Used for drawing the cake visualization
- **Responsive Design**: Mobile-friendly layout
- **Smooth Animations**: CSS transitions and keyframes
- **Single File**: Everything contained in one HTML file for easy deployment

## Customization

You can easily customize:
- **Colors**: Modify the gradient values in the CSS
- **Button Styles**: Change the `.option-btn` classes
- **Cake Drawing**: Adjust the canvas drawing functions
- **Add New Options**: Add more flavors, toppings, or frosting colors

## Image Integration

The current implementation uses HTML Canvas to draw cakes dynamically. To use actual images instead:

1. Add image files to an `images/` folder
2. Replace the `drawCake()` function to use image composition
3. Use the cake configuration to select and layer appropriate images

## Browser Compatibility

Works on all modern browsers that support:
- CSS Grid
- Canvas API
- ES6 JavaScript

## Example Output

"You made a 2-layer chocolate birthday cake with pink frosting, topped with mango, and sprinkles!"

Enjoy creating your dream cakes! 🎂✨
