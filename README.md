# Tricopter-Arduino-NRF24L01-PPM-
This is final tricopter project with Arduino Nano 328p, Multiwii 2.3, PPM Transceiver NRF24L01 and BMP085

<h2>Main Wiring (Flight Controller Y-Copter/Tricopter)</h2>
<img src="https://github.com/ArduJimmy/Tricopter-Arduino-NRF24L01-PPM-/blob/main/Main-Wiring.jpg" title="Main Wiring (Flight Controller Y-Copter" alt="Main Tricopter Schematic Diagram"/>

<br />

<h2>Receiver Wiring</h2>
<p>Connect pin D2 of Arduino Promini to pin D2 Arduino Nano</p>

<img src="https://github.com/ArduJimmy/Tricopter-Arduino-NRF24L01-PPM-/blob/main/PPM_Receiver_Wiring.jpg" title="PPM Receiver Wiring" alt="PPM Receiver Arduino Project" />

<h2>Transmitter Wiring</h2>
<p>Please pay attention of the explanation about Transmitter. Actually, I build the transmitter for Double Usage: Multiwii drone (including Tricopter, Quadcopter, etc). That;s why the wiring and the codes will include one SWITCH.</p>

<p>Terjemahan: TOlong perhatikan dengan seksama untuk diagram wiring transmitter ini karena aku membuatnya untuk DUAL TX, Dual TX berarti, transmitter ini bisa digunakan untuk drone Tricopter dan lainnya misal: arduino car, balancingWii /self balancing robot (lihat Channel YT Ardujimmy untuk tutorialnya).</p>

<ul>
  <li>SWITCH ON: Drone / Tricopter</li>
  <li>SWITCH OFF: BalancingWii or Arduino Car, etc.</li>
</ul>

<img src="https://github.com/ArduJimmy/Tricopter-Arduino-NRF24L01-PPM-/blob/main/Transmitter-Wiring.jpg" title="Tricopter Transmitter" alt="Dual TX Wiring" />

<h2>MULTIWIICONF GUI</h2>
<p>Karena kita menggunakan BMP180 maka konfigurasi mutlwiiconf GUI sbb: (note: BMP180 adalah hal <strong>WAJIB</strong> membantu servo menyesuaikan diri melalui modul barometer)</p>

<img src="https://github.com/ArduJimmy/Tricopter-Arduino-NRF24L01-PPM-/blob/main/konfigurasi_multiwiiConf_GUI.PNG" alt="multiwiiconf GUI Tricopter" title="MultiwiiConf GUI pada Tricopter"/>
<br />
<p>Tutorial video dan tes terbang silahkan cek di: https://www.youtube.com/watch?v=1LeyG4wXDZA</p>
