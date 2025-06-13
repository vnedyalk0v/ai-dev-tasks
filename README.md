# 🚀 AI Project Development Framework for Cursor 🤖

Welcome to the **AI Project Development Framework**! This repository provides a collection of `.mdc` (Markdown Command) files designed to supercharge your **entire project development** workflow within the [Cursor](https://cursor.sh/) editor. By leveraging these commands with Cursor's AI Agent, you can systematically approach building complete applications from conception to deployment, with built-in checkpoints for verification and quality control.

Stop wrestling with monolithic AI requests and start guiding your AI collaborator through structured project development!

## ✨ The Core Idea

Building complete applications with AI can feel overwhelming and unstructured. This framework brings systematic project management, clarity, and control to AI-assisted development by:

1.  **Comprehensive Project Planning:** Creating a detailed Project Specification Document (PSD) that covers all aspects of your application
2.  **Structured Implementation:** Breaking down the entire project into manageable phases and tasks
3.  **Systematic Execution:** Guiding the AI through each phase with proper dependencies, quality gates, and approval checkpoints
4.  **Quality Assurance:** Built-in testing, documentation, and deployment considerations

This structured approach ensures the AI maintains focus across complex, multi-phase projects while giving you confidence in the generated code and architecture.

## Workflow: From Idea to Deployed Application 💡➡️🚀

Here's the step-by-step process for building complete projects using the `.mdc` files:

### 1️⃣ Create a Project Specification Document (PSD)

First, establish the complete blueprint for your application. A PSD defines what you're building, the technical architecture, feature requirements, and deployment strategy.

1.  Ensure you have the `create-project-spec.mdc` file accessible.
2.  In Cursor's Agent chat, initiate PSD creation:

    ```
    Use @create-project-spec.mdc
    Here's the project I want to build: [Describe your complete application/project]
    Reference these files if relevant: [Optional: @existing-file1.py @existing-file2.ts]
    ```

    _(Pro Tip: For comprehensive PSDs, using MAX mode in Cursor is highly recommended for thorough project analysis.)_

### 2️⃣ Generate Your Complete Project Task List

With your PSD drafted (e.g., `project-spec-ecommerce-platform.md`), generate a comprehensive, phase-based implementation plan that covers the entire project lifecycle.

1.  Ensure you have `generate-project-tasks.mdc` accessible.
2.  In Cursor's Agent chat, create the project task list:

    ```
    Now take @project-spec-ecommerce-platform.md and create the complete project tasks using @generate-project-tasks.mdc
    ```

    _(Note: Replace with your actual PSD filename)_

### 3️⃣ Review Your Project Roadmap

You'll now have a comprehensive project roadmap with:

- **6 structured phases** (Setup → Architecture → MVP → Advanced Features → Testing → Deployment)
- **Detailed task breakdown** for each phase
- **Complete project structure** with all files and directories
- **Dependencies and execution order** clearly defined

This provides a complete development roadmap from initial setup to production deployment.

### 4️⃣ Execute Project Phases Systematically

Use `process-project-tasks.mdc` to guide systematic execution through your project phases. This ensures proper dependency management and quality gates.

1.  Create or ensure you have the `process-project-tasks.mdc` file accessible.
2.  In Cursor's Agent chat, start with Phase 1:

    ```
    Please start with Phase 1 (Project Setup) and use @process-project-tasks.mdc
    ```

    _(Important: You only need to reference `@process-project-tasks.mdc` for the first phase. The instructions guide the AI through all subsequent phases.)_

### 5️⃣ Phase-by-Phase Review and Approval ✅

As the AI completes each major task within a phase:

- **Review the implementation** against the project requirements
- **Approve progress** with "yes" to continue to the next major task
- **Provide feedback** if adjustments are needed before moving forward
- **Track completion** as phases are systematically completed

You'll see steady progress through:

- ✅ **Phase 1**: Repository setup, CI/CD, infrastructure provisioning
- ✅ **Phase 2**: Database architecture, authentication, core API framework
- ✅ **Phase 3**: MVP feature development and UI foundation
- ✅ **Phase 4**: Advanced features and third-party integrations
- ✅ **Phase 5**: Comprehensive testing and quality assurance
- ✅ **Phase 6**: Production deployment and launch preparation

### Video Demonstration 🎥

The original feature-focused approach was demonstrated on [Claire Vo's "How I AI" podcast](https://www.youtube.com/watch?v=fD4ktSkNCw4). The same principles now apply to complete project development.

![Demonstration of AI Dev Tasks on How I AI Podcast](https://img.youtube.com/vi/fD4ktSkNCw4/maxresdefault.jpg)

## 🗂️ Files in this Repository

- **`create-project-spec.mdc`**: Guides the AI in generating a comprehensive Project Specification Document covering all aspects of your application
- **`generate-project-tasks.mdc`**: Takes a PSD and creates a complete, phase-based project implementation roadmap with detailed tasks and dependencies
- **`process-project-tasks.mdc`**: Provides systematic project execution guidelines with phase management, quality gates, and approval workflows

## 🌟 Benefits of the Project-Level Approach

- **Complete Project Coverage:** Handles everything from initial setup to production deployment
- **Systematic Quality Control:** Built-in testing, documentation, and code review processes
- **Dependency Management:** Proper sequencing of tasks and phases to avoid blocking issues
- **Scalable Architecture:** Ensures projects are built with proper architectural foundations
- **Production-Ready:** Includes CI/CD, monitoring, security, and deployment considerations
- **Team Collaboration:** Structured approach suitable for both solo developers and teams
- **Risk Mitigation:** Phase-based approach with checkpoints reduces project risk
- **Technology Agnostic:** Works with any technology stack or project type

## 🛠️ How to Use

1.  **Clone or Download:** Get these `.mdc` files into your project workspace where Cursor can access them
2.  **Follow the Project Workflow:** Use the 5-step workflow above for systematic project development
3.  **Customize as Needed:**
    - Modify the prompts within the `.mdc` files to match your specific requirements
    - Adjust the project phases based on your project type and complexity
    - Add additional quality gates or approval points as needed

## 💡 Tips for Success

- **Be Comprehensive:** Provide detailed project requirements in your initial description - the more context, the better the AI's output
- **Technology Stack Clarity:** Clearly specify your preferred technologies, frameworks, and architectural patterns
- **Phase-by-Phase Focus:** Don't rush through phases - each phase builds the foundation for the next
- **Quality Gates:** Use the built-in approval checkpoints to ensure quality before moving to complex phases
- **Documentation:** Maintain the project documentation as you progress through phases
- **Environment Setup:** Ensure your development environment is properly configured before starting implementation phases

## 📊 Project Types Supported

This framework works for various project types:

- **Web Applications** (frontend + backend)
- **API Services** (REST, GraphQL, microservices)
- **Mobile Applications** (React Native, Flutter, native)
- **Desktop Applications** (Electron, native)
- **CLI Tools** and utilities
- **Data Processing** pipelines
- **Machine Learning** projects
- **DevOps** and infrastructure projects

## 🤝 Contributing

Got ideas to improve these `.mdc` files or have new ones that enhance the project development workflow? Contributions are welcome!

Please feel free to:

- Open an issue to discuss improvements or suggest new project management features
- Submit a pull request with your enhancements
- Share your experience using this framework with different project types

---

Happy AI-assisted project development!
