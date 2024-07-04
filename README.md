<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
</head>
<body>

<h1>Simon Game</h1>

<p>Welcome to the <strong>Simon Game</strong>, a fun and engaging memory game! In this game, you have to remember and reproduce a sequence of colors that gets progressively longer and more challenging. Test your memory and see how many levels you can complete!</p>

<h2>How to Play</h2>
<ol>
    <li><strong>Start the Game</strong>: Press any key to start the game. The level will be displayed at the top of the screen.</li>
    <li><strong>Watch the Sequence</strong>: A button will flash to indicate the color sequence. Pay close attention to the order in which the buttons blink.</li>
    <li><strong>Repeat the Sequence</strong>: Click the buttons in the same order as they flashed. If you get the sequence correct, you'll advance to the next level where the sequence gets longer by one color.</li>
    <li><strong>Continue</strong>: Each level adds a new color to the sequence. You must remember the entire sequence and click the buttons in the correct order.</li>
    <li><strong>Game Over</strong>: If you click the wrong button, the game is over. The screen will flash, and a "Game Over" message will be displayed. Press any key to restart the game and try again!</li>
</ol>

<h2>Features</h2>
<ul>
    <li><strong>Dynamic Color Sequence</strong>: The sequence of colors is randomly generated and increases in length as you progress.</li>
    <li><strong>Interactive Buttons</strong>: Clickable buttons that light up and play sounds when pressed.</li>
    <li><strong>Level Display</strong>: The current level is displayed at the top of the screen, motivating you to reach higher levels.</li>
    <li><strong>Sound Effects</strong>: Enjoy sound effects for each button press and when the game ends.</li>
</ul>

<h2>Screenshot</h2>
<p><img src="https://github.com/itzdiv/Simon-Game/blob/main/render_images/image.png" alt="Game Screenshot"></p>


<h2>How It Works</h2>
<p>The game starts when you press any key. The <code>nextSequence</code> function generates a random color and adds it to the <code>gamePattern</code> array. The buttons flash in the sequence, and you must replicate the pattern by clicking the buttons in the correct order. The <code>checkAnswer</code> function verifies your input, and if you get the sequence correct, the game advances to the next level. If you make a mistake, the game plays a "wrong" sound, displays a "Game Over" message, and resets.</p>

<h2>Code Overview</h2>
<p>The JavaScript code consists of the following main parts:</p>
<ul>
    <li><strong>Variables</strong>: Arrays to store the game pattern and the user's clicked pattern, along with other variables to manage game state.</li>
    <li><strong>Event Listeners</strong>: Detects key presses to start the game and button clicks for user input.</li>
    <li><strong>Functions</strong>:
        <ul>
            <li><code>nextSequence()</code>: Generates the next color in the sequence.</li>
            <li><code>checkAnswer(currentLevel)</code>: Checks if the user's input matches the game pattern.</li>
            <li><code>playSound(name)</code>: Plays the corresponding sound for each color.</li>
            <li><code>animatePress(currentColor)</code>: Animates button presses.</li>
            <li><code>startOver()</code>: Resets the game variables to restart the game.</li>
        </ul>
    </li>
</ul>

<h2>Technologies Used</h2>
<ul>
    <li><strong>HTML</strong>: Structure of the game page.</li>
    <li><strong>CSS</strong>: Styling of the game elements.</li>
    <li><strong>JavaScript</strong>: Game logic and interactivity.</li>
    <li><strong>jQuery</strong>: Simplified JavaScript for DOM manipulation.</li>
</ul>

<h2>Getting Started</h2>
<p>To play the Simon Game, simply open the <code>index.html</code> file in your web browser. Make sure you have the necessary sound files in a <code>sounds</code> folder in the same directory as your HTML file.</p>

<h2>Contribution</h2>
<p>Feel free to fork this repository, make improvements, and submit pull requests. Any contributions are welcome!</p>

<h2>License</h2>
<p>This project is licensed under the MIT License. See the LICENSE file for more details.</p>

<p>Enjoy the game and challenge your memory skills with the Simon Game!</p>

</body>
</html>
