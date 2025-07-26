# Learners-Compass

Learner’s Compass Dashboard

1. My Idea for the Learner’s Compass Dashboard
The current dashboards used in most LMS and EdTech platforms are not designed with the learner’s career growth in mind. They mostly track course completion or offer limited insights into how the learning connects with career outcomes. The Learner’s Compass aims to solve this by offering a career-focused, skill-oriented dashboard that helps learners like Ananya Sharma see where they stand in their career preparation journey.
Main Concept
The Learner’s Compass is a personalized dashboard that tracks a learner’s skills, projects, certifications, and career goals in one place. It provides real-time skill analysis, highlights the gaps between current knowledge and target job requirements, and offers actionable suggestions like courses.
It is designed to be interactive and dynamic. In the settings, Ananya can connect her GitHub, Coursera, LinkedIn, and Udemy accounts. Based on the data fetched from these sources, the dashboard will automatically update her skills, certifications, and projects. This digital footprint will help her visualize her current progress and align it with the roadmap of a Machine Learning Engineer or any other related career path.













Key Features
Skills Map
 A visual representation that shows Ananya’s current technical skills (like Python, SQL, TensorFlow) and compares them to the requirements for a Machine Learning Engineer role. This gives her clarity on where she stands.


Skill Gap Finder
 This section shows the difference between her existing skills and the skills required for her dream job. It highlights high-priority gaps and recommends courses, articles, or project ideas to close them.


Career Path Explorer
 An interactive feature that allows Ananya to explore other related roles like Data Scientist or MLOps Engineer. It shows how small changes in skills or certifications can open up new opportunities.


Learning Progress Feed
 A timeline that doesn’t just track completed courses but also logs skills gained from projects. For example, if she used Pandas and Matplotlib in a Sentiment Analysis project, it will be recorded here.


Project Showcase
 Projects from GitHub will be automatically fetched and displayed along with the relevant skills and tools used. This helps recruiters and mentors see practical applications of her knowledge.


Learning Quiz
 Based on her recent learning and skill level, a basic quiz can be generated using ChatGPT’s API. This keeps her active and helps with knowledge retention.


Notes Section
 A space where Ananya can write and save important notes she wants to remember from any course or project.


Calendar Integration
 Integration with Google Calendar to track upcoming deadlines, events, interviews, and keep reminders. It will also show her scheduled learning sessions or quizzes.


Mentorship and Feedback
 A section where Product Owners, mentors, or career coaches can leave comments or suggest actions. Ananya can also request a session if she needs support.


Badges and Motivation
 Inspired by platforms like LeetCode, badges will be awarded for achieving skill milestones. This keeps learners motivated by gamifying progress.


AI-Powered Insights
 The dashboard includes an AI assistant trained to guide Ananya. It will help her understand her strengths, give customized advice, and explain what’s needed to reach her goals.


Skill Analysis Tool
 This feature will analyze how far Ananya is from her target job in terms of skills, projects, and certifications. It gives a clear percentage or visual indicator to track her journey.











Tech & Data Plan

For the frontend, I will use React.js because it allows for a responsive and modular dashboard. With React, it’s easier to build interactive components like the Skills Map, Career Path Explorer, and real-time Skill Gap charts with this, we can also use bootstrap or tailwindcss for prebuilt component
For backend, I will use Node.js with Express.js to build REST APIs and manage user data, career roadmaps, and course connections. Node.js is lightweight and works well for handling multiple data sources. For the AI features like generating quizzes or giving career advice I will use ChatGPT API to provide smart, personalized recommendations
For the database, I will use MongoDB. It’s flexible and fits well for storing user-specific data like skill assessments, project details, notes, certifications, and learning progress.
For authentication, I will use Firebase Authentication. It allows users to log in securely using email, Google, or GitHub, it gives us pre-built backend.
The dashboard will integrate with:
GitHub API – to fetch Ananya’s recent projects and repositories.
Google Calendar API – to schedule learning sessions and send reminders.
ChatGPT API – to create personalized quizzes and suggestions based on learning activity.

Data Sources

In the settings section of the dashboard, there will be options for Ananya to connect her GitHub, Coursera, Udemy, and other learning platforms. Once she gives access, Learner’s Compass will use their official APIs to fetch the required data — like her completed courses, certifications, and public projects. This will help us automatically update her skills, learning timeline, and project showcase without her needing to add everything manually. All access will be with her permission and fully secure.

