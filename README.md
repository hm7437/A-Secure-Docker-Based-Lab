# A Secure Docker Based Lab 
TCS iON RIO-125 Project

This project sets up a fully isolated and configurable penetration testing lab using Docker containers deployed on an AWS EC2 Ubuntu instance. The environment simulates real-world attack surfaces and supports security testing tools like Nmap, Metasploit, Wireshark (Dockerized), and more.

Designed to be scalable and secure, the lab isolates networks, controls port exposure, and simulates typical server environments using custom-built Docker images.

---

🔧 Features

- 🐳 Containerized Infrastructure  
  - Ubuntu-based containers for different roles (e.g., Python, Java, Web Server, MySQL)
  - Static IP and private subnet networking
  - Controlled port exposure for security

- ☁️ AWS Cloud Integration
  - EC2 (Ubuntu) setup with Docker and AWS CLI
  - IAM role-based access with least privilege principle

- 🔐 Security-Focused Setup
  - Tools: `nmap`, `metasploit`, `wireshark` (via Docker), `hydra`, `john`, `nessus`
  - Penetration testing and vulnerability scanning ready
  - Secured through private Docker networks and minimized surface area

- 🔬 Test Environment Ready
  - Custom containers for running vulnerable services or applications
  - Supports manual and automated attack/defense scenarios
