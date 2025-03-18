---
layout: help
title: Internal SOP - Train Booking
---

## Step 1 – Ensure Agent’s Email is Mapped with the Account  

- Use the **Zoho form iframe** to verify if the agent’s email is linked to their account.  

## Step 2 – Manage Zoho Ticket Creation  
 
- Once the email is submitted in the Zoho form, ensure a ticket is created automatically on Zoho Desk.  

![Ticket submitted successfully](/empages/images/help/Internal SOP - Train Booking/IP1.png)

## Step 3 – Assist Agents in Obtaining MAC Address & Device ID  

### Steps to Find the **MAC Address** Using Command Prompt (CMD)  

**Method 1: Using `getmac` Command** 

1. Press **`Win + R`**, type **`cmd`**, and press **Enter** to open the Command Prompt.  
2. To obtain the DeviceID, type the following command and press **Enter**:  

    ```sh
    getmac
    ```

![DEVICE ID](/empages/images/help/Internal SOP - Train Booking/IP2.png)

3. To obtain **MAC address** of active network adapters write the following command **getmac \v \fo list**
![MAC address of active network adapters](/empages/images/help/Internal SOP - Train Booking/IP3.png)

**Method 2: Using `ipconfig /all` Command**  

1. Open **Command Prompt** (press **`Win + R`**, type **`cmd`**, and hit **Enter**).  
2. Type the following command and press **Enter**:  

    ```sh
    ipconfig /all
    ```
3. Scroll through the output and find the **"Physical Address"** for your network adapter (Wi-Fi, Ethernet, or Bluetooth).  
4. The **Physical Address** listed is your **MAC address**.  

![To find mac address of device](/empages/images/help/Internal SOP - Train Booking/IP4.png)
### **Notes:**  

- The **MAC address** format is typically **XX-XX-XX-XX-XX-XX**.  
- Each network adapter (Wi-Fi, Ethernet, Bluetooth) has a different MAC address.  
- If multiple adapters are listed, locate the **active** one (e.g., "Wireless LAN adapter" for Wi-Fi users).  

## Step 4 – Email MOS Team for ID Activation  

Send an email to the **MOS team** with the following agent details for ID activation:  

- **Name**  
- **Mobile number**  
- **Ekocode**  
- **Email**  
- **K-code**  
- **MAC Address**  
- **Device ID**  
- **Aadhaar & PAN copies**  

### Sample Email Format  

Subject: Request for IRCTC ID Activation  

Dear MOS Team,  

Kindly help in activating the IRCTC ID for the following user as per the attached details:  

**User Details:**  
Name: Vijay Kumar  
Mobile Number: 7037470402  
CSP Code: 36305001  

**Additional Details:**  
MAC Address: F4-D1-08-E6-DA-20  
Device ID: \Device\Tcpip_84039C3B-043E-42BC-B723-CB0FDA1CCF4B  
Email: kumarvijay.eps@eko.co.in  
K Code: identity_value: 579451  

Please process the request at the earliest and confirm once activated.  

Best Regards,  
[Your Name]  
[Your Contact Information] 

## Step 5 – Notify MOS After Aadhaar Verification  

- Once the **Aadhaar verification** is successfully completed, notify the MOS team to proceed with the ID activation.