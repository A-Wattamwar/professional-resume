# Professional Resume Template

A clean, modern LaTeX resume template designed for software engineers and computer science professionals.

## 📋 Features

- **Clean and Professional Layout**: Modern design optimized for ATS (Applicant Tracking System) compatibility
- **Customizable Sections**: Easy-to-modify sections for Education, Projects, Experience, and Technical Skills
- **Font Options**: Multiple font choices (sans-serif and serif) with easy switching
- **Responsive Design**: Optimized for both digital viewing and printing
- **Icon Integration**: FontAwesome icons for contact information and social links
- **Hyperlinks**: Clickable links for email, LinkedIn, GitHub, and project repositories

## 🚀 Quick Start

### Prerequisites

You'll need a LaTeX distribution installed on your system:

- **Windows**: [MiKTeX](https://miktex.org/) or [TeX Live](https://www.tug.org/texlive/)
- **macOS**: [MacTeX](https://www.tug.org/mactex/)
- **Linux**: `sudo apt-get install texlive-full` (Ubuntu/Debian)

### Compilation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/professional-resume.git
   cd professional-resume
   ```

2. Compile the LaTeX file:
   ```bash
   pdflatex Professional_Resume.tex
   ```

3. For hyperlinks to work properly, compile twice:
   ```bash
   pdflatex Professional_Resume.tex
   pdflatex Professional_Resume.tex
   ```

### Online Compilation

You can also use online LaTeX editors:
- [Overleaf](https://www.overleaf.com/) (recommended)
- [ShareLaTeX](https://www.sharelatex.com/)

## 📝 Customization

### Personal Information

Update the header section with your details:

```latex
\begin{center}
    \textbf{\Huge \scshape Your Name} \\ \vspace{1pt}
    \footnotesize \raisebox{-0.1\height}
    \faPhone\ \underline{+1 (xxx) xxx-xxxx} ~ 
    {\faEnvelope\  \underline{your.email@domain.com}} ~ 
    \faLinkedin\ \underline{\href{https://linkedin.com/in/yourprofile}{linkedin.com/in/yourprofile}} ~
    \faGithub\ \underline{\href{https://github.com/yourusername}{github.com/yourusername}}
\end{center}
```

### Font Options

Uncomment one of the font options in the preamble:

```latex
% Sans-serif fonts
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% Serif fonts
% \usepackage{CormorantGaramond}
% \usepackage{charter}
```

### Adding New Sections

Use the predefined commands for consistency:

```latex
\section{\textbf{New Section}}
\resumeSubHeadingListStart
  \resumeSubheading
    {Title}{Date}
    {Subtitle}{Location}
  \resumeItemListStart
    \resumeItem{Description of your achievement or responsibility}
  \resumeItemListEnd
\resumeSubHeadingListEnd
```

## 📁 File Structure

```
professional-resume/
│
├── Professional_Resume.tex    # Main LaTeX resume file
├── README.md                 # This file
└── Professional_Resume.pdf   # Compiled PDF (generated)
```

## 🎨 Template Sections

The template includes the following sections:

1. **Header**: Name and contact information with icons
2. **Education**: Academic background with GPA, coursework, and achievements
3. **Projects**: Technical projects with descriptions and GitHub links
4. **Experience**: Work experience and internships
5. **Technical Skills**: Programming languages, tools, and frameworks

## 💡 Tips for Best Results

1. **Keep it concise**: Aim for 1-2 pages maximum
2. **Use action verbs**: Start bullet points with strong action verbs
3. **Quantify achievements**: Include numbers and metrics when possible
4. **Tailor content**: Customize for each job application
5. **Proofread**: Check for typos and formatting consistency

## 🔧 Troubleshooting

### Common Issues

1. **Missing packages**: Install required LaTeX packages if compilation fails
2. **Font errors**: Comment out font packages if not available on your system
3. **Hyperlink issues**: Compile twice for proper hyperlink generation

### Package Dependencies

The template uses these LaTeX packages:
- `fontawesome5` (for icons)
- `hyperref` (for clickable links)
- `titlesec` (for section formatting)
- `enumitem` (for list customization)
- `tabularx` (for table formatting)

## 📄 License

This template is available under the MIT License. Feel free to use, modify, and distribute.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request with improvements or bug fixes.

## 📞 Support

If you encounter any issues or have questions about using this template, please open an issue in this repository.

---

**Made with ❤️ for the developer community** 