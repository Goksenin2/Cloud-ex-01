# CLOUD-EX-01: Connecting a Cloud Service

## Objective
Create a GCP virtual machine, open ICMP (ping), and verify connectivity from a local machine.

## Steps

1. **Create GCP Project**  
   - New project named `myfirstproject`.

2. **Enable Compute Engine**  
   - Enabled the Compute Engine API.

3. **Launch VM Instance**  
   - VM named `myfirstmachine`  
   - Machine type `e2-micro`, Debian 11 boot disk.

4. **Configure Firewall**  
   - Created a rule `allow-icmp` on network `default` allowing protocol `ICMP` from `0.0.0.0/0`.

5. **Find External IP**  
   - Obtained `34.154.72.151` from the VM instances page.

6. **Ping Test**  
   ping 4 34.154.72.151
