## Web Social (Button Library)
One line of code, your desired button

Web Social is a lightweight and customizable library for adding pre-styled icon buttons into your project.
Whether it's your social media profile link, or a link to you PayPal to ask for donations, Web Social has these buttons.
You can easily add buttons for popular brands like YouTube, Twitter, Bitcoin, and more. Linking your socials has never been this easy

## Features

- Easy to add: A line of code for each button including whatever icon you prefer.
- Customizable: Change the appearance and behavior of buttons to match your website's design.
- Lightweight: Web Social is designed to be lightweight and fast-loading, ensuring optimal performance for your website.
- Modular: Each social media button is a separate component, allowing you to choose only the buttons you need for your project.

## Installation

To install Web Social in your project, simply include the CSS and JavaScript files in your project directory and link them in your HTML document:

The CSS In the `<head>` section, before your css file(if any)
```
<link rel="stylesheet" href="path/to/web-social.css">
```

The JS file before the closing `</body>` tag
```
<script src="path/to/web-social.js"></script>
```

## Usage
One line of code, like this...

```
<button class="ws ws-facebook" ws-link="your-link"></button>
```

`ws` - defines button type
(ws: default, wss: square, wsr: round)
`ws-facebook` - adds the icon button
`ws-link` - put your link here
See [our website][s] for all available buttons and class names

## Customization

Web Social provides various customization options, including button themes, sizes, and styles. You can customize the appearance of buttons by modifying the CSS styles in the `web-social.css` file.

## Examples

Here are some examples demonstrating how to use Web Social buttons in your website:

```html
<button class="ws ws-facebook" ws-link="https://facebook.com">Facebook</button>
<button class="ws ws-twitter" ws-link="https://twitter.com">Twitter</button>
<button class="ws ws-instagram" ws-link="https://instagram.com">Instagram</button>
```

## Contributing

Contributions are welcome! If you have any ideas for improving Web Social or want to report a bug, please open an issue or submit a pull request on GitHub.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
```
