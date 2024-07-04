# Analyze Network Traffic using Wireshark
              
**Step 1: Launch Wireshark:**

 ![Screenshot1](/images/SS1.JPG)
 
**Step 2: Capture Interfaces:**
Click on ‘Capture’ -> ‘Options’ or the gear icon in the toolbar to see a list of available network interfaces.
Identify and select the interface through which you want to capture network traffic (e.g., Wi-Fi).
 
 ![Screenshot2](/images/SS2.JPG)

**Step 3: Capturing Network Traffic:**
**Start Capturing:**
Select the desired network interface.
Click the shark fin icon (Start Capturing Packets) or press ‘Ctrl+E’.
Wireshark will start capturing all the packets flowing through the selected interface.

 ![Screenshot3](/images/SS3.JPG)
 
**Generate Traffic:**
Perform normal network activities such as browsing the web, streaming videos, or downloading files. 

 ![Screenshot4](/images/SS4.JPG)
 
 Stop Capturing:
 Click the red square icon (Stop Capturing Packets) or press ‘Ctrl+E’ again to stop capturing.

 ![Screenshot5](/images/SS5.JPG)

 
**Step 4: Analyzing Captured Data:**
**Basic Filtering:**
Use the display filter bar at the top to filter specific types of traffic.
    HTTP traffic: ‘http’
 
 ![Screenshot6](/images/SS6.JPG)

**Filter by IP address: ‘ip.addr == 10.0.0.159’**

 ![Screenshot7](/images/SS7.JPG)

**Filter DNS traffic: ‘dns’**
 
 ![Screenshot8](/images/SS8.JPG)


**Step 5: Inspecting Packets:**
Click on any packet in the Packet List Pane to highlight it.
The Packet Details Pane will show detailed information about the selected packet, broken down byprotocol layers (e.g., Ethernet, IP, TCP/UDP).
Expand the sections to view more details about each protocol layer.
The Packet Bytes Pane shows the raw data (hexadecimal and ASCII) of the selected packet.
 
 ![Screenshot9](/images/SS9.JPG)

 ![Screenshot10](/images/SS10.JPG)


**Step 6: Advanced Analysis:**
**Using Statistics:**
   Protocol Hierarchy:
    Go to ‘Statistics’ -> ‘Protocol Hierarchy’.
This shows a breakdown of all protocols used in the captured traffic.

 ![Screenshot11](/images/SS11.JPG)
 
 ![Screenshot12](/images/SS12.JPG)
 
**Conversations:**
   Go to ‘Statistics’ -> ‘Conversations’.
This provides detailed information about communication between network endpoints.

 ![Screenshot13](/images/SS13.JPG)

**Endpoints:**
      Go to ‘Statistics’ -> ‘Endpoints’.
 Lists all IP addresses involved in the capture, with details about data sent and received.

 ![Screenshot14](/images/SS14.JPG)
   
**IO Graphs:**
     Go to ‘Statistics’ -> ‘IO Graphs’.
Allows you to visualize traffic patterns over time. Customize the graph to highlight specific protocols or traffic types.

 ![Screenshot15](/images/SS15.JPG)
 
**Flow Graphs:**
    Go to ‘Statistics’ -> ‘Flow Graph’.
 This visualizes the sequence of packet exchanges between hosts, useful for understanding the flow of a session.
 
![Screenshot16](/images/SS16.JPG)

![Screenshot17](/images/SS17.JPG).

**Expert Information:**
   Go to ‘Analyze’ -> ‘Expert Information’.
This displays potential issues detected by Wireshark, such as retransmissions, packet loss, or malformed packets.

 ![Screenshot18](/images/SS18.JPG)

**Step 7: Reporting and Documentation:**
**Generating Reports:**
Export specific capture data or statistics by going to ‘File’ -> ‘Export Packet Dissections’ -> ‘As CSV’/’As XML’/’As Plain Text’.
Save the capture file for sharing or further analysis by going to ‘File’ -> ‘Save As’ and choosing the appropriate format.

 ![Screenshot19](/images/SS19.JPG)

 ![Screenshot20](/images/SS20.JPG)

 

