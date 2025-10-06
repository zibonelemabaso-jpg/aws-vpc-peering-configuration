# aws-vpc-peering-configuration
Configured inter-VPC communication using VPC Peering to enable private connectivity between isolated networks in AWS.

# AWS VPC Peering Configuration

This project was completed as part of the **CloudSec Network AWS Bootcamp**.  
It demonstrates the configuration of **inter-VPC communication** using **VPC Peering** in Amazon Web Services (AWS).

---

## 🧠 Objective of the Task
The primary objective of this task was to **configure and implement inter-VPC communication** through **VPC Peering** within the AWS environment.  
This exercise simulated a real-world scenario in which two separate virtual networks (VPCs) must communicate securely and efficiently **without traversing the public internet**.

---

## ⚙️ Steps Undertaken

1. **Creation of Two Virtual Private Clouds (VPCs)**  
   - Created two distinct VPCs, each with its own **CIDR block**, representing isolated network environments.

2. **Subnet Configuration**  
   - Configured subnets within each VPC to logically divide the IP address range and support resource deployment.

3. **Establishment of a VPC Peering Connection**  
   - Initiated a **VPC peering request** from one VPC and directed it to the other, enabling private communication between the two networks.

4. **Acceptance of the Peering Request**  
   - Accepted the request in the recipient VPC to establish mutual trust and enable bidirectional data flow.

5. **Route Table Modifications**  
   - Updated the **route tables** in both VPCs to include routes directing traffic to the peer network via the peering connection.
   - Ensured that all traffic between the two networks flows securely through the peering link.

6. **Validation of Connectivity**  
   - Tested communication between instances in both VPCs to confirm successful private connectivity.

---

## 📸 Deliverables
Included in the `/screenshots` folder:
- The two created VPCs in AWS Console  
- Active VPC Peering Connection  
- Updated Route Tables showing peer routes  
- Successful connectivity test results  

---

## 🧩 Skills Demonstrated
- AWS VPC Configuration  
- Network Segmentation  
- Routing and Peering  
- Secure Inter-VPC Communication  
- AWS Networking Best Practices  

---

## 🧰 Tools & Services Used
- Amazon VPC  
- Subnets  
- VPC Peering  
- Route Tables  
- EC2 Instances for Validation  

---

## 📚 Author
**Zibonele “Rone” Mabaso**  
Full Stack Developer | AWS Cloud Computing Student  
[LinkedIn Profile]www.linkedin.com/in/mpendulo-mabaso-50a1b8315) | [GitHub Profile](https://github.com/zibonelemabaso-jpg)
