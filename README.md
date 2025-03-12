# Host server troubleshooting
<br>
<h2>Description</h2>
The host server, responsible for hosting the cloud environment for the clients, failed. The server became unresponsive, and IPMI was also non-functional. I was tasked with investigating the issue and resolving it as quickly as possible.
<h2>My Role</h2>
As the technician assigned to troubleshoot the issue, I employed a systematic approach and a variety of troubleshooting methods. I also contacted the server's primary provider for system diagrams and additional information to assist with the investigation.
<h2>Technical Trobleshooting</h2>
First I followed a systematic approach, starting by inspecting the internal components to check for any loose connections. During my inspection, I found no visible damage on the motherboard. After further investigation, I decided to test the CPUs to identify any potential issues. This specific motherboard uses dual CPUs, so I tested one CPU at a time to determine if one had failed.

I started by testing CPU number one, which successfully loaded the BIOS. After removing CPU one, I installed CPU number two and attempted to boot the server. However, with CPU number two installed, the server failed to respond, and I observed red indicator lights on the server. From this, I concluded that CPU number two had failed. Additionally, upon further inspection, I noticed one of the motherboard connections was defective.

<h2>Issues encountered</h2>
<li>CPU Failure: Unfortunately, CPU number two had failed, preventing the server from booting when installed.</li>
<li>Defective Motherboard Connector: After further inspection, I discovered that one of the connectors soldered to the motherboard was damaged, which contributed to the failure of the system.</li>
<li>Dual CPU Dependency: Since the system uses a dual-CPU configuration, I was unable to boot the server with just a single CPU. This caused additional complications, as part of the SSD was not accessible without both CPUs functioning.</li>
<li>Need for Replacement Parts: At this point, it became clear that both the motherboard and CPU would need to be replaced by the manufacturer, which would extend the resolution time.</li>
<h2>Solution</h2>
<li>Opened Support Ticket: Initiated a support ticket with the manufacturer to address the issue with the server.</li>
<li>Scheduled Teams Conference: The manufacturer scheduled a Teams conference to discuss the solution and clarify the next steps.</li>
<li>Discussed Solution and Timeline: During the conference, we discussed the proposed solution and the estimated time for receiving the replacement parts.</li>
<li>Fast Shipping: Shipping was expedited, and we successfully agreed on a two-day shipping timeframe for the replacement parts.</li>
<li>einstallation Process: Once the replacement parts arrived, the reinstallation process was straightforward and efficient.</li>
<li>System Operational: After reinstallation, the entire environment was fully operational and running without any issues.</li>

<h2>Technical Skills</h2>
<li>Hardware Diagnostics</li>
<li>Server Management</li>
<li>System Testing and Component Isolation</li>
<li>Collaboration with Vendor and Support</li>
<li>Problem Solving and Critical Thinking</li>
<li>Knowledge of Server Architecture Dual CPU Configuration</li>
<li>Cloud Infrastructure Understanding</li>
<li>Installation and Reinstallation of Hardware</li>
<h2>Results</h2>
<li>Issue Resolution: The server issue was successfully identified and resolved by replacing the faulty CPU and motherboard connection.</li>
<li>System Stability Restored: After the hardware replacement and reinstallation, the server environment was restored to full functionality without any further issues.</li>
<li>Minimal Downtime: Due to fast shipping and efficient reinstallation, the system was back up and running within a short timeframe, minimizing downtime for the client.</li>
<li>Client Satisfaction: The solution met the client’s needs, ensuring the continued stability and reliability of their cloud environment.</li>

