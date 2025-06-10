# Template Usage Guide

## 📋 How to Use This Template

This repository is a GitHub template for AI-powered applications using Python with Semantic Kernel and TypeScript frontends. Follow these steps to create your own project from this template.

### 🎯 Step 1: Create Your Repository

1. Click the **"Use this template"** button on the GitHub repository page
2. Choose a name for your new repository
3. Select whether it should be public or private
4. Click **"Create repository from template"**

### ✏️ Step 2: Customize Your Project

After creating your repository, you'll need to replace template placeholders with your project-specific content:

#### Required Replacements

1. **Project Name and Description**
   - Replace `[Your Project Name]` with your actual project name
   - Replace the description placeholder with your project description
   - Update the repository name in all badge URLs

2. **Badge URLs**
   - Replace `your-username` with your GitHub username
   - Replace `your-repo-name` with your actual repository name
   - Update workflow names if different from "CI"

3. **Documentation Content**
   - Customize `docs/product_requirements_document.md` with your specific requirements
   - Remove template notes and placeholder text
   - Add your project-specific content

4. **Project Structure**
   - Update the project structure description in `.github/instructions/general-coding.instructions.md`
   - Modify coding standards to match your project needs
   - Update any technology-specific instructions

5. **License**
   - Update `LICENSE` file with your name or organization
   - Replace `[Your Name or Organization]` with the actual copyright holder

### 🔧 Step 3: Set Up Development Environment

1. **Clone your new repository**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Set up your development environment** (customize as needed)
   ```bash
   # Backend setup
   cd backend
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   
   # Frontend setup
   cd ../frontend
   npm install
   ```

3. **Configure your project**
   - Set up environment variables
   - Configure API keys and credentials
   - Update configuration files

### 📝 Step 4: Start Development

1. **Create your first ADR** (if you make architectural decisions)
   - Copy `docs/adr/template.md` to create a new ADR
   - Follow the naming convention: `NNNN-title-with-hyphens.md`
   - Add the ADR to `docs/adr/index.md`

2. **Update documentation**
   - Complete the product requirements document
   - Add technical specifications as needed
   - Document your architecture decisions

3. **Begin coding**
   - Follow the coding standards in `.github/instructions/`
   - Write tests for your functionality
   - Maintain documentation as you develop

### 🎨 Template Features

This template includes:

- **📁 Organized Structure**: Clear separation of backend, frontend, and documentation
- **📋 Documentation Templates**: PRD, ADR, and technical specification templates
- **🛠️ Development Standards**: Coding guidelines and best practices
- **📄 License**: MIT License template
- **🙈 .gitignore**: Comprehensive ignore file for Python, Node.js, and common tools

### 🔄 Keeping Your Template Updated

If you want to update your project with changes from the template:

1. Add this template repository as a remote:
   ```bash
   git remote add template https://github.com/SecuringTheRealm/str-template.git
   ```

2. Fetch the latest template changes:
   ```bash
   git fetch template
   ```

3. Merge template updates (be careful with conflicts):
   ```bash
   git merge template/main
   ```

### 💡 Tips for Success

1. **Start Small**: Begin with the core functionality and expand gradually
2. **Document Early**: Use the ADR template for important decisions
3. **Follow Standards**: Stick to the coding guidelines for consistency
4. **Test Often**: Write tests as you develop features
5. **Version Control**: Make frequent, small commits with clear messages

### 🆘 Need Help?

- Review the existing documentation templates for examples
- Check the `.github/instructions/` folder for development guidelines
- Create issues in your repository to track tasks and bugs
- Follow the contribution guidelines when working with teams

### 📚 Next Steps

1. Complete the product requirements document
2. Set up your development environment
3. Create your first architectural decision record
4. Start building your core functionality
5. Document your progress and decisions

Happy coding! 🚀