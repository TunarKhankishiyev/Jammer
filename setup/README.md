# 🛠️ Setup & Wiring

> ⚠️ Authorized lab use only. Ensure your environment is RF-shielded or fully isolated.

## Prerequisites

- Arduino IDE or PlatformIO with the ESP32 board package
- Libraries: `U8g2`, `RF24`

## Wiring

<table>
<tr>
<td valign="top">
<b>SPI bus (all three radios)</b><br><br>
<table>
<tr><th>Signal</th><th>ESP32 GPIO</th></tr>
<tr><td>SCK</td><td>GPIO 18</td></tr>
<tr><td>MISO</td><td>GPIO 19</td></tr>
<tr><td>MOSI</td><td>GPIO 23</td></tr>
</table>
</td>
<td valign="top">
<b>NRF24L01+ modules</b><br><br>
<table>
<tr><th>Radio</th><th>CE</th><th>CSN</th></tr>
<tr><td>Radio A</td><td>GPIO 5</td><td>GPIO 17</td></tr>
<tr><td>Radio B</td><td>GPIO 16</td><td>GPIO 4</td></tr>
<tr><td>Radio C</td><td>GPIO 15</td><td>GPIO 2</td></tr>
</table>
</td>
</tr>
<tr>
<td valign="top">
<b>OLED (SH1106, I2C)</b><br><br>
<table>
<tr><th>Signal</th><th>ESP32 GPIO</th></tr>
<tr><td>SDA</td><td>GPIO 13</td></tr>
<tr><td>SCL</td><td>GPIO 14</td></tr>
</table>
</td>
<td valign="top">
<b>Buttons &amp; accessories</b><br><br>
<table>
<tr><th>GPIO</th><th>Function</th></tr>
<tr><td>GPIO 25</td><td>Left / Back</td></tr>
<tr><td>GPIO 26</td><td>Up / Toggle</td></tr>
<tr><td>GPIO 27</td><td>Right / Data rate</td></tr>
<tr><td>GPIO 32</td><td>Select</td></tr>
<tr><td>GPIO 33</td><td>Down / Channel</td></tr>
<tr><td>GPIO 12</td><td>Passive buzzer</td></tr>
</table>
</td>
</tr>
</table>
