# 300a Powermeter
This project was created, so that we could exceed our currrent meter limitation for the orange cube + by creating our own hall effect based current meter board.
### General Inforamtion:
The ardupilot cube orange+ unit comes out of the box with a 30A max current meter. 
We wanted to use the orange plus for our UAV drone, aiming to compete at the 2026 [UAS challenge](https://www.imeche.org/events/challenges/uas-challenge) as members of [Starbound Team](https://starbound.e-ce.uth.gr/).

Our main challenge was the need for a current meter that can measure Amperage of at least 250A. The current meter included with the orange plus is limited to 30A maximum.
We designed a custom PCB responsible for current sensing of at least 250A. For our purposes, we chose the ACS772 (250-CS772ECB300BPFFT) hall effect sensor. 
For more information please check the [Starbound_Power_Meter_Design.pdf](https://github.com/VasilisOuzas/300a_powermeter/blob/main/Starbound__Power_Meter_Design.pdf)

