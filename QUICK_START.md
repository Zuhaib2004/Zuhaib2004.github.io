# ⚡ Quick Reference Cheat Sheet

## 🚀 One-Command Deployments

### Vercel
```bash
npx vercel --prod
```

### Netlify
```bash
npx netlify-cli deploy --prod --dir=.
```

### GitHub Pages
```bash
git add . && git commit -m "Update" && git push
# Site updates automatically at: https://Zuhaib2004.github.io
```

---

## 📂 File Overview

```
📦 Your Portfolio Package
├── 🎨 portfolio.html      - Main website (DEPLOY THIS!)
├── 📝 README.md           - GitHub profile README
├── 🚀 DEPLOYMENT.md       - Detailed deployment guide
├── 🔧 GITHUB_SETUP.md     - Complete GitHub setup
├── 📦 package.json        - NPM configuration
└── ⚡ THIS FILE           - Quick reference
```

---

## 🎯 Essential Links

### Deploy Your Site
- **Vercel**: https://vercel.com/new
- **Netlify**: https://app.netlify.com/drop
- **GitHub Pages**: Settings → Pages

### Your Live URLs
- **Portfolio**: `https://Zuhaib2004.github.io`
- **Vercel**: `https://your-project.vercel.app`
- **Netlify**: `https://your-project.netlify.app`

### Resources
- **GitHub Stats**: https://github-readme-stats.vercel.app
- **Shields.io**: https://shields.io
- **Font Awesome**: https://fontawesome.com
- **Google Fonts**: https://fonts.google.com

---

## 🛠️ Quick Fixes

### Portfolio not loading?
```bash
# Check file name
# Must be: portfolio.html (lowercase)

# Or rename index.html
mv portfolio.html index.html
```

### Custom cursor not working?
- Only works on desktop (intentional design)
- Mobile uses native touch

### GitHub stats broken?
- Wait 5 minutes (API rate limit)
- Verify username is correct
- Ensure repository is public

### Need local preview?
```bash
# Option 1: Python
python -m http.server 8000

# Option 2: Node
npx serve

# Option 3: VS Code
# Install "Live Server" extension
# Right-click HTML → "Open with Live Server"
```

---

## 📝 Git Commands

### Initial Setup
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/Zuhaib2004/portfolio.git
git push -u origin main
```

### Regular Updates
```bash
git add .
git commit -m "Your message here"
git push
```

### Undo Last Commit
```bash
git reset --soft HEAD~1
```

### See What Changed
```bash
git status
git diff
```

---

## 🎨 Customization Quick Edits

### Change Colors
Find in `portfolio.html` around line 15-25:
```css
--accent-cyan: #00f0ff;      /* Main accent */
--accent-magenta: #ff006e;   /* Secondary accent */
--accent-purple: #8b5cf6;    /* Tertiary accent */
```

### Update Your Info
- **Name**: Line ~180
- **Title**: Line ~180-182
- **Email**: Line ~950
- **Phone**: Update manually
- **GitHub**: Replace "Zuhaib2004" globally
- **LinkedIn**: Line ~945

### Add Projects
Find `<!-- Projects Section -->` around line 450
Copy-paste project card structure

---

## 📊 README Stats Customization

### Change Theme
```markdown
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Zuhaib2004&theme=THEME_NAME)
```

**Themes**: radical, dark, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, dracula

### Hide Stats
```markdown
&hide=stars,commits,prs,issues,contribs
```

### Top Languages Config
```markdown
&layout=compact&langs_count=8&exclude_repo=repo1,repo2
```

---

## 🔗 Important URLs to Update

### In portfolio.html
- [ ] Line ~945: GitHub profile
- [ ] Line ~947: LinkedIn profile  
- [ ] Line ~950: Email address
- [ ] Line ~460-580: Project repository links
- [ ] Line ~25: Custom domain (if applicable)

### In README.md
- [ ] All `Zuhaib2004` references
- [ ] LinkedIn URL
- [ ] Email address
- [ ] Project links

---

## 📱 Social Media Templates

### LinkedIn Bio
```
🚀 AI & Software Engineering @ UIC
💻 Building intelligent systems | React Native | Cloud Computing
🌐 Portfolio: [YOUR_URL]
```

### GitHub Bio
```
🔭 Working on AI-powered platforms
🌱 Learning Advanced ML & Distributed Systems
💬 Ask me about React Native, Python, Cloud Computing
📫 zilyas53@gmail.com
```

### Twitter/X Bio
```
AI & Software Engineer 🚀 | CS @ UIC 🎓 | Building the future 💻
Portfolio: [YOUR_URL]
```

---

## 🎯 Pre-Launch Checklist

### Content
- [ ] Name is correct
- [ ] Email is correct
- [ ] Phone (if included) is correct
- [ ] All links work
- [ ] No placeholder text
- [ ] Projects match your repos
- [ ] Experience dates are accurate

### Technical
- [ ] Tested on Chrome
- [ ] Tested on Firefox
- [ ] Tested on Safari
- [ ] Tested on mobile
- [ ] Loads under 3 seconds
- [ ] No console errors
- [ ] All images load

### SEO
- [ ] Title tag is set
- [ ] Meta description included
- [ ] Open Graph tags (optional)
- [ ] Keywords relevant

### Deployment
- [ ] GitHub repo is public
- [ ] Pushed to main branch
- [ ] GitHub Pages enabled
- [ ] Custom domain (optional) configured
- [ ] HTTPS enabled

---

## 🐛 Emergency Contacts

### Something Broken?

1. **Check Browser Console** (F12 → Console)
2. **Validate HTML**: https://validator.w3.org
3. **Test Performance**: https://pagespeed.web.dev
4. **Ask for Help**:
   - Stack Overflow
   - GitHub Discussions
   - Reddit r/webdev

### Rollback Changes
```bash
# Go back to previous commit
git log  # Find commit hash
git reset --hard COMMIT_HASH
git push --force
```

---

## 💡 Pro Tips

1. **Update Regularly**: Add new projects as you build them
2. **Monitor Analytics**: See who visits your portfolio
3. **A/B Test**: Try different layouts/colors
4. **Get Feedback**: Share with friends/mentors
5. **Keep Learning**: Stay updated with web trends
6. **Backup**: Keep code on GitHub always
7. **Mobile First**: Most visitors are on mobile
8. **Load Speed**: Keep it fast (< 3 seconds)
9. **Accessibility**: Use semantic HTML
10. **SEO**: Update meta tags

---

## 🎓 Learning Resources

### Design Inspiration
- **Awwwards**: https://www.awwwards.com
- **Dribbble**: https://dribbble.com
- **Behance**: https://www.behance.net

### Web Development
- **MDN**: https://developer.mozilla.org
- **CSS Tricks**: https://css-tricks.com
- **Web.dev**: https://web.dev

### Animations
- **Framer Motion**: https://www.framer.com/motion
- **GSAP**: https://greensock.com
- **Anime.js**: https://animejs.com

---

## 📞 Support

### Questions?
- Check DEPLOYMENT.md for detailed guides
- Check GITHUB_SETUP.md for GitHub help
- Open an issue on your repo
- Email: zilyas53@gmail.com

---

## 🎉 Success Metrics

### Track Your Portfolio Performance

**Week 1 Goals:**
- [ ] Deploy to GitHub Pages
- [ ] Share on LinkedIn
- [ ] Add to resume
- [ ] Get 5 profile views

**Month 1 Goals:**
- [ ] Add 3+ new projects
- [ ] Get 50+ profile views  
- [ ] Connect custom domain
- [ ] Add testimonials section

**Month 3 Goals:**
- [ ] 200+ profile views
- [ ] Featured on Awwwards/Similar
- [ ] Job interview from portfolio
- [ ] Speaking/Blogging about it

---

<div align="center">

## 🚀 YOU'RE READY TO LAUNCH!

**Everything you need is in this folder.**

Choose a platform. Deploy. Share. Win. 🏆

**Questions?** Check the guides. Still stuck? Open an issue.

---

### **Made with 💙 by Zuhaib Ilyas**

*Go build something amazing!* ✨

</div>
