# VidyarthiPulse 🎓

VidyarthiPulse is an AI-powered educational platform designed to provide instant, high-quality explanations for students' doubts. Built with modern web technologies, it leverages Google's Gemini AI to analyze questions—including images of handwritten or printed text—and generates easy-to-understand, step-by-step explanations.

## Features ✨
- **Instant Doubt Resolution:** Upload images of questions or provide transcripts, and get instant explanations.
- **AI-Powered Analysis:** Powered by Google's state-of-the-art Gemini AI model.
- **Study Dashboard:** Automatically breaks down concepts, provides formulas, and generates quick quizzes to test understanding.
- **Multilingual Explanations:** Get explanations in simple plain text, perfect for sharing over WhatsApp or saving as notes.
- **Printable Notes:** Beautiful, print-ready study notes that can be exported as PDFs or printed directly from the dashboard.

## Tech Stack 🛠️
- **Frontend:** React 19, Vite, Tailwind CSS, Motion (Framer)
- **Backend:** Node.js, Express, TypeScript
- **AI:** Google GenAI SDK (Gemini 2.5 Flash)
- **Database:** PostgreSQL (via Drizzle ORM)
- **Authentication:** Firebase Authentication

## Getting Started 🚀

### Prerequisites
- Node.js (v18 or higher)
- PostgreSQL database
- Firebase account
- Google Gemini API Key

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Sujaykumar4/vid.git
   cd vid
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory and add the necessary credentials as outlined in `.env.example`.
   ```env
   GEMINI_API_KEY=your_gemini_api_key
   # Add other required environment variables (Firebase, Database)
   ```

4. **Run the development server:**
   ```bash
   npm run dev
   ```
   The application will be available at `http://localhost:3000`.

## Contributing 🤝
Contributions are welcome! Please feel free to submit a Pull Request.

## License 📄
This project is open-source and available under the MIT License.
