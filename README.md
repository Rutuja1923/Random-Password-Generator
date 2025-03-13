# 🔐 Random Password Generator  

A **React-based** random password generator that allows users to generate secure passwords with custom options for length, numbers, and special characters.  

## Features  
- Generate random passwords  
- Set password length (6 to 25)  
- Include numbers and special characters  
- Copy password to clipboard  
- Visual feedback when password is copied  

## Technologies Used  
- **React.js** (Hooks: `useState`, `useCallback`, `useEffect`, `useRef`)  
- **Tailwind CSS** (for styling)  

## Preview  
![Password Generator Preview](https://raw.githubusercontent.com/Rutuja1923/Random-Password-Generator/main/public/screenshot.png) 

## Installation & Setup  

1. Clone the repository:  
```bash
git clone https://github.com/Rutuja1923/Random-Password-Generator.git
```
  
2. Navigate to the project folder:  
```bash
cd Random-Password-Generator
```

3. Install dependencies:  
```bash
npm install
```

4. Start the development server:  
```bash
npm start
```

The app will be available at **`http://localhost:3000`**   

## Usage  
1. Adjust the **password length** using the slider.  
2. Toggle **numbers** and **special characters** to include them in the password.  
3. Click the **copy button** to copy the password to the clipboard.  
4. The button will temporarily change to **"Copied"** with a ✔ icon for 1 second.  

## Hooks Used  
- **`useState`** → Manage length, number inclusion, character inclusion, and password state.  
- **`useCallback`** → Optimize functions (`passwordGenerator`, `copyPasswordToClipboard`).  
- **`useEffect`** → Automatically generate a new password when settings change.  
- **`useRef`** → Handle the input selection for copying passwords.  