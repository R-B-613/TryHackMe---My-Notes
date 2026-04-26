# 

link: https://tryhackme.com/room/redteamthreatintel?utm_campaign=social_share&utm_medium=social&utm_content=room&utm_source=copy&sharerId=6939e0bdb7964810692cdc70

Summary:

A red team can work with Threat Intelligence (TI) or Cyber Threat Intelligence (CTI).
They decide which threat group to emulate to test if the blue team knows how to detect it and defend against it.
The intelligence provides all the information about the nature of the selected adversary group's activity.
They also collect IOCs (Indicators of Compromise), these are technical signs that indicate a breach.
And they also collect TTPs - their tactics, techniques, and procedures.
And classify them based on different characteristics, like:
- Threat Group
- Kill Chain Phase
- Tactic
- Objective/Goal
Overall, the red team consumes threat intelligence to analyze and emulate the behaviors of adversaries using the collected TTPs and IOCs.

Mapping TTPs to the Kill Chain

I saw the MITRE ATT&CK website and examined the methods of operation of carbanak.

The red team not only plans an attack like the chosen adversary, but also during the attack itself uses the same ports and communication times as them, and the same system commands and files, in order to look exactly like the adversary.
When planning to go to battle, you need to examine scenarios from all perspectives: offensive, defensive, and the adversary's perspective. To examine every detail of their attack methodology.
Like I did in the exercises - an in-depth examination of the software the adversary uses, the ways they attack, the tools they use, and so on.
