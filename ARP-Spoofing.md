# ARP Spoofing (ARP Poisoning)

## 📌 Overview
ARP Spoofing (also known as ARP Poisoning) is a **Man-in-the-Middle (MITM)** attack technique used in local area networks (LAN).  
In this attack, an attacker sends fake ARP replies to associate their MAC address with the IP address of another device (usually the gateway).

---

## 🧠 What is ARP?
**ARP (Address Resolution Protocol)** maps an IP address to a MAC address in a local network.

Example:
- IP: `10.200.36.132`
- MAC: `08-00-27-1f-b7-23`
![Image](https://github.com/user-attachments/assets/53af3773-7f70-4128-9169-519c2e40814f)

![Image](https://github.com/user-attachments/assets/80ef34a0-73cb-4594-abc0-1bb29396c2ec)

ARP has **no authentication**, which makes it vulnerable.

---

## ⚔️ How ARP Spoofing Works
1. Attacker scans the local network
2. Attacker sends forged ARP replies
3. Victim believes attacker is the router
4. Traffic passes through attacker

![Image](https://github.com/user-attachments/assets/e82406fa-aeea-4ad3-946e-e9fb1f805562)
   
5. Attacker can sniff, modify, or block data

 
 Screenshot Before attack


![Image](https://github.com/user-attachments/assets/ed7813ef-aa97-4b3a-903f-ab0d8754fcc1)
 
 Screenshot after attack


![Image](https://github.com/user-attachments/assets/512bb170-2a1f-448e-ad88-3b266f310ece)
---

## 🎯 Impact of ARP Spoofing
- Packet sniffing
- Session hijacking
- Credential theft
- DNS spoofing
- MITM attacks

---

## 🛡️ Prevention Techniques
- Use **Static ARP entries**
- Enable **Dynamic ARP Inspection (DAI)**
- Use **HTTPS / TLS**
- Monitor ARP tables
- Use IDS/IPS systems

---

## 🧪 Learning Environment
This concept should be practiced only in:
- Virtual labs
- Test networks
- CTF challenges
- Authorized environments

---

## ⚠️ Disclaimer
This repository is created **strictly for educational and ethical purposes only**.  
Any misuse of this knowledge is the sole responsibility of the user.

---
