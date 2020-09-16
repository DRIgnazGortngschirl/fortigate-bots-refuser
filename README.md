# fortigate-bots-refuser

# How to use
1. git clone the repo
2. Read and accept Terms and Conditions 
3. Execute with test mode ```./fortigate-bots-refuser.sh -t```

```
mario@michels-server:~/fortigate-bots-refuser$ ./fortigate-bots-refuser.sh -h
[i]: Init start
Usage ./fortigate-bots-refuser.sh [OPTIONS]
      OPTIONS
          -h, --help          Prints out this help page
          -r, --remove        Starts the removal process
          -p, --removeautopolicy    Removes the already configured policy ID. New polcy ID will be Autoconfigured if enabled
          -t, --test          Will not push config to FortiGate (What would happen)
```
