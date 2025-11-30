# Insight AI - Article Summarizer

This is a Chrome extension that uses Google's Gemini API to  summarize any article into brief, detailed, or bullet point formats. 

##  Features

- **Multiple Summary Formats**: Choose from brief, detailed, or bullet point summaries
- **One-Click Summarization**: Get instant summaries with a single click
- **Smart Text Extraction**: Automatically extracts main content from any article
- **Copy to Clipboard**: Easily copy summaries for sharing or note-taking
- **Dark Theme**: Easy on the eyes with a modern dark interface
- **Secure**: Your API key is stored locally in Chrome storage

##  Installation

### Method: Manual Installation
1. Download or clone this repository
2. Open Chrome and navigate to `chrome://extensions/`
3. Enable "Developer mode" in the top-right corner
4. Click "Load unpacked" and select the extension folder
5. The extension will appear in your toolbar

##  Setup

### Getting Your Gemini API Key
1. Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Sign in with your Google account
3. Click "Create API Key"
4. Copy your new API key

### Configuring the Extension
1. Click the extension icon in your toolbar
2. Click the gear icon (⚙️) to open settings
3. Paste your Gemini API key in the input field
4. Click "Save Settings"

##  How to Use

1. **Navigate** to any article or webpage you want to summarize
2. **Click** the Insight AI extension icon in your toolbar
3. **Select** your preferred summary type:
   - **Brief**: 2-3 sentence overview
   - **Detailed**: Comprehensive summary with key points
   - **Bullet Points**: 5-7 key takeaways in list format
4. **Click** "Summarize" to generate the summary
5. **Use** the "Copy" button to save the summary to your clipboard

##  Use Cases

- **Students**: Quickly summarize research papers and articles
- **Professionals**: Stay updated with industry news during busy schedules
- **Researchers**: Extract key points from academic papers
- **Content Creators**: Get inspiration and understand trending topics
- **Casual Readers**: Save time on long-form content

##  Technical Details

- **AI Model**: Google Gemini 2.0 Flash
- **API**: Google Generative AI API
- **Storage**: Chrome Extension Storage API
- **Content Scripts**: For intelligent text extraction
- **Security**: All processing happens locally, no data stored on external servers

