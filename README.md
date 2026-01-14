\# 🌾 FarmSmart AI – Data-Driven Smart Irrigation using Reinforcement Learning 



This project presents a \*\*Reinforcement Learning based Smart Irrigation System\*\* that dynamically adapts irrigation decisions based on crop type, soil type and environmental conditions.



 It is based on my research paper titled:


> \*\*"Data-Driven Smart Irrigation using Reinforcement Learning"\*\*


---


\## 📌 Project Objectives

* Reduce water wastage  

* Maintain optimal soil moisture  

* Learn crop-specific irrigation strategies  

* Implement AI-driven precision agriculture  


---


\## 🧠 System Levels



\### Phase A1 — Basic Reinforcement Learning

In this part, I implemented simple RL methods like:

* Monte Carlo

* TD(0)

* SARSA

* Q-Learning

* This helped me understand how RL works and how an agent learns from rewards.




\### Phase A2 — Data-Driven Environment

Here I used the actual dataset (data\_core.csv) and created:


Crop-wise and crop–soil-wise moisture targets

A more realistic environment

Weather-based evaporation and random rainfall

This made the RL training more meaningful and closer to real farming.


&nbsp;


\### Phase A3 — Deep Q-Network (DQN)

This is the main part of the project. I built a DQN model that learns irrigation decisions from continuous inputs:


\[Moisture, Temperature, Humidity, Crop, Soil]

The DQN uses a neural network, replay buffer, epsilon-greedy exploration, and a target network to learn stable irrigation patterns.


The actions the agent can take:

* 0 → No water

* 1 → Low

* 2 → Medium

* 3 → High

---


\## 🗂 Repository Structure

rlaiproject

├── code

├── data

├── research-paper

├── images

└── README.md 


---


\## 📊 Output Results:

* DQN performs much better than simple RL
* Moisture stays stable
* Water usage goes down
* The agent learns when to irrigate and when not to



!\[Reward Curve](images/reward\_curve.png)  

!\[Moisture Graph](images/moisture\_graph.png)


---


\## 📄 Research Paper


You can read the complete paper here:  

📘 \[Click Here](research-paper/RLAI\_Research\_Paper.pdf)


---


\## ⚙ Technologies Used


* Python  

* Reinforcement Learning  

* Q-Learning  

* Deep Q-Network  

* NumPy  

* Pandas  

* Matplotlib  

* TensorFlow / PyTorch  


---


\## 📁 Project Files

* A1/ → Basic RL algorithms

* A2/ → Data-driven environment using the dataset

* A3/ → DQN implementation

* data/ → Dataset used

* README.md → Project info


---


\## 📈 Key Achievements


*  Improved moisture stability  

*  Reduced water wastage  

*  Crop \& soil personalized irrigation  

* Adaptive decision making  


---


\## 👩‍💻 Team Members


* Diksha
* Diwanshi
* Harshada

---


\## ⭐ Future Scope

* IoT sensor integration  

* Real-time weather API  

* Mobile app monitoring  

* Cloud deployment  


---


\## 📬 Contact
If you have any questions, collaboration ideas, or feedback, feel free to reach out:

📧 Email: diwanshipandey331@gmail.com  

🔗 GitHub: https://github.com/diwanshi-04

💼 LinkedIn: https://linkedin.com/in/diwanshi04

