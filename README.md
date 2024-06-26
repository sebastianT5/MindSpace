## Inspiration
MindSpace was inspired by the need to address teenage mental health issues, fueled by my struggles to find someone to talk to and the limitations of chatGPT's lengthy responses. I aimed to create a tech-psychology solution for immediate support and a safe space for teens to express themselves.

## What it does
MindSpace is a mobile-friendly web app designed to support teenage mental well-being. It features an AI-powered chatbot that provides basic emotional support and resources, an anonymous check-in form for users to express their moods and challenges, and personalized recommendations based on user responses. The platform aims to bridge the gap between teenagers and professional mental health support.

How I built it
I developed MindSpace primarily using Python for backend logic, leveraging the Flask framework for web application development. For front end, I utilized HTML, CSS, and JavaScript. The AI chatbot functionality was implemented using Python, with libraries such as transformers for natural language processing tasks. Specifically, the chatbot utilizes the DialoGPT-medium model for generating responses.

## Challenges I ran into
Some of the challenges I encountered during the development process included integrating the various components seamlessly, ensuring data security and anonymity for users, and fine-tuning the AI chatbot's responses to provide relevant and helpful support. I got stuck with an error message on the packages of Pytorch with the error torch._C not found. I eventually found out that it was because I was using the Replit so I installed VScode and finally got the Python program to work as intended. Additionally, there some programs with the CSS because the link called style.css was made using the flask URL so I just used the regular command and it worked perfectly!

## Accomplishments that I'm proud of
I'm proud to have created a functional and polished web app within the hackathon's timeframe that addresses a pressing social issue. Our accomplishment lies in developing a platform that not only provides immediate support but also encourages users to prioritize their mental health and seek professional assistance when needed. Furthermore, outlining a clear roadmap for future development highlights my commitment to continuous improvement and impact.

## What I learned
Throughout the development of MindSpace, I learned valuable lessons in Python and how to troubleshoot the problems that arise with projects like this as I am an absolute beginner to programming with Python and using Hugging Face's API. Additionally, working under time constraints pushed me to innovate and problem-solve efficiently.

## What's next for MindSpace
Looking ahead, my vision for MindSpace involves expanding its capabilities and reach. I plan to integrate with crisis hotlines and mental health professional directories to provide users with immediate access to professional assistance. Additionally, I aim to enhance the chatbot's capabilities to offer more personalized support and interactive exercises, further empowering teenagers to manage their mental well-being effectively. Developing a mobile app version of MindSpace will also increase accessibility and reach a wider audience that could be used by anyone, not just teenagers.  Finally, I plan on researching existing mental health resources for teenagers including them in my app, as well as talking to psychology professionals and therapists to further increase its impact on all the users.
