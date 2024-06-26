# Quiz

This is a web-based quiz application that offers quizzes on various programming languages including HTML, Python, C++, and C. The quizzes are presented in a card format and can be accessed via modal pop-ups. The application utilizes Bootstrap for styling and layout.

https://github.com/InsaneSamie/Quiz/assets/101932418/236a741c-5014-4146-a863-69ec2092ad5f

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Dependencies](#dependencies)
- [Contributing](#contributing)

## Features

- Responsive design using Bootstrap.
- Quizzes available for HTML, Python, C++, and C.
- Quizzes are accessible via modal pop-ups on larger screens.
- Direct navigation to quiz pages on smaller screens.

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/quiz-web-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd quiz-web-app
   ```

3. Ensure you have an internet connection to load Bootstrap and jQuery from their CDNs.

## Usage

1. Open the `index.html` file in your web browser.

2. On larger screens, click on the "Take Quiz" button to open the quiz in a modal pop-up.

3. On smaller screens, clicking the "Take Quiz" button will navigate directly to the quiz page.

## File Structure

```
quiz-web-app/
├── quizes/
│   ├── c_quiz.html
│   ├── cpp_quiz.html
│   ├── html_quiz.html
│   └── python_quiz.html
├── images/
│   ├── web.png
│   ├── python.png
│   ├── c++.png
│   └── c.png
├── index.html
└── README.md
```

- `index.html`: The main HTML file containing the structure of the web application.
- `quizes/`: Directory containing individual quiz HTML files.
- `images/`: Directory containing images used in the web application.
- `README.md`: The file you are currently reading.

## Dependencies

- [Bootstrap 5.1.1](https://getbootstrap.com/)
- [jQuery 3.2.1](https://jquery.com/)
- [Popper.js](https://popper.js.org/)

These dependencies are included via CDN links in the `index.html` file.

## Contributing

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes with a descriptive message.
4. Push your changes to the branch.
5. Open a Pull Request to the main branch.

---

This README file provides a comprehensive guide to understanding, installing, and using the Quiz. If you have any questions or suggestions, please feel free to open an issue or contact the repository owner.
