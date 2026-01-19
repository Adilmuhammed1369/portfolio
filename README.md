# Adil Muhammed - Portfolio Website

A modern, responsive portfolio website showcasing skills, experience, projects, and achievements. Built with HTML, CSS, and JavaScript with a focus on smooth animations and user experience.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works seamlessly on all devices
- **Modern UI**: Clean and contemporary design with gradient accents
- **Smooth Animations**: Engaging scroll animations and hover effects
- **Interactive Elements**: Dynamic navigation, skill bars, and project cards
- **Contact Form**: Integrated contact form for easy communication
- **Mobile-Friendly**: Optimized for mobile devices with hamburger menu

## 🛠️ Technologies Used

- HTML5
- CSS3 (with CSS Variables and Animations)
- JavaScript (ES6+)
- Font Awesome Icons

## 📂 Project Structure

```
portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # CSS styling and animations
├── script.js           # JavaScript for interactivity
└── README.md          # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor (VS Code, Sublime Text, etc.) for customization

### Installation

1. **Clone or download the repository**
   ```bash
   git clone <repository-url>
   ```

2. **Navigate to the project directory**
   ```bash
   cd portfolio
   ```

3. **Open the project**
   - Simply double-click `index.html` to open in your default browser
   - Or use a local server (recommended):
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js
     npx serve
     ```

4. **View in browser**
   - Navigate to `http://localhost:8000` (if using local server)
   - Or open `index.html` directly in your browser

## ✏️ Customization

### Updating Personal Information

1. **Basic Info** - Edit the following in `index.html`:
   - Name, title, and description in the Hero section
   - About Me content
   - Contact information (email, phone, location)

2. **Skills** - Modify skill percentages in the Skills section:
   ```html
   <div class="skill-progress" style="width: 90%"></div>
   ```

3. **Experience** - Add/edit your work experience in the Experience section

4. **Projects** - Update project details, technologies, and links

5. **Social Links** - Replace placeholder URLs with your actual social media profiles:
   ```html
   <a href="https://github.com/yourusername">
   <a href="https://linkedin.com/in/yourusername">
   ```

### Color Scheme

The color scheme is defined using CSS variables in `styles.css`. You can easily customize colors by modifying these variables:

```css
:root {
    --primary-color: #6366f1;      /* Main brand color */
    --secondary-color: #8b5cf6;    /* Secondary accent */
    --accent-color: #ec4899;       /* Highlight color */
    --dark-bg: #0f172a;           /* Dark background */
    --text-primary: #f1f5f9;      /* Primary text */
}
```

### Adding Images

To add a profile image or project images:

1. Create an `images` folder in the project directory
2. Add your images to the folder
3. Update the image sources in `index.html`:
   ```html
   <img src="images/profile.jpg" alt="Profile Picture">
   ```

## 📱 Sections

The portfolio includes the following sections:

1. **Hero/Home** - Introduction with name, title, and call-to-action buttons
2. **About** - Background, interests, and current goals
3. **Skills** - Technical skills with visual progress bars
4. **Experience** - Professional work experience timeline
5. **Projects** - Featured projects with descriptions and technologies
6. **Education** - Academic background and certifications
7. **Contact** - Contact form and social media links

## 🎨 Design Features

- **Gradient Accents**: Modern gradient colors throughout the design
- **Hover Effects**: Interactive hover states on buttons and cards
- **Scroll Animations**: Elements fade in and slide up as you scroll
- **Skill Progress Bars**: Animated progress bars showing skill levels
- **Mobile Menu**: Responsive hamburger menu for mobile devices
- **Smooth Scrolling**: Smooth navigation between sections

## 🌐 Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select the main branch as source
4. Your site will be published at `https://yourusername.github.io/repository-name`

### Netlify

1. Create a Netlify account
2. Drag and drop your project folder to Netlify
3. Your site will be live instantly with a custom URL

### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts to deploy

## 📝 Customization Tips

1. **Resume Download**: Add your resume PDF to the project and link it:
   ```html
   <a href="resume.pdf" download class="btn btn-download">
   ```

2. **Add More Sections**: You can add sections like:
   - Testimonials
   - Blog posts
   - Awards and achievements
   - Volunteer work

3. **Integrate Backend**: For the contact form to actually send emails, integrate with:
   - EmailJS
   - Formspree
   - Your own backend server

4. **Analytics**: Add Google Analytics to track visitors:
   ```html
   <!-- Add before </head> -->
   <script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
   ```

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Feel free to fork this project and customize it for your own use. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## 📧 Contact

For any questions or feedback, please reach out:

- **Email**: adilm@example.com
- **GitHub**: [Your GitHub Profile]
- **LinkedIn**: [Your LinkedIn Profile]

## 🙏 Acknowledgments

- Inspired by modern portfolio designs
- Icons from [Font Awesome](https://fontawesome.com/)
- Design influenced by [Rahul's Portfolio](https://rahul-portfolio-flame.vercel.app/)

---

**Built with ❤️ by Adil Muhammed**

🚀 Ready to showcase your work to the world!
