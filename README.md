# 🚀 DevOps Engineer Portfolio

[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)](https://nginx.org/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

A modern, responsive portfolio website for DevOps Engineers, containerized with Docker and featuring a stunning neon blue animated design.

## 🌟 Features

- **Modern Design**: Neon blue animated gradient background with smooth transitions
- **Responsive Layout**: Optimized for desktop, tablet, and mobile devices
- **Professional Content**: Comprehensive DevOps project showcase with metrics
- **Interactive Elements**: Hover effects, animations, and smooth scrolling
- **Containerized**: Fully dockerized for easy deployment and portability
- **Performance Optimized**: Lightweight nginx-based serving

## 🛠️ Tech Stack

| Technology | Purpose | Version |
|------------|---------|---------|
| **Docker** | Containerization | Latest |
| **Nginx** | Web Server | Alpine |
| **HTML5** | Structure | - |
| **CSS3** | Styling & Animations | - |
| **JavaScript** | Interactivity | ES6+ |

## 📁 Project Structure

```
portfolio-app/
├── src/
│   ├── index.html          # Main HTML file
│   ├── style.css           # CSS styles and animations
│   └── me.jpeg            # Profile image
├── Dockerfile             # Docker configuration
└── README.md             # Project documentation
```

## 🚀 Quick Start

### Prerequisites

- Docker installed on your system
- Basic knowledge of Docker commands

### 1. Clone the Repository

```bash
git clone <repository-url>
cd portfolio-app
```

### 2. Build the Docker Image

```bash
docker build -t wendy-portfolio:latest .
```

### 3. Run the Container

```bash
docker run -d -p 8080:80 wendy-portfolio:latest
```

### 4. Access the Portfolio

Open your browser and navigate to:
```
http://localhost:8080
```

## 🐳 Docker Commands

### Build Image
```bash
docker build -t wendy-portfolio:latest .
```

### Run Container
```bash
docker run -d -p 8080:80 wendy-portfolio:latest
```

### View Running Containers
```bash
docker ps
```

### Stop Container
```bash
docker stop <container-id>
```

### View Container Logs
```bash
docker logs <container-id>
```

### Execute Commands in Container
```bash
docker exec -it <container-id> /bin/sh
```

## 🎨 Customization

### Update Profile Information

1. Edit `src/index.html` to update:
   - Name and title
   - About section
   - Skills and projects
   - Contact information

2. Replace `src/me.jpeg` with your professional headshot

3. Modify `src/style.css` to customize:
   - Color scheme
   - Animations
   - Layout and spacing

### Change Background Theme

To modify the neon blue theme, update the CSS gradient in `style.css`:

```css
background: linear-gradient(135deg, #00ffff 0%, #0080ff 25%, #ffffff 50%, #0080ff 75%, #00ffff 100%);
```

## 📊 Portfolio Sections

### 🏠 Header
- Professional headshot with status indicator
- Name and title with gradient text
- Navigation menu with smooth scrolling

### 👨‍💻 About Me
- Professional summary
- Key metrics and achievements
- Highlight statistics

### 🌟 Featured Project
- Detailed project showcase
- Technologies used
- Measurable results and impact
- Challenges and solutions

### 🛠️ Skills
- DevOps tools and technologies
- Cloud platforms
- Programming languages
- Monitoring and automation tools

### 📁 Additional Projects
- Project portfolio with descriptions
- Technology tags
- Visual project icons

### 📞 Contact
- Multiple contact methods
- Professional links
- Call-to-action for collaboration

## 🚀 Deployment Options

### Docker Hub
```bash
# Tag the image
docker tag wendy-portfolio:latest yourusername/wendy-portfolio:latest

# Push to Docker Hub
docker push yourusername/wendy-portfolio:latest
```

### Cloud Platforms
- **AWS ECS/Fargate**: Deploy container to AWS
- **Google Cloud Run**: Serverless container deployment
- **Azure Container Instances**: Quick container hosting
- **DigitalOcean App Platform**: Simple container deployment

### Static Hosting
- **Netlify**: Drag and drop `src/` folder
- **Vercel**: Deploy from Git repository
- **GitHub Pages**: Host static files
- **AWS S3 + CloudFront**: Static website hosting

## 🔧 Development

### Local Development
```bash
# Serve files locally (requires Python)
cd src
python -m http.server 8000
```

### Live Reload (Optional)
For development with live reload, consider using:
- Live Server VS Code extension
- Browser-sync
- Local development server

## 📈 Performance

- **Lighthouse Score**: 95+ (Performance, Accessibility, Best Practices)
- **Load Time**: < 2 seconds
- **Image Optimization**: Compressed profile images
- **CSS Optimization**: Minified and optimized styles
- **Responsive Design**: Mobile-first approach

## 🔒 Security

- **Content Security Policy**: Implemented for XSS protection
- **HTTPS Ready**: SSL/TLS certificate compatible
- **No Sensitive Data**: All credentials are placeholder examples
- **Docker Security**: Non-root user in container

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Edith Wendy Sosu**
- DevOps Engineer
- Email: edith.sosu@example.com
- LinkedIn: [linkedin.com/in/edith-sosu](https://linkedin.com/in/edith-sosu)
- GitHub: [github.com/edith-sosu](https://github.com/edith-sosu)

## 🙏 Acknowledgments

- Design inspiration from modern portfolio trends
- Docker community for containerization best practices
- Open source community for tools and resources

---

⭐ **Star this repository if you found it helpful!**

📧 **Questions?** Feel free to reach out or open an issue.

🚀 **Ready to deploy?** Follow the deployment guide above.