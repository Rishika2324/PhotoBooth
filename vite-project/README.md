#  MonkeyKing Booth

A modern, interactive photo booth web application built with React and Vite. Capture fun photos with various filters and download your photo strips!

##  Features

-  **Webcam Integration** - Real-time camera access for photo capture
- **Multiple Filters** - Choose from 7 different photo filters:
  - 90s Vintage
  - 2000s Retro
  - Noir (Black & White)
  - Fisheye
  - Rainbow
  - Glitch
  - Crosshatch
-  **Photo Strip Generation** - Automatic 3-photo strip creation with countdown
-  **Download Photos** - Save your photo strips as JPEG images
-  **Interactive UI** - Coin-operated booth interface with curtain animation
-  **Smooth Animations** - Powered by Framer Motion

##  Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- A webcam (for photo capture)

### Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd photobooth-main/vite-project
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

##  Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

##  Technologies Used

- **React** - UI library
- **Vite** - Build tool and dev server
- **Framer Motion** - Animation library
- **react-webcam** - Webcam integration
- **html2canvas** - Canvas to image conversion
- **CSS3** - Styling and animations

##  How to Use

1. **Start the app** - Click "INSERT COIN HERE" to begin
2. **Activate Camera** - Click the coin to open the curtain and access the photo studio
3. **Choose Filter** - Select your preferred filter from the filter bar
4. **Take Photos** - Click the 📸 button to start the 3-photo sequence
5. **View Results** - See your photo strip with date stamp
6. **Download** - Click "Download Strip" to save your photos

##  Project Structure

```
vite-project/
├── public/
│   └── images/          # Background images
├── src/
│   ├── components/
│   │   ├── Hero.jsx     # Main container
│   │   ├── PhotoBooth.jsx    # Coin-operated booth interface
│   │   └── PhotoStudio.jsx   # Photo capture and filter studio
│   ├── App.jsx          # Root component
│   └── main.jsx         # Entry point
└── package.json
```

##  Customization

You can customize the app by:
- Modifying filter styles in `PhotoStudio.css`
- Changing booth appearance in `PhotoBooth.css`
- Adding new filters in `PhotoStudio.jsx`
- Updating colors and themes in CSS files

##  License

This project is open source and available under the MIT License.

##  Contributing

Contributions, issues, and feature requests are welcome!

## Author
Rishika Mandlay
Made with ❤️ using React and Vite
