ARP Spoofing Detector
Objective: Create a network security tool to detect ARP spoofing attacks in realtime.
Features:
• ARP Traffic Monitoring: Capture and analyze ARP packets
• Spoofing Detection: Identify duplicate IP-MAC mappings
• Alert System: Notify administrators of attacks
• Attack Visualization: Show network topology changes
• Logging & Reporting: Record attack details
how to run :
cd ~
source arp_env/bin/activate
You should see:

(arp_env)
pip install scapy pandas matplotlib colorama.
sudo $(which python) arp_spoof_detector.py -i en0 -n 192.168.1.0/24

