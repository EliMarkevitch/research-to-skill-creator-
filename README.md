# Research to Skill Creator

Transform your research markdown files into powerful Claude skills with your brand identity embedded.

![App Preview](https://img.shields.io/badge/Made%20with-React-61DAFB?style=for-the-badge&logo=react)
![Deployed on](https://img.shields.io/badge/Deployed%20on-Vercel-000000?style=for-the-badge&logo=vercel)

## 🎯 Features

- **Upload Research**: Import your .md research files with one click
- **Skill Configuration**: Name your skill and write comprehensive descriptions
- **Brand Identity Integration**: Upload or type your brand voice and guidelines
- **Live Preview**: See your generated skill in real-time
- **File Upload Options**: Upload documents for all text fields
- **One-Click Download**: Generate and download your SKILL.md file instantly

## 🎨 Design

- Contemporary Inter font
- Purple and pink color scheme
- Responsive layout
- Smooth transitions and hover effects

## 🚀 Deployment

### Deploy to Vercel (Recommended)

1. Push this repository to GitHub
2. Go to [Vercel](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Click "Deploy"

That's it! Vercel will automatically detect this as a static site.

### Deploy to Netlify

1. Push this repository to GitHub
2. Go to [Netlify](https://netlify.com)
3. Click "New site from Git"
4. Select your repository
5. Click "Deploy site"

## 💻 Local Development

Simply open `index.html` in your browser. No build process required!

```bash
open index.html
```

Or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

Then visit `http://localhost:8000`

## 📁 Project Structure

```
research-to-skill-creator/
├── index.html          # Main application file
├── README.md           # This file
├── .gitignore         # Git ignore rules
└── vercel.json        # Vercel configuration
```

## 🛠️ Technology Stack

- **React 18** - UI framework
- **Tailwind CSS** - Styling
- **Babel Standalone** - JSX transformation
- **Pure Frontend** - No backend required

## 📖 How to Use

1. **Upload Research**: Click to upload your .md research file
2. **Add Details**: Enter your skill name and comprehensive description
3. **Brand Identity**: Type or upload your brand voice and guidelines
4. **Edit Content**: Modify research content directly in the editor
5. **Preview**: Click "Show Preview" to see your generated skill
6. **Download**: Click "Download SKILL.md" to get your file

## 🎯 What Gets Generated

The app creates a properly formatted SKILL.md file with:

```markdown
---
name: your-skill-name
description: Your comprehensive skill description
---

# Brand Guidelines

## Brand Voice
[Your brand voice content]

## Brand Guide
[Your brand guide content]

# Research Content
[Your research markdown content]
```

## 🤝 Contributing

Feel free to fork and customize this app for your needs!

## 📝 License

MIT License - feel free to use this however you'd like!

---

Made with 💜 using Claude
