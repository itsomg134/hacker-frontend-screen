<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/46e06e39-6d9c-4ba2-a272-bc5fa1ed316e" />
# 🖥️ Hacker Terminal Interface

A retro-styled, cyberpunk-themed terminal interface with a classic green-on-black hacker aesthetic. Perfect for portfolios, themed projects, or just for fun!

![Terminal Interface](https://img.shields.io/badge/style-hacker-green?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## ✨ Features

- **Authentic Terminal Experience**: Interactive command-line interface with multiple working commands
- **Retro CRT Effect**: Scanlines and glowing text for that classic hacker movie aesthetic
- **Live System Stats**: Real-time monitoring of CPU usage, connections, and uptime
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Smooth Animations**: Typing effects, flickering, and smooth transitions
- **Background Activity**: Random system messages for added realism

## 🎮 Demo

Try these commands in the terminal:
- `help` - Display all available commands
- `status` - Check system status
- `scan` - Scan network for active devices
- `ls` - List directories
- `whoami` - Display current user
- `date` - Show current date and time
- `sysinfo` - Display system information
- `clear` - Clear the terminal

## 🚀 Quick Start

1. Clone the repository:
```bash
git clone https://github.com/yourusername/hacker-terminal.git
```

2. Navigate to the project directory:
```bash
cd hacker-terminal
```

3. Open `index.html` in your browser:
```bash
open index.html
# or simply double-click the file
```

That's it! No build process or dependencies required.

## 📁 Project Structure

```
hacker-terminal/
│
├── index.html          # Main HTML file with embedded CSS and JS
└── README.md          # This file
```

## 🎨 Customization

### Color Scheme
Change the terminal colors by modifying the CSS variables in the `<style>` section:

```css
color: #00ff00;  /* Main text color */
border: 2px solid #00ff00;  /* Border color */
background: #0a0a0a;  /* Background color */
```

### Add Custom Commands
Extend the command list by adding to the `commands` object in the JavaScript section:

```javascript
const commands = {
    help: 'Available commands: ...',
    yourcommand: 'Your command output here',
    // Add more commands
};
```

### Modify Stats
Customize the dashboard statistics in the HTML stats section:

```html
<div class="stat-box">
    <div class="stat-label">YOUR LABEL</div>
    <div class="stat-value" id="yourstat">VALUE</div>
</div>
```

## 🛠️ Built With

- **HTML5** - Structure
- **CSS3** - Styling and animations
- **Vanilla JavaScript** - Interactivity (no frameworks!)

## 💡 Use Cases

- **Portfolio Projects**: Showcase your cybersecurity or developer portfolio
- **Educational Tools**: Teach basic command-line concepts
- **Themed Websites**: Add a hacker aesthetic to your site
- **CTF/Hacking Games**: Create immersive user interfaces
- **Movie Props**: Screen-accurate hacker terminals for film/video projects

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Ideas for Contributions
- Add more terminal commands
- Implement command history (up/down arrow keys)
- Add tab completion
- Create different color themes
- Add sound effects
- Implement file system simulation

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by classic hacker movies and cyberpunk aesthetics
- CRT scanline effect adapted from retro terminal designs
- Community feedback and suggestions
