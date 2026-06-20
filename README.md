# React Portfolio

A modern, responsive, and beautiful portfolio website built entirely with React. Showcase your projects, skills, and experience in an elegant and professional manner.

## Features

✨ **Modern Design** - Clean and professional UI with smooth animations  
📱 **Responsive** - Fully responsive design that works on all devices  
🚀 **Fast Performance** - Optimized React components for quick loading  
🎨 **Beautiful Styling** - CSS Modules for scoped and maintainable styles  
🧭 **Easy Navigation** - React Router for smooth page transitions  
💬 **Contact Form** - Built-in contact form with form validation  
🎯 **Sections Included**:
  - Home/Hero Section
  - About Me
  - Projects Showcase
  - Skills Display
  - Contact Form
  - Responsive Navbar
  - Footer

## Tech Stack

- **React 18.2.0** - UI library
- **React Router v6** - Client-side routing
- **CSS Modules** - Scoped styling
- **JavaScript ES6+** - Modern JavaScript

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager

### Installation

1. Navigate to the project directory:
```bash
cd "Shilpi Portfolio"
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

The application will open in your browser at `http://localhost:3000`

## Available Scripts

In the project directory, you can run:

### `npm start`
Runs the app in development mode.

### `npm build`
Builds the app for production to the `build` folder.

### `npm test`
Launches the test runner.

## Project Structure

```
src/
├── components/
│   ├── Navbar/
│   │   ├── Navbar.js
│   │   └── Navbar.module.css
│   └── Footer/
│       ├── Footer.js
│       └── Footer.module.css
├── pages/
│   ├── Home/
│   ├── About/
│   ├── Projects/
│   ├── Skills/
│   └── Contact/
├── App.js
├── App.css
├── index.js
└── index.css
public/
├── index.html
└── favicon.ico
```

## Customization

### Update Personal Information
- Edit text in each component to add your own information
- Update contact details in the Contact page
- Add your actual project links in the Projects page
- Update social media links in the Footer

### Modify Colors
- Colors are defined using CSS variables in the CSS files
- Primary gradient: `#667eea` to `#764ba2`
- Update these in the CSS modules to match your brand

### Add More Projects
- Edit `src/pages/Projects/Projects.js`
- Add new project objects to the `projects` array

## Deployment

### Deploy to Vercel (Recommended)
1. Push your code to GitHub
2. Connect your repository to Vercel
3. Vercel will automatically deploy on every push

### Deploy to Netlify
1. Push your code to GitHub
2. Connect your repository to Netlify
3. Build command: `npm run build`
4. Publish directory: `build`

## Contributing

Feel free to fork this repository and use it as a template for your own portfolio.

## License

This project is open source and available under the MIT License.

## Support

If you have any questions or need help, feel free to reach out!

---

**Made with ❤️ using React**
