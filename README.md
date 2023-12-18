<h1>Configure Firewall Rules Using Windows Defender Firewall</h1>


<h2>Description and Objectives</h2>

In this project I was able to:

- Configure Firewall Rules Using Windows Defender Firewall</b>
- Configure Firewall Rules Using Windows Defender Firewall with Advanced Security</b>


<h2>Project walk-through</h2>

<h3><p align="center">1.Configure Firewall Rules Using Windows Defender Firewall: </h3>

<p align="center"><img width="452" alt="image" src="https://github.com/matteoarnetoli/configure_firewall_rule/assets/152484037/72ca0d42-f8f6-4db9-b04a-837cc6fe7fa6"></b>

I navigated to the _Firewall & network protection_ area within _Windows Security_ to make sure that the firewall configurations for _Domain Network_, _Private Network_ and _Public Network_ were active.</b>

Next, I wanted to allow a specific app to communicate on the Public Network. To do so, I needed to change the configuration from the _Allow an app through firewall_ area.

<p align="center"><img width="60%" alt="image" src="https://github.com/matteoarnetoli/configure_firewall_rule/assets/152484037/8c11d591-4b74-4386-9265-9d1ace81fc75"></b>

I found the app needed (Mozilla Firefox) and ticked the Public box next to its name. After this, users will be able to use the app on public network moving forward.

<h3><p align="center">2.Configure Firewall Rules using Windows Defender Firewall with Advanced Security: </h3>

<p align="center"><img width="40%" alt="image" src="https://github.com/matteoarnetoli/update_threats/assets/152484037/c137d7b1-12a4-412b-8ca0-341b9468fab5"></b>

I ran a quick scan by pressing the relevant button withing the _Current threats_ area of Microsoft Defender.</b>

<p align="center"><img width="452" alt="image" src="https://github.com/matteoarnetoli/update_threats/assets/152484037/64531e0b-1925-4b51-a95b-b4d54050bb81"></b>

By clicking _Threat History_, once the scan is completed, I accessed the details of any recent findings. In this section, I can view whether any threats was identified. In addition, I can see any quarantined file as well as any object that was recognized as a threat but is still allowed to run in the machine (_Allowed threats_).</b>

<h3><p align="center">3.Run a custom scan: </h3>

<p align="center"><img width="50%" alt="image" src="https://github.com/matteoarnetoli/update_threats/assets/152484037/579ca651-063a-441b-a257-bf420f1d4ba7"></b>

I decided to run a custom scan that only scans files included in the **Downloads** folder. To achieve this is followed the following path:</b>


Select **Scan options** under the **Quick scan** button > Select **Custom scan**, then click **Scan now** > Select the **Downloads** folder and click the **Select Folder** button > Click  **Scan now**.
</b>

