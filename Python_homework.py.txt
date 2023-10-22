Create a Python script that can determine if a particular IP address (192.168.0.1) belongs to the router or a lease.

print("Enter an IP address")
x = input()
if x == "192.168.0.1":
    print("Router")
else:
    print("Lease")