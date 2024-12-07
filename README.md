# VRV_Python_assignment
<b><h3>Log Analysis Script</h3></b>
<p>
<b>This Python script analyzes web server log files to extract useful insights, including:</b>
<ol>
<li><b>IP Request Counts:</b> Tracks the number of requests made by each IP address.</li>
<li><b>Most Accessed Endpoint:</b> Identifies the most frequently accessed endpoint (GET/POST/PUT/DELETE requests).</li>
<li><b>Suspicious Activity Detection:</b> Flags IP addresses with a high number of failed login attempts (e.g., status code 401 or "Invalid credentials").</li>
</ol>
<b>The script outputs the results in two formats:</b>

<ul>
  <li><b>Terminal Output:</b> Displays the data in a human-readable format.</li>
  <li><b>CSV File:</b> Saves the analysis in a structured CSV file for further examination.</li>
</ul>
<b>Key Features:</b>
<ul>
<li>Efficient parsing of log files with regular expressions.</li>
<li>Detection of suspicious activity based on failed login attempts.</li>
<li>Clean, modular code with clear documentation.</li>
<li>Ideal for monitoring web server activity and identifying potential security issues.</p></li></ul>
