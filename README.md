# 🚀 Agency.AI - Digital Agency Website

A modern, high-performance digital agency website built with React, showcasing cutting-edge UI/UX design and smooth animations. This project demonstrates best practices for building professional web applications with a focus on user experience and performance.

![Agency.AI Preview](https://via.placeholder.com/800x400/1a1a1a/ffffff?text=Agency.AI+Preview) <!-- Replace with actual screenshot -->

## ✨ Features

### 🎨 Modern UI/UX Design
- **Light/Dark Mode Toggle** - Seamless theme switching with persistent storage
- **Custom Animated Cursor** - Interactive cursor with smooth following animation
- **Scroll-Triggered Animations** - Engaging animations using Framer Motion
- **Fully Responsive Design** - Optimized for all device sizes
- **Professional Layout** - Clean, modern design with attention to detail

### ⚛️ Technical Features
- **React 19** - Latest React features and hooks
- **Vite Build Tool** - Fast development and optimized production builds
- **Tailwind CSS** - Utility-first CSS framework for rapid styling
- **Framer Motion** - Smooth animations and transitions
- **React Hot Toast** - Elegant notification system

### 📧 Contact Integration
- **Web3Forms Integration** - Backend-less contact form
- **Real-time Validation** - Client-side form validation
- **Success/Error Notifications** - User feedback for form submissions

## 🛠️ Tech Stack

- **Frontend Framework:** React 19
- **Build Tool:** Vite
- **Styling:** Tailwind CSS
- **Animations:** Framer Motion
- **Notifications:** React Hot Toast
- **Contact Forms:** Web3Forms API
- **Icons & Assets:** Custom SVG icons and images

## 📂 Project Structure

```
agency-ai/
├── public/
│   └── favicon.ico
├── src/
│   ├── assets/
│   │   └── assets.js          # Asset imports and exports
│   ├── components/
│   │   ├── Navbar.jsx         # Navigation component with theme toggle
│   │   ├── Hero.jsx           # Landing section with animations
│   │   ├── TrustedBy.jsx      # Social proof section
│   │   ├── Services.jsx       # Services overview
│   │   ├── ServiceCard.jsx    # Individual service cards
│   │   ├── OurWork.jsx        # Portfolio/showcase section
│   │   ├── Teams.jsx          # Team members section
│   │   ├── ContactUs.jsx      # Contact form with Web3Forms
│   │   ├── Footer.jsx         # Footer with links
│   │   ├── ThemeToggleBtn.jsx # Theme switching button
│   │   └── Title.jsx          # Reusable title component
│   ├── App.jsx                # Main application component
│   ├── main.jsx               # Application entry point
│   ├── index.css              # Global styles
│   └── App.css                # App-specific styles
├── index.html                 # HTML template
├── vite.config.js             # Vite configuration
├── eslint.config.js           # ESLint configuration
├── package.json               # Dependencies and scripts
└── README.md                  # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/agency-ai.git
   cd agency-ai
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**

   Create a `.env` file in the root directory and add your Web3Forms access key:

   ```env
   VITE_WEB3FORMS_ACCESS_KEY=your_web3forms_access_key_here
   ```

   Get your access key from [Web3Forms](https://web3forms.com/)

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**

   Navigate to `http://localhost:5173` to view the application.

## 📜 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint for code quality

## 🎯 Services Offered

The agency website showcases four main service areas:

1. **Advertising** - Digital advertising solutions
2. **Content Marketing** - Strategic content creation and distribution
3. **Social Media Marketing** - Social media presence and engagement
4. **Software Development** - Custom web and mobile applications

## 🌟 Key Components

### Custom Cursor Animation
Implements a dual-cursor system with a small dot and larger outline that follows mouse movement with smooth easing.

### Theme Management
Persistent light/dark mode toggle using localStorage and CSS custom properties.

### Form Handling
Contact form with validation, API integration, and user feedback through toast notifications.

### Responsive Design
Mobile-first approach with breakpoints for tablet and desktop views.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Mohib Khan**
- Frontend Developer
- Portfolio: [text](https://mohib-khan.vercel.app/)
- LinkedIn: [text](https://www.linkedin.com/in/mohib-khan-615368254/)

## 🙏 Acknowledgments

- This project was learned from [GreatStack Dev](https://www.youtube.com/@GreatStackDev)
- Design inspiration from modern digital agency websites
- Icons and assets from various free resources
- Special thanks to the open-source community

---

**Note:** This is a practice project demonstrating modern React development techniques. Feel free to use it as a reference for your own projects!
