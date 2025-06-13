# 🚀 AI Development Framework for Cursor 🤖

Welcome to the **AI Development Framework**! This repository provides a collection of `.mdc` (Markdown Command) files designed to supercharge your **application development** workflow within the [Cursor](https://cursor.sh/) editor. By leveraging these commands with Cursor's AI Agent, you can systematically approach building high-quality applications with consistent architecture, robust security, and optimal performance.

Stop building inconsistent applications with AI and start developing with structured, quality-focused development practices!

## ✨ The Core Idea

Building applications with AI often leads to inconsistent code, security vulnerabilities, and performance issues across projects. This framework brings systematic development practices, code quality standards, and security/performance focus to AI-assisted development by:

1.  **Comprehensive Development Planning:** Creating detailed Project Specification Documents (PSD) that ensure consistent architecture and quality standards
2.  **Structured Implementation:** Breaking down development into logical phases with built-in quality checkpoints
3.  **Systematic Execution:** Guiding the AI through each development phase with proper code quality, security, and performance considerations
4.  **Quality Assurance:** Built-in testing, code review, and optimization practices throughout development

This structured approach ensures consistent, secure, and performant applications across all your projects - whether building HRM systems, portfolio websites, product websites, or any other applications.

## Workflow: From Idea to Quality Application 💡➡️💻

Here's the step-by-step process for building consistent, high-quality applications:

### 1️⃣ Create a Project Specification Document (PSD)

First, establish the complete development blueprint for your application. A PSD defines architecture, quality standards, security requirements, and performance targets.

1.  Ensure you have the `create-project-spec.mdc` file accessible.
2.  In Cursor's Agent chat, initiate PSD creation:

    ```
    Use @create-project-spec.mdc
    Here's the application I want to build: [Describe your application/project]
    Reference these files if relevant: [Optional: @existing-file1.py @existing-file2.ts]
    ```

    _(Pro Tip: For comprehensive PSDs, using MAX mode in Cursor is highly recommended for thorough project analysis.)_

### 2️⃣ Generate Your Complete Development Task List

With your PSD drafted (e.g., `project-spec-hrm-system.md`), generate a comprehensive, phase-based development plan that ensures quality throughout the development process.

1.  Ensure you have `generate-project-tasks.mdc` accessible.
2.  In Cursor's Agent chat, create the development task list:

    ```
    Now take @project-spec-hrm-system.md and create the complete development tasks using @generate-project-tasks.mdc
    ```

    _(Note: Replace with your actual PSD filename)_

### 3️⃣ Review Your Development Roadmap

You'll now have a comprehensive development roadmap with:

- **6 structured development phases** (Setup → Architecture → MVP → Advanced Features → Testing → Optimization)
- **Quality-focused task breakdown** for each phase
- **Complete project structure** with proper file organization
- **Security and performance considerations** built into each phase

This provides a complete development roadmap focused on building quality, maintainable code.

### 4️⃣ Execute Development Phases Systematically

Use `process-project-tasks.mdc` to guide systematic execution through your development phases with built-in quality gates and code review processes.

1.  Create or ensure you have the `process-project-tasks.mdc` file accessible.
2.  In Cursor's Agent chat, start with Phase 1:

    ```
    Please start with Phase 1 (Project Setup & Development Environment) and use @process-project-tasks.mdc
    ```

    _(Important: You only need to reference `@process-project-tasks.mdc` for the first phase. The instructions guide the AI through all subsequent phases.)_

### 5️⃣ Phase-by-Phase Review and Approval ✅

As the AI completes each major development task within a phase:

- **Review the implementation** against the project requirements and quality standards
- **Approve progress** with "yes" to continue to the next major task
- **Provide feedback** if code quality, security, or performance improvements are needed
- **Track completion** as phases are systematically completed with quality assurance

You'll see steady progress through:

- ✅ **Phase 1**: Development environment setup, code quality tools, coding standards
- ✅ **Phase 2**: Database design, authentication, core application architecture
- ✅ **Phase 3**: MVP feature development with proper testing and documentation
- ✅ **Phase 4**: Advanced features, integrations, and enhanced user experience
- ✅ **Phase 5**: Comprehensive testing, code review, and quality assurance
- ✅ **Phase 6**: Performance optimization and security hardening

## 🗂️ Files in this Repository

- **`create-project-spec.mdc`**: Guides the AI in generating a comprehensive Project Specification Document with quality standards, security requirements, and performance targets
- **`generate-project-tasks.mdc`**: Takes a PSD and creates a complete, phase-based development roadmap with quality checkpoints and best practices
- **`process-project-tasks.mdc`**: Provides systematic development execution guidelines with code quality management, security practices, and performance optimization
- **`project-structure-guide.mdc`**: AI instruction for preventing directory and file management mistakes
- **`development-standards-checklist.mdc`**: AI instruction for preventing common development mistakes and maintaining code quality

## 🌟 Benefits of the Development-Focused Approach

- **Consistent Quality:** Ensures consistent code quality, architecture patterns, and development practices across all projects
- **Security by Design:** Built-in security best practices and vulnerability prevention throughout development
- **Performance Optimization:** Performance considerations integrated into every development phase
- **Maintainable Code:** Emphasis on clean, modular, well-documented code that's easy to maintain
- **Testing-Driven:** Comprehensive testing strategies built into the development process
- **Best Practices:** Enforces industry best practices for coding standards, file organization, and architecture
- **Scalable Architecture:** Ensures applications are built with proper architectural foundations for future growth
- **Developer Productivity:** Structured approach that eliminates inconsistency and reduces technical debt

## 🛠️ How to Use

1. **Create Project Specification:** Use `create-project-spec.mdc` with either:

   - **Structured approach:** Fill out `project-information-template.md` and reference it
   - **Direct approach:** Describe your project directly in natural language

2. **Generate Task Roadmap:** Use `generate-project-tasks.mdc` to create a detailed 6-phase development plan with complexity-adjusted tasks and cross-platform considerations

3. **Execute Development:** Use `process-project-tasks.mdc` to systematically implement each task with quality validation, security scanning, and performance optimization

### Two Ways to Start Your Project

**Option 1 - Structured Template (Recommended for complex projects):**

```
Use @create-project-spec.mdc
Here's the application/project information.md
```

**Option 2 - Direct Description (Great for quick starts):**

```
Use @create-project-spec.mdc
Here's the application I want to build: [Describe your application/project]
```

## 💡 Tips for Success

- **Choose Your Approach:** Use the structured template for complex projects, direct description for simpler ones
- **Start with Thorough Planning:** Complete the Project Specification Document before generating tasks
- **Assess Complexity Early:** Use the complexity assessment to right-size your approach
- **Prioritize Ruthlessly:** Focus on MVP features first, resist scope creep
- **Design for All Devices:** Implement responsive design and accessibility from the beginning
- **Security First:** Apply the zero-vulnerability mandate throughout development
- **Validate Early and Often:** Run quality validation after every major task
- **Document Technology Decisions:** Keep track of why specific technologies were chosen
- **Test Cross-Platform:** Verify functionality across all target devices and browsers
- **Maintain Project Structure:** Use project-structure.md to prevent directory confusion and file duplication
- **Validate Working Directory:** Always confirm you're working in the correct project location before creating files
- **Enforce Development Standards:** Use the development standards checklist to prevent common AI mistakes
- **Establish Conventions Early:** Set naming conventions, error handling patterns, and coding standards in Phase 1

## 📊 Project Types Supported

This framework works for various application types:

- **Web Applications** (React, Vue, Angular, etc.)
- **Backend APIs** (REST, GraphQL, microservices)
- **Full-Stack Applications** (Next.js, Nuxt.js, etc.)
- **Single Page Applications** (SPAs)
- **Progressive Web Apps** (PWAs)
- **Desktop Applications** (Electron, Tauri)
- **Mobile Web Apps** (responsive designs)
- **Content Management Systems**
- **E-commerce Platforms**
- **Business Applications** (HRM, CRM, etc.)

## 🤝 Contributing

Got ideas to improve these `.mdc` files or have new ones that enhance the development workflow? Contributions are welcome!

Please feel free to:

- Open an issue to discuss improvements or suggest new development management features
- Submit a pull request with your enhancements
- Share your experience using this framework with different project types

---

Happy AI-assisted development!

This framework provides structured guidance for AI assistants to build entire applications from concept to completion. It addresses the consistency, security, and performance issues that arise when building projects without systematic guidance.

## 📁 Framework Files

- `project-information-template.md` - Structured template for project requirements
- `project-information-example.md` - Complete example of template usage
- `create-project-spec.mdc` - AI instruction for creating Project Specification Documents
- `generate-project-tasks.mdc` - AI instruction for generating development roadmaps
- `process-project-tasks.mdc` - AI instruction for systematic task execution
- `project-structure-guide.mdc` - AI instruction for preventing directory and file management mistakes
- `development-standards-checklist.mdc` - AI instruction for preventing common development mistakes and maintaining code quality
- `README.md` - This documentation file

## Framework Components

### 1. Project Information Template (`project-information-template.md`)

Optional structured template for comprehensive project planning:

- **Organized Information Gathering:** Systematic collection of all project requirements
- **Consistent Project Definition:** Ensures no critical information is missed
- **AI-Friendly Format:** Structured for optimal AI parsing and understanding
- **Flexible Usage:** Can be partially filled or used as a checklist
- **Example Provided:** See `project-information-example.md` for a complete example

### 2. Project Specification Document (`create-project-spec.mdc`)

Create comprehensive project specifications with:

- **Technology Stack Decision Framework:** Guided questions to select optimal technologies
- **Project Complexity Assessment:** Systematic evaluation to match tasks to project scope
- **MVP Definition & Feature Prioritization:** MoSCoW method for focused development
- **Cross-Platform Considerations:** Device support, browser compatibility, accessibility standards
- **Dual Input Support:** Works with both structured templates and direct descriptions
- Technical architecture and integration requirements
- Quality standards and SEO optimization requirements

### 3. Project Task Generation (`generate-project-tasks.mdc`)

Generate detailed 6-phase development roadmaps with:

- **Complexity-Based Task Adjustment:** Granularity matching Simple/Medium/Complex projects
- **Cross-Platform Foundation Setup:** Responsive design and accessibility from day one
- **Feature Dependency Management:** Proper sequencing based on PSD prioritization
- **Conditional Task Logic:** Database and authentication tasks only when needed
- Quality validation after every major task
- Emphasis on clean code principles and DRY methodology

### 4. Project Task Processing (`process-project-tasks.mdc`)

Execute tasks systematically with:

- **Technology-Aware Implementation:** Following PSD architecture and tool decisions
- **Complexity-Adjusted Approaches:** Implementation patterns matching project complexity
- **MVP-Focused Development:** Prioritizing MUST HAVE → SHOULD HAVE → COULD HAVE features
- **Cross-Platform Validation:** Testing responsiveness, browser compatibility, accessibility
- Zero-vulnerability development with comprehensive security validation
- Performance optimization and SEO compliance throughout development

### 5. Project Structure Management (`project-structure-guide.mdc`)

Prevent common AI development mistakes with:

- **Directory Confusion Prevention:** Ensures files are created in correct locations
- **File Purpose Tracking:** Maintains documentation of every file's responsibility
- **Working Directory Validation:** Prevents AI from creating files outside project boundaries
- **Duplicate Functionality Prevention:** Stops AI from recreating existing functionality
- **Structure Documentation:** Living project-structure.md file updated continuously
- **Emergency Recovery:** Procedures for fixing structure problems when they occur

### 6. Development Standards Checklist (`development-standards-checklist.mdc`)

Prevent the 10 most common AI development mistakes:

- **Naming Convention Consistency:** Prevents mixing camelCase, snake_case, kebab-case in same project
- **Complete Error Handling:** Ensures every external operation has proper error management
- **Input Validation:** Prevents security vulnerabilities through comprehensive validation
- **Configuration Management:** Eliminates hardcoded values and ensures proper environment setup
- **Security Best Practices:** Prevents SQL injection, XSS, CSRF, and other vulnerabilities
- **Import/Export Consistency:** Maintains consistent module patterns throughout codebase
- **Performance Optimization:** Prevents common performance anti-patterns
- **Accessibility Compliance:** Ensures WCAG standards are met consistently
- **Testing Completeness:** Prevents gaps in test coverage and edge case handling
- **Standards Recovery:** Emergency procedures when standards are violated

## 🚀 **How to Set Up for Cursor IDE**

### **📥 Installation & Initial Setup**

1. **Download & Install Cursor:**

   - Visit [cursor.com](https://cursor.com) and download for your OS
   - Run installer and complete setup wizard
   - Sign up for free account (includes 14-day Pro trial)

2. **Import VS Code Settings (Optional):**

   - During first launch, Cursor will offer to import VS Code extensions, themes, and settings
   - Accept if you're migrating from VS Code for familiar experience

3. **Configure Essential Settings:**
   - Go to `Cursor` > `Settings` > `Cursor Settings`
   - Enable **Codebase Indexing** for better AI context
   - Set your preferred AI model in **Models** section
   - Configure **Privacy** settings according to your needs

### **📁 Framework Files Setup**

#### **Directory Structure:**

Place all framework files in your main development directory:

```
your-development-folder/
├── ai-dev-framework/
│   ├── project-information-template.md
│   ├── project-information-example.md
│   ├── create-project-spec.mdc
│   ├── generate-project-tasks.mdc
│   ├── process-project-tasks.mdc
│   ├── project-structure-guide.mdc
│   ├── development-standards-checklist.mdc
│   └── README.md
└── your-projects/
    ├── project-1/
    └── project-2/
```

#### **Always Load These Files:**

Configure Cursor to always have access to these core framework files by:

1. **Adding to Cursor Workspace:**

   - Open Cursor and go to `File` > `Add Folder to Workspace`
   - Add your `ai-dev-framework` folder

2. **Pin Important Files:**
   - Keep these files pinned as tabs for quick access:
     - `process-project-tasks.mdc` (most frequently used during development)
     - `development-standards-checklist.mdc` (used in every quality validation)
     - `project-structure-guide.mdc` (prevents common mistakes)

#### **On-Demand Files:**

Load these when starting new projects or specific phases:

- `project-information-template.md` (when gathering requirements)
- `create-project-spec.mdc` (when creating project specifications)
- `generate-project-tasks.mdc` (when generating development roadmaps)

### **⚙️ Cursor Configuration for AI Development**

#### **Essential Settings:**

1. **AI Rules Configuration:**

   ```
   Cursor > Settings > General > Rules for AI
   ```

   Add these rules:

   ```
   - Always prioritize security and follow zero-vulnerability practices
   - Use clean code principles and DRY methodology
   - Validate file locations against project structure before creating files
   - Check development standards checklist for every implementation
   - Maintain consistent naming conventions throughout the project
   ```

2. **Codebase Indexing:**

   ```
   Cursor > Settings > Features > Codebase Indexing
   ```

   - ✅ Enable "Default Index New Files"
   - ✅ Enable "Git Graph Relations"
   - Add large files to ignore list

3. **Chat Settings:**
   ```
   Cursor > Settings > Features > Chat and Composer
   ```
   - ✅ Enable "Auto-scroll to Bottom"
   - ✅ Enable "Auto-apply to Out-of-context Files"

### **🎯 Using the Framework with Cursor**

#### **Starting a New Project:**

```bash
# Method 1: Using structured template
Use @create-project-spec.mdc
Here's the application/project information.md

# Method 2: Direct description
Use @create-project-spec.mdc
Here's the application I want to build: [Your description]
```

#### **Generating Development Tasks:**

```bash
Use @generate-project-tasks.mdc
Reference: @project-spec-[your-project-name].md
```

#### **During Development:**

```bash
Use @process-project-tasks.mdc
Current task: [Phase X, Task Y]
Reference: @project-structure.md
```

#### **Quality Validation:**

```bash
Use @development-standards-checklist.mdc
Validate implementation for: [specific task or feature]
```

### **⌨️ Essential Cursor Shortcuts**

| Shortcut           | Action               | Usage with Framework                                 |
| ------------------ | -------------------- | ---------------------------------------------------- |
| `Ctrl+L` (`Cmd+L`) | Open AI Chat         | Primary way to interact with framework files         |
| `Ctrl+K` (`Cmd+K`) | Inline AI Edit       | Quick code modifications following standards         |
| `Ctrl+I` (`Cmd+I`) | Composer Mode        | Complex multi-file changes with structure validation |
| `@filename`        | Reference File       | Essential for using framework files                  |
| `Tab`              | Accept AI Suggestion | Accept code that follows established conventions     |

### **📝 Framework File Reference Patterns**

#### **Project Planning Phase:**

```bash
@create-project-spec.mdc + @project-information-template.md
```

#### **Development Phase:**

```bash
@process-project-tasks.mdc + @project-structure.md + @development-standards-checklist.mdc
```

#### **Quality Validation:**

```bash
@development-standards-checklist.mdc + @project-structure.md
```

### **🔧 Advanced Configuration**

#### **Custom Keybindings:**

Add these to your Cursor keybindings for faster framework access:

```json
{
  "key": "ctrl+shift+f",
  "command": "workbench.action.quickOpen",
  "args": "@process-project-tasks.mdc"
},
{
  "key": "ctrl+shift+s",
  "command": "workbench.action.quickOpen",
  "args": "@development-standards-checklist.mdc"
}
```

#### **Workspace Settings:**

Create `.vscode/settings.json` in your framework folder:

```json
{
  "cursor.chat.defaultModel": "claude-4-sonnet",
  "cursor.indexing.enabled": true,
  "cursor.chat.autoScroll": true
}
```

### **📚 Additional Resources**

- **Official Cursor Documentation:** [docs.cursor.com](https://docs.cursor.com)
- **Cursor Community Forum:** [forum.cursor.com](https://forum.cursor.com)
- **Video Tutorials:** Search "Cursor AI setup" on YouTube for visual guides
- **VS Code Migration Guide:** Available in Cursor docs for smooth transition

### **💡 Pro Tips for Framework Usage**

1. **Keep Framework Files Updated:** Regularly update your framework files with lessons learned
2. **Use Consistent Referencing:** Always use `@filename` to reference framework files for better context
3. **Maintain File Organization:** Keep your framework files in a dedicated, easily accessible folder
4. **Regular Validation:** Use the development standards checklist after every major task
5. **Document Customizations:** Note any project-specific modifications to framework files

**Remember:** The framework files work best when Cursor has full context. Always reference the relevant framework files in your prompts for optimal AI assistance!

## Key Features

- **Technology Decision Guidance:** Systematic approach to selecting optimal tech stacks
- **Complexity-Aware Planning:** Task granularity matching project complexity (Simple/Medium/Complex)
- **MVP-Driven Development:** MoSCoW prioritization preventing scope creep
- **Cross-Platform Excellence:** Responsive design, accessibility, and browser compatibility built-in
- **Zero-Vulnerability Mandate:** Security scanning and validation at every step
- **Performance First:** Core Web Vitals optimization and performance monitoring throughout
- **SEO Optimization:** Search engine optimization integrated into development process
- **Clean Code Enforcement:** DRY principles and maintainable code practices
- **Quality Validation:** Comprehensive testing and validation after each major task
- **Project Structure Management:** Prevents directory confusion and file duplication common in AI development
- **Development Standards Enforcement:** Prevents the 10 most common AI coding mistakes through systematic validation
