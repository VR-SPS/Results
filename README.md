#                        Security, Privacy and Safety Risk Assessment for Virtual Reality Learning Environment Applications

## Introduction:


## Results discussion:
### Security threats
- Using Clumsy 0.2, we changed the percentage of packets dropped to measure the time for a complete crash of a VRLE environment and recorded its effect on the VRLE environment. The corresponding VR world screens with and without the presence of severe packet loss are shown in figures below.
- For network discrepancy, we considered different bandwidth qualities - high (normal), medium and low for upload and download speed to observe the frame rate and High Fidelity content download time.
The results showed that any upload speed below 30 Kbps resulted in High Fidelity crashing. We observed similar impacts on VR headset content rendering. 
<p float="left">
  <img src="https://github.com/VR-SPS/Results/blob/master/Without%20Packet%20Loss.PNG" width="400" height="400" />
  <img src="https://github.com/VR-SPS/Results/blob/master/After%20Packet%20Loss.PNG" width="400" height="400" align="right"/> 
</p>

### Privacy threats

- In our proposed VRLE (Virtual Reality Learning Application), vSocial, to simulate packet sniffing attacks, we captured a subset of packets being sent to/from our High Fidelity VRLE server IP address using Wireshark. Using the packet sniffing, we found that confidential information such user's avatar, host server information for VR rendering. etc. can disclosed compromising user privacy in VR environment. Explained results are represented below.
- This demonstrated that any packet containing confidential information about the user or application can be captured and deciphered. This becomes a serious risk compromising privacy, especially without a secured network protocol.
                   <img src="https://github.com/VR-SPS/Results/blob/master/packet_sniffing.PNG" align="center"/>


### Safety threats
- For the simulation of safety attacks, we conducted a usability study introducing threats such as session failure and network discrepancy. Through this study, we measured the user Quality of Experience (QoE).
- It is important to note that any security and privacy threats can also have safety consequences. For example, reducing the bandwidth can cause sudden changes in the VR content, which could severely impact the users' educational experience. This in turn could also highly disorient users and increase confusion and frustration levels. For our usability study, five participants entered the VRLE and their experience was measured under two conditions. They represented the two scenarios of control case with no threats and security breach.
- We analyzed the statistically significant differences between the two conditions (breach and no breach) and displayed the results below to demonstrate a clear difference specifically in dizziness, confusion, control, and attitude towards the VRLE.
                   <img src="https://github.com/VR-SPS/Results/blob/master/packet_sniffing.PNG" align="center"/>
