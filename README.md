# Networking-Fundamentals
OSI Model Layers Explanation
The OSI stands for Open System Interconnection. The OSI Model has seven layers. Each layer does a specific job in moving data across a network. Also, each layer can only communicate with corresponding layers. That is, only the layers directly above and/or below it.
A popular mnemonic for remembering the seven layers is: Please Do Not Throw Sausage Pizza Away.
Let’s say we want to download a movie from the internet to your device, here’s how the data moves using the OSI Model..
 
1. Application Layer: This is the user interface where the download happens. You use a web browser or app to click “download” and start the process.

2. Presentation Layer: In this layer, the data is converted to a readable format. It is a translation layer. Here, data is encrypted, translated and compressed. For instance, the movie may be compressed to reduce file size and to ensure it travels faster too. When it gets to your device, it is decompressed and maybe converted to a playable format to enable you watch it properly.

3. Session Layer: This layer ensures that connection between your device and the server is maintained while downloading. If the session breaks, the movie download will either pause or fail.

4. Transport Layer: This layer breaks data into smaller packets or segments.The movie you are downloading is split into small data packets before being sent and then reassembled when it gets to your device.. 

5. Network Layer: The network layer attaches the IP address and finds the best path for the data(the movie) to travel through. It uses the IP addresses of the website's server and your device and then finds the best route to send the movie to your device.

6. Data Link Layer: This layer ensures that the data (in this case, the movie) is sent to the right device using MAC addresses. It also detects errors in transmission and corrects them.
  
7. Physical Layer: This layer has to do with physical connections like cables, hardware, switches, fiber-optics or Wi-Fi signals. It breaks the data into 0’s and 1’s. You have to be connected to the internet first before you can even start downloading.
##How the TCP/IP protocol suite operates across layers
This model has four layers and here is how it works using a real-life scenario such as loading a website. Say, the M4Ace website.

1. Application Layer: You type in www.m4ace.com. Your browser then sends a request to the m4ace’s server. The HTTP or HTTPS protocol is used to request the webpage and the DNS protocol helps find the IP address of m4ace.

2. Transport Layer: The request is then broken down into smaller packets to travel through the internet. The TCP ensures that the packets arrive correctly and in order.

3. Internet Layer: Each packet is assigned two IP addresses, source and destination. That is, yours and m4ace’s. The IP protocol then determines the best route to send the packets.

4. Network/Link Layer: The packets travel through mobile networks, Wi-Fi, etc. until they get to m4ace’s server. The server processes the request and sends back the webpage contents like text, images, HTML and other data in packets. Your browser reassembles the packets to display the m4ace website properly.
