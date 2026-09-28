# Sentinel — Bank Duress & Threat Alert System

A concept and working prototype for a real-time duress alert system for banks,
built in response to South Africa's high rates of ATM and cash-in-transit crime.

## The problem
Bank security today relies mostly on CCTV — useful after a crime, but no help
during one. This project explores how a bank could respond *while* a robbery
or coercion is happening.

## The idea
Two parts:
1. **Suspicious activity detection** — flagging unusual behaviour patterns
   near ATMs/branches (loitering, groups converging, face coverings), not
   facial identity matching, to avoid bias and legal risk under POPIA.
2. **Duress alert** — a customer can silently signal distress via an
   alternate PIN or hidden gesture, so the bank is alerted without the
   attacker knowing. A visible in-app panic button is also included as a
   secondary channel.

## Try the prototype
Open `duress-alert-demo.html` in any browser. Two views:
- **Customer tab** — enter PIN `1234` for a normal transaction, or `9999`
  for the duress code.
- **Bank ops tab** — watch alerts arrive in real time with location and
  status.

## Status
This is a proof-of-concept, not a production system. See the full writeup
in `Sentinel_Duress_Alert_Project.docx` for the tech stack, privacy/legal
considerations, and next steps toward a real backend integration.

## About
Built while studying cybersecurity independently. Feedback welcome.
