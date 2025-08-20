# Wireless-Network-Design

**English:**
Wireless network design is the process of planning and deploying Wi-Fi to ensure coverage, performance, and security for all users. It involves choosing access point (AP) locations, channels, frequency bands, and capacity planning.

**Urdu:**
Wireless network design ka matlab hai Wi-Fi ka plan banana taa ke har jagah proper coverage mile, users ke liye speed theek ho aur security bhi strong ho. Isme APs ka placement, frequency aur channel selection important hota hai.

### Wireless Site Survey

**English:**
A site survey is the process of analyzing the physical environment where Wi-Fi will be deployed. It helps identify coverage gaps, interference, and best AP placement.

**Urdu:**
Site survey ka matlab hai us area ka survey karna jahan Wi-Fi lagana hai. Isme check karte hain ke signal kahan strong hai, kahan weak hai aur kahan interference zyada hai.

### Site Survey Considerations

**English:**
When doing a survey, engineers consider:

**Building Structure**– walls, glass, metal (block signals).

**Coverage Area** – indoor, outdoor, floors.

**User Density** – how many devices will connect.

**Interference Sources** – microwaves, Bluetooth, other Wi-Fi.

**AP Placement** – ceiling, wall, hidden areas.

Power & Cabling availability.

**Urdu:**
Survey karte waqt in cheezon ka khayal rakhte hain:

Walls aur materials jo signal rok sakte hain

Kitni area cover karna hai

Kitne users connect karenge

Interference sources jaise microwave, dusra Wi-Fi

AP ka sahi jagah placement

Power aur cable availability

### Predictive Site Survey

**English:**
Predictive survey uses software tools (like Ekahau, AirMagnet) to create a virtual wireless model of the building before physical installation. It predicts coverage and helps in initial design.

**Urdu:**
Predictive survey ek software based survey hoti hai jisme building ka map banake Wi-Fi ka virtual model banaya jata hai taa ke estimate mile coverage aur interference ka.

### Wireless Access Survey (Active + Passive)

**English:**

**Active Survey:** Engineer connects to APs, measures actual throughput, latency.

**Passive Survey:** Just listens to wireless signals (no active connection).

**Urdu:**

Active survey me AP se connect hokar speed aur latency test karte hain.

Passive survey me sirf signals sunte hain aur data collect karte hain.

### Wireless Heatmap

**English:**
A heatmap is a visual representation of Wi-Fi coverage, showing areas of strong (green) and weak (red) signal strength.

**Urdu:**
Wireless heatmap ek visual map hota hai jo dikhata hai signal kaha strong hai (green) aur kaha weak hai (red).

### Heatmap Visualization

**English:**
Tools generate heatmaps with:

Signal Strength (RSSI)

Noise & Interference

Data Rates

Channel Overlap

**Urdu:**
Heatmap visualization se apko idea milta hai ke:

Signal strength kahan weak hai

Noise/interference kahan zyada hai

Kis area me data rate slow hai

Channel overlap kaha ho raha hai

### Set Service Identifier (SSID)

**English:**
SSID = Wi-Fi network name. Best practices:

Use unique SSID (not default)

Hide SSID (optional for extra obscurity)

Different SSIDs for guest & enterprise users

**Urdu:**
SSID Wi-Fi ka naam hota hai. Best practice hai ke:

Default naam (jaise TP-Link123) change karo

Guest aur staff k liye alag SSIDs rakho

Zarurat ho to SSID hide bhi kar sakte ho

### Wireless Discovery Technology

**English:**
Wireless discovery means scanning for Wi-Fi networks and devices using tools like Wireshark, Kismet, NetSpot. Attackers also use discovery to find vulnerable networks, so admins must monitor regularly.

**Urdu:**
Wireless discovery ka matlab hai Wi-Fi networks ko scan aur detect karna. Isme legit admins bhi karte hain aur hackers bhi. Tools jaise Wireshark aur Kismet is kaam me use hote hain.

### Wireless Security Hardening

**English:**
Steps to harden Wi-Fi networks:

Use WPA3 (or WPA2-AES if WPA3 not supported).

Disable WEP & WPA-TKIP (weak).

Strong & unique SSID and passwords.

Enable RADIUS / 802.1X for enterprise.

Use MAC filtering & VLAN segmentation.

Disable WPS (Wi-Fi Protected Setup).

Regular firmware updates on APs/routers.

**Urdu:**
Wireless ko secure karne ke liye:

WPA3 use karo (ya WPA2-AES).

Purane protocols (WEP, TKIP) disable karo.

Strong passwords rakho.

Enterprise network me RADIUS authentication use karo.

Guest aur staff k liye separate VLANs banao.

WPS band karo (easy hack hota hai).

APs aur routers ka firmware update karte raho.

### In short:

**Design:** Plan coverage, performance, security.

**Survey:** Check environment (walls, users, interference).

**Predictive survey:** Software modeling.

**Heatmap:** Visualize signal coverage.

**SSID:** Unique, separated for guest vs enterprise.

**Discovery:** Scanning networks (admin + attackers).

**Hardening:** WPA3, strong passwords, VLANs, disable weak protocols.
