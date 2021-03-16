# ProxyLogon

ProxyLogon is the formally generic name for CVE-2021-26855, a vulnerability on Microsoft Exchange Server that allows an attacker bypassing the authentication and impersonating as the admin. We have also chained this bug with another post-auth arbitrary-file-write vulnerability, CVE-2021-27065, to get code execution. (source: [proxylogon.com](https://proxylogon.com))

## Disclaimer
The information provided on this Github repository is for educational purposes only. All information on this Github is provided in good faith, however I make no representation or warranty of any kind, express or implied, regarding the accuracy, adequacy, validity, reliability, availability, or completeness of any information.

## Getting Started

If you want to test the vulnerability do so on your systems only

```python
python ProxyLogon.py <hostname> <email>
```

## Screenshot
![ProxyLogon](https://raw.githubusercontent.com/RickGeex/ProxyLogon/main/proxylogon_screenshot.png)

## Credits

This proof of concept is created based on info from Github user testanull (https://github.com/testanull) and the related blog post: https://testbnull.medium.com/ph%C3%A2n-t%C3%ADch-l%E1%BB%97-h%E1%BB%95ng-proxylogon-mail-exchange-rce-s%E1%BB%B1-k%E1%BA%BFt-h%E1%BB%A3p-ho%C3%A0n-h%E1%BA%A3o-cve-2021-26855-37f4b6e06265


