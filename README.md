# JS + CSS Clock 

A simple and elegant analog clock built with HTML, CSS and JavaScript.

## Features

- Real-time clock display with hour, minute, and second hands
- Smooth rotating animations for the clock hands
- Responsive design with a watercolor background
- Custom emoji display for the time indicator

## Project Structure

```
03 - Clock-JavasCript-CSS" /
├── index.html              # Main HTML file
├── style.css               # Styles for the clock
└── dark-green-watercolor-brush-stroke.jpg  # Background image
```

## How It Works

The clock is built using:

1. **HTML**: Creates the clock face structure with three hands (hour, minute, second)
2. **CSS**: Styles the clock with a dark slate gray background, dark cyan border, and smooth transitions
3. **JavaScript**: 
   - Gets the current time using `new Date()`
   - Calculates rotation degrees for each hand based on current time
   - Updates hand positions every second using `setInterval()`

## Clock Mathematics

- **Second hand**: `(seconds / 60) * 360 + 90` degrees
- **Minute hand**: `(minutes / 60) * 360 + (seconds / 60) * 6 + 90` degrees
- **Hour hand**: `(hours / 12) * 360 + (minutes / 60) * 30 + 90` degrees

The `+90` offset accounts for the initial rotation of the hands to point upward at 12 o'clock.

## Usage

Simply open `index.html` in any modern web browser to see the clock in action.

## Technologies

- HTML5
- CSS3 (Flexbox, Transforms, Transitions)
- JavaScript (Vanilla)

## Preview

The clock features:
- A circular clock face with a dark cyan border
- Three animated hands that move smoothly
- A watercolor background texture
- A decorative title with an emoji indicator

## Browser Compatibility 🌐

Works in all modern browsers:
- Chrome/Edge
- Firefox
- Safari
- Opera

## License 📝

This project is open source and free to use for any purpose.

## Credits 👏

Created by Juan Sebastian Andrade Sanchez - Built with ❤️ using HTML, CSS, and JavaScript
---

**Do you know what time it is?** 🎉