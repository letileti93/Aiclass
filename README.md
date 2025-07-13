# MyFarm 

A React Native application that displays a student identification card similar to the NSW driver license in Australia. The app features a professional design with student information, photo, and interactive elements.

## Features

- **Professional ID Card Design**: Styled similar to NSW driver license with clean, official appearance
- **Student Information Display**: Shows full name, student ID, course, expiry date, and status
- **Photo Section**: Dedicated area for student photo with professional border
- **Description Section**: Detailed student description and background information
- **Interactive Welcome Button**: Generates an alert with welcome message when pressed
- **Responsive Design**: Optimized for mobile devices with proper spacing and typography
- **Modern UI**: Clean, professional styling using StyleSheet

## Screenshots

The app displays:
- Header with "STUDENT IDENTIFICATION CARD" and university name
- Student photo in a bordered container
- Student details (name, ID, course, expiry, status)
- Description section with student background
- Footer with ownership and validity information
- Welcome button for interaction

## Installation

1. **Install Dependencies**:
   ```bash
   npm install
   ```

2. **Start the Development Server**:
   ```bash
   npm start
   ```

3. **Run on Device/Simulator**:
   - Press `i` for iOS simulator
   - Press `a` for Android emulator
   - Scan QR code with Expo Go app on your phone

## Project Structure

```
student-id-card/
├── app/
│   ├── _layout.js        # Root layout for Expo Router
│   └── index.js          # Main application component
├── package.json          # Dependencies and scripts
├── app.json             # Expo configuration
├── babel.config.js      # Babel configuration
└── README.md            # Project documentation
```

## Technologies Used

- **React Native**: Cross-platform mobile development
- **Expo SDK 53.0.0**: Latest development platform and tools
- **Expo Router**: File-based routing system
- **StyleSheet**: CSS-like styling for React Native components
- **Alert API**: For displaying welcome message

## Customization

You can easily customize the student information by modifying the values in `app/index.js`:

- Student name and details
- Photo URL (currently using placeholder)
- Course information
- Description text
- Expiry date and status

## Styling

The app uses a comprehensive StyleSheet with:
- NSW driver license-inspired color scheme (#0066CC blue)
- Professional typography with proper letter spacing
- Shadow effects for depth
- Responsive layout with flexbox
- Clean borders and spacing

## SDK 53.0.0 Features

This project has been upgraded to Expo SDK 53.0.0, which includes:
- **Expo Router**: File-based routing for better navigation
- **Enhanced Performance**: Improved app performance and stability
- **Latest React Native**: Version 0.76.3 with latest features
- **Better TypeScript Support**: Enhanced development experience
- **Improved Development Tools**: Better debugging and development workflow

## License

This project is for educational purposes and demonstrates React Native development concepts. 