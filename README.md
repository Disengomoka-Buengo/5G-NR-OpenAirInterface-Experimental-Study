# 5G-NR-OpenAirInterface-Experimental-Study
Experimental implementation and evaluation of a 5G NR Standalone network using OpenAirInterface (OAI) and the OAIBOX™ platform. Includes 5G Core analysis, radio performance evaluation, Wireshark protocol inspection, 5G security, network slicing and PLMN/SIM configuration.

# Experimental Study of 5G NR Networks with OpenAirInterface

**5G NR Standalone | OpenAirInterface | OAIBOX™ | 5G Core**

## Project Overview

This repository documents an experimental study focused on the implementation, configuration and evaluation of a 5G New Radio Standalone (5G NR SA) network.

The project was developed using the **OpenAirInterface (OAI)** open-source software and the **OAIBOX™** experimental platform.

**Project Authors:** Disengomoka Buengo and Chelsea Coimbra

**Institution:** School of Technology, Polytechnic University of Castelo Branco (UPCB)

**Degree:** Electronics and Telecommunications Engineering

## Experimental Platform

The laboratory environment included:

- OAIBOX™ platform running OpenAirInterface.
- 5G Core Network (CN5G).
- OAI gNB.
- USRP B210 software-defined radio.
- Quectel RM520N-GL 5G modem as User Equipment (UE).
- Ethernet connectivity to the institutional network.

## Main Experimental Areas

1. 5G NR radio configuration and bandwidth analysis.
2. Carrier frequency and TDD/FDD configuration.
3. Modulation and Coding Scheme (MCS).
4. SISO and MIMO performance evaluation.
5. Wireshark signalling and protocol inspection.
6. 5G security and authentication procedures.
7. Network slicing: eMBB and URLLC.
8. PLMN configuration and 5G SIM programming.

## Protocol Analysis

Wireshark was used to inspect signalling and network traffic.

The project included analysis of:

- NGAP signalling between the gNB and AMF.
- NAS registration and authentication procedures.
- MAC-NR, RLC-NR, PDCP-NR and SDAP protocol layers.
- GTP-U traffic across the N3 interface.
- User-plane traffic across Uu, N3 and N6.

Documented Wireshark display filters include `ngap` and `nr rrc`, according to the packet inspection performed during the project.

## Performance Indicators

The experimental evaluation considered:

- RSRP
- RSRQ
- SINR
- CQI
- BLER
- RI
- MCS
- Throughput

## Repository Contents

- `docs/` — Project documentation and methodology.
- `architecture/` — 5G SA architecture and topology.
- `hardware/` — Experimental hardware components.
- `experiments/` — Experimental procedures.
- `wireshark/` — Protocol and signalling analysis.
- `results/` — Experimental measurements and KPI analysis.
- `images/` — Laboratory photographs and technical figures.
- `references/` — Technical references and standards.

## Project Objective

The main objective was to gain practical insight into the architecture, operation and performance of a 5G NR Standalone network, combining radio access, 5G Core configuration, protocol analysis and experimental validation.

## Contributors

**Disengomoka Buengo**  
**Chelsea Coimbra**

This was a collaborative academic project. The repository documents the shared experimental work.

## Acknowledgements

We acknowledge the academic supervision and the support provided by Allbesmart through access to the OAIBOX™ experimental platform.

## Disclaimer

This repository is intended for educational and technical documentation purposes. It does not constitute a production-ready 5G deployment guide.
