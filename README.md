# 📝 Todo App

A simple, clean, and efficient todo list application built with vanilla JavaScript. This app helps you organize your tasks and boost your productivity.

![Todo App](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## 🌟 Features

- ✅ **Add Tasks**: Quickly add new tasks to your todo list
- ✏️ **Edit Tasks**: Update existing tasks inline
- ✔️ **Mark as Complete**: Toggle tasks between complete and incomplete states
- 🗑️ **Delete Tasks**: Remove tasks you no longer need
- 💾 **Local Storage**: Your tasks are automatically saved in the browser
- 📱 **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- 🎨 **Clean UI**: Intuitive and user-friendly interface

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with flexbox/grid layouts
- **JavaScript (ES6+)**: Core application logic
- **Local Storage API**: Client-side data persistence

## 🚀 Getting Started

### Prerequisites

You only need a modern web browser to run this application. No additional dependencies or installations required!

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Sans2004bid/todo-app.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd todo-app
   ```

3. **Open in browser**
   - Simply open the `index.html` file in your preferred web browser
   - Or use a local development server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (if you have http-server installed)
     npx http-server
     ```
   - Then navigate to `http://localhost:8000` in your browser

## 📖 Usage

1. **Adding a Task**
   - Type your task in the input field at the top
   - Press Enter or click the "Add" button
   - Your task will appear in the list below

2. **Completing a Task**
   - Click on the checkbox next to a task to mark it as complete
   - Completed tasks will be visually distinguished (usually with strikethrough text)

3. **Editing a Task**
   - Click on the task text to edit it
   - Make your changes and press Enter or click outside to save

4. **Deleting a Task**
   - Click the delete button (usually an "X" or trash icon) next to the task
   - The task will be permanently removed

5. **Persistence**
   - All your tasks are automatically saved to your browser's local storage
   - Your tasks will remain even after closing and reopening the browser

## 📁 Project Structure

```
todo-app/
│
├── index.html          # Main HTML file
├── style.css           # Styling and layout
├── script.js           # Application logic
└── README.md           # Project documentation
```

## 🎯 Key Features Explained

### Local Storage Integration
The app uses the browser's Local Storage API to persist tasks between sessions. This means your data stays on your device and doesn't require a backend server.

### Responsive Design
The application is fully responsive and adapts to different screen sizes, providing an optimal experience on:
- Desktop computers
- Tablets
- Mobile phones

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

## 📝 Future Enhancements

Potential features for future versions:
- [ ] Task categories/tags
- [ ] Due dates and reminders
- [ ] Task priority levels
- [ ] Dark mode toggle
- [ ] Export tasks to JSON/CSV
- [ ] Search and filter functionality
- [ ] Task statistics and analytics

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👤 Author

**Sans2004bid**
- GitHub: [@Sans2004bid](https://github.com/Sans2004bid)

## 🙏 Acknowledgments

- Inspired by various todo list applications
- Built as a learning project to practice vanilla JavaScript
- Thanks to the open-source community for inspiration and resources

---

⭐ If you found this project helpful, please consider giving it a star!
