
Incident Report Analysis Using NIST CSF

Project Description:
This project demonstrates the application of the National Institute of Standards and Technology's (NIST) Cybersecurity Framework (CSF) to analyze and respond to a cybersecurity incident. The scenario involves a Distributed Denial of Service (DDoS) attack on a multimedia company, which compromised its internal network for two hours. The report includes a detailed analysis of the event, identification of vulnerabilities, and a comprehensive response and recovery plan to improve the organization's network security.

---

1. Identify
   
Summary of the Security Event:
- Type of Attack: Distributed Denial of Service (DDoS) attack.
- Cause: A flood of ICMP packets overwhelmed the internal network due to an unconfigured firewall.
- Impact: Internal network services were non-responsive for 2 hours, disrupting normal operations.
- Targeted Systems: The company’s network resources and internal services.
- Attack Source: A malicious actor using spoofed IP addresses to send a flood of ICMP packets.

---

2. Protect
   
Immediate Action Plan:
- Update and configure firewalls to block excessive ICMP traffic and prevent similar attacks.
- Implement firewall rules to limit the rate of incoming ICMP packets.
- Enforce source IP address verification to detect and block spoofed packets.
- Regularly audit network configurations to identify gaps like unconfigured firewalls.
- Provide training for the IT team on identifying and responding to DDoS attacks.

---

3. Detect
   
Monitoring and Analysis Plan:
- Deploy network monitoring software to detect unusual traffic patterns and alert the security team.
- Use Intrusion Detection and Prevention Systems (IDS/IPS) to identify and block suspicious traffic in real time.
- Implement log analysis tools to analyze historical data and identify attack patterns.
- Track incoming traffic by categorizing trusted and non-trusted IP addresses.
- Establish automated alert systems to notify stakeholders about potential incidents.

---

4. Respond
   
Response Plan for Future Incidents:
- Containment: Immediately block traffic from identified malicious IP addresses and isolate affected systems.
- Neutralization: Temporarily disable all non-critical services while addressing the source of the attack.
- Analysis: Use logs from the IDS/IPS and monitoring tools to trace the attack’s origin and method.
- Mitigation: Reconfigure firewalls and update security protocols based on insights from the attack.
- Establish a communication plan to inform stakeholders of ongoing issues and resolutions.

---

5. Recover
   
Recovery Steps:
- Immediate Information Needs: Access to IDS/IPS logs, backup configurations, and incident response documentation.
- Restoration Process:
  1. Bring critical network services back online in a controlled manner.
  2. Verify the integrity of restored systems to ensure no residual vulnerabilities.
  3. Validate that all new firewall rules and monitoring configurations are functioning as intended.
- Long-Term Recovery Improvements:
  - Conduct a post-incident review to identify lessons learned.
  - Update the organization’s Incident Response Plan to include specifics on handling DDoS attacks.
  - Schedule regular penetration testing to ensure the network remains hardened against future attacks.
