**#Owl Eye Rotation**
This project creates a dynamic effect where an owl's eyes rotate to follow the movement of the mouse pointer. The interactive animation mimics the behavior of an owl tracking objects, providing an engaging visual experience.

**Features**
Interactive Animation: The owl's pupils move in real time, following the cursor's position.
Smooth Movement: The rotation uses trigonometric calculations for precise and natural movement.
Lightweight and Responsive: Built with minimal HTML, CSS, and JavaScript for quick loading and responsiveness.
How It Works
Mouse Movement Detection:

Listens for the mousemove event to track the cursor's position.
Eye Center and Angle Calculation:

Identifies the center coordinates of each eye.
Calculates the angle between the eye center and the cursor using Math.atan2.
Dynamic Rotation:

Applies the calculated angle to the pupils using the CSS transform: rotate() property.
