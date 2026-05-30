# Cable Pull: Modem to Second Level Network Closet (Planned)

## Why I did this
- Needed dedicated 10GbE link between my workstation and NAS.
- Existing Wi-Fi was unreliable for large file transfers (video editing).
- Wanted to learn proper low-voltage cabling techniques (Keystone termination, Strain relief, Sheilded Cabling).

## Planning
### Materials Used
| Item | Spec | Why this choice |
|------|------|----------------|
| Cable | Cat6 (shielded, CMX rated) | 10GbE, safe for exterior use |
| Keystone jacks | shielded | Sheilded for safety of exterior run |

### Tools
- Cable Tester
- Punch Down Tool
- RJ45 Crimping Tool

**Steps:**  
Modem (demarc) > through basement ceiling > Basement Surface Keystone > Exterior > Second level Surface Keystone > Switch

*The keystones used in the basement and second level where technically unnecessary, however I choose to have the outside cable be "Isolated" from the interior ones in case I needed to replace them for whatever reason*
