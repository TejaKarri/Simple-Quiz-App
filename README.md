# Simple-Quiz-App

This quiz app allows you to add multiple questions with four answer choices for each question. When you select an answer, the answer button's background color will turn green if it is the correct answer, and red if it is the wrong answer. Once you select an answer, you cannot change it, but you can proceed to the next question.

## Displaying Quiz Score or Result

When the user submits the answer to the last question and clicks the next button, the app will display the quiz score.

### How to Add More Questions

You can add more questions to the quiz by following the format provided below:

```javascript
const questions = [
    {
        question: "Which is the largest animal in the world?",
        answers: [
            { text: "Shark", correct: false },
            { text: "Blue Whale", correct: true },
            { text: "Elephant", correct: false },
            { text: "Giraffe", correct: false },
        ]
    },
    // Add more questions here
];
```
The End
