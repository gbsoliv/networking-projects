# Vertex Solutions Enterprise Network

Vertex Solutions is a mid-sized technology company specializing in cloud migration, software development, cybersecurity consulting, and managed IT services. The company requires a scalable, secure, and highly available enterprise network to support daily operations. 

## Business Requirements
- Support approximately 200 corporate users
- Provide secure network segmentation
- Separate voice, data, and guest traffic
- Support future expansion
- Ensure high availability
- Secure management access
- Internet connectivity
- Centralized network services

## 3 Tier Topology

                    Internet
                        │
                    ISP Router
                        │
                    Firewall
                        │
                 Core Layer Switch
                  /             \
                 /               \
         Distribution 1     Distribution 2
            /      \          /      \
      Access SW1  SW2    SW3      SW4
           │         │      │         │
        End Users  Phones  APs   Printers


        
