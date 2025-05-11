Automotive Threat Analysis and Risk Assessment (TARA)

Advanced Cybersecurity Course Project | Group 15
Overview

Conducted a comprehensive Threat Analysis and Risk Assessment (TARA) for an automotive headlight control system, following ISO/SAE 21434 guidelines. The project focused on identifying cybersecurity risks across a distributed architecture (CAN bus, telematics gateway, mobile app, and cloud infrastructure) and proposing mitigations to reduce residual risks.
Key Contributions

    Threat Identification: Leveraged STRIDE methodology to catalog six critical attack vectors, including CAN bus tampering, actuator spoofing, and cloud API exploitation.

    Risk Quantification: Evaluated threats using operational/safety impact (e.g., life-threatening injuries) and financial exposure (€0–5M liability range).

    Mitigation Design: Proposed cryptographic controls (CAN bus encryption), zero-trust cloud policies, and FIDO2 authentication for mobile apps.

    Residual Risk Analysis: Reduced high/critical risks by 75% through controls aligned with UNECE R155 and ISO/SAE 21434 standards.

Methodology

    System Analysis:
    Mapped data flows between the Body Control Module (BCM), CAN bus, telematics gateway, and cloud APIs using Data Flow Diagrams (DFDs).

    Threat Modeling:
    Applied STRIDE to identify spoofing (malicious mobile app), tampering (CAN bus sniffing), and information disclosure (cloud API breaches).

    Risk Scoring:
    Ranked threats by safety impact (life-threatening injuries) and exploit feasibility (attacker skill, access requirements).

Technical Deliverables

    Security Controls:

        CAN Bus: AES-128 message encryption + HMAC authentication.

        Mobile App: Certificate pinning and mutual TLS for command validation.

        Cloud: OAuth 2.0 authorization with anomaly detection.

    Compliance Alignment:

        Mapped mitigations to ISO/SAE 21434 Section 8.3 (Risk Treatment).

        Addressed UNECE R155 requirements for vehicle cybersecurity.


Skills Demonstrated

    Cybersecurity Standards: ISO/SAE 21434, UNECE R155.

    Technical Analysis: CAN bus protocols, PKI, zero-trust architectures.

    Risk Management: CVSS-like scoring, safety/financial impact prioritization.
