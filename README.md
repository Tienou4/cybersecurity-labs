# Cybersecurity Labs

Mes labs pratiques de cybersécurité (réseau, défense et offensif), réalisés principalement sur la plateforme **Proxmox VE** de l'INSA Centre Val de Loire.

## Labs

| Lab | Thèmes | Outils |
|---|---|---|
| Routage & NAT | Routeur/pare-feu, NAT, segmentation en sous-réseaux | OPNsense, Proxmox (bridges) |
| Services réseau | Serveur DHCP dédié, DNS | isc-dhcp-server, bind9 |
| Analyse de trafic | Capture DHCP, observation de la traduction NAT | Wireshark, tcpdump |
| Attaques LAN | DHCP spoofing, DNS spoofing (environnement isolé) | Kali Linux |
| Durcissement | SSH, règles de pare-feu | OpenSSH, iptables/nftables |
| TryHackMe | Write-ups de rooms | TryHackMe |

## Structure

```
proxmox/      topologies et configuration des labs
network/      DHCP, DNS, NAT, pare-feu
offensive/    labs d'attaque en environnement isolé
tryhackme/    write-ups
```

> ⚠️ Usage pédagogique uniquement, dans des environnements de lab isolés.
