
# চদু ক্যালকুলেটর - Personality Test 🤡

![Version](https://img.shields.io/badge/version-1.0.0-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Status](https://img.shields.io/badge/status-fun--project-orange)

একটি মজাদার ব্যক্তিত্ব পরীক্ষা যেখানে আপনি জানতে পারবেন আপনি কতটা "চদু"! এই টেস্টটি পূর্ণ বাংলাদেশি জেনজি স্ল্যাং, মিমস এবং হাসিখুশি মুডে তৈরি।

## 🎯 Features

- **✅ ২০টি মজার প্রশ্ন** - বাংলাদেশি স্ল্যাং এবং ইমোজি সহ
- **✅ জেনজি জেনারেশন ফ্রেন্ডলি** - আপ-টু-ডেট স্ল্যাং ব্যবহার
- **✅ ভিজ্যুয়াল রেজাল্ট** - রাডার চার্ট এবং স্কোর কার্ড
- **✅ সোশ্যাল মিডিয়া শেয়ার** - ফেসবুকে শেয়ার করার অপশন
- **✅ রেজাল্ট ডাউনলোড** - ইমেজ হিসেবে রেজাল্ট সেভ করা
- **✅ রেস্পন্সিভ ডিজাইন** - সব ডিভাইসে কাজ করে

## 🚀 Quick Start

### Method 1: Direct HTML
# সরাসরি index.html ফাইলটি ব্রাউজারে ওপেন করুন

### Method 2: Live Server
# VS Code এ Live Server এক্সটেনশন ব্যবহার করুন
# অথবা Python দিয়ে:
python -m http.server 8000

### Method 3: Online Deployment
# Netlify, Vercel বা GitHub Pages এ ডেপ্লয় করুন

## 📱 How to Use

1. **শুরু করুন** - "শুরু করুন" বাটনে ক্লিক করুন
2. **প্রশ্নের উত্তর দিন** - ২০টি মজার প্রশ্নের উত্তর দিন
3. **রেজাল্ট দেখুন** - আপনার চদু স্কোর এবং বিশ্লেষণ দেখুন
4. **শেয়ার করুন** - সোশ্যাল মিডিয়ায় শেয়ার করুন বা ডাউনলোড করুন

## 📊 Score Interpretation

| Score Range | Level | Description |
|------------|-------|-------------|
| 90-100% | 👑 চদুর রাজা | আপনি তো চদুদের চদু! |
| 70-89% | 💼 প্রোফেশনাল চদু | পাকা চদু, আর্ট ফর্ম! |
| 50-69% | 😎 অ্যাভারেজ চদু | মাঝেমধ্যে চদুপনি |
| 30-49% | 🙂 নরমাল মানুষ | সাধারণ মানুষ |
| 0-29% | 😇 সাধু মানুষ | খুবই ভালো মানুষ |

## 🎭 Sample Questions

- "আপনি কি মানুষের হোগায় আঙুল দিতে পছন্দ করেন?" 🤔👆
- "অন্যের ভালো কি আপনার সহ্য হয়?" 😒
- "আপনার জীবনের লক্ষ্য কী?" 🎯
- "সোস্যাল মিডিয়ার আপনি কেমন?" 📱

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Charts**: Chart.js for visualization
- **Styling**: Custom CSS with CSS Variables
- **Icons**: Emoji and Unicode Characters
- **Responsive**: Mobile-first design

## 📁 Project Structure

```text
  chodu-calculator/
  │
  ├── index.html          # Main HTML file
  ├── README.md           # Project documentation
  │
  ├── assets/             # Static assets (optional)
  │   ├── images/         # Screenshots and icons
  │   └── fonts/          # Custom fonts (if any)
  │
  └── deployment/         # Deployment configs (optional)
      ├── vercel.json     # Vercel configuration
      └── netlify.toml    # Netlify configuration
```

## 🌐 Deployment

### Vercel
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

### Netlify
1. Drag and drop the project folder to Netlify
2. Or connect your GitHub repository

### GitHub Pages
1. Push to GitHub repository
2. Go to Settings > Pages
3. Select source branch

## 🎨 Customization

### Adding New Questions
Edit the `questions` array in `script.js`:

```javascript
{
    text: "আপনার নতুন প্রশ্ন? ❓",
    options: [
        { text: "ক) প্রথম অপশন 👍", value: 1 },
        { text: "খ) দ্বিতীয় অপশন 👎", value: 2 }
    ]
}
```

### Modifying Styles
Edit CSS variables in `style` tag:

```css
:root {
    --primary: #e74c3c;    /* Main color */
    --secondary: #f39c12;  /* Accent color */
    --dark: #2c3e50;       /* Dark color */
    --light: #ecf0f1;      /* Light color */
}
```

## 🤝 Contributing

আপনি যদি মজার প্রশ্ন যোগ করতে চান:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/new-questions`
3. Commit your changes: `git commit -m 'Add new questions'`
4. Push to the branch: `git push origin feature/new-questions`
5. Open a Pull Request

### Contribution Ideas:
- নতুন মজার প্রশ্ন যোগ করুন
- আরও স্ল্যাং যুক্ত করুন
- ডিজাইন ইম্প্রুভ করুন
- বাংলা টাইপোগ্রাফি ইম্প্রুভ করুন

## 🐛 Known Issues

- [ ] Mobile Safari share API compatibility
- [ ] Chart.js rendering on some mobile devices
- [ ] Bengali font rendering consistency

## 📝 Changelog

### v1.0.0 (2023-12-01)
- ✅ Initial release
- ✅ 20 questions with emojis
- ✅ Score calculation and visualization
- ✅ Social media sharing
- ✅ Result download feature

## ⚠️ Disclaimer

**❗ গুরুত্বপূর্ণ নোট:** এই প্রজেক্টটি শুধুমাত্র **বিনোদনের উদ্দেশ্যে** তৈরি করা হয়েছে। 

- এটি কোনো সাইকোলজিক্যাল টেস্ট নয়
- কোনো ব্যক্তিকে হেয় করার উদ্দেশ্য নেই  
- সিরিয়াসলি নেওয়ার কিছু নেই! 😅
- সবাইকে সম্মান দিয়ে মজা করুন

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**আপনার নাম**
- GitHub: [@Visible-Unknown](https://github.com/Visible-Unknown)
- Email: sust.cse572022@gmail.com

## 🙏 Acknowledgments

- Bangladeshi Gen-Z community
- Meme pages for cultural references
- Contributors who added fun questions

---

<div align="center">

### ⚠️ সতর্কতা: এই টেস্ট দিলে আপনার চদু স্কোর ফেসবুতে ভাইরাল হতে পারে! 📱🔥

**স্ট্যাটাস:** 🟢 Live | **ভাষা:** বাংলা | **টার্গেট:** জেনজি জেনারেশন

</div>
