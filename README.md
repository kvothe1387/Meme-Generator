# Meme Generator

A React application that allows users to create custom memes with personalized text.

## Features

- Fetch popular meme templates from the imgflip API
- Add custom top and bottom text to memes
- Generate random meme templates with a single click
- Simple and intuitive user interface

## Demo

![Meme Generator Demo](/public/meme-generator-screenshot.png)

## Technologies Used

- React
- JavaScript (ES6+)
- CSS
- imgflip API

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/meme-generator.git
   ```

2. Navigate to the project directory:
   ```
   cd meme-generator
   ```

3. Install dependencies:
   ```
   npm install
   ```

4. Start the development server:
   ```
   npm start
   ```

5. Open your browser and visit `http://localhost:3000`

## How to Use

1. The app loads with a default meme template and placeholder text
2. Modify the top and bottom text fields to customize your meme
3. Click "Get a new meme image" to randomly select a different template
4. Your custom text will be applied to the new template automatically

## Project Structure

```
meme-generator/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── components/
│   │   └── Main.js
│   ├── App.js
│   ├── index.js
│   └── styles.css
└── package.json
```

## API Reference

This project uses the [imgflip API](https://imgflip.com/api) to fetch meme templates.

- Endpoint: `https://api.imgflip.com/get_memes`
- Response: JSON object containing an array of meme templates with URLs and metadata

## Future Improvements

- Add ability to download or share created memes
- Implement categories for meme templates
- Add user authentication to save favorite memes
- Implement a gallery of user-created memes

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [imgflip](https://imgflip.com/) for providing the meme templates API
- [React documentation](https://reactjs.org/docs/getting-started.html) for guides and references