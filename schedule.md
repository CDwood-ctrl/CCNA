# CCNA 200-301 — Full Breakdown & Schedule

The complete task list behind the dashboard, in plain text. Tick them off in `index.html`; read them here. Week ranges assume **~5–6 hrs/week** and are a guide, not a deadline.

**Weekly rhythm:** 2–3 hrs tutoring · ~1–1.5 hrs new video · ~1–1.5 hrs lab · 5–10 min Anki daily.

---

## Phase 00 — Foundation Lock-In  ·  ~2–3 weeks
*Bring the core online. Mostly consolidation of what you've already proved.*

- [ ] Cold-recall: 20 subnet questions, under 60s each (subnettingpractice.com)
- [ ] Drill the −2 reflex until "usable" auto-fires minus-two
- [ ] Memorise private ranges: `10/8` · `172.16–31` · `192.168/16`
- [ ] Mask conversion both ways: `/8`–`/30` ⇄ dotted decimal
- [ ] IPv6 addressing: structure + abbreviation rules
- [ ] IPv6 types: global, link-local, unique-local; EUI-64 / SLAAC
- [ ] Well-known ports to 100%: 20/21, 22, 23, 25, 53, 80, 110, 143, 443
- [ ] Set up Anki + Jeremy's deck; commit to daily reviews
- [ ] Install Packet Tracer; build a 2-PC + switch ping test

**Milestone:** subnet/VLSM cold in <60s; IPv6 address types straight.

---

## Phase 01 — Switching & VLANs  ·  ~6–8 weeks
*Light up the access layer. First heavy config — lab everything.*

- [ ] Jeremy: switching fundamentals; observe MAC table in a lab
- [ ] Configure access ports + VLANs from a blank switch
- [ ] 802.1Q trunking between two switches; verify with `show` commands
- [ ] Inter-VLAN routing: router-on-a-stick, end-to-end
- [ ] Inter-VLAN routing: Layer-3 switch / SVIs
- [ ] STP: root bridge election + port states
- [ ] Configure + verify STP; manipulate root bridge priority
- [ ] RSTP + PortFast + BPDU Guard
- [ ] EtherChannel (LACP): config + verify
- [ ] Wireless fundamentals: AP modes, WLC, SSIDs, roaming
- [ ] Mini-lab: VLANs + trunks + STP + EtherChannel from blank
- [ ] Phase quiz: 85%+ on a switching question set

**Milestone:** configure VLANs + trunking + STP from a blank switch, from memory.

---

## Phase 02 — Routing & OSPF  ·  ~8–10 weeks  *(biggest domain — 25%)*
*Open the routes. The heart of CCNA.*

- [ ] Routing fundamentals: routing table, longest-match, AD vs metric
- [ ] Static routes: next-hop, exit-interface, fully-specified
- [ ] Default routes + floating static
- [ ] Lab: multi-router static routing end-to-end
- [ ] OSPF concepts: areas, LSAs, DR/BDR, neighbor states
- [ ] Configure single-area OSPFv2; verify adjacencies
- [ ] OSPF network types + DR/BDR election
- [ ] OSPF cost / metric tuning
- [ ] Troubleshoot OSPF: break an adjacency, diagnose with `show`/`debug`
- [ ] FHRP / HSRP: concepts + config
- [ ] IPv6 routing: static + OSPFv3 basics
- [ ] Mega-lab: 3+ router OSPF network — build, break, fix, from memory
- [ ] Phase quiz: 85%+ on a routing set

**Milestone:** stand up OSPF from scratch and troubleshoot a broken adjacency.

---

## Phase 03 — IP Services  ·  ~3–4 weeks
*Turn on the services that make the network usable.*

- [ ] DHCP: IOS server config + relay (`ip helper-address`); lab it
- [ ] DNS basics + IOS name resolution
- [ ] NAT: static, dynamic, PAT/overload; lab to a simulated "internet"
- [ ] NTP: client/server config
- [ ] SNMP fundamentals (v2c / v3 concepts)
- [ ] Syslog: severity levels + config
- [ ] QoS basics: marking, queuing, shaping vs policing
- [ ] SSH: secure remote access config (retire Telnet)
- [ ] Mini-lab: DHCP + NAT + SSH on one topology
- [ ] Phase quiz: 85%+

**Milestone:** configure DHCP + NAT so a LAN reaches a simulated internet.

---

## Phase 04 — Security Fundamentals  ·  ~4–5 weeks
*Lock the doors. ACLs are the big one.*

- [ ] Security concepts: threats, vulnerabilities, CIA, attack types
- [ ] Standard ACLs: config, placement, verify
- [ ] Extended ACLs: protocol/port matching; permit/deny lab
- [ ] Named ACLs + editing
- [ ] Port security: config + violation modes; lab
- [ ] DHCP snooping + Dynamic ARP Inspection
- [ ] AAA: RADIUS / TACACS+ / 802.1X concepts
- [ ] VPN concepts: site-to-site vs remote-access, IPsec basics
- [ ] Wireless security: WPA2 / WPA3, auth methods
- [ ] Device hardening: enable secret, banners, disable unused services
- [ ] Mini-lab: ACLs + port security on the access layer
- [ ] Phase quiz: 85%+

**Milestone:** write and apply ACLs that permit/deny specific traffic correctly.

---

## Phase 05 — Automation & Programmability  ·  ~3–4 weeks
*Automate the fabric. Lighter, but real weight (~10%) and growing in v1.1.*

- [ ] Controller-based / SDN: control plane vs data plane
- [ ] Cisco DNA Center + intent-based networking
- [ ] REST APIs: methods, CRUD, response codes
- [ ] Data formats: read + interpret a JSON payload; XML, YAML
- [ ] Config management: Ansible vs Puppet vs Chef vs Terraform
- [ ] Programmability benefits vs traditional config
- [ ] Phase quiz: 85%+

**Milestone:** read a JSON payload and explain a REST API call.

---

## Phase 06 — Exam Prep & Go-Live  ·  ~4–6 weeks
*Go live. Timed reps until you're consistently over the line.*

- [ ] Packet Tracer mega-lab #1 (multi-domain) from blank
- [ ] Packet Tracer mega-lab #2 (troubleshooting focus)
- [ ] Boson ExSim exam A (timed) — review every miss
- [ ] Boson ExSim exam B (timed) — review every miss
- [ ] Boson ExSim exam C (timed)
- [ ] Drill weakest domain back up to 85%+
- [ ] Second question source pass (Pearson Test Prep / Jeremy bonus)
- [ ] Re-confirm the 200-301 blueprint on cisco.com
- [ ] Hit 85%+ consistently, timed → schedule the exam
- [ ] Final light review — no cramming the day before

**Booking gate:** consistently 85%+ on Boson, timed, before you schedule.

---

## Daily drills (keep these warm)

Your banked weak spots. One pass a day — it's the cheap habit that stops decay between sessions.

- 5 subnet speed questions
- −2 usable-hosts reflex check
- Private ranges recall (`10/8` · `172.16–31` · `192.168/16`)
- Mask conversion: 3 prefixes → dotted decimal
- Well-known ports flash review

---

## The go-live gate (before booking)

- [ ] Phases 0–5 complete, every milestone hit
- [ ] All weak spots automatic (Anki mature)
- [ ] Build + troubleshoot in Packet Tracer, cold
- [ ] Boson 85%+ consistently, timed
- [ ] Blueprint reconfirmed on cisco.com
- [ ] → Book it.
