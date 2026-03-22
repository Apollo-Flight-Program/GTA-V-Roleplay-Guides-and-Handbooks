# Dispatch Codes Reference

Dispatch codes, response codes, and unit designations work alongside 10-codes to form the communication backbone of law enforcement and emergency services in GTA V roleplay. While 10-codes describe situations and statuses, dispatch codes describe how to respond, how to organize, and how to prioritize.

This reference covers response codes, signal codes, unit designations, priority levels, and CAD basics used across most RP servers.

---

## Response Codes

Response codes tell officers how urgently to respond to a call and what equipment to use en route.

| Code | Name | Meaning | Lights/Siren |
|---|---|---|---|
| **Code 1** | Routine | Respond at your leisure. No urgency. Handle when available. | No |
| **Code 2** | Urgent | Respond promptly. Situation requires attention but is not life-threatening. | No (some servers allow lights only, no siren) |
| **Code 2 High** | Priority Urgent | Respond quickly. Elevated urgency but not yet an emergency. | Lights only, no siren |
| **Code 3** | Emergency | Respond immediately. Life-threatening situation or active crime in progress. | Full lights and siren |
| **Code 4** | Scene Secure | No further assistance needed. The situation has been resolved or stabilized. | N/A |
| **Code 5** | Stakeout | Maintain position and observe. Do not approach or engage unless directed. | No — maintain stealth |
| **Code 6** | Out for Investigation | Officer is out of the vehicle investigating on foot at a specific location. | N/A |
| **Code 7** | Meal Break | Officer is on break. Available only for emergency calls. | N/A |
| **Code 8** | Request Fire/EMS | Fire department or EMS needed at the scene. | N/A |
| **Code 30** | Officer Needs Help | Urgent request for backup. Not as critical as Code 99 but requires immediate response. | Code 3 response from all available units |
| **Code 99** | Emergency — All Units | Officer down or extreme emergency. Every available unit responds immediately. | Full Code 3, all units |
| **Code 100** | In Position | SWAT/tactical unit is in position and ready for action. | N/A |

---

## Situation Codes

These codes describe the nature of a call or event. Servers vary, but the following are widely used.

| Code | Meaning |
|---|---|
| **187** | Homicide |
| **207** | Kidnapping |
| **211** | Robbery |
| **211A** | Armed robbery |
| **213** | Use of explosives |
| **240** | Assault |
| **242** | Battery |
| **245** | Assault with a deadly weapon |
| **246** | Shooting at an inhabited dwelling |
| **261** | Sexual assault |
| **273** | Domestic violence |
| **288** | Indecent exposure |
| **314** | Indecent exposure in public |
| **390** | Intoxicated person |
| **415** | Disturbance / noise complaint |
| **417** | Person with a firearm |
| **459** | Burglary |
| **480** | Hit and run (felony) |
| **481** | Hit and run (misdemeanor) |
| **484** | Petty theft |
| **487** | Grand theft |
| **488** | Petty theft in progress |
| **502** | Driving under the influence |
| **503** | Stolen vehicle |
| **505** | Reckless driving |
| **510** | Speeding / street racing |
| **586** | Illegal parking |
| **594** | Malicious mischief / vandalism |
| **647** | Disorderly conduct |
| **901** | Ambulance needed |
| **901K** | Ambulance needed — victim deceased |
| **904** | Fire |
| **998** | Officer involved shooting |
| **999** | Officer needs immediate assistance |

---

## Signal Codes

Signal codes supplement 10-codes and response codes to provide additional context. They are used less frequently but are recognized across many servers.

| Signal | Meaning |
|---|---|
| **Signal 0** | Officer in immediate danger — all units respond |
| **Signal 1** | Proceed with caution |
| **Signal 2** | Proceed normally — routine response |
| **Signal 3** | Stealth approach — no lights, no siren |
| **Signal 4** | No further assistance needed |
| **Signal 11** | Running radar / speed trap |
| **Signal 20** | Notify news media |
| **Signal 100** | In position for tactical operation |

---

## Unit Designations

Law enforcement units are identified by designators that indicate their type, area, and assignment. The exact format varies by server, but the phonetic letter system is widely adopted.

### Phonetic Unit Types

| Designator | Unit Type | Description |
|---|---|---|
| **Adam** | Two-officer unit | Standard patrol with a partner. |
| **Boy** | Backup unit | Unit designated to provide backup or secondary coverage. |
| **Charles** | Command unit | Supervisor or watch commander. |
| **David** | SWAT / Tactical | Special weapons and tactics unit. |
| **Edward** | Traffic unit | Assigned to traffic enforcement and accident investigation. |
| **Frank** | Foot patrol | Officer on foot beat. |
| **George** | Gang unit | Specialized gang enforcement. |
| **Henry** | Helicopter / Air unit | Aerial support. Usually "Air-1" or "Henry-1." |
| **Ida** | Investigative unit | Detective or investigator on assignment. |
| **King** | K-9 unit | Officer with a police dog. |
| **Lincoln** | One-officer unit | Solo patrol unit. |
| **Mary** | Motor unit | Motorcycle officer. |
| **Nora** | Narcotics unit | Undercover or specialized drug enforcement. |
| **Tom** | Training unit | FTO with a cadet. |

### Unit Number Format

Most servers follow this structure:

```
[Unit Type]-[Beat Number][Unit Number]

Examples:
  Lincoln-41    → Solo patrol unit, beat 4, unit 1
  Adam-12       → Two-officer unit, beat 1, unit 2
  David-1       → SWAT team leader
  Henry-1       → Police helicopter (Air-1)
  King-9        → K-9 unit
  Tom-14        → Training unit, beat 1, officer 4 with cadet
```

---

## Beat Numbers / Patrol Zones

Beat numbers divide the city into geographic zones. Each patrolling unit is assigned a beat to ensure coverage across the map.

| Beat | General Area |
|---|---|
| **Beat 1** | Downtown Los Santos, Mission Row, Pillbox Hill |
| **Beat 2** | Vinewood, Rockford Hills, Burton |
| **Beat 3** | Del Perro, Vespucci, Pacific Bluffs |
| **Beat 4** | South Los Santos — Davis, Strawberry, Chamberlain Hills |
| **Beat 5** | East Los Santos — La Mesa, El Burro Heights, Cypress Flats |
| **Beat 6** | Port of Los Santos, LSIA, Terminal, Elysian Island |
| **Beat 7** | Chumash, Pacific Highway, Tongva Hills |
| **Beat 8** | Sandy Shores, Alamo Sea, Harmony |
| **Beat 9** | Grapeseed, Mount Chiliad, Paleto Forest |
| **Beat 10** | Paleto Bay, Procopio Beach, Raton Canyon |

---

## Priority Levels for Calls

Dispatch assigns priority levels to incoming calls to determine which units respond and how quickly.

| Priority | Description | Expected Response |
|---|---|---|
| **Priority 1 (P1)** | Life-threatening emergency. Active shooter, officer down, major traffic collision with injuries. | Immediate Code 3 response. Multiple units dispatched. |
| **Priority 2 (P2)** | Serious incident. Robbery in progress, assault, pursuit. | Urgent Code 2 High or Code 3. Nearest available units. |
| **Priority 3 (P3)** | Non-emergency but requires response. Disturbance, theft report, suspicious activity. | Code 2 response. Next available unit. |
| **Priority 4 (P4)** | Low priority. Noise complaint, parking violation, non-urgent report. | Code 1 response. Handle when available. |
| **Priority 5 (P5)** | Administrative. Warrant service, follow-up investigation, community event. | Scheduled or assigned at officer discretion. |

---

## Dispatch Response Templates

Dispatchers use standardized formats when broadcasting calls. Below are templates commonly used in RP.

### Standard Call Broadcast

```
"All units, all units — [situation code] reported at [location].
[Description of the situation]. Respond [response code].
Any available units, please advise."
```

**Example:**
> *"All units, all units — 211 in progress at the Fleeca Bank on Great Ocean Highway. Two suspects, one armed with a handgun, one hostage reported inside. Respond Code 3. Any available units, please advise."*

### Unit Acknowledgment

```
"Dispatch, [unit designation], 10-76 to [location], ETA [time]."
```

**Example:**
> *"Dispatch, Lincoln-41, 10-76 to Fleeca on Great Ocean, ETA two minutes."*

### Arrival on Scene

```
"Dispatch, [unit designation], 10-23 at [location]. [Initial observations]."
```

**Example:**
> *"Dispatch, Lincoln-41, 10-23 at Fleeca. I have visual on one suspect at the front entrance. Setting up a perimeter."*

### Requesting Backup

```
"Dispatch, [unit designation], requesting [backup type] at my 10-20.
[Reason for request]."
```

**Example:**
> *"Dispatch, Adam-12, requesting additional units at my 10-20. Shots fired, two suspects fleeing on foot southbound through the alley."*

### Scene Cleared

```
"Dispatch, [unit designation], [location] is Code 4.
[Number] suspects in custody / Scene resolved. Resuming patrol."
```

**Example:**
> *"Dispatch, Lincoln-41, Fleeca Bank is Code 4. Two suspects in custody, hostage is safe, EMS on scene for minor injuries. Resuming patrol."*

---

## CAD (Computer Aided Dispatch) Basics

Most RP servers use a CAD system — either a web-based application or an in-game tablet — that allows officers and dispatchers to manage calls, run records, and track units in real time.

### Common CAD Functions

| Function | Description |
|---|---|
| **Run Person** | Search for a civilian's name to pull up their record — ID, criminal history, warrants, known vehicles, flags. |
| **Run Plate** | Search a vehicle license plate to find the registered owner, vehicle description, stolen status, and flags. |
| **Create Call** | Dispatch creates a new call with location, situation code, priority, and assigns units. |
| **Attach to Call** | An officer assigns themselves to an active call in the CAD. |
| **Update Call** | Add notes, change status, or escalate priority on an existing call. |
| **Create BOLO** | Post a Be On the Lookout alert visible to all on-duty officers. |
| **Create Warrant** | File an arrest or search warrant pending judicial approval. |
| **Log Arrest** | Record an arrest with charges, evidence, and booking information. |
| **Unit Status** | Officers update their status in CAD — 10-8 (available), 10-6 (busy), 10-7 (out of service), etc. |

### CAD Etiquette

- Keep call notes factual and concise
- Update your unit status whenever it changes
- Do not create false BOLO entries or fictional warrants without IC justification
- Dispatchers should broadcast high-priority calls over radio in addition to logging them in CAD
- All officers should check CAD at the start of their shift for active BOLOs, warrants, and ongoing calls

---

## Combining It All — Example Radio Traffic

Here is an example of a complete dispatch interaction using all elements covered in this guide:

> **Dispatch:** *"All units, all units — 245, assault with a deadly weapon, reported at the parking garage on Integrity Way, downtown. Suspect is a white male, red hoodie, armed with a knife. One victim with lacerations. Respond Code 2 High. Priority 2."*
>
> **Lincoln-41:** *"Dispatch, Lincoln-41, 10-76 from Mission Row, ETA ninety seconds."*
>
> **Adam-12:** *"Dispatch, Adam-12, 10-76 from Pillbox Hill, ETA two minutes."*
>
> **Lincoln-41:** *"Dispatch, Lincoln-41, 10-23 at the parking garage. I have visual on the victim on the second level. No sign of the suspect. Requesting EMS, Code 2."*
>
> **Dispatch:** *"Copy, Lincoln-41. EMS notified, en route Code 2. Adam-12, proceed to the east exit and set a perimeter."*
>
> **Adam-12:** *"Adam-12, copy. Moving to the east exit."*
>
> **Lincoln-41:** *"Dispatch, Lincoln-41 — suspect spotted fleeing on foot northbound on Integrity Way. White male, red hoodie confirmed. I am in foot pursuit."*
>
> **Dispatch:** *"All units, BOL for a white male, red hoodie, armed with a knife, fleeing northbound on Integrity Way from the parking garage. Suspect is wanted for 245. All available units respond Code 3."*
>
> **Adam-12:** *"Adam-12, suspect in custody. Integrity Way and Vespucci Boulevard. Code 4."*
>
> **Dispatch:** *"Copy, Adam-12. Scene is Code 4. All additional units, disregard."*

---

*See also: [10-Codes Reference](10-Codes.md) | [Radio Etiquette Guide](Radio-Etiquette.md) | [NATO Alphabet](NATO-Alphabet.md) | [Common RP Terms Glossary](Common-RP-Terms-Glossary.md)*
