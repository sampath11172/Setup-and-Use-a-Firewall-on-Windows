# TASK: Setup-and-Use-a-Firewall-on-Windows


## Objective
To configure Windows Defender Firewall to block Telnet (port 23) and allow SSH (port 22).

## Steps Followed

### 1. Opened Firewall Settings
Used `wf.msc` to open Advanced Firewall Settings.

### 2. Created Inbound Rule to Block Telnet
- Created a new inbound rule for TCP port 23.
- Set it to "Block the connection".

### 3. Tested the Block
- Used Telnet to test port 23.
- Connection was refused as expected.

### 4. Allowed SSH Port 22
- Created a rule to allow TCP port 22.

### 5. Removed the Telnet Block Rule
- Deleted the block rule to restore firewall to original state.

## Summary
Windows Firewall helps in filtering traffic based on port rules. Blocking Telnet increases security because it's an insecure protocol. SSH is allowed as it's more secure.

