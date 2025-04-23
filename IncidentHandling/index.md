# Incident Handling Process

Preparation ----> Detection and Analysys ----> Containment, Eradication & Recover ---> Post-Incident Activity


## Preparation Stage
###  Lookup
* DMARC
* Endpoint hardening & EDR
  * Disable LLMNR/NETBOID
  * Implement LAPS
  * Disable or configure PowerShell in "ConstrainedLanguage" Mode
  * Implement Whitelisting
  * Block Scripts: .hta, .vbs, .cmd, .bat, .js, and smiliar
  * LOLBin files - used in wild for initial access to bypass whitelising
  * Block workstation to workstation communication and blcok outbound traffic to LOLBins
  * Deply an EDR product. Currently 4/22/25 AMSI provides gread visibility into obfuscated sripts for antimalware products to inspect before it gets excecuted

## Detectiong & Analysis

## Containment, Eradication & Recovery

## Post-Incident Activity Stage
