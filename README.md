<p align="center"><img src="https://raw.githubusercontent.com/ayushsharma82/WebSerial/master/docs/logo.svg?sanitize=true" width="450"></p>

<hr/>

<p align="center">
<!-- <img src="https://img.shields.io/travis/com/ayushsharma82/WebSerial.svg?style=for-the-badge" />
&nbsp; -->
<img src="https://img.shields.io/github/last-commit/ayushsharma82/WebSerial.svg?style=for-the-badge" />
&nbsp;
<img src="https://img.shields.io/github/license/ayushsharma82/WebSerial.svg?style=for-the-badge" />
&nbsp;
<a href="https://www.patreon.com/bePatron?u=16780597" target="_blank"><img src="https://img.shields.io/badge/patreon-donate-orange.svg?style=for-the-badge&logo=patreon" /></a>
</p>

<hr/>

<br/>

<p><b>WebSerial</b> is a Serial Monitor for <b>ESP8266</b> & <b>ESP32</b> Microcontrollers that can be accessed remotely via a web browser. Webpage is stored in program memory of the microcontroller.</p>

<br/>

<h2>Preview</h2>
<p align="center"><img src="https://raw.githubusercontent.com/ayushsharma82/WebSerial/master/docs/webserial.PNG" width="850"></p>

<br/>
<br/>
<br/>

<h2>Features</h2>
<p>
  <ul style="list-style-position: inside;">
      <li>Works on Websockets</li>
      <li>Realtime logging</li>
      <li>Any number of Serial Monitors can be opened on the browser</li>
      <li>Uses Async Webserver for better performance</li>
  </ul>
</p>

<br/>
<br/>

<h2>Dependencies</h2>
<p>
  <h5>For ESP8266:</h5>
  <ul style="list-style-position: inside;">
      <li>ESP8266 Arduino Core - <b>v2.5.0</b></li>
      <li>ESPAsyncTCP - <b>v1.2.0</b></li>
  	  <li>ESPAsyncWebServer - <b>v1.2.0</b></li>
  </ul>
  
  <h5>For ESP32:</h5>
  <ul style="list-style-position: inside;">
      <li>ESP32 Arduino Core - <b>v1.0.1</b></li>
      <li>AsyncTCP - <b>v1.0.3</b></li>
  	  <li>ESPAsyncWebServer - <b>v1.2.0</b></li>
  </ul>
</p>

<br/>

<h2>How to Install</h2>

###### Directly Through Arduino IDE ( Currently Submitted for Approval. Use Mannual Install till it gets Approved.)
Go to Sketch > Include Library > Library Manager > Search for "WebSerial" > Install

###### Manual Install

For Windows: Download the [Repository](https://github.com/ayushsharma82/WebSerial/archive/master.zip) and extract the .zip in Documents>Arduino>Libraries>{Place "WebSerial" folder Here}

For Linux: Download the [Repository](https://github.com/ayushsharma82/WebSerial/archive/master.zip) and extract the .zip in Sketchbook>Libraries>{Place "WebSerial" folder Here}

###### Manually through IDE

Download the [Repository](https://github.com/ayushsharma82/WebSerial/archive/master.zip), Go to Sketch>Include Library>Add .zip Library> Select the Downloaded .zip File.

<br>

<h2>Documentation</h2>
<p>WebSerial is very similar to the default Serial Monitor Library of Arduino.</p>

Please see `Demo` examples for better understanding on how to setup WebSerial for your Project: [Click Here](https://github.com/ayushsharma82/WebSerial/blob/master/examples/ESP8266_Demo/ESP8266_Demo.ino)


WebSerial has 2 main functions:
- `print`
- `println`


`print` - simply prints the data sent over WebSerial without any newline character.


`println` - prints the data sent over WebSerial with a newline character.


Both functions support the following datatypes: `String`, `const char`, `char`, `int`, `uint8_t`, `uint16_t`, `uint32_t`, `double`, `float`.


<b>To Access Webserial:</b> Go to `<IP Address>/webserial` in your browser ( where `<IP Address>` is the IP of your ESP).

<br>

<h2>Contributions</h2>
<p>Every Contribution to this repository is highly appriciated! Don't fear to create pull requests which enhance or fix the library as ultimatly you are going to help everybody.</p>
<p>
If you want to donate to the author then <b>you can become my patron</b>, It really helps me keep these libraries updated:
<br/><br/>
<a href="https://www.patreon.com/bePatron?u=16780597" target="_blank"><img src="https://img.shields.io/badge/patreon-donate-orange.svg?style=for-the-badge&logo=patreon" /></a>
</p>
<br/>
<br/>


<h2>License</h2>
ESP-DASH is licensed under General Public License v3 ( GPLv3 ).
<br/>
<br/>
<img src="https://img.shields.io/github/license/ayushsharma82/WebSerial.svg?style=for-the-badge" />
</div>
