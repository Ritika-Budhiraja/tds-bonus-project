# jarvis - Advanced AI Assistant 🧠

<div align="center">
  <img src="https://img.shields.io/badge/Version-2.8.0-blue.svg" alt="Version">
  <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License">
  <img src="https://img.shields.io/badge/PWA-Ready-purple.svg" alt="PWA Ready">
  <img src="https://img.shields.io/badge/JavaScript-ES6+-yellow.svg" alt="JavaScript">
</div>

## 📋 Overview

**jarvis** is a sophisticated, web-based AI assistant that combines multiple advanced capabilities into a single, intuitive interface. Built as a Progressive Web App (PWA), it offers a modern, responsive experience with powerful multi-tool functionality, voice interface, and real-time collaboration features.

## ✨ Key Features

### 🤖 **AI-Powered Chat Interface**
- Advanced conversational AI with context awareness
- Multi-provider LLM support (Google Gemini, and more)
- Customizable model parameters (temperature, max tokens)
- Conversation history and management

### 🔧 **Multi-Tool Capabilities**
- **Web Search**: Real-time web search integration for current information
- **Code Execution**: Safe JavaScript code execution environment
- **File Processing**: Upload and analyze various file formats (.txt, .json, .csv, .md, .js, .py, .html, .css, .xml, .yaml, .sql, .log)
- **Data Visualization**: Create interactive charts and graphs from data

### 🎙️ **Voice Interface**
- Speech-to-text input recognition
- Text-to-speech output with customizable voice settings
- Multiple language support
- Adjustable speech rate and preferences

### 🎨 **Modern UI/UX**
- Dark/Light theme support with auto-detection
- Responsive design for desktop and mobile
- Smooth animations and transitions
- Performance monitoring dashboard
- Drag-and-drop file upload
- Context menu integration

### 📱 **PWA Features**
- Offline functionality
- Install as native app
- Service worker caching
- Cross-platform compatibility

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (for AI services and web search)
- Microphone access (optional, for voice features)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Ritika-Budhiraja/tds-bonus-project
   cd tds-bonus-project-LLM-Agent
   ```

3. **Access the application:**
   Open your browser 

### API Configuration

The application comes pre-configured with default API keys for testing. For production use:

1. Obtain your own API keys from supported providers
2. Update the settings through the UI or modify the default configuration in `agent.js`
3. Supported providers: Google Gemini

## 📁 Project Structure

```
tds-bonus-project-LLM-Agent/
├── index.html          # Main HTML structure and UI components
├── agent.js           # Core AI assistant logic and functionality
├── styles.css         # Styling and responsive design
└── README.md          # Project documentation
```

## 🛠️ Technical Architecture

### Core Components

- **`jarvis` Class**: Main application controller with state management
- **Event-Driven Architecture**: Reactive UI updates and performance monitoring
- **Tool System**: Modular function calling for external capabilities
- **Caching Layer**: Intelligent caching for improved performance
- **State Management**: Proxy-based reactive state with persistence

### Key Technologies

- **Frontend**: Vanilla JavaScript (ES6+), HTML5, CSS3
- **Styling**: Bootstrap 5.3.2, Font Awesome 6.5.0, Custom CSS
- **Fonts**: Space Grotesk, JetBrains Mono
- **Code Highlighting**: Highlight.js
- **APIs**: Google Gemini AI, Web Search APIs
- **PWA**: Service Workers, Web App Manifest

### Performance Features

- **Lazy Loading**: Components loaded on demand
- **Debounced Operations**: Optimized user input handling
- **Memory Monitoring**: Built-in performance tracking
- **Response Caching**: Intelligent API response caching
- **Progressive Enhancement**: Works on all devices and connection speeds

## 🎯 Usage Examples

### Basic Chat
```javascript
// Simply type your question in the input field
"What's the weather like today?"
"Explain quantum computing in simple terms"
```

### Web Search
```javascript
// The assistant automatically searches the web when needed
"What are the latest developments in AI?"
"Current stock price of Tesla"
```

### Code Execution
```javascript
// Ask for code execution
"Calculate the fibonacci sequence for n=10"
"Create a function to reverse a string"
```

### File Processing
```javascript
// Drag and drop files or use the upload button
"Analyze this CSV data"
"Summarize this document"
```

## ⚙️ Configuration Options

### LLM Settings
- **Provider**: Choose AI model provider
- **Model**: Select specific model version
- **Temperature**: Control response creativity (0.0-2.0)
- **Max Tokens**: Set response length limit

### UI Preferences
- **Theme**: Auto, Light, or Dark mode
- **Animations**: Enable/disable UI animations
- **Font Size**: Small, Medium, or Large
- **Sound**: Audio feedback toggle

### Voice Settings
- **Language**: Multiple language support
- **Speech Rate**: Adjustable playback speed
- **Input/Output**: Separate controls for recognition and synthesis

### Advanced Options
- **Auto-save**: Automatic conversation persistence
- **Analytics**: Usage tracking (optional)
- **History Limit**: Maximum stored conversations

## 🔒 Security & Privacy

- **Local Processing**: Sensitive operations handled client-side
- **Secure Communication**: HTTPS for all external API calls
- **No Data Collection**: Privacy-focused design
- **Sandboxed Execution**: Safe code execution environment

## 🐛 Troubleshooting

### Common Issues

1. **Application won't load**
   - Check browser console for errors
   - Ensure you're serving over HTTP/HTTPS (not file://)
   - Clear browser cache and reload

2. **Voice features not working**
   - Grant microphone permissions
   - Check browser compatibility (Chrome recommended)
   - Ensure HTTPS connection for voice APIs

3. **File upload issues**
   - Check file type is supported
   - Ensure file size is reasonable
   - Try different file formats

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



## 👏 Acknowledgments

- **AI Integration**: Advanced LLM capabilities
- **Open Source Libraries**: Bootstrap, Font Awesome, Highlight.js
- **Community**: Thanks to all contributors and users

## 📞 Support

If you encounter any issues or have questions:


1. Create a new issue with detailed information
2. Include browser version, OS, and steps to reproduce

---

<div align="center">
  <strong>Built with ❤️ for the AI community</strong>

</div>

