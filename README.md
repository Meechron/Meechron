# hey, i'm amir 👋

i build systems where code actually controls something in the real world.

mainly interested in embedded systems, control, and making things work reliably — not just once.

---

## 🚗 autonomous vehicle system  
🔗 https://github.com/Meechron/Autonomous-Vehicle-Driving-System  

i built a small-scale autonomous driving system running on raspberry pi.

it processes sensor input in real time and controls the vehicle through a modular pipeline:
sensing → decision → actuation

what it does:
- lane following using grayscale sensors  
- obstacle avoidance with ultrasonic sensing  
- traffic sign handling (stop, yield, etc.)  
- navigation logic across a mapped environment  

the system is split into modules (controller, lane follower, navigator, sign handler), so each part can be tested and improved independently.

big focus was making it **reliable**, not just “working once”.

---

## 🧠 how i approach systems

- separate sensing / logic / control cleanly  
- design for debugging (not guessing)  
- handle edge cases, not just ideal scenarios  
- if it’s not consistent → it’s not finished  

---

## 🛠 stack

- python  
- raspberry pi + sensors  
- linux / git  

---

## 🌐 portfolio

https://meechron.github.io/portfolio-website/

---

## 🎯 right now

trying to build more systems at this level — where software meets hardware and has to perform in real conditions.
