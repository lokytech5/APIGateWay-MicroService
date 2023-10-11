## Personalized Learning Management System - API Gateway

The API Gateway is the focal point for all client interactions, directing them to the corresponding microservices. 
It encompasses functions like request routing, user authentication, logging, and rate limiting.

📘 **Project Overview**:
This platform, powered by Spring Boot, is crafted to amplify 
the learning experience. It lets users pose questions, 
obtaining AI-driven responses tailored to their queries, 
and is supplemented with well-curated resources to enrich their 
understanding.

### 🚀 Core Features:

- **User Profiles**: Tailor learning preferences, strengths, and improvement areas.

- **📚 AI-driven Q&A:**: Instantly get answers to queries, powered by ChatGPT or similar AI models. For instance, "What is the Pythagorean theorem?".

- **🌐 Resource Curation**: Post-answer, users are suggested reading materials, video links, or online courses for a deeper insight.

- **📈 Progress Tracking**: Observe and visualize the learning curve over time.

- **🤝 Collaborative Learning**: Engage in collective discussions with AI facilitating in real-time.

- **💌 Feedback System**: Grade AI's outputs to refine its relevance and accuracy over time

### 🏗 Microservices Architecture:

- **Chat Service**: Facilitates integration with the ChatGPT API.
- [#]

- **Resource Service**: Manages and suggests pertinent learning resources.

- **📚 UserService**: Manages user data, including registration, login, and retrieval of user information.

- **Feedback Service**: Gathers user feedback to polish and optimize the system.

### 🛠 Tech Stack:

- **Languages & Frameworks**: Java with Spring Boot, Spring MVC, Spring DevTools
- **Database**: MySQL with Spring JPA
- **Microservices**: Spring Feign, Spring Netflix Eureka Server, Spring Config Client
- **Containerization**: Docker

### 🚧 Challenges:

- **🎯 Quality Control:**: Ensures AI offers consistent and relevant answers.

- **🔄 Resource Curation: **: Regularly curates and updates a repository of top-tier resources to support learning.



### 📅 Updates:

Updates and newly introduced features will be chronicled here as the platform progresses.

---