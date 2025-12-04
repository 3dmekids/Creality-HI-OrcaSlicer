<h1 align="center">🅲🆁🅴🅰🅻🅸🆃🆈 🅷🅸</h1>
<h1 align="center">🅾🆁🅲🅰 - 🆂🅻🅸🅲🅴🆁 🅲🅰🅼🅴🆁🅰 🅵🅸🆇</h1>

<p align="center">
  <strong>Full Orca Slicer Setup Guide for Creality Hi / Hi-Pro / K1 / K1C / K1 Max<br>(HiOS 2024–2025)</strong>
</p>

<hr>

<h2>📸 Correct Camera Stream for Orca Slicer</h2>

<p>
This guide enables <strong>full camera support</strong> in Orca Slicer for all Creality Hi-Series printers.<br>
If your HiOS camera doesn't appear in Orca, this fix forces Orca to accept the correct MJPEG stream.<br><br>
Orca will <strong>NOT</strong> auto-detect the correct camera type unless this manual URL is entered.
</p>

<hr>

<h2>✅ Working Camera Stream URL</h2>

<p>Use this in Orca:</p>

<pre>
http://&lt;your_printer_IP&gt;:8000/webcam/?action=stream
</pre>

<ul>
  <li>✔ Works on all HiOS versions</li>
  <li>✔ Smooth low-latency MJPEG stream</li>
  <li>✔ Compatible with Orca’s Camera Preview & Timelapse</li>
</ul>

<hr>

<h2>🛠 How to Add This in Orca Slicer</h2>

<ol>
  <li>Open <strong>Orca Slicer</strong></li>
  <li>Go to <strong>Printer Settings</strong> (wrench icon)</li>
  <li>Select <strong>Machine → Cameras</strong></li>
  <li>Add a camera or edit the existing one</li>
  <li>Use the following values:</li>
</ol>

<h3>Camera URL Stream</h3>
<pre>
http://&lt;your_printer_IP&gt;:8000/webcam/?action=stream
</pre>

<h3>Camera Snapshot URL</h3>
<pre>
http://&lt;your_printer_IP&gt;:8000/webcam/?action=stream
</pre>

<h3>Stream Type</h3>
<pre>HTTP page</pre>


<img width="617" height="641" alt="image" src="https://github.com/user-attachments/assets/730b37a8-2135-4f39-ae75-d1c35bcd878f" />

  
<img width="1027" height="586" alt="image" src="https://github.com/user-attachments/assets/3a482d23-127b-4e52-b476-b11dc9784786" />



<h2 align="center"><font color="red"><b>I am using a Creality Nebula Cam</b></font></h2>




<p align="center">
  <img width="538" height="447" alt="image" src="https://github.com/user-attachments/assets/6fa9e694-81fb-443f-a470-29444957a67a" />

<h3
