# BGP Vulnerabilities and Hijacking Attacks
This repo explores the vulnerabilities of [Border Gateway Protocol](https://en.wikipedia.org/wiki/Border_Gateway_Protocol) BGP and focuses on a specific type of attack known as BGP hijacking attacks. BGP, a fundamental protocol for routing internet traffic between [Autonomous Systems](https://en.wikipedia.org/wiki/Autonomous_system_(Internet)) ASes, is susceptible to abuse and manipulation.
## What are BGP Hijacking Attacks?
BGP hijacking attacks involve maliciously manipulating BGP through false announcements by rogue ASes. By falsely advertising a shorter path to a specific prefix, the attacker tricks victim ASes into redirecting their traffic through the malicious AS. This deception exploits BGP routing behaviour, enticing victim ASes to choose the newly advertised route, which appears more advantageous.

## Usage
TODO
