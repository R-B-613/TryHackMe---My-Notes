# Red Team Fundamentals

link:
https://tryhackme.com/room/redteamfundamentals?utm_campaign=social_share&utm_medium=social&utm_content=room&utm_source=copy&sharerId=6939e0bdb7964810692cdc70

Summary:
The red team improves security effectiveness by carrying out penetration attempts that simulate a real attacker.

The blue team must detect the attacker and block them.
The white team coordinates between the red and blue teams and ensures they stay balanced, since up to a certain point, the blue team does not know that the breach is only a test and not a real incident.

The framework was established due to the difficulty of identifying security weaknesses through regular penetration tests, because of time constraints, budget limitations, and other factors.

Stages of a technique used by the red team:
  1. Reconnaissance - Obtain information on the target (Harvesting emails, OSINT)
  2. Weaponization - Combine the objective with an exploit. Commonly results in a deliverable payload (Exploit with backdoor, malicious office document)
  3. Delivery - How the weaponized function will be delivered to the target	(Email, web, USB)
  4. Exploitation - Exploit the target's system to execute code	(MS17-010, Zero-Logon, etc.)
  5. Installation - Install malware or other tooling	(Mimikatz, Rubeus, etc.)
  6. Command & Control - Control the compromised asset from a remote central controller	(Empire, Cobalt Strike, etc.)
  7. Actions on Objectives - Any end objectives: ransomware, data exfiltration, etc.	(Conti, LockBit2.0, etc.)
