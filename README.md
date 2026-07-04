<div align="center">
  <img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

# Nisar Creative Hub ✨

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Google Gemini AI](https://img.shields.io/badge/Google_Gemini_AI-4285F4?style=for-the-badge&logo=google&logoColor=white)

## Description

**Nisar Creative Hub** is a dynamic web application designed to be a central space for managing your digital presence and unleashing creativity with AI-powered tools. This platform offers a suite of functionalities including an AI-enhanced content creation studio for social media, a customizable link management dashboard, and an integrated in-browser development studio for HTML, CSS, and JavaScript projects. 

Leveraging Google Gemini AI, users can effortlessly enhance their content and generate engaging captions, making digital content creation border-free and highly efficient. The application prioritizes user experience with a responsive design, dark mode support, and a clean, intuitive interface powered by React and Tailwind CSS.

## Table of Contents 📖

*   [Features](#features-%EF%B8%8F)
*   [Tech Stack](#tech-stack-%F0%9F%9B%A0%EF%B8%8F)
*   [Installation](#installation-%F0%9F%93%A6)
*   [Usage](#usage-%F0%9F%9A%80)
*   [How to Use](#how-to-use-%F0%9F%91%89)
*   [API Reference](#api-reference-%F0%9F%93%8B)
*   [Project Structure](#project-structure-%F0%9F%8C%B3)
*   [Contributing](#contributing-%F0%9F%A4%9D)
*   [License](#license-%F0%9F%93%9D)
*   [Important Links](#important-links-%F0%9F%8C%8D)
*   [Footer](#footer)

## Features 🌟

*   **Nisar Creative Hub Homepage**: A vibrant landing page offering quick access to your portfolio, Dev Studio, and Admin panel.
*   **AI-Powered Post Creator (Content Creation Studio)**:
    *   ✍️ **AI Content Enhancement**: Generate and enhance social media content with Google Gemini AI for creative and impactful posts.
    *   💡 **Caption Generation**: Automatically generate catchy social media captions with relevant hashtags.
    *   🎨 **Customizable Post Templates**: Choose from a variety of preset themes (modern, gradient, minimal, glass, sunset, ocean, forest, midnight) or create your own.
    *   🖼️ **Image Upload**: Personalize posts by uploading custom background images.
    *   🌈 **Style Customization**: Fine-tune text and background colors with color pickers.
    *   🔠 **Typography Options**: Select from multiple font families (sans, serif, mono, cursive) to match your brand.
    *   💾 **Template Management**: Save your unique designs as templates and load them anytime.
    *   ⬇️ **Image Export**: Download your finished posts as high-resolution PNG images.
*   **AI Dev Studio (In-Browser Code Editor)**:
    *   💻 **Code Editor**: Edit HTML, CSS, and JavaScript files directly in the browser.
    *   👁️ **Live Preview**: See real-time updates of your code changes instantly.
    *   📁 **File Management**: Create new files and switch between multiple project files with ease.
    *   ⚙️ **Auto-Save**: Ensures your work is continuously saved.
    *   ✨ **3D Layouts**: Default templates showcase immersive 3D-enhanced web experiences.
*   **Admin Link Manager (Dashboard Administration)**:
    *   🔗 **Link Management**: Add and remove custom social/contact links to centralize your online presence.
    *   🔄 **Dynamic Display**: Custom links are dynamically integrated and displayed across the application.
*   **Dynamic Contact Links**: A visually appealing grid of fixed and custom social/contact links featuring a tilt effect on hover, including GitHub, WhatsApp, Email, and Discord.
*   **Dark Mode Toggle**: Seamlessly switch between light and dark themes for enhanced readability and user comfort.
*   **Progressive Web App (PWA) Support**: Offers an "Install App" feature for a native-like experience.

## Tech Stack 🛠️

The Nisar Creative Hub is built using a modern and robust tech stack:

*   **Frontend**: 
    *   [React](https://react.dev/) - A JavaScript library for building user interfaces.
    *   [TypeScript](https://www.typescriptlang.org/) - A superset of JavaScript that adds static typing.
    *   [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework for rapid UI development.
    *   [Vite](https://vitejs.dev/) - A fast build tool that provides an instant development server.
*   **AI Integration**: 
    *   [Google GenAI](https://ai.google.dev/) - For AI-powered content generation and enhancement.
*   **Libraries**: 
    *   [html2canvas](https://html2canvas.hertzen.com/) - Used for taking screenshots of web pages (for post download functionality).
    *   [Font Awesome](https://fontawesome.com/) - For iconic fonts and SVG toolkits.

## Installation 📦

Follow these steps to get Nisar Creative Hub up and running on your local machine.

### Prerequisites

Ensure you have the following installed:

*   [Node.js](https://nodejs.org/) (which includes npm)

### Steps

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/rananisarsb51214-web/Advantage-ai-studio-
    cd Advantage-ai-studio-
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Set up your Google Gemini API Key:**
    *   Create a `.env.local` file in the root directory of the project.
    *   Add your Google Gemini API key to this file:
        ```
        GEMINI_API_KEY=YOUR_GEMINI_API_KEY
        ```
    *   You can obtain a Gemini API key from [Google AI Studio](https://aistudio.google.com/).

4.  **Run the application locally:**
    ```bash
    npm run dev
    ```
    The application will typically be accessible at `http://localhost:3000` (or another port if 3000 is occupied).

## Usage 🚀

Nisar Creative Hub serves as a versatile platform for individuals and small businesses to manage their digital presence, create engaging content, and even experiment with web development in an integrated environment. Its modular design allows users to seamlessly switch between different tools, streamlining their workflow.

### Real-World Use Cases:

*   **Social Media Managers**: Quickly generate compelling content and captions for various platforms.
*   **Content Creators**: Design visually appealing posts with custom themes and images, then export them for distribution.
*   **Freelancers/Entrepreneurs**: Consolidate all important contact and portfolio links into one easily manageable dashboard.
*   **Web Developers/Students**: Experiment with HTML, CSS, and JavaScript in a live coding environment without needing a separate IDE setup.
*   **Personal Branding**: Maintain a consistent and professional digital footprint across all online channels.

## How to Use ➡️

Once the application is running, you can navigate through its different sections using the persistent Navbar:

1.  **Home**: The central dashboard provides an overview and quick access to other modules. Click the "View My Portfolio" button to access the creator's portfolio, "Open Studio" to launch the Dev Studio, or "Manage Links" for the Admin panel.

2.  **Dev Studio**:
    *   Click on "Dev Studio" in the Navbar.
    *   You'll see a code editor and a live preview pane.
    *   Select `index.html`, `style.css`, or `script.js` from the sidebar to edit.
    *   Make changes in the editor, and the live preview will update automatically.
    *   Use the "Run" button to explicitly execute code or "Save" to save your project (simulated in this demo).
    *   Use the sidebar to create new files or load templates.

3.  **Post Editor**:
    *   Select "Post Editor" from the Navbar.
    *   Enter your content in the `Content` textarea.
    *   Click "AI Enhance" to get an AI-rewritten version of your text or "Generate Caption" for social media captions and hashtags.
    *   Choose a `Base Theme` or customize `Text Color`, `Bg Color`, and `Typography`.
    *   Upload a `Background Image` for your post.
    *   Preview your post in real-time in the `Live Preview` section.
    *   Hover over preset or saved templates to see a larger preview.
    *   Click "Download Template" to save your design as a PNG image.
    *   Use the "Templates" section to load `Presets` or `My Templates` (saved designs).

4.  **Admin**:
    *   Go to the "Admin" section via the Navbar.
    *   In the `Admin Link Manager`, enter a `Link Label` and `URL`.
    *   Click "Add Active Link" to add a new custom link.
    *   Existing links will be listed, and you can click the trash icon to `remove` them.
    *   These custom links will appear in the `Connect & Collaborate` section on the Home page.

## API Reference 📚

The application integrates with Google Gemini AI to provide intelligent content services. The API key for Gemini AI is managed via environment variables (`GEMINI_API_KEY`).

### `enhanceContent`
Rewrites social media post content to be more engaging and impactful based on a specified tone.

```typescript
async enhanceContent(text: string, tone: 'professional' | 'creative' | 'casual'): Promise<string>
```

*   `text`: The original social media post text.
*   `tone`: The desired tone for the rewritten content (`'professional'`, `'creative'`, or `'casual'`).
*   **Returns**: A `Promise` that resolves to the enhanced content string.

### `generateCaption`
Generates a short, catchy social media caption, including relevant hashtags, based on a given topic.

```typescript
async generateCaption(topic: string): Promise<string>
```

*   `topic`: The subject or theme for which to generate a caption.
*   **Returns**: A `Promise` that resolves to the generated caption string.

## Project Structure 🌳

The project follows a component-based architecture for better organization and maintainability:

```
Advantage-ai-studio-/
├── public/
│   └── manifest.json
├── src/
│   ├── components/
│   │   ├── ContactLinks.tsx
│   │   ├── DevStudio.tsx
│   │   ├── LinkManager.tsx
│   │   ├── Navbar.tsx
│   │   └── PostCreator.tsx
│   ├── services/
│   │   └── gemini.ts
│   ├── App.tsx
│   ├── index.css
│   ├── index.tsx
│   └── types.ts
├── .env.local (You need to create this for API Key)
├── index.html
├── package.json
├── README.md
├── tsconfig.json
└── vite.config.ts
```

*   `public/`: Contains static assets and the PWA manifest.
*   `src/`: Core source code for the React application.
    *   `components/`: Reusable React components that make up the UI.
    *   `services/`: Modules for API integrations, specifically Google Gemini.
    *   `App.tsx`: The main application component that orchestrates views and global state.
    *   `index.css`: Global styles, including TailwindCSS directives and custom scrollbar styles.
    *   `index.tsx`: Entry point for the React application.
    *   `types.ts`: TypeScript type definitions for interfaces like `SocialLink`, `PostTemplate`, and `ViewState`.
*   `.env.local`: Environment variables, crucial for securely storing API keys.
*   `index.html`: The main HTML file, serving as the entry point for the web application, incorporating TailwindCSS configuration.
*   `package.json`: Defines project metadata, scripts, and dependencies.
*   `tsconfig.json`: TypeScript compiler configuration.
*   `vite.config.ts`: Vite build tool configuration.

## Contributing 🤝

Contributions are welcome! If you have suggestions for improvements, new features, or bug fixes, please open an issue or submit a pull request.

## License 📜

This project does not have a specific license mentioned. Please contact the repository owner for licensing information.

## Important Links 🌐

*   **Live Demo (AI Studio App)**: [Nisar Creative Hub on AI Studio](https://ai.studio/apps/drive/1FGvvqm-D-0CxMp93lhPyO4My5zm9KJ85)
*   **My Portfolio**: [View Rana Nisar's Portfolio](https://sites.google.com/d/1bePsY8n0K3tx5CUBxDlWpAPpkAehqtPN/p/1WlyY3H4ZtDUUcQUG05SSEcgMWHar8J9t/edit)
*   **GitHub Profile**: [rana51214](https://github.com/rana51214/)
*   **Contact via WhatsApp**: [Message me on WhatsApp](https://wa.me/message/3A7MFOQTRE2ZL1)
*   **Contact via Email**: [Send an Email](mailto:rananisar943@gmail.com)
*   **Join Discord**: [Discord Community](https://discord.gg/gtyKuj7Rg)

## Footer

Developed with ❤️ by [Rana Nisar](https://github.com/rana51214/)

Repository: [Advantage-ai-studio-](https://github.com/rananisarsb51214-web/Advantage-ai-studio-)

Feel free to fork this repository, give it a star ⭐, and open issues 🐞 for any suggestions or bugs. Your support is appreciated!

---
**<p align="center">Generated by [ReadmeCodeGen](https://www.readmecodegen.com/)</p>**