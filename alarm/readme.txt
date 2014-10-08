Andrew Brieff

Correctly Implemented:
For the Live Stream:
Detects Credit Card numbers
Detects XMAS scans
Detects NULL scans

For the Log:
Detects NMAP scans
Detects Shellcode
Detects HTTP errors

Collaboration: Got idea to use Apache Log Regex gem from Daniel Griffin

Time spent: ~5 hours

1. Are the heuristics used in this assignment to determine incidents "even that good"?
    No, the heuristics used in this assignment will only detect a very small percentage of potential intrusions, and only the most basic ones. 
    For example, we do not account for any number of other stealthy possible scans, only accounting for the null and xmas scans.
2. If you have spare time in the future, what would you add to the program or do differently with regards to detecting incidents?
  If I have spare time in the future, I would implement detectors for various other scans, and look to log suspicious get requests made to the 
  server to make sure the web pages visited were not downloading unwanted data.