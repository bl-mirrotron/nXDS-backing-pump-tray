# Backing Pump System
* <a href="https://github.com/bl-mirrotron/nXDS-backing-pump-tray" target="_blank">Source code</a>
* [Vacuum system overview](https://bl-mirrotron.github.io/#vacuum-system)
* [Control system overview](https://bl-mirrotron.github.io/)

The exhaust of each turbo pump is pumped with an <a href="https://shop.edwardsvacuum.com/products/a73701983/view.aspx" target="_blank">Edwards nXDS15i</a> dry pump used as a backing pump as shown in Figure 1. The backing pump has a 15 pin logic connection as shown in Figure 2. The logic interface can be configured to communicate with a RS232 connection as shown in Figure 3. This RS232 interface can then be transformed into a USB interface with a <a href="https://www.electrokit.com/en/product/usb-rs232-converter-for-pc/" target="_blank">USB-RS232 converter</a> and then connected to a Raspberry Pi computer as shown in Figure 4.

The tray code is written in the <a href="https://nodered.org/" target="_blank">Node-RED</a> programming environment. The tray code uses a modified Blinky-Lite template for ASCII serial communication using Blinky-Bus as shown in Figure 5.

<p></p><p style="text-align:center;font-size: large;"><span style="font-weight: bold;color: green;">Figure 1. </span> <span style="font-style: italic;">RFQ Vacuum system layout</span></p>
<div style="width:100%;text-align:center;"><img width="100%" style="border-style:solid;border-color:#1c6e97;" src="doc/VacuumLayout.png"/></div><br>

<p></p><p style="text-align:center;font-size: large;"><span style="font-weight: bold;color: green;">Figure 2. </span> <span style="font-style: italic;">Edwards nXDS15i dry pump</span></p>
<div style="width:100%;text-align:center;"><img width="100%" style="border-style:solid;border-color:#1c6e97;" src="doc/backingPumpDiagram.png"/></div><br>

<p></p><p style="text-align:center;font-size: large;"><span style="font-weight: bold;color: green;">Figure 3. </span> <span style="font-style: italic;">RS232 connection to backing pump logic interface</span></p>
<div style="width:100%;text-align:center;"><img width="100%" style="border-style:solid;border-color:#1c6e97;" src="doc/BPRS232Connection.png"/></div><br>

<p></p><p style="text-align:center;font-size: large;"><span style="font-weight: bold;color: green;">Figure 4. </span> <span style="font-style: italic;">USB-RS232 converter to a Raspberry Pi 3B</span></p>
<div style="width:100%;text-align:center;"><img width="100%" style="border-style:solid;border-color:#1c6e97;" src="doc/backingPumpZoom.jpg"/></div><br>

<p></p><p style="text-align:center;font-size: large;"><span style="font-weight: bold;color: green;">Figure 5. </span> <span style="font-style: italic;">Backing pump tray flow</span></p>
<div style="width:100%;text-align:center;"><img width="100%" style="border-style:solid;border-color:#1c6e97;" src="doc/backingPumpFlow.png"/></div><br>
