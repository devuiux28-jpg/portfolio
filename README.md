# Aria Chen - Professional Portfolio Website

A modern, premium UI/UX and Graphic Designer portfolio website built with React, Vite, and cutting-edge design techniques.

## 🎨 Features

### Design Elements
- **Dark Theme Aesthetic** with electric blue and purple accents
- **Glassmorphism Effects** for modern, premium look
- **Smooth Animations** and micro-interactions
- **Fully Responsive** design for all devices
- **Performance Optimized** for fast loading

### Sections
1. **Hero Section** - Full-screen introduction with animated gradients
2. **About Section** - Profile information with key skills
3. **Portfolio Section** - Project showcase with filtering and hover effects
4. **Skills Section** - Expertise visualization with progress bars
5. **Testimonials Section** - Client feedback and reviews
6. **Contact Section** - Contact form and social links
7. **Footer** - Navigation links and copyright

## 🚀 Tech Stack

- **React 18** - UI framework
- **Vite** - Fast build tool
- **CSS3** - Modern styling with CSS variables
- **Lucide React** - Beautiful icon library
- **Google Fonts** - Poppins and Syne typography

## 📦 Installation

1. Extract the project files
2. Navigate to the project directory:
   ```bash
   cd designer-portfolio
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:3000`

## 🏗️ Build for Production

```bash
npm run build
```

This creates an optimized production build in the `dist` folder.

## 📁 Project Structure

```
designer-portfolio/
├── src/
│   ├── components/
│   │   ├── Header.jsx & Header.css
│   │   ├── Hero.jsx & Hero.css
│   │   ├── About.jsx & About.css
│   │   ├── Portfolio.jsx & Portfolio.css
│   │   ├── Skills.jsx & Skills.css
│   │   ├── Testimonials.jsx & Testimonials.css
│   │   ├── Contact.jsx & Contact.css
│   │   └── Footer.jsx & Footer.css
│   ├── data/
│   │   └── portfolio.js
│   ├── styles/
│   │   └── index.css
│   ├── App.jsx
│   └── main.jsx
├── index.html
├── vite.config.js
├── package.json
└── README.md
```

## 🎯 Customization

### Colors
Edit the CSS variables in `src/styles/index.css`:
```css
:root {
  --accent-blue: #00d9ff;
  --accent-purple: #9d4edd;
  --accent-pink: #ff006e;
}
```

### Content
Update portfolio data in `src/data/portfolio.js`:
- Projects
- Skills
- Testimonials
- Tools

### Typography
Modify fonts in `index.html` or `src/styles/index.css`

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🌟 Key Features Explained

### Glassmorphism
Soft transparent cards with blur effect for modern aesthetic

### Hover Animations
Interactive elements that respond to user interaction with smooth transforms and glows

### Gradient Accents
Dynamic color gradients for visual impact and brand identity

### Performance
- Optimized images
- CSS animations (no heavy JS)
- Lazy loading ready
- Mobile-first approach

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is open source and available for personal and commercial use.

## 🤝 Support

For questions or issues, feel free to contact or create an issue in the repository.

---

**Made with ♥ by Aria Chen**
