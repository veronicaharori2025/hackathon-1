# TECNO Spark 40 Hackathon - Adaptive Outage Mode

> A smart battery mode for real campus realities

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Responsive](https://img.shields.io/badge/Responsive-Yes-brightgreen)](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)

## 📱 Project Overview

**Adaptive Outage Mode** is an innovative battery management feature designed for the TECNO Spark 40, specifically addressing power challenges faced by students at Upper Kabete Campus, University of Nairobi.

### 🎯 Problem Statement
Students face daily power outages (6PM-10PM) during peak study hours, causing phones to die when needed most for emergencies, navigation, and communication.

### 💡 Solution
An intelligent battery mode that:
- Learns users' electricity access patterns
- Automatically adjusts phone settings during predicted outages
- Prioritizes critical functions (flashlight, SOS calls, messaging)
- Limits non-essential apps to extend battery life

## 🌟 Features

- **📊 Smart Pattern Recognition**: Learns from daily power outage schedules
- **🔦 Emergency Priority**: Reserves battery for flashlight and emergency calls
- **⚡ Automatic Activation**: No manual intervention required
- **📱 Campus-Specific**: Tailored for Upper Kabete Campus realities
- **💰 Budget-Friendly**: Designed for $50 phones and low-income users

## 🖥️ Website Features

### Technical Stack
- **Frontend**: Pure HTML5 + CSS3 (No JavaScript)
- **Design**: Modern glassmorphism with responsive layout
- **Video**: Embedded TikTok demo video
- **Typography**: Inter font from Google Fonts
- **Compatibility**: Works on all modern browsers

### Design Elements
- ✨ **Glassmorphism Effects**: Modern semi-transparent backgrounds
- 🎨 **Gradient Backgrounds**: Beautiful purple-blue color scheme
- 📱 **Responsive Grid**: Adapts to desktop, tablet, and mobile
- 🎬 **Video Integration**: TikTok demo embedded seamlessly
- ♿ **Accessibility**: Semantic HTML and proper alt texts

## 🚀 Quick Start

### Prerequisites
- Any modern web browser
- Internet connection (for fonts and TikTok video)

### Installation

1. **Clone or Download**
   ```bash
   # Clone the repository
   git clone https://github.com/yourusername/tecno-spark40-hackathon.git
   
   # Or download the ZIP file and extract
   ```

2. **Open the Website**
   ```bash
   # Navigate to the project folder
   cd tecno-spark40-hackathon
   
   # Open index.html in your browser
   open index.html
   # or double-click the file
   ```

3. **That's it!** 🎉 The website is ready to view.

## 📁 File Structure

```
tecno-spark40-hackathon/
│
├── index.html          # Main website file (HTML + CSS)
├── README.md           # This file
├── images/             # Image assets folder
│   ├── tecno-logo.png
│   ├── uon-logo.png
│   ├── spark40-phone.jpg
│   └── phone-flashlight.jpg
└── assets/             # Additional assets (optional)
```

## 🎨 Customization

### Replace Placeholder Images

The website currently uses placeholder images. Replace these URLs in `index.html`:

```html
<!-- Replace these placeholder URLs with your actual images -->
<img src="https://via.placeholder.com/120x60/667eea/white?text=TECNO" alt="TECNO Logo">
<img src="https://via.placeholder.com/120x60/764ba2/white?text=UoN" alt="UoN Logo">
<img src="https://via.placeholder.com/300x600/333/white?text=SPARK+40" alt="TECNO Spark 40">
```

### Update Content

Modify text content in the HTML file:
- Update team information
- Change contact details
- Modify feature descriptions
- Update campus-specific data

### Customize Colors

The color scheme can be modified in the CSS section:

```css
/* Main gradient background */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Accent colors */
color: #667eea; /* Primary blue */
border-left: 4px solid #667eea; /* Accent border */
```

## 📱 TikTok Video Integration

The website includes an embedded TikTok video showcasing the Adaptive Outage Mode demo:

```html
<iframe src="https://www.tiktok.com/embed/7533993588049317126" 
        width="325" 
        height="578" 
        frameborder="0">
</iframe>
```

**Video ID**: `7533993588049317126`  
**Creator**: [@beautyquincy254](https://www.tiktok.com/@beautyquincy254)

## 🌐 Browser Compatibility

| Browser | Support |
|---------|---------|
| Chrome | ✅ Full |
| Firefox | ✅ Full |
| Safari | ✅ Full |
| Edge | ✅ Full |
| Mobile Browsers | ✅ Full |

## 📱 Responsive Breakpoints

- **Desktop**: > 768px
- **Tablet**: 768px - 481px
- **Mobile**: < 480px

## ♿ Accessibility Features

- **Semantic HTML**: Proper heading structure (H1, H2, H3)
- **Alt Text**: All images include descriptive alt attributes
- **Color Contrast**: High contrast ratios for readability
- **Keyboard Navigation**: All interactive elements are keyboard accessible
- **Screen Reader**: Compatible with screen reader software

## 🎯 Target Audience

### Primary Users
- **Students**: University of Nairobi, Upper Kabete Campus
- **Demographics**: Age 18-45, Income <$200/month
- **Use Case**: Emergency communication during power outages

### Secondary Users
- **Small Business Owners**: In areas with unreliable electricity
- **Rural Families**: Managing phone battery during outages
- **Low-income Individuals**: Maximizing phone utility on budget devices

## 📊 Campus Data & Research

### Upper Kabete Campus Realities
- **Daily Outages**: 6PM-10PM during peak study hours
- **Verification**: Kenya Power's Kabete Division outage tracker (July 2024)
- **Student Behavior**: Mass charging at library/kiosks 4PM-6PM
- **Social Impact**: 72% complain of missed online classes (#KabeteBlackout)

### User Behaviors
- Phone flashlights for navigation in unlit dormitories
- Charging at communal kiosks before predictable outages
- Reliance on phones for emergency communication

## 🚀 Deployment Options

### Local Development
- Open `index.html` directly in browser
- Use local server: `python -m http.server 8000`

### Web Hosting
- **GitHub Pages**: Push to repository and enable Pages
- **Netlify**: Drag and drop the HTML file
- **Vercel**: Connect GitHub repository
- **Traditional Hosting**: Upload to any web server

### CDN Integration
The website uses external resources:
- **Google Fonts**: Inter font family
- **TikTok Embed**: Video content

## 🤝 Contributing

We welcome contributions to improve the project!

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit changes (`git commit -am 'Add new feature'`)
5. Push to branch (`git push origin feature/improvement`)
6. Create a Pull Request

### Areas for Improvement
- [ ] Add more interactive elements
- [ ] Improve mobile performance
- [ ] Add more accessibility features
- [ ] Include offline functionality
- [ ] Add analytics integration

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact & Support

### Project Team
- **Creator**: [@beautyquincy254](https://www.tiktok.com/@beautyquincy254)
- **Institution**: University of Nairobi, Upper Kabete Campus
- **Event**: TECNO Spark 40 Hackathon 2025

### Get Help
- 🐛 **Issues**: Open a GitHub issue
- 💬 **Discussions**: Use GitHub Discussions
- 📧 **Email**: Contact through university channels

## 🏆 Hackathon Details

### Event Information
- **Name**: TECNO Spark 40 Hackathon
- **Year**: 2025
- **Focus**: Adaptive battery management solutions
- **Target Device**: TECNO Spark 40 ($50 smartphone)
- **Location**: Upper Kabete Campus, University of Nairobi

### Project Goals
- Address real campus power challenges
- Create practical solutions for budget smartphones
- Demonstrate technical innovation with social impact
- Showcase student creativity and problem-solving

## 📈 Future Roadmap

### Phase 1: Basic Implementation ✅
- [x] Website development
- [x] Demo video creation
- [x] Feature documentation

### Phase 2: Enhanced Features 🔄
- [ ] Interactive battery simulator
- [ ] User feedback collection
- [ ] Performance metrics
- [ ] Campus data integration

### Phase 3: Production Ready 📋
- [ ] TECNO integration discussions
- [ ] User testing with students
- [ ] Feature refinement
- [ ] Market deployment strategy

---

## 🙏 Acknowledgments

- **TECNO Mobile** for hosting the hackathon
- **University of Nairobi** for campus support
- **Upper Kabete Students** for real-world insights
- **Kenya Power** for outage data accessibility

---

**Made with ❤️ for students facing power challenges**

*Building technology that understands real-world problems* 🌍
