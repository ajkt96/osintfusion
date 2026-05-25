# OSINTFUSION: Threat Actor Profiling

Aggregates multi-source OSINT data for threat actor attribution and infrastructure mapping.

## Features

- Shodan IP intelligence integration
- - VirusTotal domain reputation checking
  - - DNS record analysis and pivoting
    - - Threat actor attribution scoring
      - - Infrastructure cluster mapping
        - - IOC enrichment and correlation
         
          - ## Quick Start
         
          - ```python
            from src.investigator import OSINTInvestigator

            investigator = OSINTInvestigator()
            results = investigator.investigate("malicious-c2.com")
            print(results['attribution'])
            ```

            ## Data Sources

            - Shodan (IP/port intelligence)
            - - VirusTotal (malware/domain reputation)
              - - DNS (infrastructure enumeration)
                - - MITRE ATT&CK (TTP mapping)
                 
                  - ## License
                 
                  - MIT License
                  - 
