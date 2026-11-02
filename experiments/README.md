# Experimental Laboratory Tests

<p align="center">
  <img src="../images/Ambiente experimental.jpg.jpeg" width="45%">
  <img src="../images/Ambiente Experimetam LOs.jpg.jpeg" width="45%">
</p>

# Experimental Laboratory Tests LoS and NLoS

<p align="center">
  <img src="../images/Ambiente Experimental LoS.jpg.jpeg" width="45%">
  <img src="../images/Ambiente Experimental NLoS.jpg.jpeg" width="10%">
</p>

This section documents the ten experimental tests performed during the 5G NR Standalone project.

# Radio Configuration
## KPI dashboard view
<img src="../images/Vizualização da Dashboard.jpg.jpeg" width="600">

# 1. Channel bandwidth impact.
## 20Mhz
<img src="../images/Análise do Impacto da Lardura de Banda no Desempenho da Ligação 5G NR 20Mhz.jpg" width="600">

## 40Mhz
<img src="../images/Análise do Impacto da Lardura de Banda no Desempenho da Ligação 5G NR 40Mhz.jpg" width="600">

# 2. Carrier frequency variation.
## n77
<img src="../images/Análise da Alteração da Frequência Central da Portadora do 5G NR n77.png" width="600">

## n78
<img src="../images/Análise da Alteração da Frequência Central da Portadora do 5G NR n78.jpg" width="600">

# 3. TDD slot configuration.
## DDDFU
<img src="../images/Testar o Modo TDD.png" width="600">

## DDFUU
<img src="../images/Testar o Modo FDD.png" width="600">

# 4. FDD operation.
## DDDFU
<img src="../images/Alterar a Configuração de Slots TDD do 5G NR DDDFU.jpg" width="600">

## DDFUU
<img src="../images/Alterar a Configuração de Slots TDD do 5G NR DDFUU.jpg" width="600">

# 5. Modulation and Coding Scheme (MCS).
<img src="../images/Alterar o Esquema de MOdulação e Codificação (MCS) do 5G NR.png" width="600">

# 6. MIMO configuration.
## SISO
<img src="../images/Testar Configurações SISO 1x1.png" width="600">

## MIMO
<img src="../images/Testar Configurações MIMO 2x2.jpg" width="600">

# Protocols and Security
# 8. 5G NR security analysis.
## Cipher
<img src="../images/Segurança na Rede 5G com Sifra.png" width="600">

## No Cipher
<img src="../images/Segurança na Rede 5G sem sifre.png" width="600">


# Advanced 5G Features and Wireshark Analysis
# Wireshark Protocol and Signalling Analysis

## Objective

Wireshark was used for packet capture, protocol inspection and Deep Packet Inspection (DPI) within the experimental 5G NR Standalone network.

## Capture Interfaces

- `oai-cn5g`
- `lo` (Loopback)

## Display Filters

### NGAP

```wireshark
ngap
```

Used to inspect the NG Setup procedure, including NGSetupRequest and NGSetupResponse messages exchanged between the gNB and AMF.

### ICMP

```wireshark
icmp
```

Used to inspect ICMP Echo Request and Echo Reply packets during connectivity testing.

## Protocol Layers Observed

- MAC-NR
- RLC-NR
- PDCP-NR
- SDAP
- NGAP
- NAS
- GTP-U

## User Plane Analysis

The project investigated packet processing across:

- Uu: Radio protocol stack.
- N3: GTP-U tunnelling between gNB and UPF.
- N6: Forwarding towards the external data network after tunnel decapsulation.

## Security Analysis

The experiments also investigated 5G-AKA authentication and security mechanisms affecting NAS signalling and user-plane traffic.

Screenshots included in this folder should be taken from the actual laboratory captures and sanitized before publication.

# 9. Network slicing using an xApp.
## URLLC
<img src="../images/Network Slicing em 5G Usando uma XApp.png" width="600">

## PRbs
<img src="../images/PRbs.png" width="600">

10. PLMN configuration and 5G SIM programming.

Each experiment should include its objective, configuration, methodology, evidence, results and conclusions.
