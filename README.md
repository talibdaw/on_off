This code for the esp8266 component and more specifically the component (esp8266_01S) is to be used with an application on a smartphone with an Android operating system that sends two words (on and off) and the code or Sketch on esp8266 performs certain actions when it recognizes the word on or off such as switching a relay on the appropriate output pin of the esp8266.


Here you can find this application: ..................


first step:To communicate with the ESP8266, you must first activate the wifi on your smartphone,among the proposed networks select AutoConnectapp.

Then  enter the name of your network and your  your password .



second step: If you are using your smartphone as a router then enter the name of your phone and the secret code of your phone network.
Your phone will then assign an IP number to the ESP8266 that you can see in your configuration menu by finding the devices connected to your phone in the personal networks menu.
the IP number assigned to the ESP8266 will be visible, memorize it it will be useful to save it in your ESP HOME application.

If you are using your home router then enter the name of your home network and the secret code of your home network.
Your home network will then assign an IP number to the ESP8266.

To find the IP address assigned to your ESP8266 go to your router's web page by typing its IP number in the address bar:

1. Find the IP address of your router:

On Windows:
Open the command prompt by searching for "cmd" in the search bar and selecting "Command Prompt".
Type "ipconfig" and press Enter.
Search for "Default Gateway". The IP address indicated is that of your router.

On macOS:

Open System Preferences, then click on Network.
Select your network connection (Wi-Fi or Ethernet) from the list.
Click on the "Advanced" button, then on the TCP/IP tab.
Your router’s IP address is listed next to “Router.”

Common IP Addresses: The most common IP addresses for routers are:

192.168.0.1
192.168.1.1
192.168.2.1
10.0.0.1

2. Access your router’s interface:

Open a web browser (Chrome, Firefox, Safari, Edge, etc.).
Type your router’s IP address into the address bar and press Enter.
A login page should appear.

3. Log in to your router’s interface:

You will need to enter a username and password.
Common default login information:
Username: admin / Password: admin
Username: admin / Password: (leave blank)
Username: user / Password: user
If this information does not work, consult your router's documentation or contact your Internet Service Provider. You can also try searching the internet for the exact model of your router followed by "default password".
4. Find the list of connected devices:

Once logged into your router's interface, look for a section titled:
"Connected Devices"
"Connected Clients"
"Connected Peripherals"
"Network Status"
"Dashboard"
This section will display a list of devices connected to your network, usually with their hostname, IP address, and MAC address.
The IP number assigned to the ESP8266 will be visible, remembering it will be useful for registering it in your ESP HOME app.


third step: make sure that your wifi on your smartphone is enabled then launch ESP HOME app.

step four: press the + button on the top right of your smartphone screen and add the ip number given earlier and the description of what the esp8266 controls.



Additional Note:
When using your phone's Wi-Fi network, the control distance between ESP8266 and your phone is about 150 meters, so you can use it anywhere outdoors or at home as long as this distance is not exceeded.
If you are using your home network's Wi-Fi, ESP8266 can only be used at home and not when traveling outdoors because the limit is still 150 meters.
