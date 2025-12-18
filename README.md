# ✨ The Design of Your Dreams - Interior AI

**AI-powered interior design platform** | Transform room photos into stunning design concepts using cutting-edge AI technology.

[![GitHub](https://img.shields.io/badge/GitHub-rakh--tech-blue)](https://github.com/rakhmetzyanova1987-tech/rakh-tech)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-Active-brightgreen)](https://rakhmetzyanova1987-tech.github.io/rakh-tech/)
[![License](https://img.shields.io/badge/License-MIT-yellow)](#license)

---

## 🚀 Features

### Core Functionality
- **📷 Photo Upload** - Upload any room photo (JPG, PNG, WebP up to 20MB)
- **🎨 15+ Design Styles** - Minimalism, Scandinavian, Modern, Industrial, Classic, Bohemian, Loft, Contemporary, Rustic, Hygge, Japandi, Maximalism, Art Deco, HI-TECH, Glamour
- **⚡ Intensity Control** - Adjust transformation intensity from 0-100%
- **💭 Custom Preferences** - Add additional design wishes and requirements
- **🤖 Interior AI Integration** - Powered by Interior AI API for professional results
- **💳 Pricing Model** - 3 free generations + 999₽ per additional generation

### Design
- **HI-TECH Aesthetic** - Modern minimalist interface with neon accents (#00d4ff, #0066ff)
- **Dark Theme** - Eye-friendly dark background with gradient design
- **Responsive Layout** - Fully responsive design for desktop and mobile
- **Smooth Animations** - Interactive UI with hover effects and transitions

---

## 🛠 Technical Stack

- **Frontend**: Pure HTML5, CSS3, JavaScript (Vanilla)
- **Styling**: Modern CSS with CSS Variables and Gradients
- **Backend Integration**: Interior AI API (https://api.interiorai.com/v1/generate)
- **Hosting**: GitHub Pages (Free deployment)
- **Version Control**: Git + GitHub

---

## 📋 Project Structure

```
rakh-tech/
├── index.html          # Main application (433 lines)
├── README.md           # Documentation
└── [GitHub Pages]
    └── Live site deployed automatically
```

---

## 🚀 Getting Started

### Live Demo
Visit: **https://rakhmetzyanova1987-tech.github.io/rakh-tech/**

### Local Development

1. **Clone repository**
   ```bash
   git clone https://github.com/rakhmetzyanova1987-tech/rakh-tech.git
   cd rakh-tech
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your browser
   open index.html
   ```

3. **Or use a local server**
   ```bash
   python -m http.server 8000
   # Visit http://localhost:8000
   ```

---

## 🔧 Configuration

### Adding Interior AI API Key

Edit `index.html` line 367:

```javascript
headers: {
  'Authorization': 'Bearer YOUR_INTERIOR_AI_API_KEY',
},
```

Replace `YOUR_INTERIOR_AI_API_KEY` with your actual API key from [Interior AI](https://interiorai.com/)

---

## 💻 Usage Guide

1. **Upload Photo**
   - Click on the upload area or drag & drop your room photo
   - Supported formats: JPG, PNG, WebP (max 20MB)

2. **Select Style**
   - Choose from 15 design styles in the dropdown
   - Each style offers unique aesthetic transformation

3. **Adjust Intensity**
   - Use the slider to control how much the design changes (0-100%)
   - 50% provides balanced transformation

4. **Add Preferences**
   - Describe additional design preferences
   - Example: "Add more light, glass surfaces, metal elements"

5. **Generate Design**
   - Click "⚡ ГЕНЕРИРОВАТЬ ДИЗАЙН" button
   - Wait for AI to process your request

6. **View & Download**
   - View the generated design
   - Click "⬇️ СКАЧАТЬ РЕЗУЛЬТАТ" to download
   - Click "← НАЗАД" to start over

---

## 📊 Project Statistics

- **File Size**: 433 lines of code (16.3 KB)
- **Language**: JavaScript, HTML5, CSS3
- **API Integration**: Interior AI
- **Response Time**: Real-time generation
- **Browser Support**: All modern browsers (Chrome, Firefox, Safari, Edge)

---

## 🎯 Completed Features (Phase 1)

✅ Project setup and GitHub Pages deployment  
✅ HI-TECH UI design with modern aesthetics  
✅ 15 design styles implementation  
✅ Photo upload functionality  
✅ Intensity control slider  
✅ Custom preferences text area  
✅ Interior AI API integration (template)  
✅ Pricing system (3 free + 999₽)  
✅ Download functionality  
✅ Demo image generation (canvas-based)  
✅ Mobile responsive design  
✅ Error handling and validation  

---

## 📈 Future Enhancements (Phase 2)

- [ ] User authentication and account management
- [ ] Save/favorite design results
- [ ] Design comparison tool
- [ ] Advanced filters and adjustments
- [ ] Real-time preview with slider
- [ ] Shopping assistant for furniture recommendations
- [ ] Multi-language support
- [ ] Payment integration (Stripe, YooKassa)
- [ ] Design history and portfolio
- [ ] Social media sharing

---

## 🐛 Known Issues & Solutions

### Issue: API Key not working
**Solution**: Verify API key is correct and has active subscription

### Issue: Images not loading
**Solution**: Check browser cache, hard refresh (Ctrl+Shift+R)

### Issue: Mobile layout broken
**Solution**: Browser might be zoomed, reset to 100%

---

## 📝 License

MIT License - Feel free to use this project for personal or commercial purposes.

---

## 👨‍💻 Author

**rakhmetzyanova1987-tech**  
AI Prompt Engineer & Web Developer  
Specializing in AI applications and creative projects

---

## 🔗 Links

- **Live Website**: https://rakhmetzyanova1987-tech.github.io/rakh-tech/
- **GitHub Repository**: https://github.com/rakhmetzyanova1987-tech/rakh-tech
- **Interior AI API**: https://interiorai.com/

---

## 💬 Support

If you have questions or need help:
1. Check the documentation above
2. Review the code comments in index.html
3. Submit an issue on GitHub

---

**Made with ❤️ by rakhmetzyanova1987-tech**  
*Last Updated: December 18, 2025*
