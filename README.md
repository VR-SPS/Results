#                        Security, Privacy and Safety Risk Assessment for Virtual Reality Learning Environment Applications

## Introduction:


## Results discussion:
### Security threats
Using Clumsy 0.2, we changed the percentage of packets dropped to measure the time for a complete crash of a VRLE environment and recorded its effect on the VRLE environment. The corresponding VR world screens with and without the presence of severe packet loss are shown in Fig. \ref{fig:1} and Fig. \ref{fig:2}, respectively.


For network discrepancy, we considered different bandwidth qualities - high (normal), medium and low (see Table \ref{Table:Bandwidth}) for upload and download speed to observe the frame rate and High Fidelity content download time.
The results summarized in Table \ref{Table:Bandwidth} show that any upload speed below 30 Kbps resulted in High Fidelity crashing. We observed similar impacts on VR headset content rendering. 
shows the frame rates inside the headset under high network performance and showcases a smooth VR rendering. Fig. \ref{Medium_FrameRate} displays the same CPU performance under a medium network condition, where the graph now contains a red coloring as well. This means that the frame rate is not really being affected, but that the High Fidelity VRLE application is using more than its allotted CPU budget. The GPU performance shows similar trends, but has not been shown for space constraints.
The most drastic case in Fig. \ref{Bad_Frame_Rate} displays the frame rate under a low bandwidth with disruptive fluctuations that makes the experience inside the headset undesirably rough and jittery.
<img src="https://github.com/VR-SPS/Results/blob/master/packet_sniffing.PNG" width="200"/> <img src="https://github.com/VR-SPS/Results/blob/master/packet_sniffing.PNG" width="200"/> 
### Privacy threats

- In our proposed VRLE (Virtual Reality Learning Application), vSocial, to simulate packet sniffing attacks, we captured a subset of packets being sent to/from our High Fidelity VRLE server IP address using Wireshark. Using the packet sniffing, we found that confidential information such user's avatar, host server information for VR rendering. etc. can disclosed compromising user privacy in VR environment. Explained results are represented below.
- This demonstrated that any packet containing confidential information about the user or application can be captured and deciphered. This becomes a serious risk compromising privacy, especially without a secured network protocol.
                   <img src="https://github.com/VR-SPS/Results/blob/master/packet_sniffing.PNG" align="center"/>


### Safety threats
- Safe
