# ☢️ Tangnet Museum: Radium Clock Collection

A digital museum exhibition documenting vintage radium clocks, their history, and the human cost of radioactive consumer products. This project combines historical education with real-time radiation monitoring in an immersive web experience.

![License](https://img.shields.io/badge/license-MIT-green)
![HTML5](https://img.shields.io/badge/HTML5-E34C26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## 🎯 Project Overview

The Tangnet Museum is an interactive web exhibition that tells the story of radium in consumer products, focusing on vintage clocks from the early-to-mid 20th century. It combines museum-quality historical documentation with live radiation monitoring, creating an educational experience about the intersection of scientific discovery, industrial exploitation, and human tragedy.

### Key Features

- **📚 Comprehensive Historical Archive** - Deep dive into radium's discovery, the Radium Girls tragedy, and evolution of safety standards
- **🕰️ Specimen Collection** - Detailed documentation of radioactive and non-radioactive vintage clocks
- **📊 Live Radiation Monitor** - Real-time CPM data visualization (simulated for web demo)
- **🎨 Hybrid Aesthetic** - Blends museum professionalism with cyberpunk terminal aesthetics
- **📱 Fully Responsive** - Optimized for all devices

## 🌐 Live Demo

Visit the exhibition at: [https://[bneidlinger.github.io/radium_clock_project](https://bneidlinger.github.io/radium_clock_project)

## 📂 Project Structure

```
radium_clock_project/
│
├── index.html                    # Main exhibition page - Radium history & safety
├── geiger-live.html             # Live radiation monitoring dashboard
├── bradleyradium1.html          # Bradley Radium Clock (1955) specimen page
├── brandleynoradium1.html       # Linden Clock (1970s) comparison specimen
├── radiumhistory.html           # Alternative history layout (terminal style)
├── radiumhistory-interactive.html # Interactive history with animations
├── radiumhistory-museum.html    # Museum-style history presentation
│
├── images/
│   ├── bradleyspicey.jpeg      # Bradley clock photograph
│   ├── bradleynospice.jpeg     # Linden clock photograph
│   └── geiger_setup.png        # Geiger counter setup image
│
├── CLAUDE.md                    # AI assistant instructions
└── README.md                    # This file
```

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/bneidlinger/radium_clock_project.git
   cd radium_clock_project
   ```

2. **Open locally**
   ```bash
   # Simple Python server
   python -m http.server 8000
   
   # Or with Node.js
   npx http-server
   ```

3. **Visit in browser**
   ```
   http://localhost:8000
   ```

## 📖 Page Descriptions

### Main Exhibition (index.html)
The primary landing page featuring:
- Complete history of radium in consumer products
- The science of radioluminescence
- The Radium Girls tragedy and its impact
- Evolution of luminous materials
- Comprehensive safety guidelines for collectors
- Links to specimen collection

### Live Radiation Monitor (geiger-live.html)
Simulated real-time radiation monitoring dashboard featuring:
- Live CPM (Counts Per Minute) display
- Real-time data visualization chart
- Multiple radiation level scenarios
- Styled as "Curie Memorial Radiation Laboratory"
- Full cyberpunk aesthetic with CRT effects

### Specimen Pages
- **Bradley Radium Clock (1955)**: Documented radioactive specimen with ~75 CPM reading
- **Linden Clock (1970s)**: Non-radioactive comparison piece showing background radiation only

## ⚠️ Safety Information

**IMPORTANT**: This project documents real radioactive artifacts. If you own vintage radium clocks:

1. **Never disassemble** radium clocks or watches
2. **Store in ventilated areas** to prevent radon accumulation
3. **Maintain distance** - do not keep near living/sleeping areas
4. **Handle minimally** with gloves when necessary
5. **Monitor radiation levels** with appropriate equipment
6. **Seek professional help** for disposal of damaged items

## 🛠️ Technical Details

### Technologies Used
- **HTML5** - Semantic markup and structure
- **CSS3** - Advanced animations and effects
- **Vanilla JavaScript** - Interactive features and data simulation
- **Tailwind CSS** - Utility-first styling (select pages)
- **Chart.js** - Data visualization
- **Google Fonts** - Typography (Playfair Display, Cinzel, Courier Prime)

### Browser Support
- Chrome/Edge (recommended)
- Firefox
- Safari
- Mobile browsers (iOS/Android)

### Performance Optimizations
- Minimal dependencies (mostly vanilla JS/CSS)
- Optimized animations using CSS transforms
- Responsive images and layouts
- Fast load times with inline critical CSS

## 🎨 Design Philosophy

The project employs a unique hybrid aesthetic that:
- Respects the serious historical subject matter with museum-quality presentation
- Engages modern audiences with cyberpunk/retro-futuristic elements
- Uses color coding for radiation levels (green = safe, yellow = caution, red = danger)
- Incorporates period-appropriate typography while maintaining readability

## 📝 Historical Context

This project serves as both a technical demonstration and educational resource about:
- The discovery of radium by Marie and Pierre Curie (1898)
- The rise of radium consumer products (1910s-1950s)
- The Radium Girls tragedy and labor rights movement
- Evolution of radiation safety standards
- Modern collecting and preservation of radioactive artifacts

## 🤝 Contributing

Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Marie and Pierre Curie for their groundbreaking scientific work
- The Radium Girls whose sacrifice led to modern workplace safety standards
- Modern collectors who preserve these artifacts responsibly
- The open-source community for tools and libraries

## 📞 Contact

For questions about the project or to report issues:
- GitHub Issues: [Create an issue](https://github.com/bneidlinger/radium_clock_project/issues)
- Email: brandon.neidlinger@gmail.com

---

**Remember**: When collecting vintage radioactive items, education and safety must always come first. Handle with care, store safely, and respect the past.

☢️ *"Those who cannot remember the past are condemned to repeat it."* - George Santayana