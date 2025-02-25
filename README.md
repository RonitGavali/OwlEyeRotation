# 🦉 Owl Eye Rotation

This project creates a dynamic effect where an owl's eyes rotate to follow the movement of the mouse pointer. The interactive animation mimics the behavior of an owl tracking objects, providing an engaging visual experience.

## ✨ Features
- 🎯 **Interactive Animation**: The owl's pupils move in real-time, following the cursor's position.
- 🎨 **Smooth Movement**: Uses trigonometric calculations for precise and natural movement.
- ⚡ **Lightweight and Responsive**: Built with minimal HTML, CSS, and JavaScript for quick loading and responsiveness.

## 🛠️ How It Works
1. **Mouse Movement Detection**
   - Listens for the `mousemove` event to track the cursor's position.
2. **Eye Center and Angle Calculation**
   - Identifies the center coordinates of each eye.
   - Calculates the angle between the eye center and the cursor using `Math.atan2`.
3. **Dynamic Rotation**
   - Applies the calculated angle to the pupils using the CSS `transform: rotate()` property.

## 📸 Execution Images
Here are some snapshots demonstrating the owl eye rotation in action:

### 🔹 Initial State
![Initial State](https://github.com/RonitGavali/OwlEyeRotation/blob/main/owl1.png)

### 🔹 Cursor Moving
![Cursor Moving](https://github.com/RonitGavali/OwlEyeRotation/blob/main/owl2.png)

### 🔹 Final Tracking Position
![Final Tracking Position](https://github.com/RonitGavali/OwlEyeRotation/blob/main/owl3.png)

## 📌 Setup and Execution
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/owl-eye-rotation.git
   ```
2. Open the `index.html` file in a browser.
3. Move your cursor to see the owl's eyes follow it.

## 📜 License
This project is licensed under the MIT License.

---

Enjoy the mesmerizing owl eye animation! 🦉✨

