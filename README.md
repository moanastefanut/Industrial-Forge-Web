# Industrial Forge Web

A Flagship Web Application Built With A Modern, High-Performance Stack (MERN-Like, But Vite-Based). Industrial Forge Web Is The Main Project Meant To Demonstrate Competencies In Clean Architecture, Minimalist UI/UX, And Fluid Animations.

## The Industrial Forge (Technical Stack)

This Project Is Built On A Robust JavaScript Ecosystem, Optimized For Speed And Maintainability. It Is Essential That Your Development Environment (E.g., Fedora, MacOS) Has **Node.js LTS** And **NPM** Installed.

| Category | Technology | Why? |
| :--- | :--- | :--- |
| **Runtime** | Node.js LTS | Stable And Async Platform For Backend Tooling. |
| **Build Tool** | Vite | Ultra-Fast Speed For Development And Efficient Bundling, Without Waiting For Rebuilds. |
| **UI Framework** | React | The Core Library For Building The Component-Based Interface. |
| **Routing** | React Router DOM | Fluid Navigation Within The SPA (Single Page Application). |
| **Styling** | Tailwind CSS | A Utility-First Workflow For Minimalist And Comfy/Simple Design, Applied Directly In Components. |
| **Animations** | Framer Motion | Implementation Of Complex Transitions And Page/Component Animations (UI/UX). |

## UI/UX & Design Philosophy

The Design Is Focused On A Clean, Non-Distracting User Experience, Aligned With A Cinematic/Dark Style.

* **Dynamic Theming:** It Uses Custom CSS Variables (E.g., `--bg: #1e1e1e;`, `--fg: #ffffff;`) Defined On The `:root` Selector In `index.css`. This Allows For Rapid And Consistent Theme Switching (Dark Mode First) Via A Simple `data-theme` Attribute Toggle.
* **Premium Typography:** It Uses A Modern Font Stack (SF Pro Display / Helvetica Neue) For Optimal Clarity And Readability.
* **System Transitions:** Framer Motion Is Used Alongside React Router DOM To Ensure Fluid Page Transitions, Enhancing The Perceived Speed And Quality Of The Application Experience.

## Getting Started (Setup)

Ensure You Have **Node.js LTS** And **NPM** Installed On Your System (Fedora Or MacOS).

1.  **Clone The Repository:**
    ```bash
    git clone [https://github.com/mitro1337/Industrial-Forge-Web.git](https://github.com/mitro1337/Industrial-Forge-Web.git)
    cd industrial-forge-web
    ```

2.  **Install Dependencies:**
    ```bash
    npm install
    ```

3.  **Run The Application In Development Mode:**
    ```bash
    npm run dev
    ```
    The Application Will Start Automatically, Usually On `http://localhost:5173/`.
