# 🎥 Smart Video Summarizer

An AI-powered web application that generates concise summaries from **YouTube videos** and **local audio/video files**. Save time by understanding long content in seconds!

## ✨ Features

- 🔗 **YouTube Integration**: Paste a YouTube link to fetch and summarize the transcript.
- 🎧 **Local Upload**: Upload `.mp3`, `.wav`, `.mp4`, or `.webm` files (up to 25MB) for transcription and summarization.
- ⚡ **AI-Powered**: Uses advanced language models to generate meaningful summaries.
- 🧠 **Smart UX**: Clean, responsive design with drag-and-drop support and real-time feedback.

## 🚀 Tech Stack

- **Frontend**: React.js, Tailwind CSS, Lucide Icons  
- **Transcription & Summarization APIs**: Custom backend APIs (assumed in `./api`)
- **File Handling**: `react-dropzone` for drag-and-drop upload
- **Type Safety**: TypeScript types for summaries and file states

## 📦 Setup

### Prerequisites

- Node.js (v14+)
- npm or yarn

### Installation

```bash
git clone https://github.com/yourusername/smart-video-summarizer.git
cd smart-video-summarizer
npm install
