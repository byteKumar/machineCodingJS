# Machine Coding Projects

This repository contains two machine coding implementations demonstrating different UI components and interaction patterns.

## Projects Overview

### 1. Counter/Calculator App (`example1.html`)
A simple counter application with customizable delta values.

**Features:**
- Increment/Decrement counter by a specified delta value
- Customizable delta input field
- Reset functionality
- Clean, centered UI design

### 2. OTP Input Component (`example2.html`)
An OTP (One-Time Password) input component with two different implementation approaches.

**Features:**
- 4-digit OTP input fields
- Two implementation approaches:
  - **Manual Input**: Users type each digit manually with auto-focus progression
  - **Autofilled**: Programmatically fills OTP from a predefined value
- Keyboard navigation support (Tab, Backspace)
- Clean, modern UI design

## OTP Implementation Details

### Approach 1: Manual Input
- Users manually enter each digit of the OTP
- Auto-focus moves to the next input field when a digit is entered
- Backspace navigation moves focus to the previous field when current field is empty
- Provides natural user experience for manual OTP entry

### Approach 2: Autofilled
- OTP is automatically populated from a predefined string (`'4321'`)
- Demonstrates programmatic filling of input fields
- Useful for testing or demo scenarios

## How to Run

1. Clone or download this repository
2. Open any of the HTML files in your web browser:
   - `example1.html` - Counter/Calculator App
   - `example2.html` - OTP Input Component

## Technical Implementation

### Technologies Used
- HTML5
- CSS3 (Flexbox for layout)
- Vanilla JavaScript (DOM manipulation, event handling)

### Key JavaScript Concepts Demonstrated
- Event handling (`addEventListener`)
- DOM manipulation (`querySelector`, `nextElementSibling`, `previousElementSibling`)
- Form input validation and navigation
- String manipulation and iteration
- Keyboard event handling

## File Structure
```
.
├── example1.html    # Counter/Calculator App
├── example2.html    # OTP Input Component
└── README.md        # This file
```

## Features Showcase

### Counter App Features
- ✅ Increment/Decrement functionality
- ✅ Custom delta value input
- ✅ Reset to zero
- ✅ Real-time result display
- ✅ Responsive design

### OTP Component Features
- ✅ 4-digit OTP input
- ✅ Auto-focus on next input
- ✅ Backspace navigation
- ✅ Autofill capability
- ✅ Clean UI design
- ✅ Keyboard accessibility

## Future Enhancements

### Counter App
- Add history of operations
- Support for decimal numbers
- Keyboard shortcuts
- Undo/Redo functionality

### OTP Component
- Variable OTP length configuration
- Input validation (numbers only)
- Copy-paste support
- Timeout functionality
- Integration with backend verification

## Browser Compatibility
- Chrome ✅
- Firefox ✅
- Safari ✅
- Edge ✅

## License
This project is open source and available under the MIT License.