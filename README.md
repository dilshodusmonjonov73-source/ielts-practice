# IELTS Practice

An IELTS practice platform that simulates the real exam experience. Take full-length Reading and Listening tests under timed conditions, get instant grading, and review your mistakes.

> **Status:** In development. Reading and Listening modules are being built first; Writing and Speaking are planned.

## Features

### Reading
- Full tests with **40 questions** and a countdown timer
- Original passages (first topic: ecology)
- Questions paraphrased at real IELTS difficulty, ordered by their position in the passage
- Text highlighting while you read
- **Automatic grading** that shows exactly which answers were wrong

### Listening
- Audio player at the top, questions below
- British-accent audio
- Full **transcript** after the test so you can check your mistakes

### Planned
- Writing practice (Task 1 and Task 2)
- Speaking practice
- Standalone desktop version (CD-style, with a main menu)

## Screenshots

<!-- Add screenshots here -->
| Main menu | Reading test | Results |
|-----------|--------------|---------|
| ![menu](docs/menu.png) | ![reading](docs/reading.png) | ![results](docs/results.png) |

## Getting Started

```bash
# Clone the repository
git clone https://github.com/<your-username>/ielts-practice.git
cd ielts-practice

# Install dependencies and run (replace with your actual commands)
# npm install
# npm start
```

## Project Structure

```
ielts-practice/
├── reading/       # Reading passages, questions, answer keys
├── listening/     # Audio files, questions, transcripts
├── docs/          # Screenshots and documentation
└── README.md
```

## How a Test Works

1. Choose a module (Reading or Listening) from the main menu.
2. Start a test. The timer begins.
3. Answer all questions.
4. Submit to see your score, the correct answers, and where you made mistakes.

## Roadmap

- [x] Reading test format (40 questions, timer, grading)
- [ ] Listening module with transcripts
- [ ] More Reading passages and topics
- [ ] Writing module
- [ ] Speaking module
- [ ] Online version

## Contributing

Suggestions and bug reports are welcome. Open an issue or submit a pull request.

## Author

**Dilshod**, cyber security student, Uzbekistan
GitHub: [@your-username](https://github.com/your-username)

## License

MIT License. See [LICENSE](LICENSE) for details.
