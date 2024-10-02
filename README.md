🎨 Chameleon Balls
Chameleon Balls is a simple yet visually captivating game built using HTML and CSS. The game features balls that move along the x-axis and change colors when hovered over, creating a fun and interactive experience.

🎮 Demo

🔗 Play with the live demo: here.

✨ Features
🟠 Interactive Balls: Hover over the balls to watch them move across the screen.
🎨 Color Change: Each ball changes color when hovered, mimicking the behavior of a chameleon.
🌈 Smooth Animations: Unique animations for each ball, making the transitions seamless and fluid.
⚙️ Customizable: Easily change ball sizes, colors, or animations through CSS.
💻 Technologies Used
HTML: Structure of the game.
CSS: Styling and animations.
transition, transform, and hover effects to create movement and color transitions.
flexbox layout for positioning elements.
🧩 Code Snippet
css
Copy code
.ball:nth-child(1):hover {
    transition: 5s ease-in-out;
    transform: translateX(90vw);
    background-color: red;
}
🚀 How to Run Locally
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/chameleon-balls.git
Navigate to the project directory:
bash
Copy code
cd chameleon-balls
Open the index.html file in your browser to play the game.
🛠 Customization
🎨 You can easily tweak the following to create your own version:

Change ball colors in the .ball class.
Adjust transition timing with the transition property.
Add more balls by duplicating the ball div in the HTML.
🤝 Contributing
Feel free to submit issues or pull requests to improve this project! Any contributions are welcome. 😊
