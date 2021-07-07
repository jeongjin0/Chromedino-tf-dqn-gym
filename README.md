# Chromedino-tf-dqn-gym

  

We implementate DQN algorithm with image_pixel input

We use [gym-chrome-dino](https://github.com/mattstruble/gym-chrome-dino) as a environment

---

### Preprocessing

  

Gym provide image pixels as a state

We use Interpolation and Edgedetection for preprocessing

We use cv2 module for preprocessing

---

### Action

  

Agent can choose Three action (Jump, Duck, Stand)

---

### Reward

  

If Agent die, we give -10 reward to agent

and if Agent survive we give 1 reward to agent

---

### RL algorithm

  

we use DQN algorithm using tensorflow

agent explorer or exploit following Epsilon Greedy Algorithm

  

we update Q-function using Q-learning Algorithm

  

we explorer by choosing random integer between 0~2

and we exploit by choosing which position the largest values of the Q-function

  
---
### Result

  

Agent fail to find optimal policy(which is jump at appropriate time)

Agent strategy is to keep jumping without ducking and standing a grahp of score is shown



<img src="https://user-images.githubusercontent.com/80797980/124690882-d7a2a580-df15-11eb-80aa-0d4f7ec1c9fd.png" width="300" height="190"> 