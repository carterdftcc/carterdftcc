# Hi, I'm Darryl Carter 👋

# Security+ PrepBot MVP

##1 What It Does
An AI-powered chatbot that helps students prepare for the CompTIA Security+ (SY0-701) certification exam. It provides instant answers to security concepts with official objective citations, offers practice quizzes with 100 questions, and uses intelligent spaced repetition to help students master difficult topics.

##2 How to Use/What it was supposed to do
1. **Ask Questions**: Type any Security+ topic (e.g., "What is MFA?") and get instant answers with official exam objective references
2. **Take Quizzes**: Click "Test Me" to start a 10-question practice quiz
3. **Track Progress**: Click "📊 Stats" to view your mastery progress, accuracy, and areas needing improvement
4. **Master Topics**: Answer questions correctly 3 times in a row to permanently master them and remove them from rotation
5. **Focus on Weak Areas**: Missed questions automatically appear in your next quiz

##3 How far did I get
It turns out that I keep trying to do two things instead of one. When creating this agent, I wanted to use it as a trainer and allow the user to ask question and fill in the gaps in their knowlege. The second part was to create test bank based on the domains in CompTIA Security+. The more I read about it, I discover I wanted to use Retrieval-Augmented Generation. I had so many note, pdf, and copies of every question I could get my hands on. Then I was awaken to the reality of need to move to a paid version to accomodate the volume of information I wanted to upload.

It works with the 220 question that I was able to upload into Claude. The issue that I created what after putting in the initial topics as a basis for asking questions, I overwhelmed my thread with upload different sets of question. 
I was able to run this locally using Podman Desktop by create a container to act as my webserver. My downfall was in the create a a container that could adequately host Ollama to carry out the AI portion of the project. Because of my limited resource and the lack of a compatible GPU, the response times were just too slow to test. I believe that if I were willing to invest in more hardware, I would have been able to bring this project into reality. 

The links shown below are two different iterations of adding question into Claude. As it stands I would give it 50% for the testbank, but only about 10% to 15% on the interactive portion. So overall, it is about 65% of where I want it to be. 
<img width="897" height="686" alt="image" src="https://github.com/user-attachments/assets/6ba2b386-c6fe-492a-b5b1-83f785c725fe" />

<img width="857" height="662" alt="image" src="https://github.com/user-attachments/assets/15edcb3d-98e1-47a3-be78-52050d24fcef" />

<img width="888" height="668" alt="image" src="https://github.com/user-attachments/assets/d5c4cf4e-fc44-4157-9be0-ea9f017608ea" />


## Try It Yourself
🔗 [Live Demo](https://claude.ai/public/artifacts/4ee20eeb-4bce-4c7f-aa0e-4d41562cccd6)

I updated this again. I increased the number of questions to 220. 

[Update Live Demo](https://claude.ai/public/artifacts/c4684d89-6a26-4b7f-b18a-5f1d89bd9325)

> **Note**: Your progress is saved in your browser. Clear browser data will reset your stats.

##4 What AI tools did you use. 
I started with Gemini because I was fascinated with the Storybook Gem. I bounce between Notion and ChatGPT for most of my research and finally settle on Claude for a working prototpye.



**Built with ❤️ for Security+ exam preparation**



