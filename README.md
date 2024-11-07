
# Volume Booster Chrome Extension

A Chrome extension to boost the volume of audio and video elements beyond the default limit. This extension allows you to increase the volume up to 200%, providing a higher volume output for media playing in the browser.

## Features

- Boost the volume of audio and video elements beyond the browser's default 100% limit (up to 200%).
- Simple, easy-to-use UI with a slider to adjust volume levels.
- Displays the current volume percentage on the UI.
- Lightweight and efficient, no need for additional configurations.

## Installation

### 1. Clone the repository
Clone the repo to your local machine:

```bash
git clone https://github.com/yourusername/volume-booster.git
```

### 2. Install dependencies
Ensure you have [Node.js](https://nodejs.org/en/) installed on your machine. Then, navigate to the project directory and install the necessary dependencies:

```bash
cd volume-booster
npm install
```

### 3. Build the extension
To create an optimized production build, run:

```bash
npm run build
```

This will generate the necessary build files for your Chrome extension.

### 4. Load the extension in Chrome

1. Open Chrome and go to `chrome://extensions/`.
2. Enable **Developer Mode** in the top-right corner.
3. Click on **Load unpacked** and select the `build` directory from the cloned repository.

Now the extension should be active and ready to use in your browser.

## Usage

- Once installed, the extension will appear in the Chrome toolbar.
- Click on the extension icon to open the volume booster slider.
- Adjust the slider to increase the volume beyond the default limit (up to 200%).
- The current volume percentage will be displayed below the slider.

## Technologies Used

- **React.js**: Used for the UI development.
- **Chrome Extension API**: Interacts with media elements (audio and video) on the webpage.
- **JavaScript/HTML/CSS**: Standard web technologies used to build the extension’s interface.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add feature'`).
5. Push to the branch (`git push origin feature-name`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to [React Icons](https://react-icons.github.io/react-icons/) for providing the volume icons used in this extension.
