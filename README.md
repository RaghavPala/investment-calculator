# 💰 Investment Calculator

A modern, responsive Angular web application that helps users calculate and visualize the growth of their investments over time. Built with Angular 18 and featuring real-time calculations with an intuitive user interface.

## 🌟 Features

- **💡 Real-time Calculations**: Instant investment projections as you type
- **📊 Comprehensive Results**: Year-by-year breakdown showing:
  - Investment value at end of each year
  - Annual interest earned
  - Total accumulated interest
  - Total amount invested
- **💰 Financial Inputs**:
  - Initial investment amount
  - Annual investment contributions
  - Expected annual return rate (%)
  - Investment duration (years)
- **🎨 Modern UI**: Clean, responsive design with professional styling
- **📱 Mobile Friendly**: Fully responsive across all device sizes
- **⚡ High Performance**: Built with Angular's latest features and optimizations

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** (v18.0 or higher) - [Download here](https://nodejs.org/)
- **npm** (comes with Node.js) or **yarn**
- **Angular CLI** (optional but recommended): `npm install -g @angular/cli`

## 🛠️ Tech Stack

- **Frontend Framework**: Angular 18
- **Language**: TypeScript
- **Styling**: CSS3 with custom responsive design
- **Forms**: Angular Reactive Forms with two-way data binding
- **Build Tool**: Angular CLI with Webpack
- **Package Manager**: npm

## 📦 Installation & Setup

1. **Clone the repository**

   ```bash
   git clone <your-repository-url>
   cd investment-calculator
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the development server**

   ```bash
   npm start
   # or
   ng serve
   ```

4. **Open your browser**
   Navigate to `http://localhost:4200`

The application will automatically reload when you make changes to the source files.

## 🏗️ Project Structure

```
src/
├── app/
│   ├── header/                 # Header component
│   ├── user-input/            # Investment input form
│   ├── investment-results/    # Results display component
│   ├── app.component.*        # Root component
│   └── investment-input.model.ts # Data models
├── assets/                    # Static assets
├── styles.css                # Global styles
└── index.html                # Main HTML file
```

## � Available Scripts

- `npm start` - Start development server
- `npm run build` - Build for production
- `npm run build --configuration production` - Optimized production build
- `npm test` - Run unit tests
- `npm run watch` - Build and watch for changes

## 🚀 Deployment

### Production Build

```bash
npm run build --configuration production
```

The build artifacts will be stored in the `dist/` directory.

### Deploy to Netlify/Vercel

1. Build the project: `npm run build --configuration production`
2. Upload the `dist/investment-calculator` folder to your hosting service

### Deploy to GitHub Pages

```bash
ng add angular-cli-ghpages
ng deploy --base-href=/investment-calculator/
```

## 🎯 Usage

1. **Enter your investment details**:

   - Initial investment amount
   - How much you plan to invest annually
   - Expected annual return rate (as a percentage)
   - Investment time horizon in years

2. **Click "Calculate"** to see your investment projection

3. **Review the results table** showing year-by-year breakdown of your investment growth

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🐛 Issues & Support

If you encounter any issues or have questions, please [open an issue](../../issues) on GitHub.

## 🙏 Acknowledgments

- Built with [Angular](https://angular.io/)
- Icons and design inspiration from modern financial applications
- Thanks to the Angular community for excellent documentation and resources

---

⭐ **If you found this project helpful, please give it a star!**
