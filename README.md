# -Mini-Project-Basic-Network-Topology-using-Cisco-Packet-Tracer
## 🖼️ 1. Network Topology Diagram

![Network Topology](diagram.png)

> The diagram shows a simple LAN setup using one router, one switch, and three PCs, all connected with straight-through cables.

---

## 🧮 2. IP Address Table

| Device  | Interface           | IP Address     | Subnet Mask     | Default Gateway |
|---------|---------------------|----------------|------------------|------------------|
| PC0     | N/A                 | 192.168.1.2    | 255.255.255.0    | 192.168.1.1      |
| PC1     | N/A                 | 192.168.1.3    | 255.255.255.0    | 192.168.1.1      |
| PC2     | N/A                 | 192.168.1.4    | 255.255.255.0    | 192.168.1.1      |
| Router  | GigabitEthernet0/0  | 192.168.1.1    | 255.255.255.0    | N/A              |
| Switch  | FastEthernet0/1     | N/A            | N/A              | N/A              |
---
## 📶 3. Ping Test Result

```plaintext
Cisco Packet Tracer PC Command Line 1.0
C:\>ping 192.168.1.3

Pinging 192.168.1.3 with 32 bytes of data:

Reply from 192.168.1.3: bytes=32 time<1ms TTL=128
Reply from 192.168.1.3: bytes=32 time<1ms TTL=128
Reply from 192.168.1.3: bytes=32 time=1ms TTL=128
Reply from 192.168.1.3: bytes=32 time<1ms TTL=128

Ping statistics for 192.168.1.3:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 0ms, Maximum = 1ms, Average = 0ms

C:\>
