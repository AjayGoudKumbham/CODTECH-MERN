# Productivity Tracker Chrome Extension

A powerful Chrome extension to help you monitor and optimize your online productivity. Track time spent on different websites, block distracting sites, and get insights into your browsing habits.

## Features

- 📊 Real-time website tracking and analytics
- 🚫 Website blocking with customizable blocklist
- 📈 Daily and weekly productivity reports
- ⚙️ Customizable settings and preferences
- 🌙 Dark mode support
- 🔄 Data syncing across devices (using Chrome storage)

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/productivity-tracker-extension.git
```

2. Install dependencies:
```bash
npm install
```

3. Build the extension:
```bash
npm run build
```

4. Load the extension in Chrome:
   - Open Chrome and go to `chrome://extensions/`
   - Enable "Developer mode" in the top right
   - Click "Load unpacked" and select the `dist` folder from this project

## Development

To start development with hot-reloading:
```bash
npm run watch
```

## Usage

1. Click the extension icon in Chrome to open the dashboard
2. View your daily website usage statistics in the Dashboard tab
3. Add distracting websites to the block list in the Block List tab
4. Customize your preferences in the Settings tab

## Tech Stack

- React.js for the user interface
- Material-UI for components and styling
- Chart.js for data visualization
- Chrome Extension APIs for browser integration
- Chrome Storage API for data persistence

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 