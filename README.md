💖 Valentine Catch-the-Bear Surprise
An interactive, web-based Valentine's Day surprise where users must "catch" a flying bear to reveal a personalized romantic message. It features a built-in card generator, responsive design for long messages, and synchronized music and animations.

✨ Features
Interactive Mini-Game: The envelope "flies" away from the mouse, requiring the recipient to catch it to see the surprise.

Card Generator: A built-in setup modal allows the sender to type a name and a custom message.

Dynamic Sharing: Generates a unique URL containing the message data so you can send it as a simple link.

Responsive Message Card: The card adapts to the text length. If the message exceeds 300 words, it becomes scrollable to ensure it remains readable.

Immersive Audio:

Romantic background music on hover/reveal.

"Woosh" sounds during the chase.

"Pop" sound effect upon opening.

Visual Effects: Custom-built CSS bear, animated bouquets, and a heart-burst particle effect when the card opens.

🚀 How to Use
For the Sender (You):
Open the index.html file in any web browser.

In the "Spread the Love" modal, enter your Valentine's name and your romantic message.

Click "Seal with a Kiss 💋".

Copy the generated link and send it to your special someone!

For the Receiver:
Open the link provided by the sender.

Try to click the flying bear/envelope.

Once caught, watch the envelope open to reveal the personalized message.

🛠️ Installation & Setup
Clone or Download this repository.

Asset Setup: Ensure you have an assets folder in the root directory with the following audio files:

card-flip.mp3

woosh.mp3

romantic-keys.mp3

Launch: Simply open index.html in your browser. No server-side language (like PHP or Node.js) is required!

📂 Project Structure
Plaintext
├── index.html        # Main logic, styles, and structure
├── assets/           # Sound effects and music
│   ├── card-flip.mp3
│   ├── woosh.mp3
│   └── romantic-keys.mp3
└── README.md         # Project documentation
🎨 Technologies Used
HTML5: Semantic structure.

CSS3: 3D transforms, keyframe animations, and custom bear/flower illustrations.

JavaScript (Vanilla): Game logic, DOM manipulation, and URL parameter handling.

📜 Technical Note on Audio
Most modern browsers block autoplay audio. To ensure the best experience:

The romantic music is triggered when the sender hovers over the input fields.

The game music is triggered by the receiver's first interaction (mouse movement or click).

Made with ❤️ for Valentine's Day.