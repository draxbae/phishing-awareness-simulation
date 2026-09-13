# Phishing Awareness Simulation

A local security awareness simulation designed to demonstrate common phishing risks and safe credential-handling practices.

## Project Overview

This project demonstrates a controlled phishing awareness scenario using a locally hosted web page.

The simulation is intentionally designed **not to collect, store, or transmit credentials**.

The objective is to demonstrate how users should recognize suspicious account verification requests and understand the risks of entering sensitive information.

## Objectives

- Understand basic phishing and social engineering concepts
- Demonstrate common phishing page characteristics
- Practice identifying suspicious verification requests
- Demonstrate safe handling of credentials
- Build security awareness through controlled simulation

## Lab Environment

| Component | Details |
|---|---|
| Platform | Kali Linux |
| Web Server | Python HTTP Server |
| Environment | Local / Isolated Lab |
| Application | Custom Awareness Simulation |

## Simulation Flow

1. User accesses the local awareness simulation.
2. A simulated account verification page is displayed.
3. Dummy training credentials are entered.
4. The form submission is prevented from sending the credentials.
5. A security awareness message is displayed.
6. No credentials are stored or transmitted.

## Security Awareness Indicators

Users should verify:

- Sender identity
- Domain name
- URL
- HTTPS and certificate validity
- Unexpected login or verification requests
- Urgency or threatening language
- Requests for passwords or sensitive information

## Evidence

### Screenshot 1 — Awareness Simulation

Shows the locally hosted account verification simulation.

### Screenshot 2 — Credential Protection

Shows the security awareness warning displayed after submitting dummy training data.

## Defensive Recommendations

- Never enter credentials into suspicious links
- Verify the domain before logging in
- Use password managers where appropriate
- Enable multi-factor authentication
- Be cautious with unexpected verification requests
- Report suspicious phishing messages to the appropriate security team

## Security Notes

This project was performed entirely in a local laboratory environment.

No real credentials were collected, stored, or transmitted.

No real organization, account, or user was targeted.

The simulation is intended exclusively for cybersecurity education and awareness training.

## Project Status

- [x] Local phishing awareness page
- [x] Safe form handling
- [x] Credential protection demonstration
- [x] Security awareness messaging
- [x] Evidence collection
- [x] Documentation

## Disclaimer

This project is an educational security awareness simulation performed in an authorized local environment. It must not be used to collect credentials or target users without explicit authorization.
