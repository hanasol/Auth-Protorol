# A Secure and Lightweight PUF-based Three-Factor Authentication Protocol for Telehealthcare

This project implements a secure and lightweight three-factor authentication protocol for telehealthcare systems, based on the paper "A Secure and Lightweight PUF-based Three-Factor Authentication Protocol for Telehealthcare". The protocol enhances security and user authentication in healthcare data systems by utilizing PUF (Physical Unclonable Function).

## Project Overview

The proposed protocol leverages three-factor authentication to strengthen the security of telehealthcare systems. The main goal is to ensure consistency of session keys, prevent key leakage, and address session synchronization issues.

## ProVerif Code

The Registration Phase and Authentication and Key Exchange Phase of the protocol are modeled in ProVerif to analyze security properties.

- protocol_v1_anonymity.pv: Models user anonymity using observational equivalence between two possible user identities (choice).

- protocol_v1_auth_key_pw.pv: Includes queries for local and mutual authentication, session-key establishment, agreement, and secrecy, long-term secret confidentiality, and password secrecy and offline-guessing resistance.

## Key Features

- Enhanced security with Three-Factor Authentication.

- Strong security provided by PUF (Physical Unclonable Function)-based authentication.

- ProVerif-based security verification (session key consistency, key leakage prevention, session synchronization, etc.).
