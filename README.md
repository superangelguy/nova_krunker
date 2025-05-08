# NovaKrunker

```
  _   _                 _  _  _                 _              
 | \ | |               | || || |               | |             
 |  \| |  ___  _   _   | || || |  ___  _ __  __| |  ___  _ __  
 | . ` | / _ \| | | |  | || || | / _ \| '__|/ _` | / _ \| '_ \ 
 | |\  ||  __/| |_| |  | || || ||  __/| |  | (_| || (_) | | | |
 |_| \_| \___| \__,_|  |_||_||_| \___||_|   \__,_| \___/|_| |_|
```

A modern, feature-rich Krunker client built with Electron and TypeScript.

## Features

- Enhanced performance settings
- Discord Rich Presence integration
- Customizable matchmaking
- Resource swapping (sounds, textures, etc.)
- Built-in hotkeys
- Modern UI with customizable settings
- Cross-platform support (Windows, macOS, Linux)

## Development Setup

1. Install dependencies:
```bash
npm install
```

2. Start development server:
```bash
npm run dev
```

3. Build for production:
```bash
npm run build
```

## Available Scripts

- `npm start` - Start the application
- `npm run dev` - Start in development mode with hot reload
- `npm run build` - Build for production
- `npm run watch` - Watch for changes and rebuild

## Configuration

The client stores settings in the following locations:
- Windows: `%APPDATA%/krunker-client/config.json`
- macOS: `~/Library/Application Support/krunker-client/config.json`
- Linux: `~/.config/krunker-client/config.json`

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 