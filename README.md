# Font Awesome Browser

Font Awesome Browser is a simple and user-friendly JavaScript plugin that lets users easily pick an icon from a modern, responsive icon browser. When an icon is selected, the plugin automatically fills the input field with the corresponding Font Awesome class name.

[Live Demo](https://codepen.io/GianlucaChiarani/pen/yLgZJvX)

## Features

- Clean and responsive icon browser
- Fast search through all Font Awesome icons
- Select an icon with a single click
- Automatically inserts the icon class into your input field
- Easy to add to any website or web app

## Installation

Add these lines inside your HTML `<head>` section:

```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/GianlucaChiarani/FontAwesomeBrowser@0.5/src/fabrowser.css" />
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/GianlucaChiarani/FontAwesomeBrowser@0.5/src/fabrowser.js"></script>
```

## Usage

1. Add an input element with the `data-fa-browser` attribute where you want the icon picker to appear:

```
<input type="text" data-fa-browser />
```

2. Initialize the plugin after the page has loaded:

```
<script>
  fabrowser();
</script>
```

### Complete Example

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Font Awesome Browser Example</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/GianlucaChiarani/FontAwesomeBrowser@0.5/src/fabrowser.css" />
  <script type="text/javascript" src="https://cdn.jsdelivr.net/gh/GianlucaChiarani/FontAwesomeBrowser@0.5/src/fabrowser.js"></script>
</head>
<body>
  <input type="text" data-fa-browser placeholder="Choose an icon..." />
  <script>
    fabrowser();
  </script>
</body>
</html>
```

## Contributing

Contributions, bug reports, and suggestions are welcome! Please open an issue or a pull request on GitHub.

## License

This project is licensed under the MIT License.
