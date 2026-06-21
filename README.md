# Carbonary 🌍⚡

**Carbonary** is a gamified, cyberpunk-themed Environmental Tracker built as a Progressive Web App (PWA). Instead of boring charts, Carbonary turns sustainability into a high-stakes, sci-fi game where your physical and digital habits directly impact your environment.

## 🚀 Key Features

* **AI Carbon Twin:** Your personal digital tamagotchi. It shifts dynamically between a *thriving* green utopia and a *struggling* dystopian wasteland based entirely on your Net Carbon Score. Good habits heal the twin; bad habits destroy it.
* **Carbon Vision (AR AI Scanner):** Integrated with the **Gemini 1.5 Flash Vision API**. Access your device's camera to scan real-world objects. The AI will calculate the object's carbon production cost, apply a penalty to your score, and suggest sustainable alternatives.
* **Daily Carbon Battle:** A tug-of-war system that pits your **Carbon Saved** (from steps and eco-friendly choices) against your **Carbon Generated** (from screen time and scanned objects). 
* **System Corruption Mechanics:** If your Net Carbon Score drops below `-500g`, the app suffers a simulated catastrophic failure. The UI degrades into a violently shaking, glitching red neon state until you initiate an "Emergency Repair Protocol".
* **Live Activity Logging:** Track your physical movement (steps) and digital footprint (screen time) to see the exact CO₂ weight of your daily routine.
* **PWA Ready:** Fully installable as a standalone application on mobile and desktop devices.

## 🛠 Tech Stack

* **Core:** React 18, Vite
* **Styling:** TailwindCSS v4, Custom CSS (Geometric clip-paths, Neon Glows, Keyframe Glitches)
* **AI Integration:** `@google/generative-ai` (Gemini API)
* **Icons:** Phosphor Icons (`@phosphor-icons/react`)
* **PWA:** `vite-plugin-pwa`

## ⚙️ Installation & Setup

1. **Clone the repository.**
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Configure Environment Variables:**
   Create a `.env` file in the root directory and add your Gemini API Key:
   ```env
   VITE_GEMINI_API_KEY=your_gemini_api_key_here
   ```
4. **Run the Development Server:**
   ```bash
   npm run dev
   ```
5. **Build for Production (PWA):**
   ```bash
   npm run build
   npm run preview
   ```

## 🎨 Design Philosophy
Carbonary eschews the traditional "clean, minimalistic green" eco-app aesthetic. Instead, it leans into a **Dark Cyberpunk HUD** style. It uses monospace fonts, chamfered geometric panels, segmented LED progress bars, and harsh neon cyan/magenta glows to make tracking your carbon footprint feel like you are operating a futuristic mainframe.
