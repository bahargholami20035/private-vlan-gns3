# Private VLAN Implementation in GNS3

This project demonstrates a practical implementation of Private VLANs (PVLANs) within a simulated network environment using GNS3.  It showcases a common use case for enhancing security and network segmentation.

**Key Features:**

*   **Topology:**  Star topology with a central Layer 2/3 switch (Cisco IOSvL2) and various servers (simulated using VPCS).
*   **Private VLAN Configuration:**  Includes a Primary VLAN (500), an Isolated VLAN (999), and a Community VLAN (600).  Proper port assignments (Promiscuous, Isolated, Community) are configured.
*   **Network Services:**  Simulates a realistic network with services such as:
    *   Web Server (Isolated)
    *   Email Server (Community)
    *   Automation Server (Community)
    *   Antivirus Server (Promiscuous)
    *   Domain Controller (Promiscuous)
    *   Router (for external connectivity)
*  **Security Focus**: Implemented to enhance security by segregating network traffic, limiting the attack surface, and controlling access.
* **Tested**: Includes ping test to validate communication.

**GNS3 Project Files:**

The repository includes the GNS3 project file (.gns3) and configurations, allowing you to directly import and run the simulation.

**How to Use:**

1.  Download and install GNS3 and the necessary Cisco IOSvL2 images.  (You'll need to provide the IOS images yourself due to licensing.)
2.  Clone this repository.
3.  Open the `.gns3` project file in GNS3.
4.  Start the devices and explore the configuration.

**Learning Outcomes:**

This project provides a hands-on example for understanding:

*   Private VLAN concepts (Primary, Isolated, Community VLANs).
*   Configuration of PVLANs on Cisco switches.
*   Network segmentation and security best practices.
*   Basic GNS3 usage for network simulation.

**Note:**  This project was developed as a student project and may have limitations due to the use of IOSvL2 within GNS3.  It serves as a good starting point for learning about PVLANs.

**contributing**
Feel free to fork the repository and improve upon it.

**Author**: Fatemeh Gholami.
