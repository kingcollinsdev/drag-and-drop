# Project Name

The project consists of a smiple kanban board that helps a user manage their tasks effectively.


## Screenshots

<img width="1352" height="529" alt="ScreenShot Tool -20260428152348" src="https://github.com/user-attachments/assets/c86d8f3a-b7ef-4f8c-a4e9-ad979900d980" />


## Features

- Main Feature - A user can drag and drop tasks from the three sections.
- Responsive design
- Cross-browser compatible

## Technologies Used

- **HTML5** - Structure and content
- **CSS3** - Styling and layout
- **JavaScript** - Interactivity and functionality

## Installation

1. Clone the repository:
```bash
git@github.com:kingcollinsdev/drag-and-drop.git
```

2. Navigate to the project directory:
```bash
cd drag-and-drop
```

3. Open `index.html` in your browser or use a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (http-server)
npx http-server
```

## Usage

This allows the drop location to know which element is being moved when you release it:

```javascript
// Example code snippet
 e.dataTransfer.setData("text/plain", this.id);
```

## Project Structure

```
project-name/
│
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Main stylesheet
├── js/
│   └── script.js       # Main JavaScript file
├── images/             # Image assets
└── README.md           # Project documentation
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contact

Your Name - Collins Wachira - collinswachira2004@gmail.com

Project Link: [https://drag-and-drop-ebon.vercel.app/](https://github.com/kingcollinsdev/drag-and-drop.git)

## Acknowledgments

- Inspiration - https://www.youtube.com/watch?v=kAiX0itnonM&t=12274s
