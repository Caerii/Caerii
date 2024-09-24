## Hi there 👋

<!-- HEADER -->
<h1 align="center">👨‍💻 Alif Jakir (Caerii) 👨‍💻</h1>
<p align="center">
  <strong>AI Engineer | Full-stack Developer | Innovator in Modular Robotics & Brain-Computer Interfaces</strong><br>
  <a href="https://alifjakir.com">🌍 Website</a> | 
  <a href="https://github.com/Caerii">💻 GitHub</a> | 
  <a href="mailto:alif@halcyox.com">📧 Email</a> | 
  <a href="https://www.linkedin.com/in/alif-jakir">LinkedIn</a>
</p>
<br>

---

<!-- FOCUS -->
<h2 align="center">⚡ Focus & Expertise</h2>
<p align="center">
I specialize in cutting-edge AI, modular robotics, and integrating brain-computer interfaces into real-time VR systems. My work combines deep technical knowledge with innovation in emerging technologies, and this GitHub is all about showcasing those projects.
</p>

---

<!-- TECHNICAL PROJECTS -->
<h2 align="center">🚀 Featured Technical Projects</h2>

(Links not currently public as code gets properly organized)

### 🔹 [**MIT Media Lab – Brain-Controlled 3D Animation**](https://github.com/Caerii/brain-controlled-animation)
- **Tech Stack**: Python, Blender, EEG, Leap Motion, Unity, Python API, WebSocket, Real-time rendering
- **Architecture**:
    - **Signal Processing Layer**: EEG signals were captured using **Emotiv Insight** and processed in real-time using Python.
    - **Control Interface**: Hand gestures were captured via **Leap Motion**, providing control signals that triggered different animation states in Blender.
    - **3D Engine**: Used **Blender** for the animation pipeline, integrated with Python APIs for real-time control over the animations.
    - **Real-time Communication**: Implemented a WebSocket-based communication protocol between the Python backend and the Blender animation system, ensuring minimal latency.
- **Challenges & Solutions**:
    - **Challenge**: Achieving low-latency control with EEG signals in real-time for holographic display.
    - **Solution**: Optimized the signal processing pipeline using lightweight Python libraries and parallelized threads for **EEG and gesture control** inputs to reduce delay and increase frame rates.
- **Impact**: Project showcased at MIT Museum as an interactive exhibit allowing users to control 3D animations using just their brain and hand movements.

---

### 🔹 [**Solar Estimator – Solar Savings Web App**](https://solarestimator.com)
- **Tech Stack**: Next.js, React, Elasticsearch, Node.js, Google Sunroof API, Vercel, Redis
- **Architecture**:
    - **Frontend**: Built with **Next.js** for SSR (Server-side Rendering) to ensure fast, SEO-optimized pages with real-time search capability using **Elasticsearch**.
    - **Backend**: **Node.js** API interacts with the **Google Sunroof API** to fetch solar data based on user inputs (like address) and calculate potential savings.
    - **Caching**: **Redis** is used to cache frequent address queries to minimize API request overhead and reduce latency for common searches.
    - **Search System**: Utilized **Elasticsearch** to allow users to search through solar service providers and optimize leads based on their location.
- **Challenges & Solutions**:
    - **Challenge**: Scaling the API request limits with Google Sunroof while handling high traffic on lead generation forms.
    - **Solution**: Implemented intelligent caching using **Redis**, cutting down the number of repetitive API requests and optimizing data flow between the client and the backend.
- **Impact**: Enabled seamless estimation of solar savings for thousands of users, improving lead generation conversion rates for solar installation companies by 30%.

---

### 🔹 [**Moodspace - MIT Reality Hack 2022**](https://github.com/Caerii/moodspace)
- **Tech Stack**: Unity, Hololens, C#, EEG, Azure Cognitive Services, WebRTC, XR SDK
- **Architecture**:
    - **Biometric Input**: Used **EEG sensors** (Emotiv) and connected them via **WebRTC** to stream real-time brainwave data into **Azure Cognitive Services** for sentiment analysis.
    - **XR Environment**: Built the virtual environment using **Unity** with **XR SDK** for integration with **Hololens**.
    - **Interaction Layer**: The system analyzed **emotional states** using EEG data and adjusted the conversation flow within the XR environment based on emotional feedback from users.
    - **Cloud Backend**: Data was processed through **Azure Cognitive Services**, leveraging real-time APIs for emotion detection and feeding the results back into the Unity engine for adaptive interactions.
- **Challenges & Solutions**:
    - **Challenge**: Accurately interpreting subtle emotional changes from EEG data.
    - **Solution**: Used a combination of **pre-trained sentiment models** and a custom-trained model for the project to map EEG signals to more accurate emotional outputs.
- **Impact**: Finalist at MIT Reality Hack, demonstrating the future potential of **emotionally-aware meta-conversations** in XR.

---

### 🔹 [**Modular Aerial Robotics – VR-Controlled Precision Drones**](https://github.com/Caerii/modular-aerial-robotics)
- **Tech Stack**: ROS, Unity, Python, VR headset, Raspberry Pi, OpenCV, Reinforcement Learning, TensorFlow
- **Architecture**:
    - **Drone Framework**: Built on **ROS (Robot Operating System)**, with modules for flight control, object manipulation, and real-time sensor input from stereo cameras.
    - **VR Interface**: Developed in **Unity** and connected to a **custom Python API**, which sends real-time positional data from the VR headset to the drone controller.
    - **Precision Manipulation**: Implemented **OpenCV** for object detection and built a **dual-arm precision manipulator** controlled via reinforcement learning algorithms, allowing the drone to autonomously grasp and manipulate objects.
    - **Deep RL**: Trained a **TensorFlow-based reinforcement learning model** to handle complex real-time tasks, such as object detection and grasping in 3D space.
- **Challenges & Solutions**:
    - **Challenge**: Ensuring accurate control over drone manipulations using VR in real-time.
    - **Solution**: Leveraged **Reinforcement Learning** for precise control and used **low-latency data transmission** between VR and the drone controller to reduce input delay.
- **Impact**: Created a modular, scalable drone platform that can be extended for various use cases like autonomous delivery, inspection, and remote handling in hazardous environments.

---

### 🔹 [**AI Code Assistant – Autonomous Coding with GPT**](https://github.com/Caerii/ai-code-assistant)
- **Tech Stack**: GPT-4, PyTorch, Node.js, Docker, GraphQL, GitHub API
- **Architecture**:
    - **AI Backend**: Used **GPT-4** for natural language code generation and refactoring across entire repositories.
    - **Frontend**: Built with **Node.js** and **GraphQL** for smooth interaction with large codebases, allowing developers to ask questions or generate new functions via a simple interface.
    - **Repository Interaction**: Integrated **GitHub API** to allow the AI agent to read entire repositories, detect bugs, suggest improvements, and even generate PRs automatically.
    - **Dockerized Microservices**: The system is fully **containerized using Docker**, allowing seamless deployment across different environments.
- **Challenges & Solutions**:
    - **Challenge**: Ensuring the AI model could handle **large codebases** efficiently without sacrificing accuracy in code suggestions.
    - **Solution**: Implemented a custom **attention mechanism** and code chunking strategies to ensure GPT-4 handled large repositories without missing context.
- **Impact**: Streamlined the development process for large teams, reducing code review times by 40% and helping developers catch bugs earlier in the development pipeline.

---

<!-- GITHUB STATS & TROPHIES -->
<h2 align="center">📊 GitHub Stats & Trophies</h2>
<p align="center">
  <img src="http://github-readme-streak-stats.herokuapp.com?user=Caerii&theme=dark&background=000000" alt="GitHub Streak Stats" width="45%" /> 
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Caerii&layout=compact&theme=vision-friendly-dark" alt="Top Languages" width="45%"/>
</p>
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Caerii&theme=darkhub" alt="Trophy Cabinet" width="80%">
</p>

---

<!-- OVERLEAF LINK -->
<h2 align="center">📄 Full CV</h2>
<p align="center">
For my full professional experience, including more unpublished research and a detailed breakdown of my academic journey, check out my CV on Overleaf:
</p>
<p align="center">
  <a href="https://www.overleaf.com/read/nvfhfhmyqqxg#951fa7" target="_blank">
    <img src="https://

