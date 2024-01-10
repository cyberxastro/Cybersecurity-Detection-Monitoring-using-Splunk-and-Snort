# Linkedin
[![](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gauravss03/)
# Portfolio 
[![](https://img.shields.io/badge/Portfolio-255E63?style=for-the-badge&logo=About.me&logoColor=white)](https://gauravsuryawanshi.pages.dev/)
# Medium Page 
[![](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@gauravss3703/detection-and-monitoring-using-snort-and-splunk-35ec5924bcfb)



# Cybersecurity Detection & Monitoring using Splunk and Snort

![snort+splunk](https://github.com/astroxhacker/Cybersecurity-Detection-Monitoring-using-Splunk-and-Snort/assets/109857735/a7f589cb-1f76-4389-9d91-72d3b0ae09f8)


This project focuses on enhancing cybersecurity measures through effective detection and monitoring using two powerful tools, Splunk and Snort. Splunk, a robust data analytics and visualization platform, is utilized for log management and analysis, while Snort, an open-source intrusion detection and prevention system, adds a layer of real-time threat detection. The integration of these tools provides a comprehensive solution for identifying and responding to potential security threats within a network.

# Key Features:

1. Splunk Integration: Leverage Splunk for centralized log management, analysis, and visualization.
2. Snort Implementation: Deploy Snort for real-time intrusion detection and prevention.
3. Custom Dashboards: Develop intuitive dashborads within Splunk for monitoring and reporting security incidents.
4. Alerting System: Implement and alerting mechanism to notify administrators of potential threats in real-time.
5. Documentation: Through documentation to guide users theough the setup, confuguration, and maintenance of the cybersecurity infrastructure [HERE](https://medium.com/@gauravss3703/detection-and-monitoring-using-snort-and-splunk-35ec5924bcfb)


# If you want the detailed Steps, please visit the Medium Page [HERE](https://google.com)

This repository provides a step-by-step guide to set up a robust cybersecurity environment using Splunk and Snort. The project involves hosting Splunk on Linode, configuring Snort for intrusion detection, and integrating both tools to enhance network security.


# Implementation:

  Begin by setting up Splunk on Linode, leveraging the provided link for $100 in free credit. Ensure that port 9997 is open for Splunk data forwarding.
  Access your Splunk instance at the Linode IP:8000, configure data forwarding, and install Snort Alert for Splunk through the Splunk App Marketplace. Followed by this, install Snort on your Ubuntu VM and perform a quick test to verify that Snort logs are generated. Monitor these logs for incoming pings to ensure Snort is functioning correctly.
  Next, set up the Splunk Universal Forwarder on your VM. Download and install it, then add your Splunk server for log forwarding. Ensure that configurations are correct and that the IP is accurate for your Splunk server.

Configure Splunk to monitor Snort alert logs, and customize Splunk configurations for optimal performance. Test the Network Intrusion Detection System (NIDS) by downloading a binary file from GitHub and running attacks on an isolated VM. Check if Snort logs capture these activities.

Encourage users to explore customization features within Splunk and Snort, such as creating custom dashboards, extracting fields, and labeling data for effective visualization. The repository also provides detailed documentation for troubleshooting and learning from practical experiences.


Benefits:
  
  This repository offers a comprehensive guide to fortifying cybersecurity using Splunk and Snort. Learn to set up Splunk on Linode, ensuring smooth data forwarding on port 9997. Access and configure Splunk through Linode's IP, integrating Snort Alert for Splunk via the App Marketplace. Install Snort on your Ubuntu VM, run tests, and monitor logs for effective intrusion detection.

Uses:
1. Establish a robust cybersecurity environment.
2. Monitor and analyze network activity in real-time.
3. Utilize Snort for intrusion detection and prevention.
4. Leverage Splunk's data analytics and visualization for effective log management.

# Conclusion:
  Conclude by summarizing the successful setup of a working Splunk environment with Snort.
