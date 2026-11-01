# 5G NR Standalone Architecture

## Overview

The experimental network was implemented using OpenAirInterface on the OAIBOX™ platform.

The platform was configured to run the 5G Core Network (CN5G) and the gNB.

## Main Components

- UE: Quectel RM520N-GL.
- gNB: OpenAirInterface 5G base station.
- 5G Core: OpenAirInterface CN5G.
- Radio Front-End: USRP B210.

- <img src="../images/Arquitetura da rede 5GNR.jpg" width="600">

## Main Interfaces

- Uu: Radio interface between UE and gNB.
- N2: Control-plane interface between gNB and AMF.
- N3: User-plane interface between gNB and UPF.
- N6: Interface between UPF and external data network.

## User Plane

The project included experimental analysis of an ICMP packet travelling through the 5G network, including radio protocol processing, GTP-U encapsulation and tunnel decapsulation.

See the topology and packet-path diagrams in this folder.
