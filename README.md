# IOC Blocklists voor Firewalls

## Nederlands

### Beschrijving
Deze repository bevat External Dynamic Lists (EDL) voor gebruik in firewalls. De lijsten worden gebruikt om malafide verkeer te blokkeren.

### Bestanden

| Bestand | Type | Beschrijving |
|---------|------|--------------|
| `blocklist-ips.txt` | IP List | IP-adressen en CIDR-ranges om te blokkeren |
| `blocklist-domains.txt` | Domain List | Domeinnamen om te blokkeren via DNS Security |
| `blocklist-urls.txt` | URL List | Specifieke URL-paden om te blokkeren |

### Formaat
- Eén entry per regel
- Comments beginnen met `#`
- Geen `http://` of `https://` prefix gebruiken
- IP-adressen ondersteunen CIDR-notatie (bijv. `10.0.0.0/24`)


### Toepassing
- **IP Lists**: Gebruik in Security Policies onder Source of Destination
- **Domain Lists**: Gebruik in Anti-Spyware profielen onder DNS Policies (Sinkhole)
- **URL Lists**: Gebruik in URL Filtering profielen

---

## English

### Description
This repository contains External Dynamic Lists (EDL) for use with firewalls. These lists are used to block malicious traffic.

### Files

| File | Type | Description |
|------|------|-------------|
| `blocklist-ips.txt` | IP List | IP addresses and CIDR ranges to block |
| `blocklist-domains.txt` | Domain List | Domain names to block via DNS Security |
| `blocklist-urls.txt` | URL List | Specific URL paths to block |

### Format
- One entry per line
- Comments start with `#`
- Do not use `http://` or `https://` prefix
- IP addresses support CIDR notation (e.g. `10.0.0.0/24`)


### Implementation
- **IP Lists**: Use in Security Policies under Source or Destination
- **Domain Lists**: Use in Anti-Spyware profiles under DNS Policies (Sinkhole)
- **URL Lists**: Use in URL Filtering profiles

---

## License
This project is provided as-is for security purposes.

## Contributing
Feel free to submit issues or pull requests to improve these blocklists.
