# Photo Organizer AI Plugin

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS-brightgreen)
![Browsers](https://img.shields.io/badge/browsers-Chrome%20%7C%20Firefox%20%7C%20Edge%20%7C%20Safari%20%7C%20Opera-orange)

**Photo Organizer AI Plugin** is a cross-browser extension for Windows and macOS that helps you organize your photos using AI-powered object recognition, tagging, and search functionality. It works seamlessly with the top 5 most popular browsers: Chrome, Firefox, Edge, Safari, and Opera.

---

## Features

- **AI-Powered Object Recognition**: Automatically detects objects, faces, and text in your photos using AI models.
- **Tagging**: Add custom tags to your photos for better organization.
- **Search & Filter**: Easily search and filter photos by tags, dates, or recognized objects.
- **Local Processing**: Uses TensorFlow.js for local AI processing, ensuring your data stays private.
- **Cross-Browser Support**: Works on Chrome, Firefox, Edge, Safari, and Opera.

---

## Installation

### Prerequisites

- Node.js (v16 or higher)
- npm (v8 or higher)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/photo-organizer-ai-plugin.git

   ```

2. Navigate to the project directory:

   ```bash
    cd photo-organizer-ai-plugin

   ```

3. Install dependencies:

    ```bash
     npm install

    ```

4.  Build the extension:

    ```bash

    npm run build

    ```

5.  Load the extension in your browser:

- **Chrome: Go to chrome:**//extensions/, enable "Developer mode," and click "Load unpacked." Select the dist folder.
- **Firefox:** Go to about:debugging#/runtime/this-firefox, click "Load Temporary Add-on," and select the dist folder.
- **Edge: Go to edge:**//extensions/, enable "Developer mode," and click "Load unpacked." Select the dist folder.
- **Safari:** Open Safari, go to Preferences > Extensions, and enable the extension.

## Usage

1. Import Photos:

- Click the "Upload" button to import photos from your local device.
- Alternatively, connect to Google Drive or iCloud to import photos from the cloud.

2. View Recognized Objects:

- After uploading, the plugin will automatically recognize objects, faces, and text in your photos.

3. Add Tags:

- Click on a photo to add custom tags (e.g., "vacation," "family," "dog").

4. Search & Filter:

- Use the search bar to find photos by tags, dates, or recognized objects.

## Technologies Used

- **Frontend:** React.js, TensorFlow.js

- **AI Models:** Google Vision API, TensorFlow.js (MobileNet)

- **Storage:** IndexedDB

- **Build Tools:** Webpack, Babel

## Contributing

We welcome contributions! If you'd like to contribute, please follow these steps:

1. Fork the repository.

2. Create a new branch:

   ```bash
   git checkout -b feature/your-feature-name

   ```

3. Commit your changes:

   ```bash
   git commit -m "Add your feature"
   ```

4. Push to the branch:

   ```bash
   git push origin feature/your-feature-name
   ```

5. Open a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For questions or feedback, feel free to reach out:

- Email: photoorganizerai@gmail.com
- GitHub Issues: Open an Issue

## Acknowledgments

- Thanks to TensorFlow.js for providing powerful AI tools.
- Special thanks to the Google Vision API team for their object recognition capabilities.


