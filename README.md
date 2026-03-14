# AIMA Exercises Showcase Website

A modern showcase website for **Artificial Intelligence: A Modern Approach (AIMA)** exercises, featuring interactive content and elegant design.

## 🎯 What It Does

This website presents exercises from the renowned AIMA textbook in an accessible, web-friendly format. It combines:

- **Interactive Exercise Browser**: Navigate through AI topics like search algorithms, knowledge representation, machine learning, and more
- **Modern Web Design**: Clean, responsive interface with smooth animations and intuitive navigation
- **Jekyll Integration**: Static site generation for fast loading and easy deployment
- **Educational Content**: Comprehensive exercises covering fundamental AI concepts

## 📚 Content Structure

The site organizes AIMA exercises by chapter:

- **Search Algorithms** (Chapter 3): Problem-solving by searching, informed/uninformed search
- **Constraint Satisfaction** (Chapter 6): CSP formulation and solving techniques  
- **Knowledge Representation** (Chapters 7-9): Logic, inference, and knowledge bases
- **Planning** (Chapters 10-11): Classical and advanced planning approaches
- **Machine Learning** (Chapters 18-21): Learning algorithms and statistical methods
- **Natural Language Processing** (Chapter 22): Language understanding and generation
- **Robotics & Perception** (Chapters 24-25): Sensors, actuators, and robotic systems

## 🛠 Tech Stack

| Technology | Purpose | Version |
|------------|---------|---------|
| 🌐 **Jekyll** | Static site generator | Latest via GitHub Pages |
| 🎨 **HTML5/CSS3** | Frontend structure & styling | Modern standards |
| ⚡ **JavaScript** | Interactive features | ES6+ |
| 📱 **Responsive Design** | Mobile-friendly layout | CSS Grid/Flexbox |
| 🚀 **GitHub Pages** | Hosting & deployment | Automatic |

## 🚀 Getting Started

### Prerequisites
- Ruby 2.7+ 
- Bundler gem

### Local Development

```bash
# Clone the repository
git clone https://github.com/stabgan/aima-website-1.git
cd aima-website-1

# Install dependencies
bundle install

# Serve locally
bundle exec jekyll serve

# Visit http://localhost:4000
```

### Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the `master` branch.

**Live Site**: [https://stabgan.github.io/aima-website-1](https://stabgan.github.io/aima-website-1)

## 📁 Project Structure

```
├── _config.yml          # Jekyll configuration
├── _posts/              # Blog posts (if any)
├── _site/               # Generated site (ignored)
├── assets/              # CSS, JS, fonts
│   ├── css/
│   ├── js/
│   └── fonts/
├── images/              # Image assets
├── exercises.html       # Exercise index page
├── index.html          # Main landing page
├── *_exercise.html     # Individual exercise pages
└── README.md           # This file
```

## 🎨 Design Features

- **Responsive Layout**: Optimized for desktop, tablet, and mobile
- **Smooth Animations**: CSS transitions and JavaScript interactions
- **Typography**: Clean, readable fonts with proper hierarchy
- **Color Scheme**: Professional palette with good contrast
- **Navigation**: Intuitive menu system with breadcrumbs

## 📖 About AIMA

*Artificial Intelligence: A Modern Approach* by Stuart Russell and Peter Norvig is the leading textbook in artificial intelligence. This website showcases exercises from the book in an interactive, web-based format.

## 👥 Contributors

- **Original Design**: [Kaustabh Ganguly](https://github.com/kaustabhganguly)
- **Mentor**: [Peter Norvig](https://norvig.com)
- **AIMA Authors**: Stuart Russell & Peter Norvig

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE.txt) file for details.

## 🔗 Related Projects

- [AIMA Code Repository](https://github.com/aimacode/aima-python) - Python implementations
- [AIMA Exercises](https://github.com/aimacode/aima-exercises) - Exercise source material
- [AIMA Book Website](http://aima.cs.berkeley.edu/) - Official textbook site

---

*Built with ❤️ for the AI education community*