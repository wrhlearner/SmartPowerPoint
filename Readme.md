# **Project Ideas**

[toc]

### **Magic Mirror**

https://www.google.com/search?q=smart+magic+mirror++weather&source=lnms&tbm=isch&sa=X&ved=2ahUKEwikuOvN_dH9AhWnjokEHclDAlAQ_AUoAXoECAEQAw&biw=1536&bih=722&dpr=1.25#imgrc=dJdD_lRUH8l99M

- add wake word detection function
- status indicator, i.e. whether the system is in PPT mode, or idle, etc.

### **Wake word detection**

- adding a display device to show text animation

### **<font color='red'>hand gesture controlled PPT presentation</font>**

- add **wake word detection** to open and close PPT
- **extract gesture** from IMU input data and control presentation
- status indicator, i.e. whether the system is in PPT mode, or idle, etc.
- *extra functionality: federal learning 

### **Emotion/MBTI detection**

- use different ways to classify you into 16 personalities, like singing a song

## **Time Schedule**

### **Resources**

- Reference book: docs/reference/TinyML Machine learning with TensorFlow Lite on Arduino and Ultra-Low-Power Microcontrollers
- Reference Code: reference book page 101

### **tasks**

- Wake Word Detection: use audio input - Jack
  - output: 
    - idle - 0
    - open ppt - 1
    - close ppt - 2
- Gesture Recognition: use proximity sensor and IMU - Yufeng
  - idle - 0
  - switch to previous ppt - 1
  - switch to next ppt - 2
- PPT control driver, generate status info and communicate with host PC - Cynthia
  - 4 instructions: close ppt, open ppt, switch to previous slide, switch to next slide
- write report/presentation

### **Meeting**

Weekly, Sat afternoon, 1pm

- <font color='red'>**deadline: April 24th**</font>

### **Schedule**

Total time: 6 weeks

- [ ] Mar 11 - Mar 18
- [ ] Mar 18 - Mar 25
- [ ] Mar 25 - Apr 1
- [ ] finish 3 functionalities
- [ ] Apr 1 - Apr 8
- [ ] integrate into a working prototype
- [ ] Apr 8 - Apr 15
- [ ] finish preparing the final presentation/report
- [ ] Apr 15 - Apr 22
- [ ] Apr 22 - Apr 23
- [ ] ddl and presentation: April 24th