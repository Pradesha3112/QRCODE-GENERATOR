# Advanced QR Code Generator

## Overview

This is a comprehensive QR code generator web application that allows users to create customized QR codes for various purposes including URLs, text, email, SMS, WiFi credentials, and contact information (vCard).

## Features

- **Multiple QR Code Types**:
  - Text
  - URL
  - Email (with subject and body)
  - SMS (with phone number and message)
  - WiFi credentials (with encryption options)
  - Contact information (vCard format)

- **Customization Options**:
  - Adjustable size (100px to 500px)
  - Custom foreground and background colors
  - Error correction levels (L, M, Q, H)
  - Margin control
  - Logo/image overlay with transparency option

- **User Experience**:
  - Responsive design that works on mobile and desktop
  - Dark/light mode toggle
  - Tab-based interface for different QR code types
  - Preview of color selections

- **Output Options**:
  - Download as PNG image
  - Copy to clipboard (where supported by browser)

## Technical Details

- Built with HTML, CSS, and vanilla JavaScript
- Uses the [qrcode.js](https://github.com/soldair/node-qrcode) library for QR generation
- No backend required - works entirely in the browser
- Responsive design using CSS Grid and Flexbox
- Dark mode support with CSS variables
- File API for logo/image handling
- Clipboard API for copying QR codes

## How to Use

1. Select the type of QR code you want to generate using the tabs
2. Fill in the required information for that QR code type
3. Customize the appearance using the options panel
4. Click "Generate QR Code"
5. Download or copy the generated QR code

## Browser Support

The application should work in all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

Note: The "Copy to Clipboard" feature may not work in some browsers due to security restrictions.

## License

This project is open source and available for anyone to use. The qrcode.js library is licensed under MIT.
