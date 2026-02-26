# YouTube Script Writer AI 🚀

A free, browser-based YouTube script generator powered by **Google Gemini AI**. Generate engaging YouTube scripts in Roman Urdu with professional formatting and AI-powered content creation.

## ✨ Features

- **AI-Powered Script Generation**: Uses Google Gemini 2.5 Flash API to generate creative, engaging YouTube scripts
- **Roman Urdu Specialization**: Tailored for TechFela YouTube channel with desi humor and cultural relevance
- **Two Video Formats**:
  - Short Video Scripts (60-90 seconds)
  - Long Video Scripts (3-6 minutes)
- **100% Client-Side**: No backend server required - all processing happens in your browser
- **Export Options**:
  - Download scripts as PDF
  - Copy scripts to clipboard
- **Modern UI**: Beautiful glassmorphic dark theme with smooth animations
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Privacy-Focused**: Your API key is never stored; all data processing happens locally
- **Free to Use**: Leverages Google's free Gemini API

## 🚀 Getting Started

### Prerequisites

1. **Google Gemini API Key** (Free)
   - Visit [ai.google.dev](https://ai.google.dev)
   - Sign in with your Google account
   - Create a new API key (it's free!)
   - No credit card required

### How to Use

1. **Open the Application**
   - Open `index.html` in any modern web browser
   - Or deploy to GitHub Pages for online access

2. **Enter Your API Key**
   - Paste your Gemini API key in the "Enter your Gemini API Key" field
   - Keep it private and don't share it

3. **Enter Your Topic**
   - Provide the YouTube video topic (e.g., "5G Technology", "AI Benefits", "Cryptocurrency")
   - Be specific for better results

4. **Select Video Type**
   - Choose between Short Video (60-90 seconds) or Long Video (3-6 minutes)

5. **Generate Script**
   - Click "🚀 Generate Script"
   - Wait for AI to create your script (typically 5-10 seconds)

6. **Export Your Script**
   - Download as PDF for easy sharing
   - Copy text to clipboard for use in your editing software

## 📋 Features Breakdown

### Script Customization
- **Roman Urdu Language**: All scripts are written in Roman Urdu (Hindustani in Latin script)
- **Conversational Tone**: Casual, witty, with light sarcasm
- **Desi Humor**: Incorporates culturally relevant humor and pop culture references
- **Professional Quality**: Structured with timestamps and clear sections

### Output Includes
- Creative video title (with emoji)
- Timestamps for video segments
- Voiceover text ready for recording
- Engaging opening hooks
- Call-to-action messages
- Professional closing

## 💻 Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **AI Engine**: Google Gemini 2.5 Flash API
- **Export**: html2pdf.js, jsPDF
- **Design**: Modern CSS with Glassmorphism, CSS Grid, Flexbox
- **Animations**: CSS keyframes for smooth interactions

## 📂 Project Structure

```
youscripwriter/
├── index.html          # Main application file (HTML + CSS + JavaScript)
└── README.md           # This file
```

## 🔧 Configuration & Customization

### Modifying System Prompts

To customize the script style, edit the `SYSTEM_PROMPTS` object in the JavaScript section:

```javascript
const SYSTEM_PROMPTS = {
    short: `Your custom prompt for short videos...`,
    long: `Your custom prompt for long videos...`
};
```

### Changing the Gemini Model

To use a different Gemini model version, modify this line:

```javascript
const GEMINI_API_URL = 'https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash:generateContent';
```

Available models:
- `gemini-2.5-flash` (Current - Fastest)
- `gemini-1.5-pro` (More capable)
- `gemini-1.5-flash` (Faster, free tier)

## 🎨 Customization Options

### UI Customization
- **Colors**: Modify CSS color variables in `<style>` section for theme customization
- **Primary Colors**: Cyan (`#0ea5e9`), Purple (`#a855f7`), Pink (`#ec4899`)
- **Fonts**: Change font-family in CSS

### Language Support
The application currently specializes in Roman Urdu. To support other languages, modify the system prompts to target a different language.

## 📱 Browser Compatibility

- ✅ Chrome/Chromium (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Edge (Latest)
- ✅ Mobile browsers

## 🔐 Security & Privacy

- **No Data Storage**: Scripts are not saved on any server
- **Client-Side Processing**: All processing happens in your browser
- **API Key Safety**: Your API key is only sent directly to Google's API
- **No Tracking**: No analytics or telemetry
- **Open Source**: Code is transparent and can be audited

## ⚠️ Important Notes

1. **API Key**: Keep your Gemini API key confidential
2. **Free Tier Limits**: Google's free tier has rate limits (~60 requests/minute)
3. **Internet Required**: Requires internet connection to call Google API
4. **Browser Storage**: Clear browser cache if you face issues
5. **Customization**: All system prompts are editable for different use cases

## 🤝 Contributing

Feel free to:
- Suggest improvements
- Report issues
- Fork and create custom versions
- Modify system prompts for your channel

## 📞 Support

- **Google Gemini API Issues**: Visit [Google AI Studio](https://aistudio.google.com)
- **Feature Requests**: Modify the source code in `index.html`
- **General Help**: Check browser console for error messages (F12)

## 📜 License

This project is free to use, modify, and distribute. Created for content creators worldwide.

## 🎬 Use Cases

Perfect for:
- 🎥 YouTube channel script generation
- 📺 Short-form content creators
- 🎙️ Podcast scripts
- 📢 Marketing videos
- 🎓 Educational content
- 💼 Professional presentations
- 🌍 Multi-language content creation

## 🚀 Deployment

### GitHub Pages
1. Fork the repository or upload to GitHub
2. Go to Settings → Pages
3. Select `main` branch as source
4. Your app will be live at `https://yourusername.github.io/youscripwriter`

### Local Use
Simply open `index.html` in your browser

### Custom Domain
Deploy to any web server or static hosting service (Vercel, Netlify, AWS S3, etc.)

## 🔔 What's Next?

Potential enhancements:
- [ ] Multiple language support
- [ ] Script templates library
- [ ] Audio generation with text-to-speech
- [ ] Video editing timeline integration
- [ ] Script history/versioning
- [ ] Collaboration features
- [ ] Mobile app version

## 💡 Pro Tips

1. **Better Scripts**: More specific topics = more relevant scripts
2. **Video Type**: Short videos are great for trending topics; long videos for deep dives
3. **Editing**: Feel free to edit generated scripts before using
4. **Brand Voice**: Customize system prompts to match your channel's unique voice
5. **Reuse**: Keep your API key secure but reuse it for multiple script generations

---

**Made with ❤️ for Content Creators**

Powered by [Google Gemini AI](https://ai.google.dev) | 🎬 TechFela YouTube Scripts | 🌍 100% Open Source

Last Updated: February 2026
