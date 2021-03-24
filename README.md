# nicer-speedtest
Slightly nicer speedtestRetrieving speedtest.net server list.

# Improvements
- Only shows what its 'Retrieving speedtest.net configuration', 'Retrieving speedtest.net server list', 'Selecting best server based on ping'
while they are in progress - then they are erased.
- Displays progressbars for download and upload

# Example output
    Testing from ISP (1.2.3.4)...
    Hosted by ISP (City, XX) [2.19 km]: 7.107 ms
    Download: 123.98 Mb/s
    Upload: 123.61 Mb/s

# Requirements
Tested with with python3-speedtest-cli-2.1.2-4.fc33.noarch

# Installation
On Fedora:
    `dnf install python3-speedtest-cli`
 
Drop nicer-speedtest into your /usr/local/bin
    `chmod a+x nicer-speedtest`
