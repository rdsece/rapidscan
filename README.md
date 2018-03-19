[![GitHub issues](https://img.shields.io/github/issues/skavngr/rapidscan.svg)](https://github.com/skavngr/rapidscan/issues)
[![GitHub forks](https://img.shields.io/github/forks/skavngr/rapidscan.svg)](https://github.com/skavngr/rapidscan/network)
[![GitHub stars](https://img.shields.io/github/stars/skavngr/rapidscan.svg)](https://github.com/skavngr/rapidscan/stargazers)
[![GitHub license](https://img.shields.io/github/license/skavngr/rapidscan.svg)](https://github.com/skavngr/rapidscan/blob/master/LICENSE)

# :diamonds: RapidScan - _The Multi-Tool Web Vulnerability Scanner_

                          
## Evolution:
> It is quite a fuss for a pentester to perform _**binge-tool-scanning**_ (_running security scanning tools one after the other_) sans automation. Unless you are a pro at automating stuff, it is a herculean task to perform binge-scan for each and every engagement. The ultimate goal of this program is to solve this problem through automation; viz. **running multiple scanning tools to discover vulnerabilities, effectively judge false-positives, collectively correlate results** and **saves precious time**; all these under one roof.<p>Enter **RapidScan**.

## Why RapidScan?
- **one-step installation**.
- **executes a multitude of security scanning tools**, does other **custom coded checks** and **prints the results spontaneously**.
- some of the tools include `nmap, dnsrecon, wafw00f, uniscan, sslyze, fierce, lbd, theharvester, dnswalk, golismero` etc executes under one entity.
- saves a lot of time, **indeed a lot time!**.
- **checks for same vulnerabilities with multiple tools** to help you **zero-in on false positives** effectively.
- **legends** to help you understand which tests may take longer time, so you can `Ctrl+C` to skip if needed. (_~**under development**~_)
- **vulnerability definitions** guides you what the vulnerability actually is and the threat it can pose. (_under development_)
- **remediations** tells you how to plug/fix the found vulnerability. (_under development_)
- **executive summary** gives you an overall context of the scan performed with critical, high, low and informational issues discovered. (_under development_)
- **artificial intelligence** to deploy tools automatically depending upon the issues found. for eg; automates the launch of `wpscan` and `plecost` tools when a wordpress installation is found. (_under development_)

---
### FYI:
- _program is still under development, **works** and currently supports :six::six: vulnerability checks._
- _parallel processing is not yet implemented, may be coded as more checks gets introduced._

## Tests For
- :heavy_check_mark: DNS/HTTP Load Balancers & Web Application Firewalls.
- :heavy_check_mark: Checks for Joomla, WordPress and Drupal
- :heavy_check_mark: SSL related Vulnerabilities (_HEARTBLEED, FREAK, POODLE, CCS Injection, LOGJAM, OCSP Stapling_).
- :heavy_check_mark: Commonly Opened Ports.
- :heavy_check_mark: DNS Zone Transfers using multiple tools (_Fierce, DNSWalk, DNSRecon, DNSEnum_).
- :heavy_check_mark: Sub-Domains Brute Forcing.
- :heavy_check_mark: Open Directory/File Brute Forcing.
- :heavy_check_mark: Shallow XSS, SQLi and BSQLi Banners.
- :heavy_check_mark: Slow-Loris DoS Attack, LFI (_Local File Inclusion_), RFI (_Remote File Inclusion_) & RCE (_Remote Code Execution_).
- & more coming up...

## Requirements
- Python 2.7
- Kali Linux 2.0 or Rolling Distro. (_the latest the distro, the better the tool performs._)

## Usage
**Download the script and give executable permissions**
- `wget -O rapidscan.py https://raw.githubusercontent.com/skavngr/rapidscan/master/rapidscan.py && chmod +x rapidscan.py`

**Run the script**
- `./rapidscan.py example.com`

## Help
- `./rapidscan.py --update`: updates scanner to latest version.
- `./rapidscan.py --help`:   displays help context.

## Output

![rapidscan intro](https://github.com/skavngr/rapidscan/blob/master/splashscreen_rapidscan_intro.PNG)
![rapidscan outro](https://github.com/skavngr/rapidscan/blob/master/splashscreen_rapidscan_outro.PNG)

## Contribution
- https://gist.github.com/MarcDiethelm/7303312

