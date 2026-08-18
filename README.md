# 📋 Resume Matcher

**AI-powered resume optimizer** that analyzes job postings and suggests keyword changes to better match positions. No coding required!

![Status](https://img.shields.io/badge/status-active-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Deployment](https://img.shields.io/badge/deployment-ready-success)

## ✨ Features

✅ **Upload Resume Files** - Supports .docx, .pdf, or paste text  
✅ **Paste Job Postings** - Analyze any job description  
✅ **AI Analysis** - Claude AI compares your resume against the job posting  
✅ **Smart Suggestions** - Get specific keyword and phrasing recommendations  
✅ **Match Score** - See how well your resume aligns (0-100)  
✅ **Formatting Preserved** - You edit your own file, no formatting lost  
✅ **No Account Needed** - Works in your browser instantly  
✅ **Free Forever** - No subscriptions, no hidden costs  

## 🚀 Quick Start

### Online (Recommended)
1. Go to your deployed link (see Deployment section below)
2. Upload your resume (.docx or .pdf) or paste the text
3. Paste a job posting
4. Click "Analyze & Get Suggestions"
5. Copy suggestions into your resume

### Local (Developer Option)
```bash
git clone https://github.com/[your-username]/resume-matcher.git
cd resume-matcher
# Open index.html in your browser
```

## 📦 What's Included

```
resume-matcher/
├── index.html              # Complete application (single file!)
├── README.md              # This file
├── DEPLOYMENT_GUIDE.md    # Step-by-step deployment instructions
└── LICENSE                # MIT License
```

## 🌐 Deployment Options

### Option 1: GitHub Pages (Easiest)
1. Create GitHub account at github.com
2. Create new repo called `resume-matcher`
3. Upload `index.html`
4. Enable GitHub Pages in Settings
5. Get your URL: `https://[username].github.io/resume-matcher`

👉 **[Full Guide →](./DEPLOYMENT_GUIDE.md#option-1-github-pages-easiest---free)**

### Option 2: Netlify (Recommended)
1. Visit netlify.com
2. Sign up with GitHub
3. Drag & drop `index.html`
4. Customize your domain
5. Get live link instantly

👉 **[Full Guide →](./DEPLOYMENT_GUIDE.md#option-2-netlify-medium---still-free)**

### Option 3: Vercel (Professional)
1. Visit vercel.com
2. Import your GitHub repo
3. One-click deployment
4. Auto-updates from GitHub

👉 **[Full Guide →](./DEPLOYMENT_GUIDE.md#option-3-vercel-professional---still-free)**

## 💡 How It Works

1. **You upload** a .docx, .pdf, or paste resume text
2. **You paste** a job posting
3. **Claude AI analyzes** both documents
4. **You get** 4-7 specific suggestions showing:
   - What's currently in your resume
   - What to change it to
   - Why that change helps match the job
5. **You copy** suggestions into your own resume file
6. **Your formatting** stays perfect because you're editing your original

## 🔒 Privacy & Security

✅ **No data stored** - Everything runs in your browser  
✅ **No signup required** - Use instantly  
✅ **Your data is yours** - Nothing saved on servers  
⚠️ **API calls only** - Uses Claude AI API (Anthropic) to analyze  
⚠️ **Never share secrets** - Don't paste sensitive personal info  

## 🎯 Use Cases

- **Job Applications** - Optimize resume for each job posting
- **Career Transitions** - Match different industry requirements
- **Keyword Optimization** - ATS (Applicant Tracking System) optimization
- **Interview Prep** - Prepare talking points from suggestions
- **Multiple Versions** - Create role-specific resume versions

## 📊 What You'll Get

**Match Score**: 0-100 rating of how well your resume matches the job

**Suggestions Include**:
- Current wording from your resume
- Suggested improvement
- Why the change helps (keywords, skills, alignment)

**Example**:
```
Current: "Managed a team of 10 people"

Suggested: "Led cross-functional team of 10+ staff members, 
improving efficiency by 25% through process optimization"

Why: Job posting emphasizes "leadership" and "process optimization"
```

## 🛠️ Technical Details

- **Single HTML file** - No build process, no dependencies to install
- **Works offline** - Just the app file (needs API key to analyze)
- **Responsive** - Works on desktop, tablet, mobile
- **Modern browser** - Chrome, Safari, Firefox, Edge (all recent versions)

## 📋 File Support

| Format | Support | Notes |
|--------|---------|-------|
| .pdf | ✅ | Text-based PDFs (not scanned images) |
| .docx | ✅ | Microsoft Word 2007+ |
| .doc | ✅ | Older Word format |
| Plain text | ✅ | Paste directly |
| .odt | ❌ | Not currently supported |
| Scanned PDF | ⚠️ | Requires OCR (not included) |

## ⚙️ How to Use (Detailed)

### Step 1: Load the Site
Open your deployed link in any browser

### Step 2: Add Your Resume
**Option A - Upload:**
- Click the upload box
- Select your .pdf or .docx file
- Wait for extraction (~2 seconds)

**Option B - Paste:**
- Click "Paste Text" tab
- Copy your resume from Word and paste it
- No formatting needed

### Step 3: Add Job Posting
- Copy the job posting from LinkedIn, Indeed, etc.
- Paste into the "Job Posting" box
- Include the full job description

### Step 4: Analyze
- Click "Analyze & Get Suggestions"
- AI analyzes (~5-10 seconds)
- You'll see your match score and suggestions

### Step 5: Update Your Resume
- Read each suggestion
- Copy it (click "Copy Suggestion" button)
- Paste into your actual resume file
- Your formatting stays perfect!

## 💬 Tips for Best Results

✅ **Use complete job postings** - Include full description, requirements, etc.  
✅ **Paste recent resume version** - Make sure it's your latest  
✅ **Review suggestions** - They're suggestions, not rules  
✅ **Be selective** - Not all changes apply to every resume  
✅ **Keep it honest** - Only suggest changes you can truthfully claim  
✅ **Test multiple times** - Try same resume against multiple jobs  

## 🔧 Customization

Want to customize the tool? The HTML file includes:
- Color scheme (currently purple/blue gradient)
- Text and wording
- Button styles
- Layout and spacing

Just edit `index.html` in any text editor and re-upload!

### Change Colors:
Find this line:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Change Text:
Find any heading and change it:
```html
<h1>📋 Resume Matcher</h1>
```

## 📞 Support & Troubleshooting

**"My file won't upload"**
- Make sure it's .pdf or .docx
- File size under 10MB
- Try a different browser

**"AI analysis isn't working"**
- Check internet connection
- Make sure both fields have content
- Try refreshing the page

**"Suggestions seem wrong"**
- AI is helpful but not perfect
- Review all suggestions before using
- Tweak them to fit your actual experience

**"Site is slow"**
- AI analysis takes 5-10 seconds
- Normal - don't refresh!
- Check your internet speed

## 🚀 Roadmap

Future improvements could include:
- [ ] Cover letter optimizer
- [ ] LinkedIn profile analyzer
- [ ] Interview question generator
- [ ] ATS scanning
- [ ] Multiple resume comparison
- [ ] Save/load suggestions
- [ ] Export updated resume

## 📄 License

MIT License - Use freely for personal or commercial purposes

## 🙏 Credits

- Built with Claude AI (Anthropic)
- PDF extraction via PDF.js
- DOCX extraction via Mammoth.js
- Styled with modern CSS

## 🤝 Contributing

Found a bug? Have a suggestion? 
- Create an issue on GitHub
- Submit a pull request
- Email feedback

## 📬 Questions?

If you need help:
1. Check the [DEPLOYMENT_GUIDE.md](./DEPLOYMENT_GUIDE.md)
2. Look at troubleshooting section above
3. Open a GitHub issue
4. Contact the creator

---

**Happy job hunting! 🎯**

*Resume Matcher - Making resume optimization easy, smart, and free.*
