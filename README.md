# Link Tree App

This is a personal Link Tree app built using **HTML**, **CSS**, and **JavaScript**. It’s a custom link aggregator designed for personal use and deployed on **GitHub Pages**.

---

## Features

- **Responsive Design**: Works seamlessly across desktop and mobile devices.
- **Dynamic Links**: Links are dynamically generated using JavaScript.
- **Customizable**: Easily update links, icons, and styling.
- **Deployed on GitHub Pages**: Accessible from anywhere.
- **Elegant UI**: Uses a modern, minimalist design with hover animations.

---

## Live Demo

Check out the live version [here](https://chaitanychaudhary.github.io/Link-Tree/).

---

## Project Structure

```
assets/        # Contains all images and assets used in the project
css/           # Stylesheets
  main.css     # Main CSS file
js/            # JavaScript files
  main.js      # Script for rendering links
  links.js     # Links data
index.html     # Main HTML file
```

---

## How It Works

1. **HTML Structure**: The `index.html` file contains the structure of the app, including placeholders for dynamically generated links.
2. **Dynamic Links**: The `links.js` file holds an array of objects, each representing a link with a name, URL, and image. These are dynamically rendered in `main.js`.
3. **Styling**: The `main.css` file defines the styles for the app, including responsiveness and hover effects.
4. **Deployment**: The app is hosted on GitHub Pages for easy access.

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/ChaitanyChaudhary/Link-Tree.git
   ```
2. Navigate to the project directory:
   ```bash
   cd link-tree-app
   ```
3. Open `index.html` in your browser to view the app.
4. Customize the links in `js/links.js` as per your requirements.

---

## Links Data Format

Update `js/links.js` to add or modify links. Each link follows this structure:
```javascript
{
    name: "Platform Name",
    link: "https://example.com",
    image: "assets/image.png"
}
```

---

## Credits

- **Icons and Images**: Custom or royalty-free images.
- **Background**: Assets folder contains the background image.

---

## License

This project is licensed under the [MIT](https://github.com/ChaitanyChaudhary/Link-Tree/blob/main/LICENSE) License. Feel free to use and modify it for your own purposes.

---

## Author

- **Chaitany Chaudhary**
