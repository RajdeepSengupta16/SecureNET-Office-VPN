# SecureNET-Office-VPN

# Office Virtual Private Network (VPN) – Java Project

A secure VPN solution for office environments, developed using Java Servlets, JSP, and deployed on Apache Tomcat. The app provides office staff with a private virtual network for secure communication, internal marketing management, and training—all via a simple web dashboard.

## Features
- Secure, encrypted communication (simulated in Java)
- Multiple modules: Admin, Marketing, Training/Networking
- Deployed on Apache Tomcat server
- Role-based access and monitoring
- Frontend dashboard (HTML/JavaScript)

## Technologies
- Java, Java Servlets, J2EE
- Apache Tomcat Server
- HTML, JavaScript (UI)

## How to Run
1. Deploy `/src` and `/web` on your Tomcat webapps directory.
2. Configure `web.xml` for servlet mapping.
3. Start Tomcat and access the app via `http://localhost:8080/vpn-office-java`.
4. Login as admin or user as appropriate.

## Modules
- **Admin:** User data and security policies
- **Marketing:** Secure marketing document sharing
- **Training:** Networking/test sessions

---

*For demo purposes, encryption and tunneling are simulated with Java logic. For production, integration with native VPN or OS modules is needed.*

## Authors
- Rajdeep Sengupta

## License
- MIT
