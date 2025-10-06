## 🌐 Network Services

This section is dedicated to the network-related services that I configure and experiment with in my homelab.  
The goal is to simulate how real-world IT infrastructure works inside enterprises, and to give myself a  
hands-on lab for networking, security, and system administration.

Here are some of the services I’ve already set up or plan to explore:

- **Firewall (pfSense / iptables / firewalld)**  
  To protect and segment my homelab network. I use firewalls to manage traffic between VMs, block unauthorized access, and practice advanced rules like NAT and masquerading.  

- **VPN (WireGuard / OpenVPN)**  
  For secure remote access into my lab when I’m outside my local network. This allows me to connect back to my VMs safely, as if I were at home.  

- **DNS (Bind9 / Pi-hole / Unbound)**  
  Running my own DNS server to resolve internal hostnames (like `server.patuyyy.local`) and experimenting with DNS-level ad-blocking.  

- **Mail Server (Postfix / Dovecot)**  
  Testing email services inside the lab, including SMTP/IMAP setup. This is great for learning how mail delivery, spam filtering, and TLS/SSL certificates work.  

- **Reverse Proxy & Load Balancer (NGINX / HAProxy)**  
  Managing multiple applications with subdomains (e.g., `server.patuyyy.com`, `monitoring.patuyyy.com`) and experimenting with load balancing techniques.  

---

### Purpose
By building these services, I’m aiming to:
- Improve my understanding of **network security** and **traffic management**.  
- Recreate real-world scenarios of enterprise infrastructure.  
- Have a flexible platform to test new tools and technologies.  

This section will grow over time as I keep experimenting and learning. 
