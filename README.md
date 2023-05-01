Download Link: https://assignmentchef.com/product/solved-embsys105-assignment-6-mp3-player-for-the-nucleo-f401re-reference-platform
<br>
<ol>

 <li>This project requires

  <ol>

   <li>the NUCLEO board</li>

   <li>the Adafruit Music Maker MP3 Shield – by now you should have received a Music Maker shield with headers soldered on.</li>

   <li>the Adafruit 2.8” TFT LCD shield</li>

   <li>headphones or earbuds</li>

  </ol></li>

 <li>You need to stack the MP3 shield onto the NUCLEO board and the LCD shield on top of the MP3 shield:

  <ol>

   <li>Carefully plug your Adafruit Music Maker MP3 Shield into your NUCLEO board – make sure all the pins are correctly aligned before inserting.</li>

   <li>Carefully plug your Adafruit 2.8” TFT LCD shield into the Adafruit Music Maker shield – make sure all the pins are correctly aligned before inserting.</li>

   <li>If in doubt, check the Lecture 5 recording which has a demo around the 1 hour mark. 3. Download and unzip the MP3Player project contained in the zip file: MP3Player.zip</li>

  </ol></li>

 <li>Open the MP3Player.eww workspace in the EWARM IDE.</li>

 <li>You will need to copy your context switch file os_cpu_a.asm to the MP3Player project otherwise it won’t build.</li>

 <li>You will get 2 warnings about variables declared and not referenced. Don’t worry, those will go away after you do Assignment 5.</li>

 <li>Launch TeraTerm</li>

 <li>Build and upload the project and start it running.</li>

</ol>

<strong>What to expect</strong>

<ol>

 <li><strong>You should see messages logged in the UART.</strong></li>

 <li><strong>If you plug headphones into the MP3 shield and reset the board you should hear endless repetitions of a ringing bell audio file.</strong></li>

 <li><strong>The LCD screen should display “Hello World!”</strong></li>

</ol>

<strong>What to do if the program builds and uploads to the board but doesn’t work as stated above</strong>

<ol>

 <li>Did you add your working uCOS port code to asm?</li>

 <li>Are the shields plugged in properly to each other, NUCLEO on bottom, MP3 middle, LCD top?</li>

 <li>Are the headphones plugged in properly, and do they work for other devices?</li>

 <li><strong>If none of the above fixes the situation don’t spend a lot of time trying to diagnose. This should just work. Break into the program to see what it is doing. Look at the call Stack (View/Call Stack). Send a message to the instructor with this information</strong>.</li>

</ol>

<h1>Objective</h1>

<ul>

 <li>Specify, design, implement and debug a multithreaded embedded project using a real-time operating system.</li>

</ul>

<h1>Overall Functional Requirements</h1>

<ul>

 <li>Create an MP3 player for the NUCLEO-F401RE reference platform using the Adafruit Music Maker MP3 Shield, and the Adafruit 2.8” TFT LCD shield, using the EWARM tool chain.</li>

 <li>Include minimum functionality to Start (from beginning of song), Stop, and indicate play in progress on the LCD.</li>

 <li>Add at least one additional functionality beyond the minimum (see optional features below for ideas).</li>

</ul>

<h1>Additional Requirements</h1>

<ul>

 <li>Produce a written specification</li>

 <li>High level description of your project’s feature set</li>

 <li>What is implemented</li>

 <li>How it works</li>

 <li>Description of the functional blocks</li>

 <li>Each task or group of tasks</li>

 <li>How they work together</li>

 <li>Produce diagrams to show the system design. Indicate tasks, ISRs, Queues, Mailboxes, major interfaces, etc.</li>

 <li>Deliver the working code, with user instructions including a list of features and how to use each feature.</li>

</ul>

<h1>Optional Features (examples)</h1>

<ul>

 <li>Pause, Fast Forward, Rewind</li>

 <li>Display song progress on the LCD display</li>

 <li>Add feature to change song</li>

 <li>Read song files from SD card</li>

 <li>Add a Help system</li>

</ul>