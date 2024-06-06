</head>
<body>
    <h1>ArcFI</h1>
    <div class="gallery">
        <img src="https://raw.githubusercontent.com/garurprani/ArcFI/main/Images/1.png" alt="Image 1">
        <img src="https://raw.githubusercontent.com/garurprani/ArcFI/main/Images/2.png" alt="Image 2">
        <img src="https://raw.githubusercontent.com/garurprani/ArcFI/main/Images/3.png" alt="Image 3">
        <img src="https://raw.githubusercontent.com/garurprani/ArcFI/main/Images/4.png" alt="Image 4">
        <img src="https://raw.githubusercontent.com/garurprani/ArcFI/main/Images/5.png" alt="Image 5">
    </div>
    
   <h2>Overview</h2>
    <p>ArcFI is a DIY, open-source project that combines the functionalities of the Hackheld and ESPert repositories. This project aims to create a more compatible and stable platform where users can play games designed for the SSD1306 display on the Hackheld device. Additionally, it supports the SH1106Wire OLED display, expanding the range of compatible hardware.</p>

   <h2>Repository Credits</h2>
    <p>This project is a combination of the following repositories:</p>
    <ul>
        <li><a href="https://github.com/SpacehuhnTech/HackHeld">HackHeld</a>: A hackable handheld device designed to be easy to build and customize, created by SpacehuhnTech.</li>
        <li><a href="https://github.com/JimmySoftware/ESPert">ESPert</a>: A repository of games for the SSD1306 display, created by JimmySoftware.</li>
    </ul>
  <h2>Installation and Setup</h2>
    <p>Before using ArcFI, make sure you have set up the Hackheld device. Follow the instructions at <a href="https://github.com/SpacehuhnTech/HackHeld">https://github.com/SpacehuhnTech/HackHeld</a>. Identify your OLED display driver as either SH1106 or SSD1306.</p>
    <p>Choose the correct bin file for your display from the ArcFI repository. Incorrect flashing can lead to issues like fizzy lines on your OLED display.</p>
<li>FORSSD1306: Download the ArcFI [SSD1306] bin.</li>
<li>FOR SH1106: Download the ArcFI [SH1106] bin.</li>
<BR>
<p>Flash the latest bin file using <a href="https://github.com/nodemcu/nodemcu-flasher">NodeMCU Flasher</a> or visit <a href="https://esp.huhn.me/">https://esp.huhn.me/</a>.</p>



  <h2>Changes Made</h2>
    <p>The following changes have been made to the ArcFI repository:</p>
    <ul>
        <li>ESPert GPIO pins:
            <ul>
                <li>GPIO13: Right button - GND</li>
                <li>GPIO12: Left button - GND</li>
                <li>GPIO14: UP button - GND</li>
                <li>GPIO1: Down button - GND</li>
                <li>GPIO0: Start button - GND</li>
                <li>GPIO15: Speaker - GND</li>
            </ul>
        </li>
        <li>Changed to Hackheld GPIO pins:
            <ul>
                <li>GPIO13: Right button - GND</li>
                <li>GPIO16: Left button - GND</li>
                <li>GPIO14: UP button - GND</li>
                <li>GPIO1: Down button - GND</li>
                <li>GPIO2: Start button - GND</li>
                <li>GPIO0: Speaker - GND</li>
            </ul>
        </li>
        <li>Added support for SH1106.</li>
        <li>Worked on some small bugs.</li>
        <li>Added TP4056 Type-C charging module, reducing the need to buy costly Hackheld battery modules. The module costs only 40 rupees.</li>
    </ul>
       <img src="https://raw.githubusercontent.com/garurprani/ArcFI/main/Images/tp4056.png" alt="Image 1">

  <h2>Future Contributions</h2>
    <p>If you want to contribute to the ArcFI repository, feel free to contact me on Telegram: @gaurprani.</p>

  <h2>Usage</h2>
    <ol>
        <li><strong>Power on the Device</strong>:
            <ul>
                <li>Connect the Hackheld device to a power source.</li>
            </ul>
        </li>
        <li><strong>Navigate through the Menu</strong>:
            <ul>
                <li>Use the buttons to navigate through the available games and functions.</li>
            </ul>
        </li>
        <li><strong>Play Games</strong>:
            <ul>
                <li>Select a game from the ESPert collection and start playing.</li>
            </ul>
        </li>
    </ol>

  <h2>Contribution</h2>
    <p>Contributions are welcome! If you have ideas for new features, improvements, or bug fixes, feel free to open an issue or submit a pull request.</p>

  <h2>License</h2>
    <p>This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for more details.</p>

  <h2>Contact</h2>
    <p>For any questions or support, please open an issue on the GitHub repository.</p>
</body>
</html>
