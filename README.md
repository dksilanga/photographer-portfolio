markdown
# 🌟 Capture Moments Photography Portfolio

A professional, responsive, and interactive photography portfolio website built with HTML5, CSS3, and JavaScript. This multi-page website showcases the work of a professional photographer with dedicated sections for services, portfolio gallery, about information, and contact details.

## 📁 Project Structure
capture-moments/
├── index.html # Homepage
├── about.html # About page with biography and skills
├── services.html # Services and pricing information
├── gallery.html # Portfolio gallery with filtering
├── contact.html # Contact form and information
├── css/
│ └── style.css # All styles for the website
├── js/
│ └── script.js # All JavaScript functionality
├── images/ # Directory for image assets
│ ├── hero-bg.jpg
│ ├── about-portrait.jpg
│ └── [other images]
└── README.md # Project documentation

text

## 🚀 Features

### ✨ Core Features
- **Responsive Design**: Fully responsive layout that works on mobile, tablet, and desktop
- **Interactive Elements**: 
  - Mobile-friendly navigation with hamburger menu
  - Testimonial slider with automatic rotation
  - Gallery filtering system
  - FAQ accordion
  - Form validation
- **Semantic HTML5**: Proper use of semantic tags for accessibility and SEO
- **Modern CSS**: CSS variables, flexbox, grid, and animations
- **Performance Optimized**: Clean, efficient code with minimal dependencies

### 📄 Page-Specific Features
- **Homepage**: Hero section, featured work, services preview, testimonials
- **About**: Biography, professional timeline, skills with progress bars
- **Services**: Detailed service offerings with pricing and features
- **Gallery**: Filterable portfolio with categorized work
- **Contact**: Contact form, business info, FAQ, and location details

## 🛠️ Technologies Used

- **HTML5**: Semantic structure and accessibility
- **CSS3**: Flexbox, Grid, Variables, Animations, and Responsive Design
- **JavaScript (ES6+)**: Interactive functionality
- **Font Awesome**: Icons
- **Google Fonts**: Typography (via CDN)

## 🎨 Design Features

- Clean, professional color scheme with CSS variables for easy customization
- Consistent navigation and footer across all pages
- Smooth animations and transitions for enhanced user experience
- Mobile-first responsive design approach
- Accessibility considerations with proper ARIA labels and semantic HTML

## 📱 Responsive Breakpoints

- **Mobile**: 0 - 576px
- **Tablet**: 577px - 768px
- **Small Desktop**: 769px - 992px
- **Large Desktop**: 993px and above

## 🔧 Setup Instructions

### Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/capture-moments.git
Navigate to the project directory:

bash
cd capture-moments
Open in your preferred code editor:

bash
code .  # If using VS Code
Run locally:

Option 1: Open any HTML file directly in a browser

Option 2: Use a local server (recommended):

bash
# Using Python
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server
Adding Your Own Images
Create an images folder in the root directory

Add your images with descriptive filenames

Update the image paths in the HTML files

🌐 Deployment
GitHub Pages
Create a new GitHub repository

Upload all project files to the repository

Enable GitHub Pages:

Go to repository Settings

Scroll down to GitHub Pages section

Select main branch as source

Your site will be live at: https://your-username.github.io/repository-name

Netlify
Drag and drop the project folder to Netlify

Or connect your GitHub repository for automatic deployments:

Log in to Netlify

Click "New site from Git"

Connect your GitHub account

Select your repository

Deploy with zero configuration

Vercel
Import the project from your GitHub repository

Deploy with zero configuration

📞 Customization Guide
Colors
Modify the CSS variables in the :root selector in css/style.css:

css
:root {
  --primary-color: #2c3e50;
  --secondary-color: #3498db;
  --accent-color: #e74c3c;
  /* Add your custom colors here */
}
Content
Update text content in respective HTML files

Replace placeholder images with your own photography

Modify services and pricing in services.html

Add your own testimonials in the testimonial slider

Contact Form
For a functional contact form, integrate with a form service like:

Formspree

Netlify Forms

FormSubmit

🐛 Troubleshooting
Common Issues
Images not loading:

Check file paths in HTML

Ensure images are in the correct directory

JavaScript not working:

Check browser console for errors

Ensure script tag is properly included

Styles not applying:

Check CSS file path

Verify CSS syntax

Browser Support
Chrome (latest)

Firefox (latest)

Safari (latest)

Edge (latest)

📄 License
This project is open source and available under the MIT License.

🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check issues page.

🙏 Acknowledgments
Photographs from Unsplash

Icons from Font Awesome

Inspiration from various photography portfolios

📞 Contact
For questions about this project, please contact:

Email: photo@gmail.com

Website: https://capturemoments.com