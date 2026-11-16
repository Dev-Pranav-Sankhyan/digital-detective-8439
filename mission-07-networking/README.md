# Mission 7 - How computers communicate

## 1. Task / objective
Explain basic network types, observe network connectivity, and describe what happens when a website loads.

## 2. Work completed
Filled out the network concepts table, ran a ping and DNS lookup in the terminal, and wrote down the steps of how a website opens.

### Task 7.1 Explain network concepts

| Concept | Explain it in your own words | Example |
| :--- | :--- | :--- |
| LAN | A network covering a small area | My hostel Wi-Fi network |
| MAN | A network covering a city or large campus | The university's main campus network |
| WAN | A network covering large geographical areas | The Internet itself |
| DNS | Translates a domain name into an IP address | Turning google.com into 142.250.x.x |
| Router | Connects networks and forwards data | The physical Wi-Fi router on my floor |
| Protocol | A set of rules devices follow to communicate | HTTP or HTTPS for web browsing |
| Packet switching | Data is divided into packets to travel | Downloading a game update in small chunks |
| Client-server | A client requests a service and a server provides it | My Mac asking a web server for a webpage |

### Task 7.2 - Observe network information
*   **What a connectivity test checks:** A `ping` test checks if another computer/website is actually reachable and how fast the connection is.
*   **What a DNS lookup displays:** It shows the exact IP address that is tied to a domain name.
*   **Role of DNS:** It acts like a phonebook. When I type a website name, DNS finds the exact IP address the computer needs to connect to it.

### Task 7.3 - What happens when you open a website?
1. The **client** (my web browser) takes the website URL I typed.
2. The browser asks the **DNS** server to find the IP address for that domain.
3. The DNS server replies with the correct IP address.
4. My computer sends a request through my **router** and out to the internet using the HTTP/HTTPS **protocol**.
5. The **server** at that IP address receives the request and sends the website data back to me.
6. My browser puts the data together and displays the webpage.

## 3. Commands / tools used
*   **Terminal**: Used `ping` to test connectivity and `nslookup` for DNS.
*   **Git**: To commit the files.

## 4. My understanding
Networks are just computers talking to each other. Because computers only understand IP addresses (like phone numbers), DNS exists so humans can just use easy names (like google.com). Protocols are the rules that make sure the data arrives correctly.

## 5. Difficulties faced
None.

## 6. How I resolved them
N/A.

## 7. Evidence / files
*   `mission-07-networking/README.md` (this file)

## 8. Commit details
Commit message used: "Explain networking concepts and website communication". Pushed to GitHub.