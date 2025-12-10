# Hi, I'm Darryl Carter 👋

## About Me
Currently taking CSC-113 AI Fundamentals and learning to collaborate with AI tools!

## My Foo 🎯
I am trying to get underserved communities excited about STEM. Rather than spending time rotting on social media, I want them to leverage STEM as an investment in their future.

## Currently Learning
- 🤖 AI collaboration and prompt engineering
- 🐙 GitHub workflows and version control
- 💡 Building my first AI assistants

## Fun Fact
I am learning 3D modeling in Tinkercad so I can create something interesting.

## Find Me
- 📫 Right here on GitHub!


# Security+ PrepBot MVP

## What It Does
An AI-powered chatbot that helps students prepare for the CompTIA Security+ (SY0-701) certification exam. It provides instant answers to security concepts with official objective citations, offers practice quizzes with 100 questions, and uses intelligent spaced repetition to help students master difficult topics.

## How to Use
1. **Ask Questions**: Type any Security+ topic (e.g., "What is MFA?") and get instant answers with official exam objective references
2. **Take Quizzes**: Click "Test Me" to start a 10-question practice quiz
3. **Track Progress**: Click "📊 Stats" to view your mastery progress, accuracy, and areas needing improvement
4. **Master Topics**: Answer questions correctly 3 times in a row to permanently master them and remove them from rotation
5. **Focus on Weak Areas**: Missed questions automatically appear in your next quiz

## Features Implemented
- **Interactive Chatbot**: Ask questions about 10 core Security+ concepts with instant answers
- **100-Question Quiz Bank**: Comprehensive practice questions covering all Security+ exam domains
- **Smart Question Selection**: 
  - Automatically prioritizes recently missed questions in next quiz
  - Excludes mastered questions (3+ consecutive correct answers)
  - Random selection from remaining unmastered questions
- **Progress Tracking**: 
  - Real-time statistics dashboard
  - Question mastery tracking (shows X/3 progress toward mastery)
  - Overall accuracy and coverage metrics
  - Identifies questions needing more practice
- **Persistent Storage**: All progress saved locally using browser localStorage
- **Responsive Design**: Mobile-friendly interface that works on all devices
- **Visual Feedback**: Color-coded answers (green = correct, red = incorrect) with explanations

## Try It Yourself
🔗 [Live Demo](https://claude.ai/public/artifacts/4ee20eeb-4bce-4c7f-aa0e-4d41562cccd6)

I updated this again. I increased the number of questions to 200. 
Update Live Demo

> **Note**: Your progress is saved in your browser. Clear browser data will reset your stats.

## What I Learned
Building this project taught me:
- **Smart Algorithm Design**: Implementing spaced repetition and adaptive quiz selection based on user performance
- **State Management**: Tracking complex user data (attempts, mastery status, consecutive streaks) across sessions
- **User Experience Design**: Creating intuitive feedback systems that motivate continued learning
- **localStorage API**: Persisting user data locally without a backend database
- **Responsive Design**: Building a mobile-first interface that works seamlessly across devices
- **Error Handling**: Gracefully managing edge cases like "all questions mastered" or empty statistics

## Technical Highlights
- **Pure Vanilla JavaScript**: No frameworks or libraries - just HTML, CSS, and JS
- **Single File Application**: Entire app in one HTML file for easy deployment
- **Intelligent Tracking System**: 
  - Tracks consecutive correct answers (not just total correct)
  - Differentiates between "new", "attempted", and "mastered" questions
  - Automatically adjusts quiz difficulty based on performance
- **Data Structures**: Used Sets and Arrays for efficient question tracking and filtering

## Future Improvements
- **Expanded Question Bank**: Add all 500+ practice questions covering every Security+ objective
- **Performance Analytics**: Add charts showing progress over time and weak objective domains
- **Study Mode**: Add flashcard-style learning for definitions and concepts
- **Export Progress**: Allow users to download their statistics and mastered questions list
- **Custom Quiz Settings**: Let users choose quiz length, specific domains, or difficulty levels
- **Timed Quizzes**: Add optional timer to simulate real exam conditions
- **Explanation Enhancement**: Add detailed explanations for each answer with links to study resources
- **Multi-User Support**: Add user accounts to sync progress across devices

## Browser Compatibility
Tested and working on:
- ✅ Chrome/Edge (v90+)
- ✅ Firefox (v88+)
- ✅ Safari (v14+)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Setup Instructions
1. Clone this repository
2. Open `index.html` in any modern web browser
3. No build process or dependencies required!

---

**Built with ❤️ for Security+ exam preparation**



