# 🎤 Sing-to-Song

**AI-powered semantic music generation using Google Gemini 3 API**

*Submission for Google Cloud Gemini Hackathon 2025*

[![Live Demo](https://img.shields.io/badge/Demo-Live-success)](https://YOURUSERNAME.github.io/sing-to-song/)
[![Gemini API](https://img.shields.io/badge/Powered%20by-Gemini%203-blue)](https://ai.google.dev/)

---

## 🌟 Live Demo

**👉 [Try Sing-to-Song Now!](https://YOURUSERNAME.github.io/sing-to-song/)** 

*Replace YOURUSERNAME with your actual GitHub username*

---

## 🎯 What It Does

Sing-to-Song is a musical intelligence layer that transforms any singer into a complete performer. 

Powered by Google Gemini 3's multimodal intelligence, the app listens to your voice in real-time—analyzing your key, pace, melody, and emotional tone—then builds a backing track that adapts to your unique performance. It re-engineers the musical foundation in real-time to fit your vocal range and style. If you shift keys mid-performance, the instruments follow. If you slow down for emotion, the track breathes with you. **The AI becomes your accompanist, not your metronome.**

### The Problem We Solve

Traditional AI music tools force singers to follow rigid tempos and preset keys. This creates a "karaoke effect" where the human adapts to the machine, stifling creativity and natural expression.

### Our Solution

**Sing-to-Song inverts this relationship.** The AI follows YOU. It analyzes your natural performance and generates contextually intelligent accompaniment that supports rather than dictates your artistic choices.

---

## 🚀 Quick Start (For Judges & Testers)

### Step 1: Get Your Free Gemini API Key (30 seconds)

1. Visit **https://aistudio.google.com/apikey**
2. Sign in with your Google account
3. Click **"Create API Key"**
4. Copy the key (starts with "AIza...")

### Step 2: Open the Live Demo

**[Click here to launch Sing-to-Song](https://YOURUSERNAME.github.io/sing-to-song/)**

### Step 3: Use the App

1. **Paste your API key** in the input field at the top
2. **Click "Quick Create" mode** (the green LIVE card)
3. **Upload your vocals:**
   - Use acapella vocals (singing without background music)
   - Formats: MP3, WAV, M4A, WEBM
   - **Suggested test:** Record yourself singing "Happy Birthday" for 15 seconds
4. **Click "Generate with Gemini 3"**
5. **Watch the magic:**
   - Gemini analyzes your voice
   - Returns semantic parameters (vibe, density, key, BPM, mood)
   - Generates adaptive backing track
   - Plays the result
6. **Export your performance** using the export button

---

## ✨ Features

### 🟢 Live Features (This Demo)

- ✅ **Quick Create Mode** - Upload vocals, AI generates complete adaptive backing track
- ✅ **Gemini 3 Multimodal Analysis** - Analyzes audio (not just text!) for:
  - Vibe (smooth/bright/energetic)
  - Density (0.1-0.9 complexity score)
  - Key signature
  - BPM (tempo)
  - Emotional mood
  - Energy level
- ✅ **3+3+2 Caribbean Rhythm Pattern** - Authentic musical structure that creates distinctive feel
- ✅ **Semantic Music Generation** - Track adapts to your voice's emotional characteristics
- ✅ **Steel Pan + Piano Ensemble** - 52 chromatic piano samples + authentic steel pan
- ✅ **Real-time Audio Synthesis** - Professional-quality Tone.js engine
- ✅ **WAV Export** - Download your complete performance

### 🟡 Demo Only (Coming in Full Release)

- 🔜 **Quick Modify Mode** - Upload existing instrumental, AI transposes to match your voice
- 🔜 **Line by Line Mode** - Type and sing lyrics with granular precision control
- 🔜 **Studio Workspace** - Vocal polishing, denoising, breathing pause removal

---

## 🏗️ How It Works

### Architecture

```
User Uploads Vocals
       ↓
Gemini 3 Multimodal API
  (Audio Analysis)
       ↓
Semantic Parameters
  {vibe, density, key, BPM, mood}
       ↓
3+3+2 Rhythm Generator
       ↓
Tone.js Audio Synthesis
  (Piano + Steel Pan)
       ↓
Web Audio API Mixing
       ↓
Exportable Performance
```

### The Semantic Mapping

**Gemini's analysis directly controls musical generation:**

1. **Vibe** → Instrument Pitch
   - "smooth" = lower piano register (G1)
   - "bright" = higher piano register (C3)
   - "energetic" = more steel pan emphasis

2. **Density** → Backing Complexity
   - 0.1 = sparse, minimal accompaniment
   - 0.9 = rich, layered backing track
   - Controls steel pan hit probability

3. **BPM** → Tempo Adaptation
   - AI matches your natural pace
   - No forcing to preset tempo

4. **Key** → Harmonic Context
   - Instruments play in your key
   - Supports natural vocal range

### The 3+3+2 Caribbean Rhythm

Our signature pattern `[0, 0.375, 0.75, 1, 1.375, 1.75]` creates authentic Caribbean feel by grouping beats as 3+3+2 rather than standard 4/4. This cultural authenticity differentiates Sing-to-Song from generic AI music generators.

---

## 🛠️ Technology Stack

- **Google Gemini 3 API** (`gemini-2.0-flash-exp`) - Multimodal audio analysis
- **Tone.js** (v14.8.49) - Web Audio synthesis framework
- **Web Audio API** - Audio processing, mixing, and export
- **Vanilla JavaScript** - No framework dependencies for maximum portability
- **Public Domain Audio Samples** - Ethically sourced, culturally authentic

---

## 🎨 Why This Matters

### Cultural Authenticity

Most AI music tools ignore Caribbean instruments like Steel Pan. We prioritize cultural representation by making Steel Pan a first-class instrument alongside Piano and Guitar.

### Human-Centered AI

We designed Sing-to-Song around the principle: **AI should amplify human creativity, not replace or restrict it.** The singer remains the creative force; AI adapts to support their vision.

### Accessibility

No expensive equipment needed. No music theory knowledge required. Just sing, and the AI handles the rest - while still respecting your artistic choices.

---

## 📜 Third-Party Integrations & Credits

### Audio Libraries
- **Tone.js** - MIT License - https://tonejs.github.io/
- Used for audio synthesis, scheduling, and effects processing

### Fonts
- **Google Fonts** - Open Font License
  - Outfit (display font)
  - Space Mono (monospace font)

### Audio Samples
- **Piano Samples**
  - Source: University of Iowa Musical Instrument Samples
  - URL: http://theremin.music.uiowa.edu/MIS.html
  - License: Public Domain (unrestricted use)
  - 52 chromatic samples across full keyboard range

- **Steel Pan Samples**
  - Source: Freesound.org
  - License: CC0 (Public Domain)
  - Chromatic range with authentic Caribbean tone

All third-party tools and content used in accordance with their respective licensing requirements.

---

## 🎬 Demo Video

[YouTube Demo Video - Link Coming Soon]

**Video demonstrates:**
- Live workflow from upload to export
- Gemini 3 analysis in action
- Semantic parameter visualization
- Backing track generation
- Audio quality showcase

---

## 🏆 Competition Information

**Google Cloud Gemini Hackathon 2025**
- **Category:** Smart Use of Data & AI
- **Focus Areas:** 
  - Multimodal AI capabilities
  - Cultural authenticity and representation
  - Adaptive intelligence systems
- **Key Innovation:** Using Gemini's multimodal understanding to create music that follows human performance rather than forcing conformity

---

## 🔐 Privacy & Security

- **Your API key stays in your browser** - Never sent to our servers
- **No user data stored** - All processing happens client-side
- **No tracking or analytics** - Your creative work remains private
- **Open source** - Inspect the code, verify our claims
- **Each user uses their own Gemini API quota** - No cost sharing, full control

### Why User-Provided API Keys?

This design choice ensures:
1. **Transparency** - You control your own API usage
2. **Cost control** - You're not paying for others' usage
3. **Privacy** - No intermediary servers handle your audio
4. **Sustainability** - The demo remains free and accessible

---

## 📝 Installation (For Local Development)

Want to run this locally or modify the code?

```bash
# Clone the repository
git clone https://github.com/YOURUSERNAME/sing-to-song.git

# Navigate to directory
cd sing-to-song

# Open with Live Server (VS Code extension)
# Or simply open index.html in your browser

# Make sure samples folder is present:
# samples/piano/
# samples/pan/
```

**Requirements:**
- Modern web browser (Chrome, Firefox, Edge, Safari)
- Internet connection (for Gemini API calls)
- Gemini API key (free from aistudio.google.com)

---

## 🐛 Troubleshooting

### "Samples not loading"
- Verify folder structure: `samples/piano/` and `samples/pan/`
- Check browser console (F12) for 404 errors
- Ensure file names match exactly (case-sensitive)

### "API key not working"
- Verify key starts with "AIza..."
- Check you have API quota remaining
- Ensure internet connection is stable
- Try regenerating key at aistudio.google.com

### "No audio output"
- Click "Test Engine" button first
- Check browser audio permissions
- Verify speakers/headphones connected
- Try refreshing the page

### "Upload fails"
- File size limit: ~10MB
- Supported formats: MP3, WAV, M4A, WEBM
- Try converting to WAV if issues persist

---

## 🚀 Future Roadmap

### Phase 2 Features (Post-Competition)
- [ ] Quick Modify mode implementation
- [ ] Line by Line mode implementation
- [ ] Studio Workspace with vocal polishing
- [ ] More instrument options (bass, drums, strings, synth)
- [ ] MIDI export capability
- [ ] Collaborative features
- [ ] Mobile app (iOS/Android)

### Phase 3 Vision
- [ ] Live microphone recording (no file upload needed)
- [ ] Real-time performance mode
- [ ] Multi-track layering
- [ ] Genre-specific templates
- [ ] Educational mode (learn music theory through creation)

---

## 🤝 Contributing

This is a competition entry, but we welcome feedback and suggestions!

**Found a bug?** Open an issue  
**Have an idea?** Start a discussion  
**Want to contribute?** Contact us after the competition concludes

---

## 📄 License

MIT License

Copyright (c) 2025 [Your Name]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---

## 👤 Author

**[Your Name]**
- GitHub: [@YOURUSERNAME](https://github.com/YOURUSERNAME)
- Competition: Google Cloud Gemini Hackathon 2025

---

## 🙏 Acknowledgments

- Google Gemini team for the incredible API
- Tone.js community for the audio framework
- University of Iowa for public domain instrument samples
- Freesound.org community for Steel Pan samples
- Everyone who tested and provided feedback

---

**Built with ❤️ for the Google Cloud Gemini Hackathon 2025**

*"Where your voice leads, AI follows."*
