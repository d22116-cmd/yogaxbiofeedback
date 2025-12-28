# YogaXBiofeedback Website

![YogaXBiofeedback](images/logo.png)

## 🧘 Observe, Measure, Transform

Official website for **YogaXBiofeedback Pvt. Ltd.** - Bridging Ancient Yogic Wisdom with Modern Biofeedback Technology.

### 🌟 Features

- **Complete Corporate Website** - Professional, responsive design
- **15+ Software Tools** - Live demos of all wellness applications
- **Hardware Showcase** - PranaFlow and other biofeedback devices
- **Research Section** - Publications, collaborations, lab gallery
- **Blog System** - Ready for content
- **Contact Form** - Integrated inquiry system
- **SEO Optimized** - Meta tags, Open Graph, semantic HTML

### 📁 Project Structure

```
yogax-website/
├── index.html              # Main homepage
├── software.html           # Software showcase page
├── blog.html               # Blog listing page
├── css/
│   └── styles.css          # Main stylesheet
├── js/
│   └── main.js             # JavaScript functionality
├── images/                 # All images (see below)
├── software/               # 15+ software HTML files
│   ├── pranayama-trainer.html
│   ├── swara-monitor.html
│   ├── yoga-instructor.html
│   ├── prakriti.html
│   ├── mental-health.html
│   ├── nidra-guide.html
│   ├── breath-games.html
│   ├── ivt-platform.html
│   ├── mantra-sadhana.html
│   ├── dinacharya.html
│   ├── swara-analyzer.html
│   ├── yoga-sadhana.html
│   ├── panchanga.html
│   ├── astrology.html
│   └── corporate-dashboard.html
└── README.md
```

### 🖼️ Required Images

Upload these images to the `images/` folder with exact filenames:

#### Logos & Branding
- `logo.png` - Main company logo
- `logo-white.png` - White logo for dark backgrounds
- `favicon.png` - Browser favicon

#### Founder
- `founder.jpg` - Main founder photo
- `founder-speaking.jpg` - Founder presenting/speaking

#### Awards
- `award-adani-trophy.jpg` - Adani award trophy
- `award-adani-poster.jpg` - Adani award poster
- `award-adani.jpg` - Adani award main
- `award-certificate.jpg` - Certificate image
- `award-iks-adani.jpg` - IKS Adani trophy
- `award-3.jpg` - Other award

#### Lab & Facilities
- `lab-1.jpg` - Lab photo 1
- `lab-2.jpg` - Lab photo 2
- `iit-mandi.jpg` - IIT Mandi campus

#### Hardware Products
- `pranaflow-1.png` - PranaFlow device front
- `pranaflow-2.png` - PranaFlow device angle
- `pranaflow-box.jpg` - PranaFlow packaging
- `breath-bands.png` - Breath bands product
- `swara-prototype.png` - Swara prototype
- `yoga-mat-sensor.jpg` - Yoga mat sensor
- `yoga-mat.png` - Yoga mat product

#### Software Screenshots
- `software-pranayama-trainer.png`
- `software-swara-monitor.png`
- `software-yoga-instructor.png`
- `software-prakriti.png`
- `software-mental-health.png`
- `software-nidra-guide.png`
- `software-breath-games.png`
- `software-ivt-platform.png`
- `software-mantra-sadhana.png`
- `software-dinacharya.png`
- `software-astrology.png`
- `software-yoga-sadhana.png`
- `software-corporate-dashboard.png`

#### Events & Testimonials
- `corporate-training.jpg`
- `demo-hcl-tech.jpg`
- `event-yoga-day-iit.jpg`
- `yoga-session.jpg`
- `testimonial-amresh-jha.jpg`

#### Backgrounds
- `hero-banner.jpg` - Homepage hero image
- `about-bg.jpg` - About section background
- `media-coverage.jpg` - Media coverage collage

### 🚀 Deployment

#### GitHub Pages

1. Create a new repository on GitHub
2. Upload all files maintaining the folder structure
3. Go to Settings → Pages
4. Select "Deploy from a branch"
5. Choose `main` branch and `/ (root)` folder
6. Your site will be live at `https://yourusername.github.io/repository-name`

#### Custom Domain

1. Add a `CNAME` file with your domain (e.g., `yogaxbiofeedback.com`)
2. Configure DNS records with your domain provider:
   - A Record: `185.199.108.153`
   - A Record: `185.199.109.153`
   - A Record: `185.199.110.153`
   - A Record: `185.199.111.153`
   - CNAME: `www` → `yourusername.github.io`

### 📧 Contact Form Setup

The contact form currently shows an alert. To make it functional:

1. **Formspree** (easiest):
   - Sign up at [formspree.io](https://formspree.io)
   - Get your form endpoint
   - Update the form action in `index.html`

2. **EmailJS**:
   - Sign up at [emailjs.com](https://emailjs.com)
   - Add the SDK and configure

3. **Custom Backend**:
   - Set up a serverless function (Netlify, Vercel, AWS Lambda)

### 🎨 Customization

#### Colors
Edit CSS variables in `index.html`:
```css
:root {
    --saffron: #FF6B2C;
    --teal: #0D9488;
    --gold: #D4A853;
    /* ... */
}
```

#### Fonts
Currently using:
- **Playfair Display** - Headings (elegant serif)
- **DM Sans** - Body text (modern sans-serif)
- **Noto Sans Devanagari** - Sanskrit text

### 📱 Browser Support

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+
- Mobile browsers (iOS Safari, Android Chrome)

### 📄 License

© 2024 YogaXBiofeedback Pvt. Ltd. All rights reserved.

### 👤 Contact

- **Website**: [yogaxbiofeedback.com](https://yogaxbiofeedback.com)
- **Email**: yogaxbiofeedback@gmail.com
- **Phone**: +91 9953094583
- **Address**: IIT Mandi, Himachal Pradesh, India

---

Made with ❤️ at IIT Mandi IKSMHA Centre
