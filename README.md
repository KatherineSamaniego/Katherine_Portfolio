# Katherine Samaniego - MBA Portfolio Website

A multi-page portfolio website built with Quarto for my MBA program at University Canada West.

## 📁 Project Structure

```
WRCD-239/
├── _quarto.yml          # Website configuration
├── index.qmd            # Home page
├── experience.qmd       # Experience & Education page
├── projects.qmd         # Projects & Case Studies page
├── skills.qmd           # Skills & Certifications page
├── contact.qmd          # Contact & Connect page
├── styles.css           # Custom CSS styling
├── assets/              # Images, PDFs, and other media
│   ├── profile-photo.jpg              (ADD THIS)
│   ├── Katherine_Samaniego_Resume.pdf (ADD THIS)
│   └── [other project images/files]
└── docs/                # Generated website (after rendering)
```

## 🚀 Quick Start

### Prerequisites

1. **Install Quarto**: Download from [quarto.org](https://quarto.org/docs/get-started/)
2. Verify installation:
   ```bash
   quarto --version
   ```

### Setup Steps

1. **Add Your Assets**
   - Create an `assets/` folder in the project root
   - Add your professional photo as `assets/profile-photo.jpg`
   - Add your resume PDF as `assets/Katherine_Samaniego_Resume.pdf`
   - Add any project images or additional files

2. **Customize the Content**
   - **IMPORTANT**: Search for all `[TODO – ...]` placeholders in the `.qmd` files
   - Replace each TODO with your own writing in your personal voice
   - Update dates, links, and any other information as needed
   - Do NOT submit AI-generated text as your own work!

3. **Render the Website**
   ```bash
   quarto render
   ```
   This generates the website in the `docs/` folder

4. **Preview the Website**
   ```bash
   quarto preview
   ```
   Your site will open at `http://localhost:XXXX`
   - The preview auto-refreshes when you save changes
   - Press `Ctrl+C` in the terminal to stop the preview

## ✅ Pre-Submission Checklist

Before submitting your portfolio, make sure you've completed:

- [ ] All `[TODO]` placeholders replaced with your own writing
- [ ] Profile photo added to `assets/profile-photo.jpg`
- [ ] Resume PDF added to `assets/Katherine_Samaniego_Resume.pdf`
- [ ] All external links (LinkedIn, email) are correct
- [ ] Page navigation works correctly in the navbar
- [ ] Content reflects your authentic voice and experiences
- [ ] APA citations included if you referenced external sources
- [ ] Website renders without errors (`quarto render` completes)
- [ ] Tested the site in preview mode (`quarto preview`)

## 📤 Publishing Options

### Option 1: GitHub Pages
1. Create a GitHub repository
2. Push your project to GitHub
3. Go to Settings → Pages
4. Set source to "Deploy from a branch"
5. Select the `docs/` folder
6. Your site will be live at `https://username.github.io/repo-name`

### Option 2: Quarto Pub (Free)
```bash
quarto publish quarto-pub
```
Follow the prompts to create a free account and publish

### Option 3: Netlify/Vercel
- Drag and drop the `docs/` folder to deploy instantly
- Or connect your GitHub repo for automatic deployments

## 📝 Editing Guide

### Adding New Content
- Edit the `.qmd` files in any text editor (VS Code, RStudio, Notepad++, etc.)
- Use Markdown syntax for formatting
- Save and run `quarto preview` to see changes live

### Changing Colors/Styling
- Edit `styles.css` for custom CSS
- Or change the theme in `_quarto.yml` (options: cosmo, flatly, pulse, sandstone, etc.)

### Adding Pages
1. Create a new `.qmd` file (e.g., `blog.qmd`)
2. Add it to the navbar in `_quarto.yml`:
   ```yaml
   - text: "Blog"
     href: blog.qmd
   ```

## 🎓 APA Citation Examples

If you need to cite resources in your portfolio:

### Quarto Documentation
```
Allaire, J. J., Teague, C., Scheidegger, C., Xie, Y., & Dervieux, C. (2024).
    Quarto (Version 1.4) [Computer software]. https://quarto.org
```

### AI Assistance
```
Anthropic. (2025). Claude (Version 3) [Large language model].
    https://www.anthropic.com/claude
```

**In-text note**: "This portfolio structure was developed with assistance from an AI tool (Anthropic, 2025), with all content personalized and written by the author."

## 🆘 Troubleshooting

**Q: The site isn't rendering correctly**
- Make sure you've run `quarto render` after making changes
- Check for YAML formatting errors in the front matter (indentation matters!)
- Look for error messages in the terminal

**Q: Images aren't showing up**
- Verify the file path is correct (e.g., `assets/profile-photo.jpg`)
- Make sure the `assets/` folder exists and contains the images
- Check file extensions match exactly

**Q: Links are broken**
- Use relative paths (e.g., `assets/resume.pdf`, not `C:/Users/...`)
- Verify all linked files exist in the correct locations

## 📚 Resources

- [Quarto Documentation](https://quarto.org/docs/websites/)
- [Quarto Gallery](https://quarto.org/docs/gallery/) (for inspiration)
- [APA Style Guide](https://apastyle.apa.org/)
- [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)

## 📧 Contact

Katherine Samaniego
- Email: kasv2793@gmail.com
- LinkedIn: [linkedin.com/in/katherine-samaniego-ventura-4750401a5](https://linkedin.com/in/katherine-samaniego-ventura-4750401a5)

---

**Note**: Remember to personalize all content before submission. Your instructor wants to see YOUR voice, not AI-generated text!
