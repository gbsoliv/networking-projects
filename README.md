# Vertex Solutions Enterprise Network

Vertex Solutions is a fictitious mid-sized technology company that needs a network solution to be implemented and support its daily operations.

## Business Requirements
- Support approximately 100 corporate users segmentated by 5 departaments: Executive, Sales, MArketing, Operations and Accounting. 
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
    End Users  End Users  End Users   AP, Printers and Servers. 


        
