# CSMASimulator
A CSMA-CA simulator for a wireless network
## Compiling
`javac *.java`
## Running
`java CSMASimulator`
### Debug Mode
`java CSMASimulator -d`
## Running Parameters
**Data Ready Probability:** Probability that a station has a packet ready to send (0 < P < 1)\
**Packet Transmission Time Weight:** Time it takes to transmit a packet (0.3 t<sub>D</sub> < t<sub>P</sub> < 0.6 t<sub>D</sub>)\
**Number of packets:** Number of packets each station is sending (1 <= M <= 6)

