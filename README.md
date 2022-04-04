# Invoke-sAMSpoofing
CVE-2021-42287/CVE-2021-42278 exploits in powershell

## Table of content
* [Overview](#Overview)
* [Menu](#Menu)
* [Screenshots](#Screenshots)
* [References](#References)

### Overview
A simple script to attack AD with CVE-2021-42287/CVE-2021-42278 exploits automatically.

### Menu
 - Invoke-sAMSpooofing
 - Invoke-GoldenTicket
 - Invoke-GoldenTips
 - RemoveMachineAccount 
 - Invoke-Rubeus
 - ADSIHound
 - Invoke-DCSync

### Screenshots
 - Invoke-sAMSpooofing  
 ![image](https://user-images.githubusercontent.com/30458572/161235503-67e882c1-32d4-479c-8f3b-faade0c39af6.png)
 ![image](https://user-images.githubusercontent.com/30458572/161314691-fbb6059b-5440-48c6-a80c-51452cd42af0.png)

 - Invoke-GoldenTicket (Just krbtgt hashes needed)
 ![image](https://user-images.githubusercontent.com/30458572/161314913-d8f1b489-b778-4a8b-9589-a7d69d2b72ce.png)
 ![image](https://user-images.githubusercontent.com/30458572/161314959-86eb3237-382a-401e-bbb9-eae8a09da42f.png)
   
   Golden ticket also injected into memory and generate to file.  
   ![image](https://user-images.githubusercontent.com/30458572/161317716-b5407954-4a03-43b7-be2d-c50278c504aa.png)

 - Invoke-GoldenTips  
 ![image](https://user-images.githubusercontent.com/30458572/161371534-1a1037e4-617b-47d3-9505-2940ad0f3015.png)

 - RemoveMachineAccount (Need domain admins privileges, also you can do this after create golden ticket.)  
 ![image](https://user-images.githubusercontent.com/30458572/161236648-8ce72238-2d48-4794-97d0-5d5a667cc152.png)
 
 - Invoke-Rubeus  
 ![image](https://user-images.githubusercontent.com/30458572/161241261-b5e5f4f8-29d9-4412-ae3e-1298d45b5625.png)

### References
 - [3gstudent: Retrieves all users ntlm hashes from AD](https://3gstudent.github.io/%E5%9F%9F%E6%B8%97%E9%80%8F-%E5%88%A9%E7%94%A8DCSync%E5%AF%BC%E5%87%BA%E5%9F%9F%E5%86%85%E6%89%80%E6%9C%89%E7%94%A8%E6%88%B7hash%E7%9A%84%E6%96%B9%E6%B3%95)
 - [eXploit.ph: cve-2021-42287-cve-2021-42278-weaponisation](https://exploit.ph/cve-2021-42287-cve-2021-42278-weaponisation.html)
 - [PowerSharpPack](https://github.com/S3cur3Th1sSh1t/PowerSharpPack)
 - [Powermad](https://github.com/Kevin-Robertson/Powermad)
 - [Rubeus](https://github.com/GhostPack/Rubeus)
