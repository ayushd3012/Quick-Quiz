# Interactive HTML & CSS Quiz

## Overview
This is an interactive quiz application built with HTML, CSS, and JavaScript. It tests knowledge on HTML and CSS fundamentals with 10 multiple-choice questions and provides detailed scoring feedback.

## Features

### Quiz Questions
- 10 multiple-choice questions covering HTML and CSS topics
- Topics include:
  - HTML basics and tags
  - CSS properties and styling
  - Best practices and standards

### Scoring System
- **Correct Answer:** +4 points
- **Wrong Answer:** -1 point
- **Unanswered Question:** No points (0)

### Results Display
After submitting the quiz, you'll see:
- **Your Score:** Total calculated score
- **Correct Answers:** Number of correctly answered questions
- **Wrong Answers:** Number of incorrectly answered questions
- **Unattemted Questions:** Number of questions left blank

## How to Use

1. Open `Quiz_1.html` in any modern web browser
2. Read each question carefully
3. Select one answer option for each question (optional - you can skip questions)
4. Click the **"Submit Quiz"** button at the bottom
5. View your detailed results including:
   - Total score
   - Breakdown of correct, wrong, and unanswered questions

## Technical Details

### HTML Structure
- Semantic HTML5 structure
- Form-based question layout with radio buttons
- Responsive container design

### Styling
- Clean, modern CSS styling
- Light slate gray background
- White form container with subtle shadow
- Mobile-friendly responsive design
- Green submit button with hover effect

### JavaScript Functionality
- Form submission handling
- Real-time score calculation
- Automatic tracking of:
  - Correct answers
  - Wrong answers
  - Unanswered questions
- Dynamic result display with formatted HTML output

## Browser Compatibility
Works in all modern web browsers:
- Chrome/Chromium
- Firefox
- Safari
- Edge
- Opera

## File Structure
```
Quiz_1.html
├── HTML Structure
│   └── 10 Quiz Questions with options
├── CSS Styling
│   └── Layout and visual design
└── JavaScript
    └── Quiz logic and scoring
```

## Notes
- No submit button is required on individual questions
- You can navigate between questions before submitting
- All calculations are done locally in your browser
- No data is saved or sent to any server
