<h1>Configure Firewall Rules Using Windows Defender Firewall</h1>


<h2>Description and Objectives</h2>

In this project I was able to:

- Configure Firewall Rules Using Windows Defender Firewall</b>
- Configure Firewall Rules Using Windows Defender Firewall with Advanced Security</b>


<h2>Project walk-through</h2>

<h3><p align="center">1.Configure Firewall Rules Using Windows Defender Firewall: </h3>

<p align="center"><img width="452" alt="image" src="https://github.com/matteoarnetoli/configure_firewall_rule/assets/152484037/72ca0d42-f8f6-4db9-b04a-837cc6fe7fa6"></b>

I navigated to the _Firewall & network protection_ area within _Windows Security_ to make sure that the firewall configurations for _Domain Network_, _Private Network_ and _Public Network_ were active.</b>

Next, I wanted to allow a specific app to communicate on the Public Network. To do so, I needed to change the configuration from the _Allow an app through firewall_ area.</b>

<p align="center"><img width="60%" alt="image" src="https://github.com/matteoarnetoli/configure_firewall_rule/assets/152484037/8c11d591-4b74-4386-9265-9d1ace81fc75"></b>

I found the app needed (Mozilla Firefox) and ticked the Public box next to its name. After this, users will be able to use the app on public network moving forward.</b>

<h3><p align="center">2.Configure Firewall Rules using Windows Defender Firewall with Advanced Security: </h3>

Firewall advance security features are accessible by clicking _Advance settings_ at the bottom of the _Firewall & network protection_ area.</b>

<p align="center"><img width="452" alt="image" src="https://github.com/matteoarnetoli/configure_firewall_rule/assets/152484037/61093cdc-21d1-42a8-8aa3-d9995af6aba3"></b>

I needed to allow the connection for Key Management Service on the Domain and Private network. I selected _Inbound rules_ from the left panel. Inbound rules determine what traffic is allowed to the computer.</b>

<p align="center"><img width="80%" alt="image" src="https://github.com/matteoarnetoli/configure_firewall_rule/assets/152484037/71d86e4d-0bc0-4e02-86cf-c7b96a8c4178"></b>

Scrolling to the Key Management Service Inbound rule I noted that:</b>

1. The policy was not enabled, as the **Enable** column says _No_</b>
2. When enabled, the policy would allow inbound communication, as specified under the **Action** column.</b>

<p align="center"><img width="80%" alt="image" src="https://github.com/matteoarnetoli/configure_firewall_rule/assets/152484037/9403a406-e840-45bb-b75b-80fb78a34b80"></b>

In order to change this, I double clicked Key Management Service. In the **General** tab, below the description of the rule itself, I maed sure that _Allow connection_ was selected within the **Action** area. </b>

<p align="center"><img width="426" alt="image" src="https://github.com/matteoarnetoli/configure_firewall_rule/assets/152484037/ac583f9c-0c2b-4f57-9290-547ac558293b"></b>

Moving on, in the **Advanced** tab, I selected _Domain_ and _Private_ in the **Profiles** area, and applied my changes.</b>

<p align="center"><img width="380" alt="image" src="https://github.com/matteoarnetoli/configure_firewall_rule/assets/152484037/75d14830-3e01-4622-b1cd-168832bfe6fc">



