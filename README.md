<div>
<h1>Vehicle Telemetry and Diagnosis Device</h1>
<p>Arduino Nano with CANBUS, GPS, GSM modules which send data at VPS with Telematic Web Application.<br>This project implements getting CAN-BUS data from vehicle and combing them with GPS location.<br>TCP/IP takes controls of the remote packets transmission and sends via GSM packets to Remote Server.</p>
</div>
<br><hr><br>

<div>
<h3>The Idea</h3>
<img src="https://apaliampelos.me/assets/images/github/rdt0001_2.jpg" alt="Project idea"/>
<p>
<ul>
<li>The implemented system is based on wireless telemetry.</li>
<li>On the left we see the transmission system while on the right the receiving system.</li>
<li>Once the Server accepts the TCP connection, the device sends data in string format via GSM network.</li>
<li>It supports connections to GSM, CANBUS with a speed of 500kbps as well as the ability to receive GPS data.</li>
</ul></p>
</div>
<br><hr><br>

<div>
<h3>What you need to build this project</h3>
<p>

<ul>
  <li>Hardware</li>
    <ol type="1">
    <li>Arduino Nano ATmega328</li>
    <li>GSM/GPRS Shield SIM900</li>
    <li>Ublox NEO-7M GPS Module </li>
    <li>CAN Bus Module - MCP2515</li>
    <li>Step-Down Voltage Regulator 7V 1A</li>
    <li>Step-Down Voltage Regulator 5V 3A</li> 
    <li>OBD-II 16 pin male</li>
    </ol>
  <li>Software</li>
  <ol type="1">
  <li>Termite 2.6</li>
  <li>SocketTest3</li>
  <li>CAN Hacker 2</li>
  <li>OBD Simulator</li>
  </ol>
</ul>
Note: you can use Socet Test 3 to send and receive packets via GSM. For that you will need to add a port forwarind rule at your router and then create a rule at Windows Firewall to accept the packets at your port/IP.
</div>
<br><hr><br>

<div>
<h3>Wiring</h3>
<p>
<img src="https://apaliampelos.me/assets/images/github/rdt0001_circuit.png" alt="Wiring diagram"/>
Wire components as the diagram above
</p>
