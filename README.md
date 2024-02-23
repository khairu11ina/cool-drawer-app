# 🎨 **Cool Drawer App**

## 📃 Table of Contents

- [Description](#description)
- [Technologies](#technologies)
- [Features](#features)
- [Live Demo](#live-demo)
- [Running the Project](#running-the-project)
- [Misc](#misc)
  - [Keyboard Shortcuts](#keyboard-shortcuts)
  - [Process](#process)

## 📝 Description

An Excalidraw clone with React and TypeScript. Rough.js is used for the sketchy, hand-drawn style. I built the side project for learning purposes. The app is not responsive. I mainly focused on the functionalities since I already have plenty of projects that are responsive.

## 📦 Technologies

- `Vite`
- `React`
- `TypeScript`
- `Rough.js`
- `CSS`
- `Vitest`
- `Cypress`
- `Testing Library`

## 🦄 Features

Here's what you can do with Cool Drawer App:

- **Choose a Tool**: You have pencils, lines, rectangles, and text tools. Pick one and start creating.

- **Draw and Move**: Click and drag on the canvas to draw. To move something, select it and drag it to a new spot. Also, resize elements by dragging the corners. Resizing only works on rectangles or lines.

- **Edit Text**: Click on the canvas and start typing to add text to your drawings. You can also edit existing text.

- **Zoom**: Use Ctrl + Scroll or click on the buttons to zoom in for detail or out to see the whole picture.

- **Pan**: Hold the Space bar and drag or use the middle mouse button to move around the whiteboard canvas.

## Live Demo

Check out the live demo of app [here]().

## 🚀 Running the Project

To run the project in your local environment, follow these steps:

1. Clone the repository to your local machine.
2. Run `npm install` or `yarn` in the project directory to install the required dependencies.
3. Run `npm run start` or `yarn start` to get the project started.
4. Open [http://localhost:5173](http://localhost:5173) (or the address shown in your console) in your web browser to view the app.

## 📦 Misc

### 🎯 Keyboard Shortcuts

Speed up your work with these shortcuts:

- **Canvas Navigation**: Press the Space bar and drag or use the middle mouse button.
- **Undo**: Ctrl + Z.
- **Redo**: Ctrl + Y or Ctrl + Shift + Z.
- **Zoom In**: Ctrl + Plus.
- **Zoom Out**: Ctrl + Minus.

### 👩🏽‍🍳 Process

I started by rendering a canvas with rough.js to create the base for all the drawings. Then, I focused on drawing on the canvas, allowing users to make lines, rectangles, and other shapes.

Next, I made sure users could move elements around. This was important for adjusting drawings. After that, I added the ability to resize elements to give more control over the shapes.

To make sure mistakes could be fixed, I implemented undo and redo features. I also added freehand drawing for a more natural sketching experience and a text tool to label or note on the canvas.

To navigate larger drawings, I put in pan and zoom tools. With everything functioning, I designed the whole UI to make it user-friendly and appealing.

Finally, I added testing with Cypress and Testing Library. I conducted end-to-end tests on drawing and manipulating text, lines, rectangles, and freehand drawings to make sure everything worked smoothly.

Along the way, while building everything, I took notes on what I've learned so I don't miss out on it. I also documented the behind-the-scenes processes every time a feature was added.

This way, I understood what I've built. The funny thing is, as soon as I started to document what happened behind the scenes and the features I've added, it made me realize that we fully understand something once we've actually taken a step back, thought about it, and documented what we've done. I think this is a good practice to follow when learning something new.
