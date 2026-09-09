# 🧠 AI-Based Cognitive Gaming & Memory Assistance Platform 

A **3D cognitive gaming and memory assistance platform** designed to support elderly users, including people experiencing dementia-related memory difficulties.

The platform provides an interactive **3D kitchen environment** where users can participate in simple memory, recognition, attention, and object-based cognitive activities.

---

## 🎯 Project Objective

The main objective is to create a **friendly, accessible, and engaging digital environment** that can support cognitive stimulation through familiar everyday activities.

The system combines:

* 🎮 Cognitive games
* 🏠 Interactive 3D environment
* 🧠 Memory exercises
* 🔊 Voice assistance
* ♿ Elderly-friendly accessibility
* 🥽 VR support
* 📊 Cognitive performance tracking

---

## ✨ Features

### 🏠 Interactive 3D Kitchen

A warm and simple 3D kitchen environment containing familiar household objects such as:

* ☕ Cup
* 🫖 Kettle
* 🥄 Spoon
* 🍽️ Plate
* 🍚 Bowl
* 🧂 Salt/Sugar container
* 🍞 Bread
* 🥛 Glass
* 🔪 Kitchen knife

Objects can be selected and identified during gameplay.

---

## 🧠 Cognitive Game Modes

The platform currently supports **six cognitive game modes**:

1. **Object Recognition**

   * Identify a requested kitchen object.

2. **Object Location Memory**

   * Remember where an object was located.

3. **Sequence Memory**

   * Remember and reproduce an object sequence.

4. **Object Matching**

   * Match related or similar objects.

5. **Category Recognition**

   * Identify objects based on their category or purpose.

6. **Short-Term Memory**

   * Temporarily remember objects and answer questions about them.

The game engine switches between these modes based on the selected game mode.

---

## 📈 Adaptive Difficulty

The system includes three difficulty levels:

| Level  | Objects | Viewing Time | Memory Delay |
| ------ | ------: | -----------: | -----------: |
| Easy   |       3 |        9 sec |        5 sec |
| Medium |       5 |        6 sec |        8 sec |
| Hard   |       7 |        4 sec |       12 sec |

The **Auto** mode can adapt the difficulty according to the user's performance.

---

## 🔊 Voice Assistance

The platform uses browser speech capabilities to provide:

* Game instructions
* Object names
* Questions
* Feedback
* Encouragement

Example:

> "Hello! Let us play a memory game together."

Voice volume and speech speed can be adjusted through the settings panel.

---

## ♿ Accessibility

The interface is designed with elderly users in mind.

Accessibility options include:

* Large text
* Adjustable text size
* Adjustable voice volume
* Adjustable speech speed
* High-contrast mode
* Simple controls
* Clear visual feedback

These settings are available directly in the application.

---

## 🥽 VR Support

The application supports **WebXR/VR interaction**.

Users can interact with kitchen objects using:

* Mouse
* Pointer interaction
* VR controller raycasting

The application uses Three.js `VRButton` and controller-based object selection.

---

## 📊 Cognitive Session Tracking

The system records gameplay events such as:

* Selected object
* Game mode
* Correct/incorrect answer
* Response time
* Attempts
* Difficulty
* Session score

The collected session information can be exported as a **JSON file** for further analysis or integration with an AI/ML backend.

---

## 🛠️ Technology Stack

### Frontend / 3D

* HTML5
* CSS3
* JavaScript
* Three.js
* WebGL
* WebXR

### Three.js Components

* Three.js
* OrbitControls
* VRButton
* Raycaster

The project currently imports Three.js and its addons through a CDN.

### AI/ML Integration

The session-data architecture is designed to be connected to a future AI/ML backend for:

* Cognitive performance analysis
* Personalized difficulty
* User progress tracking
* Long-term performance analysis

---

## 📂 Project Structure

```text
cognitive-kitchen/
│
├── index.html
├── README.md
│
├── assets/
│   ├── models/
│   ├── textures/
│   └── audio/
│
├── screenshots/
│
└── data/
    └── cognitive_sessions/
```

> If your current project is a single HTML file, you can initially keep everything inside `index.html` and gradually separate the JavaScript, CSS, assets, and game modules.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/cognitive-kitchen.git
```

### 2. Open the Project

Go to the project directory:

```bash
cd cognitive-kitchen
```

### 3. Run the Application

Because the project uses browser-based JavaScript modules, it is recommended to run it using a local server.

For example, with VS Code:

```text
Install Live Server
→ Right click index.html
→ Open with Live Server
```

Then open the provided local URL in your browser.

---

## 🎮 How to Play

### Step 1

Open the application.

### Step 2

Click **Start Game**.

### Step 3

Observe the kitchen and objects carefully.

### Step 4

Listen to the voice instruction.

### Step 5

Select the correct object or answer the cognitive question.

### Step 6

Receive immediate feedback.

### Step 7

Continue through multiple rounds.

The game tracks the user's performance and adjusts difficulty when Auto mode is enabled.

---

## ⚙️ Available Controls

* 🎮 **Start Game**
* 🔄 **New Round**
* 🔊 **Repeat**
* 🏠 **Free Explore**
* ⚙️ **Settings**
* 🥽 **VR Mode**

---

## 🔮 Future Enhancements

Future versions can include:

* 🤖 AI-based cognitive assessment
* 📱 Flutter mobile application
* ☁️ Cloud-based user profiles
* 🔐 Secure authentication
* 📊 Caregiver dashboard
* 📈 Cognitive progress reports
* 🧠 Personalized game recommendations
* 🌐 Multi-language voice support
* 🗣️ Regional language support
* 🏡 Additional 3D environments
* 👨‍⚕️ Caregiver/clinician monitoring
* 🔗 FastAPI AI backend
* 🗄️ Database integration

---

## 🌏 Target Region

The platform is intended for deployment and evaluation with elderly users in the **North Eastern Region (NER) of India**, with emphasis on creating culturally familiar and accessible digital experiences.

---

## ⚠️ Disclaimer

This project is intended as a **cognitive gaming and memory-support platform**.

It is **not a medical diagnostic tool** and should not be used as a replacement for professional medical evaluation, diagnosis, or treatment.

---

## 👥 Team

**Project:** AI-Based Cognitive Gaming and Memory Assistance Platform

**Focus Areas:**

* Artificial Intelligence
* Machine Learning
* Cognitive Gaming
* 3D/WebXR
* Memory Assistance
* Elderly-Friendly Technology

---

## 📜 License

This project is developed for **educational, research, and hackathon purposes**.

Add an appropriate open-source license such as **MIT License** if you intend to make the project open source.

---

## ⭐ Project Vision

> **Making cognitive support engaging, accessible, and familiar through AI-powered interactive environments.**

If you find this project useful, consider giving the repository a ⭐.

