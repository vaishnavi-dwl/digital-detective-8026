## Task 7.1: Network concepts

| Concept | Explanation in my own words | Example |
|---|---|---|
| LAN (Local Area Network) | A network that connects devices within a small area, such as a home, school, or office. | Computers and printers connected to the same home Wi-Fi. |
| MAN (Metropolitan Area Network) | A network that connects devices or smaller networks across a city or large campus. | A network connecting several university buildings across a city. |
| WAN (Wide Area Network) | A network that connects devices or networks over large geographical distances. | The Internet, which connects networks around the world. |
| DNS (Domain Name System) | A system that translates website names into IP addresses that computers use to locate servers. | Translating example.com into an IP address. |
| Router | A device that connects different networks and forwards data between them. | A home Wi-Fi router connecting your devices to the Internet. |
| Protocol | A set of rules that devices follow to exchange information over a network. | HTTP and HTTPS are protocols used for web communication. |
| Packet switching | A method of sending data by splitting it into smaller packets that travel across a network and are reassembled at the destination. | Sending a photo over the Internet. |
| Client-server | A communication model where a client requests information or a service and a server responds. | A browser (client) requesting a webpage from a web server. |

## Task 7.2: Observing network information

| Question | Answer |
|---|---|
| What does a connectivity test check? | A connectivity test checks whether my computer can communicate with another device or website over a network. It can also show response time and whether packets are lost. |
| What information does a DNS lookup display? | A DNS lookup displays information about a domain name, including the IP address associated with it and the DNS server that provided the answer. |
| What is the role of DNS when entering a website name? | DNS finds the IP address associated with the website name so the browser can locate and communicate with the correct server. |

**My observations**

| Test | Observation |
|---|---|
| Connectivity test | `ping -c 4 example.com`: 4 packets transmitted, 4 packets received, 0.0% packet loss. Round-trip min/avg/max/stddev = 9.691/11.675/14.174/1.659 ms |
| DNS lookup | Server:8.8.8.8   Address:	8.8.8.8#53  Non-authoritative answer:   Name:	youtube.com    Address: 142.251.221.174 |
| What I learned | The connectivity test checks communication, while DNS lookup finds the IP address associated with a domain name. |

## Task 7.3: What happens when I open a website

1. **The client makes a request:** I enter a website name in my browser. The browser acts as the client and prepares to request the webpage.
2. **DNS finds the server address:** The browser uses DNS to find the IP address associated with the website's domain name.
3. **The network forwards the request:** My computer sends data through the local network and router. The router forwards it towards the destination server.
4. **The server receives the request:** The web server receives the browser's request and processes it. The client and server communicate using network protocols such as HTTPS.
5. **The server sends a response:** The server sends the requested webpage data back across the network in packets.
6. **The browser displays the webpage:** The browser receives and processes the response, loads the necessary content, and displays the website on the screen.
