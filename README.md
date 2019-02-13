#                        User Safety at Risk: Assessing Potential Threats Causing Cybersickness in Virtual Reality

## Introduction:
Sociotechnical systems such as Virtual Reality (VR) provides applications in areas such as disaster training, learning environments, flight simulations, military training and so on. Such sociotechnical applications focus mainly on user experience but ignores user safety such as cybersickness as their primary concern.  Our study shows that cyber-attacks on network connected components such as IoT devices in VR applications may induce cybersickness to the end users. 


## Results discussion:

### User confidential information getting diclosed disrupting one of the child nodes(Collect Information)

- In our proposed VRLE (Virtual Reality Learning Application), vSocial, captured a set of packets being sent to/from our High Fidelity using Wireshark to see what kind of information can get disclosed. Using the packet sniffing, we found that confidential information such user's avatar, host server information for VR rendering. etc. can disclosed compromising user privacy in VR environment as shown in diagram below.
- This demonstrated that information about the user or application can be captured which compromises privacy of the user, especially without a secured network protocol. After dislcosure of such information, an attacker can act as a legitimate user/ instructor and can hamper the experience of the user in VR environment. We tested this by conducting a usability test consisting multiple users in which an attacker was acting as a legitimate instructor and resulted in nausea, cybersicknews in users also affecting user experience.
<p align="center">
<img src="https://github.com/VR-SPS/Results/blob/master/packet_sniffing.PNG" align="center"/>
</p>

### Cybersickness due to intermittent network discrepancies
- We also validated how different bandwidth conditions and low frame rates can cause cybersickness in users. By simulating packet loss in which we changed the percentage of packets dropped, we recorded its effect on the VRLE environment and user experience. The corresponding VR world screens with and without the presence of severe packet loss are shown in figures below.
- For network discrepancy, we considered different bandwidth qualities - high (normal), medium and low for upload and download speed to observe the frame rate and High Fidelity content download time.
The results showed that any upload speed below 30 Kbps resulted in High Fidelity crashing. We observed similar impacts on VR headset content rendering.
- In another case study, we found that low frame rate occuring due to low bandwidth can affect user health resulting in cybersickness. Causes such as low frame rate in VR makes very difficult for the users to stay in the environment for a long time. In addition, reducing 
<p float="left">
  <img src="https://github.com/VR-SPS/Results/blob/master/Without%20Packet%20Loss.PNG" width="400" height="400" />
  <img src="https://github.com/VR-SPS/Results/blob/master/After%20Packet%20Loss.PNG" width="400" height="400" align="right"/> 
</p>

- For the simulation of safety attacks, we conducted a usability study introducing threats such as session failure and network discrepancy. Through this study, we measured the user Quality of Experience (QoE).
- It is important to note that any security and privacy threats can also have safety consequences. For example, reducing the bandwidth can cause sudden changes in the VR content, which could severely impact the users' educational experience. This in turn could also highly disorient users and increase confusion and frustration levels. For our usability study, five participants entered the VRLE and their experience was measured under two conditions. They represented the two scenarios of control case with no threats and security breach.
- We analyzed the statistically significant differences between the two conditions (breach and no breach) and displayed the results below to demonstrate a clear difference specifically in dizziness, confusion, control, and attitude towards the VRLE.
<p align="center">
<img src="https://github.com/VR-SPS/Results/blob/master/Usability.PNG" align="center"/>
</p>
