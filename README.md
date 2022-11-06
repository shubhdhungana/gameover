# GAMEOVER
> An automated web app hacking &amp; reconnaissance tool. I built this tool initially for my own automated web app hacking and reconnaissance purpose. Since, it was a lot helpful for me, so thought of giving back to the community.


# Features
i) Collecting php endpoints urls, fetching js files and its endpoints. Finding hidden links from js files.
ii) Automated subdomain enumeration using tools like **assetfinder, subfinder, amass**.
iii) Filtration of live subdomains using grep and **httpx tool**.
iv) Checking for open ports for subdomains using tool called **httprobe**.
v) Automated and fast screenshotting of all possible fetched subdomains using tool called **aquatone**.
vi) Fetching urls and other endpoints using tools called **gau** and **waybackurls**.
vii) Fetching vulnerable patterns for **xss, ssrf, sqli, open-redirect, idor,** etc. using tool called **gfpattern**
viii) Searching for hidden web directories using tool called **dirsearch**.
ix) Automated bug finding using nuclei tool.

# Installation
i) First Step:
```
git clone https://github.com/shubhdhungana/gameover
```

ii) Second Step:
```
cd gameover
```

iii) Third Step:
```
chmod u+x gameover
```

iv) Final STep:
```
./gameover target.com
```

## Note:
i) You should install these tools in your system before you use this automated tool:
- gfpattern
- dirsearch
- assetfinder
- subfinder
- waybackurls
- amass
- httpx and httprobe
- aquatone
- gau
- nuclei
- linkfinder
- uro

ii) Create one folder named **automation_embedded_tools** in your desktop. Put the folder named **automation_embedded_tools** in your system desktop. Install 3 tools ie. dirserach, linkfinder and nuclei-templates inside **automation_embedded_tools** folder. All the tools can be found on github
iii) Finish. Thank You :)
iv ) Any Queries: shubhdhungana@gmail.com
