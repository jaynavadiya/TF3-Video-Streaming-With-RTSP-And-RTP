# Goal: Make a streaming video server and client
Application Layer: RTSP - Real Time Streaming Protocol
RTP - Real Time Transfer Protocol

## Objective of the project: 
-Implement RTSP Protocol in Client
-Implement RTP Packetization in Server

## Already Provided:
- RTSP Protocol in Server
- RTP de-packetization in Client

## Code Part
1. Client.py, ClientLauncher.py
	- ClientLauncher.py, Opens UI which is used for sending RTSP commands
	- Implement: In Client.py, Implement the actions that are taken when the buttons are pressed
	- No modification: ClientLauncher.py

2. Server.py, ServerWorker.py
	- Implements the server together
	- Already Implemented: RTSP interaction 
	- ServerWorker.py, calls methods from RtpPacket.py to packetize the video data
	- No modification: Server.py, ServerWorker.py

3. RtpPacket.py
	- Handles RTP Packets
	- Already Implemented: Methods for handling received packets on client side
	- Already Implemented, No Modification: De-packetization of data
	- Implement: the video data RTP Packetization (used by the server)

4. VideoStream.py
	- Used to read data from the file
	- No modification: VideoStream.py
