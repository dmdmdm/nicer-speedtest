# nicer-speedtest
Slightly nicer speedtestRetrieving speedtest.net server list.

# Improvement
- Only shows what its 'Retrieving speedtest.net configuration', 'Retrieving speedtest.net server list', 'Selecting best server based on ping'
while they are in progress - then they are erased.
- Displays progressbars for download and upload

# Example output
    Testing from ISP (1.2.3.4)...
    Hosted by ISP (City, XX) [2.19 km]: 7.107 ms
    Download: 123.98 MB/s
    Upload: 123.61 MB/s

# Requirements
Works with python3-speedtest-cli-2.1.2-4.fc33.noarch at least.
