﻿# Interactsh Collaborator Everywhere

This is a Burp Suite extension for [Interact.sh](https://github.com/projectdiscovery/interactsh/). `Interact.sh` is an open-source tool for detecting out-of-band interactions. It is a tool designed to detect vulnerabilities that cause external interactions.

This plugin is the combination of the two extensions, [Interactsh Collaborator](https://github.com/wdahlenburg/interactsh-collaborator) and [Collaborator Everywhere](https://github.com/PortSwigger/collaborator-everywhere) 

Please check out [this amazing article from James Kettle](https://portswigger.net/research/cracking-the-lens-targeting-https-hidden-attack-surface) about how he uncovered the inner systems of ISPs, DoD networks, and other big company's network and found interesting vulnerabilities using Burp Collaborator Everywhere 

### Build

1. `mvn package`
2. Add the target/everywhere-0.x-dev-jar-with-dependencies.jar file as a new Java extension in Burpsuite

### Development

- Development in progress
