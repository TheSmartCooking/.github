# 🍳 Smart Cooking

> **A community-driven recipe sharing platform that makes cooking accessible, healthy, and budget-friendly for everyone—especially students.**

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![Prototype](https://img.shields.io/badge/Prototype-Live-green)](https://thesmartcooking.github.io/Prototype/)
[![Docker](https://img.shields.io/badge/Docker-Required-blue)](https://www.docker.com/)

## 🌟 What is Smart Cooking?

Smart Cooking is an open-source web platform where **anyone can share recipes, cooking tips, and practical advice**—no specialized culinary knowledge required! Our mission is to help people achieve the perfect balance between **health, taste, and budget**, with a special focus on student needs.

**🎯 Try our prototype:** [thesmartcooking.github.io/Prototype](https://thesmartcooking.github.io/Prototype/)

## ✨ What Makes Us Different

Unlike traditional recipe websites, Smart Cooking is built **by the community, for the community**:

- **User-Generated Content**: Anyone can publish their own recipes and cooking discoveries
- **Smart Curation**: Featured recipes include admin picks, community favorites, and trending discoveries  
- **Student-Focused**: Budget-friendly recipes and tips designed for student lifestyles
- **Quality Control**: Moderation system with reputation-based publishing (karma system)
- **Progressive Web App**: Seamless experience across desktop and mobile devices

## 🏗️ Architecture & Tech Stack

### Current Tech Stack
- **Database**: PostgreSQL (migrating from MariaDB)
- **Backend**: FastAPI (migrating from Flask)
- **Frontend**: Nuxt.js (considering React for future mobile integration)
- **Containerization**: Docker with DevContainers
- **Authentication**: Custom authentication service

### Repository Structure
Our codebase is organized across multiple repositories:
- 🗄️ **Database**: Schema, migrations, and database configurations
- 🚀 **API**: FastAPI backend with business logic
- 🎨 **Frontend**: Nuxt.js web application and PWA
- 🔐 **Authentication**: Custom authentication service
- *(More repositories as the project grows)*

## 🚀 Key Features

### 📱 User Experience
- **Recipe Discovery**: Browse pinned admin suggestions, latest recipes, and community favorites
- **Smart Rankings**: Recipes ranked by unique views-to-likes ratio (behind the scenes)
- **User Profiles**: Personal recipe collections and community presence
- **Comments & Likes**: Engage with the cooking community
- **Draft System**: Save and refine recipes before publishing

### 🛡️ Content Moderation
- **Review System**: New user recipes are moderated before going public
- **Reputation Building**: Trusted contributors can publish immediately
- **Quality Assurance**: Community-driven quality control

### 📊 Community Features
- **Account-Based Sharing**: Users create accounts but can use pseudonyms
- **Karma System**: Build reputation through quality contributions
- **Community Feedback**: Comments and likes drive recipe popularity

## 🛠️ Getting Started

### Prerequisites
- **Docker** (only requirement - we use DevContainers!)

### Quick Setup
```bash
# Clone the repositories you want to work on
git clone https://github.com/TheSmartCooking/[repo-name]
cd [repo-name]

# Open in VS Code with Dev Containers extension
code .
# VS Code will prompt to reopen in container
```

Each repository contains detailed setup instructions in its own README.

## 🤝 Contributing

**We'd love your help!** Smart Cooking is open source and welcomes contributors of all skill levels.

### 🎨 Especially Seeking
- **UI/UX Designers**: Help make cooking accessible through great design
- **Frontend Developers**: Enhance user experience and mobile responsiveness  
- **Backend Developers**: Improve API performance and add new features
- **Content Creators**: Share amazing recipes and cooking tips!

### How to Contribute
1. **Check out our repositories** and find one that interests you
2. **Read the contributing guidelines** in each repo
3. **Join the discussion** through issues and pull requests
4. **Start small** - documentation improvements and bug fixes are always welcome!

### Contribution Process
- Fork the relevant repository
- Create a feature branch
- Make your changes with clear commit messages
- Submit a pull request with a detailed description
- Engage with the review process

## 🎯 Project Goals

### Immediate Goals
- **Build Community**: Create a vibrant community of cooking enthusiasts and learners
- **Educational Value**: Serve as a real-world learning project for software engineering students
- **MVP Enhancement**: Improve the current MVP based on user feedback

### Long-term Vision  
- **Mobile Excellence**: Fully-featured Progressive Web App experience
- **Global Community**: Support for multiple languages and cuisines
- **Smart Recommendations**: AI-powered recipe suggestions based on preferences and dietary needs
- **Sustainability Focus**: Promote eco-friendly cooking practices and local ingredients

## 📄 License

This project is licensed under the **GNU Affero General Public License v3.0** - see the [LICENSE](LICENSE) file for details.

*We chose AGPL v3 to ensure that Smart Cooking remains open and community-driven, even when deployed as a web service.*

## 🌍 Community

- **🐛 Found a bug?** Open an issue in the relevant repository
- **💡 Have an idea?** Start a discussion or create a feature request
- **❓ Questions?** Check repository discussions or reach out to maintainers

---

**🍽️ Happy Cooking, Happy Coding!**

*Smart Cooking is more than just a recipe platform—it's a community learning experience where food lovers and developers come together to create something meaningful.*
