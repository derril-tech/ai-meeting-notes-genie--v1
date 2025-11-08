# 🎙️ Meeting Notes Genie
**OpenAI SDK AI Agents-Powered Meeting Notes from Audio & Video**

🌐 **See the Live Application**: [https://ai-meeting-notes-genie.vercel.app/](https://ai-meeting-notes-genie.vercel.app/)

> **Transform your meeting recordings into professional notes with action items, summaries, and insights—instantly and accurately.** ⚡

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![Next.js](https://img.shields.io/badge/Next.js-15.1-black.svg)](https://nextjs.org/)
[![Railway](https://img.shields.io/badge/Deploy-Railway-blueviolet.svg)](https://railway.app/)

---

## ✨ Features

### 🎯 **Core Functionality**
- 🎙️ **Audio Transcription** - Upload MP3, WAV, M4A files (up to 50MB)
- 🎥 **Video Integration** - Extract audio from YouTube, Zoom, Loom, Vimeo, and 1000+ platforms
- 🤖 **AI-Powered Notes** - Get structured meeting summaries with OpenAI
- 🗣️ **Speaker Identification** - See who said what with color-coded transcripts
- 🌍 **Multi-Language Support** - Auto-detect or specify from 60+ languages
- 📝 **Custom Templates** - Board meetings, standups, sales calls, interviews, lectures

### 🎨 **Beautiful UI/UX**
- ✨ **Modern 2025 Design** - Glassmorphism with animated video background
- 🌙 **Dark Mode** - Default dark theme with full light mode support
- 📱 **Fully Responsive** - Mobile-first with hamburger menu navigation
- ♿ **Accessible** - Clean, intuitive interface
- 🎬 **Smooth Transitions** - Hero section to app form with state-driven UI

### 📊 **Dashboard Features**
- 📈 **Analytics Dashboard** - Usage stats, trends, and insights
- 📝 **Meeting History** - Browse past meetings with search and filters
- 👥 **Workspaces & Teams** - Email-based collaboration with access codes
- 🔍 **Search & Filter** - Find meetings by date, language, or template
- 📋 **Export Options** - Copy markdown, download as text or PDF

### 🚀 **Advanced Features**
- 🎯 **Structured Output** - Title, summary, key points, action items, decisions
- 👥 **Speaker Statistics** - Talk time percentage, word count, filter by speaker
- 🔄 **Real-Time Processing** - Background job system with live progress updates
- 🔔 **Browser Notifications** - Get notified when processing completes
- 💾 **Persistent Storage** - All jobs saved to Supabase for analytics
- 🎚️ **Template-Specific Fields** - Motions/votes for boards, blockers for standups, etc.
- 🔄 **Regenerate Notes** - Refine results with custom instructions

---

## 🏗️ Tech Stack

### **Backend** 🐍
- **FastAPI** - Modern Python web framework
- **OpenAI API** - GPT-4.1-mini for meeting summaries
- **AssemblyAI** - Advanced speech-to-text with speaker diarization
- **yt-dlp** - Video audio extraction from 1000+ platforms
- **Python 3.11+** - Latest features and performance

### **Frontend** ⚛️
- **Next.js 15.1** - React 19 with App Router
- **Tailwind CSS** - Utility-first styling
- **shadcn/ui** - Beautiful component library
- **Recharts** - Analytics charts and visualizations
- **Lucide Icons** - Modern icon set

### **Database & Cache** 💾
- **Supabase** - PostgreSQL for persistent job storage and analytics
- **Redis** - Real-time job status and transcript caching

### **External APIs** 🔌
- **OpenAI** - GPT-4.1-mini for intelligent summarization
- **AssemblyAI** - Speech-to-text with speaker labels
- **yt-dlp** - Video platform integration

### **Deployment** 🚀
- **Railway** - Backend API deployment
- **Vercel** - Frontend deployment
- **FFmpeg** - Audio processing and conversion

---

## 📖 User Guide

### 🎙️ Processing a Meeting

1. **Choose Input Method**
   - 🔗 **URL** - Paste a link from YouTube, Zoom, Loom, Vimeo, etc.
   - 💻 **File Upload** - Drop an audio file (MP3, WAV, M4A)

2. **Select Meeting Type**
   - 📋 **General Meeting** - All-purpose notes
   - 📊 **Board/Council** - Motions and votes
   - 💻 **Engineering Standup** - Updates and blockers
   - 💰 **Sales/Client Call** - Pain points and next steps
   - 🎓 **Lecture/Training** - Key concepts and Q&A
   - 📝 **Job Interview** - Candidate assessment

3. **Choose Language**
   - 🌍 **Auto-detect** - Let AI identify the language
   - Or select from 60+ supported languages

4. **Add Context (Optional)**
   - Provide meeting details for better results
   - Example: *"Weekly team sync, focus on Q1 goals"*

5. **Process & Review**
   - Watch real-time progress updates
   - Get notified when complete
   - View structured notes with speaker attribution

### 📊 Using Analytics

1. **View Key Metrics**
   - Total meetings processed
   - Success rate and error count
   - Estimated time saved
   - Average processing time

2. **Analyze Trends**
   - Meetings over time (line chart)
   - Busiest days of the week
   - Template usage distribution
   - Language distribution
   - Top action item owners

3. **Filter by Date Range**
   - Last 7 days
   - Last 30 days (default)
   - Last 90 days

### 👥 Using Workspaces

1. **Create a Workspace**
   - Enter your team email
   - Generate a unique access code
   - Share code with team members

2. **Join a Workspace**
   - Enter workspace email
   - Provide access code
   - Access shared meeting history

3. **Collaborate**
   - All team meetings in one place
   - Shared history and analytics
   - Email-based organization

### 📝 Meeting History

1. **Browse Past Meetings**
   - View all processed meetings
   - See status, date, and language
   - Quick access to full notes

2. **Search & Filter**
   - Search by title or content
   - Filter by status (done/error)
   - Sort by date (newest/oldest)

3. **Regenerate Notes**
   - Add custom instructions
   - Refine AI output
   - Keep original and new versions

---

## 🎨 Customization

### Theme Options
- 🌙 **Dark Mode** - Default theme (recommended)
- ☀️ **Light Mode** - Clean, bright interface
- 🖥️ **System** - Follows OS preference

### Meeting Templates
- **General** - Flexible, all-purpose notes
- **Board/Council** - Decisions, motions, votes
- **Engineering Standup** - What was done, what's next, blockers
- **Sales/Client Call** - Pain points, objections, decision makers
- **Lecture/Training** - Key concepts, Q&A, resources
- **Job Interview** - Assessment, strengths, recommendation

### Language Support
- **Auto-detect** - Automatically identify language
- **Manual selection** - Choose from 60+ languages
- **Supported**: English, Spanish, French, German, Chinese, Japanese, and more

---

## 🚀 Getting Started

### Prerequisites
- Python 3.11+
- Node.js 18+
- Redis instance
- Supabase project
- OpenAI API key
- AssemblyAI API key
- FFmpeg installed


---

## 🎯 Feature Highlights

### Feature #1-15 Implementation
1. ✅ **Audio Upload** - Drag & drop with progress
2. ✅ **Speaker Diarization** - AssemblyAI integration
3. ✅ **Custom AI Prompts** - OpenAI structured output
4. ✅ **Meeting History** - Supabase persistence
5. ✅ **Markdown Export** - Copy & download
6. ✅ **URL Processing** - Direct audio links
7. ✅ **PDF Export** - Generate PDF reports
8. ✅ **Regenerate Notes** - Custom instructions
9. ✅ **Language Detection** - 60+ languages
10. ✅ **Browser Notifications** - Background alerts
11. ✅ **Meeting Templates** - 6 specialized types
12. ✅ **Analytics Dashboard** - Usage insights
13. ✅ **Speaker Identification** - Color-coded transcripts
14. ✅ **Video Integration** - 1000+ platforms via yt-dlp
15. ✅ **Workspaces & Teams** - Email-based collaboration

---

## 🔒 Security & Privacy

- 🔐 **No signup required** - Use immediately
- 🗑️ **No data retention** - Transcripts cached temporarily
- 🔒 **Secure processing** - HTTPS only
- 🚫 **No tracking** - Your meetings stay private
- ⚡ **Edge caching** - Fast, secure delivery

---

## 🐛 Known Limitations

- **File size**: Max 50MB for uploads
- **Video length**: Longer videos take more time to process
- **Concurrent jobs**: Processing is queued for fairness
- **Speaker names**: Labeled as A, B, C (not real names)
- **Accuracy**: Depends on audio quality and accents


---

## 👨‍💻 Creator

**Created by Derril Filemon**

---

## 🙏 Acknowledgments

- **OpenAI** - For GPT-4 API
- **AssemblyAI** - For speech-to-text with speaker diarization
- **Supabase** - For database & persistence
- **Railway** - For backend deployment
- **Vercel** - For frontend deployment
- **yt-dlp** - For video platform integration
- **shadcn/ui** - For beautiful components

---

## 📞 Support

- 📧 **Email**: support@meetingnotesgenie.com
- 🐛 **Issues**: [GitHub Issues](https://github.com/derril-tech/ai-meeting-notes-genie/issues)
- 💬 **Discussions**: [GitHub Discussions](https://github.com/derril-tech/ai-meeting-notes-genie/discussions)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**⭐ Star this repo if you find it useful!**

Made with ❤️ and ☕ by [Derril Filemon](https://github.com/derril-tech)

</div>
