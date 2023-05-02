Download Link: https://assignmentchef.com/product/solved-comp8049-lab-1
<br>
<h2>Q1</h2>

Write a c program which  reads in a text file and finds all the identifiers in the file. An identifier is a token (sequence of characters)  that starts with an underscore or a letter and continues with underscores or letters or digits.

You are to sort all the identifiers in the input text file and output them in alphabetical order.

Q2

Create a model for the traffic light simulation and state machine that is detailed in section 10.4 of the traffic-light-simulator.pdf  also here

<a href="http://users.ece.utexas.edu/~valvano/Volume1/E-Book/C10_FiniteStateMachines.htm">http://users.ece.utexas.edu/~valvano/Volume1/E-Book/ </a><a href="http://users.ece.utexas.edu/~valvano/Volume1/E-Book/C10_FiniteStateMachines.htm">C10_FiniteStateMachines.htm</a>

This model is a c program that runs on your laptop in Linux. You can use the code in traffic-model.c. You can then emulate a button press by simple key presses on the keyboard. For example:-

<ol>

 <li>enter the letter N to indicate that the North button is on.</li>

 <li>enter the letter E to indicate that the East button is on.</li>

 <li>enter the letter B to indicate that both buttons are on.</li>

 <li>any other key to indicate that both buttons are off</li>

</ol>

<h2>Q3</h2>

Using your code in Q2 build a traffic light controller model and simulation that is cross compiled for an ARM based SOC.

You can use the qemu-system-arm emulator https://wiki.qemu.org/Documentation/Platforms/ARM.

<ul>

 <li>| P a g e</li>

</ul>

See here for steps to build a binary for the qemu emulated versatilepb board.

<a href="https://balau82.wordpress.com/2010/02/28/hello-world-for-bare-metal-arm-using-qemu/">https://balau82.wordpress.com/2010/02/28/hello-world-for-bare-metal-arm-using</a><a href="https://balau82.wordpress.com/2010/02/28/hello-world-for-bare-metal-arm-using-qemu/">qemu/</a>

See emulating-arm-pl011-serial-ports.pdf for an example which emulates the serial communications to the qemu emulated versatilepb board. <a href="https://balau82.wordpress.com/2010/11/30/emulating-arm-pl011-serial-ports/">https://balau82.wordpress.com/2010/11/30/emulating-arm-pl011-serial-ports/</a>