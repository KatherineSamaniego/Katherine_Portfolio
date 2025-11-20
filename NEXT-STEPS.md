# 📋 Next Steps for Your MBA Portfolio

Your multi-page Quarto portfolio website has been created! Follow these steps to personalize and publish it.

## ✅ Step 1: Add Your Media Files (REQUIRED)

1. **Add your professional photo**
   - Save a professional headshot as `assets/profile-photo.jpg`
   - Recommended size: 500x500px (square)

2. **Add your resume PDF**
   - Export your resume as a PDF
   - Save it as `assets/Katherine_Samaniego_Resume.pdf`

3. **Optional: Add project images**
   - Screenshots from El Paisano project
   - Charts from Netflix report
   - Slides from leadership presentation

## ✅ Step 2: Personalize ALL Content (CRITICAL!)

⚠️ **VERY IMPORTANT**: Your instructor wants to see YOUR voice, not AI-generated text!

### Search for ALL `[TODO – ...]` placeholders and replace them with your own writing:

**In `index.qmd` (Home page):**
- Personal introduction about what drives you professionally
- What you hope to do after graduation
- What you're most excited to learn in your MBA

**In `experience.qmd` (Experience page):**
- Revise the professional summary in your own voice
- Add reflections about what you learned in each role
- Describe what you hope to achieve with your MBA

**In `projects.qmd` (Projects page):**
- Introductory sentence about what these projects mean to you
- Personal learnings from El Paisano project
- Reflections on Netflix AI report and using Quarto
- How the Leadership project changed your thinking

**In `skills.qmd` (Skills page):**
- How you've built these skills
- Any additional software/tools you've learned
- Which leadership skills you're developing during MBA
- How your bilingual abilities have helped your career
- Future certifications you plan to pursue

**In `contact.qmd` (Contact page):**
- What kind of conversations you're hoping to have
- Volunteer work or community involvement
- Student clubs or MBA associations
- Any leadership or cultural organizations

### How to find TODOs:
- Open each `.qmd` file in a text editor
- Use Ctrl+F (Windows) or Cmd+F (Mac) to search for `[TODO`
- Replace EVERY instance with your own authentic writing

## ✅ Step 3: Preview Your Website

1. **Open terminal/command prompt** in the `WRCD-239` folder

2. **Run preview command:**
   ```bash
   quarto preview
   ```

3. **Your website will open** in a browser at `http://localhost:XXXX`

4. **Make edits** to the `.qmd` files and save - the preview will auto-refresh

5. **Press Ctrl+C** in the terminal when done previewing

## ✅ Step 4: Render the Final Website

When you're happy with your content:

```bash
quarto render
```

This creates the final website in the `docs/` folder.

## ✅ Step 5: Final Pre-Submission Checks

- [ ] All `[TODO]` placeholders replaced with my own writing
- [ ] Profile photo exists in `assets/profile-photo.jpg`
- [ ] Resume PDF exists in `assets/Katherine_Samaniego_Resume.pdf`
- [ ] All links (LinkedIn, email, resume) work correctly
- [ ] Navigation bar works (can click between all pages)
- [ ] Content sounds like MY voice, not AI
- [ ] No invented information (all jobs, dates, skills are accurate)
- [ ] APA citations added if I referenced external sources
- [ ] Website renders without errors

## ✅ Step 6: Publish (Optional)

If you want to put your portfolio online:

### Option A: GitHub Pages (Free)
1. Create a GitHub account if you don't have one
2. Create a new repository
3. Upload all files to the repository
4. Go to Settings → Pages → Select `docs/` folder
5. Your site will be live at `https://yourusername.github.io/repo-name`

### Option B: Quarto Pub (Free & Easy)
```bash
quarto publish quarto-pub
```
Follow the prompts to create an account and publish.

### Option C: Netlify Drop (Free, No Account Needed)
1. Go to https://app.netlify.com/drop
2. Drag and drop your entire `docs/` folder
3. Get an instant live URL

## 🆘 Need Help?

- **Quarto won't render?** Check for YAML errors (indentation matters!)
- **Images not showing?** Verify file paths and that files exist in `assets/`
- **Links broken?** Make sure all linked files are in the correct locations

**Resources:**
- Quarto Docs: https://quarto.org/docs/websites/
- Quarto Gallery: https://quarto.org/docs/gallery/
- README.md has full troubleshooting guide

## 🎓 Remember

**Your instructor is evaluating:**
1. ✅ Organization & clarity (structure is done!)
2. ✅ Content completeness (replace all TODOs!)
3. ✅ Your authentic voice (write in YOUR words!)
4. ✅ Visual elements (add photos, resume PDF, links)
5. ✅ Professional presentation (Quarto does this!)

The technical structure is complete. Now make it YOURS! 🚀

---

**Questions?** Check the main `README.md` file for detailed documentation.
