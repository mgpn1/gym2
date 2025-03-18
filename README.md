# EliteFit Gym Website

A modern, responsive gym website built with HTML, CSS, and JavaScript. This website is designed to showcase a premium fitness facility with a focus on user experience and modern design elements.

## Features

- Responsive design that works on all devices
- Modern and clean user interface
- Smooth scrolling navigation
- Animated sections and elements
- Contact form with validation
- Mobile-friendly navigation menu
- Social media integration
- Class and trainer showcase
- Opening hours information

## Technologies Used

- HTML5
- CSS3 (with CSS Variables and Flexbox/Grid)
- JavaScript (Vanilla)
- Font Awesome Icons
- Google Fonts (Poppins)

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/yourusername/elitefit-gym.git
```

2. Navigate to the project directory:
```bash
cd elitefit-gym
```

3. Open the project in your preferred code editor.

4. To view the website locally, you can use any local server. For example:
   - Using Python: `python -m http.server`
   - Using Node.js: Install `http-server` globally and run `http-server`
   - Using VS Code: Install the "Live Server" extension and click "Go Live"

5. Open your browser and navigate to `http://localhost:8000` (or the port specified by your local server).

## Project Structure

```
elitefit-gym/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── images/
│   ├── hero-bg.jpg
│   ├── strength-training.jpg
│   ├── cardio.jpg
│   ├── yoga.jpg
│   ├── crossfit.jpg
│   ├── trainer1.jpg
│   ├── trainer2.jpg
│   └── trainer3.jpg
└── README.md
```

## Customization

### Colors
The website uses CSS variables for easy color customization. You can modify the colors in the `:root` section of `style.css`:

```css
:root {
    --primary-color: #ff4d4d;
    --secondary-color: #333;
    --accent-color: #ffd700;
    --text-color: #333;
    --light-bg: #f9f9f9;
    --white: #ffffff;
}
```

### Images
Replace the images in the `images/` directory with your own images. Make sure to maintain the same file names or update the image paths in the HTML file.

### Content
Edit the content in `index.html` to match your gym's information, including:
- Gym name and description
- Class offerings
- Trainer information
- Contact details
- Opening hours
- Social media links

## Browser Support

The website is compatible with all modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Your Name - your.email@example.com
Project Link: https://github.com/yourusername/elitefit-gym 