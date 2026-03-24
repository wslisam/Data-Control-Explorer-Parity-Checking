# Data Control Explorer  - Parity Checking

This interactive web application is designed to help students easily understand the concepts of data accuracy in Computer Science: **Validation**, **Verification**, and **Parity Checks**. 

This tool provides a hands-on learning experience to see exactly how computers detect errors when transmitting data.

<img width="1042" height="985" alt="image" src="https://github.com/user-attachments/assets/d6bf4cbc-f27c-48ef-8ca3-cd40504402e7" />

## 🚀 What You Will Learn
1. **Validation vs Verification:** Learn the difference between checking if data is "sensible/logical" (Validation) versus checking if it is "absolutely correct" (Verification).
2. **Parity Checks:** Understand how computers use an extra bit (the Parity Bit) to validate data sent over a network.
3. **Communication Protocols:** See why the sender and receiver must agree on rules (Even or Odd parity) before talking to each other.
4. **Error Detection Limitations:** Discover why a parity check is great for catching single-bit errors, but fails if two errors happen at the same time.

## 🎮 How to Use the Simulator
The "Space Mission" simulator lets you act as both the sender (Earth) and the receiver (Mars). 

1. **Enter a Character:** Type any letter (A-Z) into the Earth terminal. The app will convert it into a 7-bit ASCII binary code.
2. **Choose a Protocol:** Select either the **Even** or **Odd** parity rule. Watch how the 8th bit (the pink Parity Bit) changes automatically to satisfy the rule you chose.
3. **Simulate Cosmic Rays:** In the "Space Transmission" section, click on any of the blue Data Bits to "flip" them (changing a 0 to a 1, or a 1 to a 0). This simulates interference or corruption during transmission.
4. **Check the Result:** Look at the Mars terminal. Did Mars accept or reject the data? 
5. **Experiment:** Try flipping exactly *two* bits. What happens? Read the "Limitations & Real Applications" section below the simulator to understand why!
6. **Reset:** Click the "Reset Simulator" button to clear your errors and try again.

## 🧠 Test Your Knowledge
At the bottom of the page, you'll find a short interactive quiz. Give it a try! Whether you get the answer right or wrong, a detailed explanation will appear to help reinforce what you've learned.

## 🌐 Language Support
This application is fully bilingual! Click the **"中文 / EN"** button in the top right corner at any time to seamlessly switch the entire interface, explanations, and quizzes between English and Traditional Chinese. 
