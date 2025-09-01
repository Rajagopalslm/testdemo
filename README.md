🚀 Test Demo - Lightweight DevOps Application
A lightning-fast, zero-dependency demonstration of modern DevOps practices using GitHub Actions and GitHub Pages.

🌟 Live Demo Live URL: https://rajagopalslm.github.io/testdemo

✨ Features

Interactive Counter: Increment, decrement, and reset functionality
Keyboard Shortcuts: Arrow keys and spacebar for interaction
Real-time Updates: Live timestamp and status indicators
Responsive Design: Works perfectly on all device sizes
Zero Dependencies: Pure HTML, CSS, and JavaScript
Lightning Fast: Instant loading with no build process

🛠️ Tech Stack

Frontend: HTML5, CSS3, JavaScript (ES6+),
CI/CD: GitHub Actions,
Hosting: GitHub Pages,
Version Control: Git.

🚀 DevOps Pipeline
This project demonstrates a complete CI/CD pipeline:

Code Change → Developer commits and pushes code
Automated Testing → GitHub Actions validates HTML structure
Build Process → Static files are prepared for deployment
Deployment → Automatic deployment to GitHub Pages
Live Site → Changes are immediately available to users


🎯 Learning Objectives
This demo showcases:

Continuous Integration/Continuous Deployment (CI/CD)
Infrastructure as Code (GitHub Actions workflow)
Automated Testing and validation
Zero-downtime deployment
Modern web development practices

🚦 Quick Start

Fork this repository
Enable GitHub Pages in repository settings
Make changes to index.html
Commit and push - watch the magic happen!

📝 Making Changes
To see the CI/CD pipeline in action:

Edit index.html (try changing the title or counter initial value)
Commit your changes:

git add .

git commit -m "Update demo application"

git push origin main


Watch the GitHub Actions workflow run
See your changes live at the demo URL

🎨 Customization
Changing the Color Scheme
Update the CSS gradient in the body selector:
cssbackground: linear-gradient(135deg, #your-color1 0%, #your-color2 100%);
Adding New Features
The JavaScript is modular - add new functions and call them from HTML:
javascriptfunction myNewFeature() {
    // Your code here
}
Modifying the Pipeline
Edit .github/workflows/deploy.yml to customize the deployment process.

📋 Project Structure
devopsdemo/

├── index.html  					# Main application file            
├── .github/workflows/deploy.yml 	# CI/CD pipeline configuration      
├── README.md            			# Project documentation   
└── .gitignore        				 # Git ignore rules    


🔧 Workflow Features

Fast Deployment: ~30 seconds from push to live
HTML Validation: Ensures code quality
Build Information: Detailed deployment logs
Error Handling: Fails fast with clear error messages
Branch Protection: Only deploys from main branch

📈 Benefits of This Approach

Zero Dependencies: No node_modules, no build tools
Lightning Fast: Loads instantly, deploys quickly
Easy to Understand: Perfect for learning DevOps concepts
Highly Customizable: Simple HTML/CSS/JS structure
Production Ready: Follows best practices

🎓 Educational Value
Perfect for:

Students learning DevOps concepts
Demonstrating CI/CD pipelines
Teaching GitHub Actions
Showing modern web deployment practices

🤝 Contributing

Fork the repository
Create a feature branch (git checkout -b feature/amazing-feature)
Commit your changes (git commit -m 'Add amazing feature')
Push to the branch (git push origin feature/amazing-feature)
Open a Pull Request

📄 License
This project is open source and available under the MIT License.

👨‍💻 Created By
Rajagopal

GitHub: @rajagopalslm

Repository: testdemo


Built with ❤️ for CSE DevOps Education

Demonstrating that great DevOps practices work for projects of any size!