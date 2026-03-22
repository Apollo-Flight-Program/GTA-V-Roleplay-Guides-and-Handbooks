# EMS Response Codes Reference

Emergency Medical Services response codes define how urgently a unit responds to a call and communicate the nature of the emergency between dispatch, EMS, and other agencies. This reference covers response priorities, situation codes, and hospital-to-EMS communication codes used across GTA V roleplay servers.

---

## EMS Response Priority Levels

| Level | Name | Description | Equipment |
|---|---|---|---|
| **Code 1** | Routine | Non-emergency transport or follow-up. No urgency. | No lights or siren |
| **Code 2** | Urgent | Scene requires attention, not immediately life-threatening. | Lights only, no siren (server dependent) |
| **Code 3** | Emergency | Life-threatening situation. Respond immediately. | Full lights and siren |
| **Code 4** | Scene Secure / Stand Down | No further EMS assistance needed. | N/A |
| **Code 5** | Stage** | Do not enter the scene. Await law enforcement clearance. | N/A — maintain safe distance |

*\*Staging is not an EMS response code — it is a tactical instruction to wait until a scene is safe.*

---

## EMS Situation Codes

These codes describe the type of call, transmitted over radio or logged in CAD.

### Trauma and Injury

| Code | Meaning |
|---|---|
| **Alpha** | Minor injury. Non-emergency transport. |
| **Bravo** | Injury — uncertain severity. Urgent but stable. |
| **Charlie** | Serious injury — life-threatening potential. Code 2 response. |
| **Delta** | Critical injury or life-threatening emergency. Code 3 response. Immediate intervention required. |
| **Echo** | Cardiac or respiratory arrest. Code 3 — all available units. CPR in progress. |
| **Omega** | Clearly deceased. No resuscitation appropriate. Document and notify coroner. |

### Specific Call Types

| Code | Meaning |
|---|---|
| **901** | Medical emergency — ambulance needed |
| **901K** | Ambulance needed — victim is deceased on arrival |
| **902** | Minor injury — ambulance requested |
| **903** | Multiple casualties — request additional units |
| **904** | Fire — EMS standby requested |
| **905** | Vehicle accident — injuries unknown |
| **905M** | Vehicle accident — major injuries confirmed |
| **906** | Shooting — multiple GSWs reported |
| **907** | Stabbing |
| **908** | Overdose / toxicological emergency |
| **910** | Mental health crisis — subject may be a danger to themselves or others |
| **912** | Childbirth / obstetric emergency |

---

## Scene Status Codes

Reported by EMS on arrival and throughout the call.

| Code | Meaning |
|---|---|
| **10-23** | Arrived on scene |
| **10-24** | Assignment complete — scene cleared |
| **10-52** | Ambulance required (used when another unit requests EMS) |
| **10-76** | En route to location |
| **10-8E** | EMS unit in service / available |
| **10-7E** | EMS unit out of service |
| **MCI** | Mass Casualty Incident declared — multiple patients, resources strained |
| **Code Red** | The receiving hospital is at capacity — redirect to alternate facility |

---

## Patient Condition Codes (Transmission to Hospital)

When transporting, EMS transmits patient status to the receiving hospital so they can prepare.

| Status | Description |
|---|---|
| **Stable** | Vital signs within acceptable range. No immediate life threat. |
| **Serious** | Vital signs abnormal but monitored. Patient responsive. |
| **Critical** | Vital signs severely compromised. Immediate intervention needed on arrival. |
| **Code Blue** | Full cardiac/respiratory arrest. CPR in progress during transport. |
| **DOA** | Dead on arrival — patient deceased before EMS contact. No transport, notify coroner. |

---

## Hospital Diversion Status

Hospitals communicate availability to EMS dispatch.

| Status | Meaning |
|---|---|
| **Open** | Hospital is receiving patients normally. |
| **On diversion** | Hospital is temporarily redirecting incoming patients to another facility. |
| **Trauma diversion** | Trauma bay specifically closed — redirect trauma patients. |
| **Full diversion** | All services closed to new admissions. |

---

## Inter-Agency Codes (EMS to Police)

| Code | Meaning |
|---|---|
| **Scene not safe** | EMS is staging — police have not confirmed the scene is clear |
| **Cleared to respond** | Law enforcement has secured the scene — EMS may enter |
| **Medical priority** | A message from EMS to police requesting they clear a route or hold traffic |
| **EMS to Fire** | Requesting fire department resources at an EMS scene |

---

## Usage Notes

- Always identify your unit before transmitting: *"Dispatch, EMS-2, we are 10-76 to the GSW on Innocence. ETA ninety seconds."*
- Confirm patient status with the receiving hospital before arrival when transporting critical patients
- Use plain language when codes create ambiguity — especially during MCIs

---

*See also: [EMS IC Glossary](Glossaries/IC-EMS-Glossary.md) | [Triage and Treatment Reference](Triage-and-Treatment-Reference.md) | [Radio Etiquette](../Communication/Radio-Etiquette.md)*
