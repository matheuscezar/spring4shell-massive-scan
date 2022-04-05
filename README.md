# spring4shell-massive-scan

This project is a bash script that aims to scan a list of URLs to identify if they are vulnerable to Spring4Shell (CVE-2022-22965). It is not possible to say if this scanner is 100% reliable, but it is a good starting point. It is worth noting that the vulnerability occurs in specific paths, so it is recommended to perform a reconnaissance of existing paths before running this tool.

Usage:

```
chmod +x scan.sh
./scan.sh wordlist.txt
```

