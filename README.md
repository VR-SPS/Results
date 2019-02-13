#                        Security, Privacy and Safety Risk Assessment for Virtual Reality Learning Environment Applications

## Introduction:
Social Virtual Reality based Learning Environments (VRLEs) such as vSocial render instructional content in a three-dimensional immersive computer experience for training youth with learning impediments. There are limited prior works that explored attack vulnerability in VR technology, and hence there is a need for systematic frameworks to quantify risks corresponding to security, privacy, and safety (SPS) threats. The SPS threats can adversely impact the educational user experience and hinder delivery of VRLE content. In this paper, we propose a novel risk assessment framework that utilizes attack trees to calculate a risk score for varied VRLE threats with rate and duration of threats as inputs. We compare the impact of a well-constructed attack tree with an adhoc attack tree to study the trade-offs between overheads in managing attack trees, and the cost of risk mitigation when vulnerabilities are identified. We use a vSocial VRLE testbed in a case study to showcase the effectiveness of our framework and demonstrate how a suitable attack tree formalism can result in a more safer, privacy-preserving and secure VRLE system.

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
<p align="center">
<img src="https://github.com/VR-SPS/Results/blob/master/packet_sniffing.PNG" align="center"/>
</p>

### Safety threats
- For the simulation of safety attacks, we conducted a usability study introducing threats such as session failure and network discrepancy. Through this study, we measured the user Quality of Experience (QoE).
- It is important to note that any security and privacy threats can also have safety consequences. For example, reducing the bandwidth can cause sudden changes in the VR content, which could severely impact the users' educational experience. This in turn could also highly disorient users and increase confusion and frustration levels. For our usability study, five participants entered the VRLE and their experience was measured under two conditions. They represented the two scenarios of control case with no threats and security breach.
- We analyzed the statistically significant differences between the two conditions (breach and no breach) and displayed the results below to demonstrate a clear difference specifically in dizziness, confusion, control, and attitude towards the VRLE.
<p align="center">
<img src="https://github.com/VR-SPS/Results/blob/master/Usability.PNG" align="center"/>
</p>
