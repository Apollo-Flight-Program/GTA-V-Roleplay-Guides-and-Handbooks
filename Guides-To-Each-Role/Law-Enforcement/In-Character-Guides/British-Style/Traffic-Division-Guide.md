# Traffic Division Guide — Roads Policing Unit

Roads policing is not traffic enforcement with a high-visibility vest. It is a specialist discipline that demands advanced driving skills, detailed knowledge of road traffic legislation, and the ability to make split-second decisions at motorway speeds where a single error in judgement can kill. The Roads Policing Unit (RPU) is responsible for keeping the road network safe, enforcing traffic law, investigating fatal and serious collisions, and intercepting criminals who use the roads to operate.

Every major criminal operation in the city uses the road network. Drug couriers move product along the motorways. Stolen vehicles cross borough boundaries within minutes. Disqualified drivers kill people because nobody stopped them. The roads policing officer is the last line of defence between a dangerous driver and a family in the oncoming lane.

This guide is written for GTA V FiveM servers running the British policing model. The geography is Los Santos and Blaine County, but the procedures, the legislation, and the terminology are British. If your server uses mph, British road markings, and expects officers to say "carriageway" instead of "highway," this is your operational manual.

---

## Role of the Roads Policing Unit

The RPU has a broader remit than simply writing speeding tickets. Roads policing officers are advanced drivers, trained investigators, and specialist enforcers who cover four core functions:

1. **Denying criminals use of the roads** — Using ANPR, intelligence-led stops, and proactive patrolling to intercept wanted persons, stolen vehicles, uninsured drivers, and vehicles linked to criminal activity.
2. **Reducing road casualties** — Speed enforcement, drink/drug driving operations, and targeted enforcement of dangerous driving to prevent death and serious injury on the roads.
3. **Investigating serious and fatal collisions** — When someone dies or is critically injured on the road, RPU officers lead the investigation, reconstruct the collision, and gather evidence for prosecution or inquest.
4. **Traffic management** — Managing major incidents, road closures, diversions, and ensuring the road network continues to function during disruptions.

Roads policing officers are expected to maintain an advanced driving qualification, know road traffic legislation in detail, and operate specialist equipment including ANPR, speed detection devices, and evidential breath testing equipment.

---

## ANPR — Automatic Number Plate Recognition

ANPR is the single most powerful tool available to a roads policing officer. Cameras mounted on police vehicles and at fixed locations continuously scan number plates and check them against national databases in real time. A vehicle that is stolen, uninsured, linked to a wanted person, or flagged for any other reason triggers an alert within seconds.

**What ANPR detects:**

| Alert Type | Meaning | Action |
|---|---|---|
| **Stolen vehicle** | Vehicle reported stolen on the PNC (Police National Computer). | Stop immediately. High-risk stop procedures. Assume occupants may be dangerous. |
| **No insurance** | Vehicle has no valid insurance policy recorded. | Stop and confirm. If uninsured, seize the vehicle under Section 165A of the Road Traffic Act 1988. |
| **Keeper alert** | The registered keeper is wanted, disqualified, or of interest to police. | Stop and identify the driver. The keeper may not be driving, so confirm identity before acting. |
| **Marker — intelligence** | Vehicle linked to criminal intelligence — drug supply, county lines, organised crime. | Stop if safe to do so. Record occupants, search if grounds exist. Feed intelligence back to the source unit. |
| **No VED (Vehicle Excise Duty)** | Vehicle has no valid road tax. | Stop and issue a fixed penalty or seize if appropriate. |
| **No MOT** | Vehicle has no valid MOT certificate (roadworthiness test). | Stop and advise. Vehicle may also be uninsured as a result. |

> **Example — ANPR Hit:**
>
> `/me is patrolling eastbound on the motorway when the ANPR system flags the silver saloon in the nearside lane. The in-car terminal displays: STOLEN — reported 03:42 hours today, carjacking, Davis.`
>
> **RPU Officer:** "Control, Tango 1. ANPR hit on a stolen vehicle, eastbound on the Los Santos Freeway approaching junction 4. Silver saloon, index Foxtrot-Golf-6-2-Alpha-Bravo-Charlie. Reported stolen from Davis in a carjacking earlier today. Two up. Requesting a second unit before I make the stop, over."
>
> **Control:** "Roger, Tango 1. Tango 3 is two minutes out from your location. Hold back and do not stop alone given the circumstances of the theft."

---

## Traffic Law Enforcement

Roads policing officers enforce the full range of road traffic legislation. The key Acts and their most commonly encountered offences are below.

| Offence | Legislation | Action |
|---|---|---|
| **Speeding** | Road Traffic Regulation Act 1984, s.89 | Fixed penalty notice, speed awareness course referral, or summons depending on speed and circumstances. |
| **Driving without due care and attention** | Road Traffic Act 1988, s.3 | Reported for summons or issued a fixed penalty. Includes tailgating, undertaking, and inattentive driving. |
| **Dangerous driving** | Road Traffic Act 1988, s.2 | Arrest. This is an either-way offence carrying a maximum of two years' imprisonment. Driving that falls far below the standard of a competent and careful driver. |
| **Drink driving** | Road Traffic Act 1988, s.5 | Arrest. Evidential breath, blood, or urine test at the station. Limit: 35 microgrammes per 100ml of breath. |
| **Drug driving** | Road Traffic Act 1988, s.5A | Arrest. Roadside drugalyser test, then blood sample at the station. Zero tolerance for illegal drugs; specified limits for prescription medications. |
| **Driving whilst disqualified** | Road Traffic Act 1988, s.103 | Arrest. Vehicle seized. Serious offence — the court has already told this person they cannot drive. |
| **No insurance** | Road Traffic Act 1988, s.143 | Fixed penalty and seizure of vehicle. Driving without insurance is an absolute offence — no excuse is a defence. |
| **Failing to stop after an accident** | Road Traffic Act 1988, s.170 | Reported for summons or arrest if circumstances warrant. Commonly known as "hit and run." |
| **Using a mobile phone whilst driving** | Road Traffic Act 1988, s.41D | Fixed penalty notice. Six points and a fine. |

> **RP Tip:** When issuing a fixed penalty or reporting someone for summons, use the actual legislation references. Saying "I'm reporting you for an offence of driving without due care and attention, contrary to Section 3 of the Road Traffic Act 1988" is immeasurably better roleplay than "you're getting a ticket for bad driving."

---

## Speed Detection

RPU officers use several methods to detect speed offences. Each has specific operational requirements and limitations.

**Stationary speed enforcement:**

- **Laser (LTI 20/20)** — Handheld laser speed detection device. Point, aim, trigger. Provides an instant reading at ranges up to 1,000 metres. Must be operated from a stationary position. Record the reading, the location, and the vehicle details.
- **Radar (mobile unit)** — Vehicle-mounted radar providing continuous speed readings for approaching or receding traffic. Requires calibration checks at the start and end of each deployment.

**Moving speed enforcement:**

- **ProVida / in-car video** — A calibrated in-car camera system that records speed from the pursuing vehicle's speedometer overlay. Used to evidence sustained speeding by following the target vehicle and recording its speed over a measured distance.
- **Pacing** — Following the target vehicle at a constant distance and reading the patrol vehicle's calibrated speedometer. The officer must pace for a sustained distance to provide a reliable reading.

> **Example — Speed Enforcement Stop:**
>
> `/me is positioned on the hard shoulder of the eastbound motorway with the laser device, targeting vehicles in the outside lane. The laser returns a reading of 112 mph on a black sports car.`
>
> **RPU Officer:** "Control, Tango 2. I've just lasered a vehicle at 112 in a 70 limit, eastbound motorway near junction 6. Black sports car, index Hotel-Yankee-1-9-Juliet-Kilo-Lima. Pulling out to stop, over."
>
> `/me activates the blue lights and pulls onto the carriageway, closing on the target vehicle. Signals it to pull to the hard shoulder.`
>
> **RPU Officer:** "Good afternoon. I'm PC Barrett from the Roads Policing Unit. I've just recorded you at 112 miles per hour in a 70 limit using a calibrated laser device. That speed is well beyond the threshold for a fixed penalty — you will be reported for the question of prosecution for speeding. I'm going to need your driving licence and proof of insurance, please."

---

## Pursuits — Authority and Conduct

Vehicle pursuits are inherently dangerous and must be authorised and managed under strict protocols. Not every officer is permitted to pursue, and not every pursuit should be continued.

**Who can pursue:**

- Only officers who hold an advanced driving qualification or response driving certification are authorised to engage in pursuits. Standard drivers must not pursue.
- RPU officers are advanced drivers by default and are the primary pursuit resource.

**Pursuit authority:**

| Authority Level | Role | Responsibility |
|---|---|---|
| **Pursuit initiator** | Officer who begins the pursuit | Immediately notifies control with reason, location, direction, speed, vehicle description, driving manner, and conditions. |
| **Pursuit controller** | Inspector or above | Authorises continuation. Continuously assesses risk. Can order termination at any time. |
| **Tactical advisor** | RPU supervisor | Advises on tactical options — TPAC, stinger, helicopter, or termination. |

A pursuit is terminated if: the risk outweighs the need to apprehend; it enters a populated area at excessive speed; the officer cannot maintain safe driving; the suspect's identity is known; or conditions make continuation unsafe.

> **Example — Pursuit RP:**
>
> **RPU Officer:** "Control, Tango 1. Vehicle failed to stop for me on the Del Perro Freeway, now heading westbound at approximately 90 mph. Red hatchback, index Mike-Papa-6-1-Foxtrot-Delta-Golf. Manner of driving is erratic — weaving through traffic, using the hard shoulder. Road conditions are dry, moderate traffic. Requesting pursuit authority, over."
>
> **Control:** "Tango 1, Duty Officer is monitoring. Pursuit is authorised. Continue to provide commentary. Any RPU units available for TPAC?"
>
> **RPU Officer:** "Tango 1, now passing junction 3 westbound, speed is 95, suspect has moved to the outside lane. Traffic is thinning out ahead. Still erratic — nearly clipped a lorry at the last junction."

---

## TPAC — Tactical Pursuit and Containment

TPAC is a coordinated method of bringing a pursued vehicle to a controlled stop using multiple police vehicles. It is not ramming. It is a disciplined, trained manoeuvre that requires a minimum of three vehicles and specific authorisation.

**Roles in a TPAC:**

| Position | Role |
|---|---|
| **Lead vehicle** | Positions in front of the suspect vehicle and gradually reduces speed to slow the pursuit. Controls the pace. |
| **Nearside vehicle** | Takes position alongside the suspect on the left (nearside), preventing lane changes in that direction. |
| **Offside vehicle** | Takes position alongside the suspect on the right (offside), boxing the vehicle in. |
| **Rear vehicle** | Follows directly behind the suspect, closing the box and preventing the suspect from braking and reversing out. |

TPAC requires authorisation from the pursuit controller (Inspector or above). It is only deployed when conditions allow — straight roads, manageable speeds, and no significant risk to other road users. TPAC is not attempted at high speed or in heavy traffic.

---

## Stinger Deployment

A stinger (hollow spike tyre deflation device) is used to deflate the tyres of a pursued vehicle, bringing it to a controlled stop. Stinger deployment is a tactical option that requires training and authorisation.

**Deployment considerations:**

- The officer deploying the stinger must be in a position of safety — behind a bridge parapet, barrier, or other hard cover
- The stinger must be placed in advance of the pursuit, not thrown in front of a vehicle at the last moment
- Motorcycles must not be stung — the risk of a fatal outcome is too high
- The deploying officer must have a clear view of the approaching pursuit to deploy at the correct moment and withdraw the device after the target vehicle has passed to avoid deflating pursuing police vehicles
- Stinger deployment requires authorisation from the pursuit controller

> **Example — Stinger Deployment RP:**
>
> **Control:** "Tango 4, pursuit approaching your location on Route 68, eastbound, two miles out. Speed 80 mph. Are you in position?"
>
> **RPU Officer (Tango 4):** "Tango 4, affirmative. Behind the crash barrier at the layby near the wind farm. Stinger ready. Clear sight for 400 metres. Standing by."
>
> `/me crouches behind the barrier, gripping the deployment cord. Sees the pursuit approaching. Yanks the cord at the right moment, deploying the stinger across the lane. The suspect's nearside front tyre hits the spikes. Immediately pulls the stinger back before the pursuing units arrive.`
>
> **RPU Officer:** "Tango 4, stinger successful — nearside front deflating. Vehicle slowing, pulling to the verge."

---

## Drink and Drug Driving

Detecting and removing impaired drivers from the road is a core RPU responsibility. British drink/drug driving enforcement follows a strict evidential process.

**Roadside procedure:**

1. **Require a breath test** — Under Section 6 of the Road Traffic Act 1988, you may require a breath test if you suspect a person has been drinking, has committed a moving traffic offence, or has been involved in a collision.
2. **Preliminary breath test** — Administered at the roadside using an approved screening device. A positive result (or a refusal) leads to arrest.
3. **Arrest and transport** — The driver is arrested on suspicion of driving with excess alcohol and transported to custody.
4. **Evidential breath test** — At the station, two evidential breath specimens are taken on a calibrated Intoximeter. The lower of the two readings is used. The legal limit is 35 microgrammes of alcohol per 100 millilitres of breath.
5. **Blood/urine option** — If the lower reading is between 40 and 50 microgrammes, the driver may opt to replace the breath specimens with a blood or urine sample.

**Drug driving:**

- A roadside drugalyser test can detect cannabis and cocaine.
- If the test is positive or you have reasonable grounds to suspect drug impairment (pupil dilation, coordination failure, erratic behaviour), arrest and transport to custody.
- At the station, a blood sample is taken and sent for laboratory analysis. Specified limits exist for both illegal and prescription drugs.

> **Example — Drink Drive Stop:**
>
> `/me approaches the vehicle stopped after being observed drifting between lanes. Notes the smell of alcohol as the window comes down.`
>
> **RPU Officer:** "Good evening. I'm PC Hartley from the Roads Policing Unit. I've stopped you because your vehicle was drifting across the lane markings. I can smell alcohol on your breath. Under Section 6 of the Road Traffic Act 1988, I require you to provide a specimen of breath for a preliminary breath test. Please step out of the vehicle."
>
> `/me retrieves the screening device and administers the test.`
>
> **RPU Officer:** "Take a deep breath and blow continuously into this tube until I tell you to stop. Blow now... keep going... and stop. Thank you."
>
> `/me reads the screening device. Positive indication.`
>
> **RPU Officer:** "That's come back positive. I'm arresting you on suspicion of driving a motor vehicle with excess alcohol, contrary to Section 5 of the Road Traffic Act 1988. You do not have to say anything. But it may harm your defence if you do not mention when questioned something which you later rely on in court. Anything you do say may be given in evidence. Do you understand?"

---

## Section 59 Warnings — Anti-Social Driving

Section 59 of the Police Reform Act 2002 gives officers the power to seize vehicles used in a manner causing alarm, distress, or annoyance. On the **first encounter**, the driver receives a verbal warning recorded on the PNC against driver and vehicle. On any **second encounter** within twelve months, the vehicle is seized immediately — no second warning.

> **Example — Section 59 Warning:**
>
> **RPU Officer:** "I've just witnessed you doing doughnuts in the car park at Del Perro Pier, causing alarm to members of the public. Under Section 59 of the Police Reform Act 2002, I am warning you that if you or this vehicle are reported for anti-social use again within twelve months, the vehicle will be seized. This warning is being recorded. Do you understand?"

---

## Vehicle Defect Notices and Prohibition

When an RPU officer encounters a vehicle with defects, they may issue one of three notices: a **Vehicle Defect Rectification Scheme (VDRS)** notice requiring repair within 14 days (for minor defects like blown bulbs or minor tyre wear); an **immediate prohibition (PG9)** preventing the vehicle from moving until the defect is rectified (for serious defects like bald tyres or defective brakes); or a **delayed prohibition** allowing the vehicle to be driven to a place of repair only.

---

## Road Traffic Incidents (RTIs)

When attending a road traffic incident, the RPU officer's priorities are: **preserve life** (first aid, request ambulance), **preserve the scene** (close lanes, protect evidence), **identify witnesses**, **investigate** (measurements, photographs, accounts), and **restore the road** as soon as safely possible.

RPU officers work closely with paramedics at RTIs. The ambulance service has primacy over casualty care — your job is to secure the scene, manage traffic, and support the medics.

When a collision results in death, the scene becomes a crime scene. A Forensic Collision Investigator (FCI) attends to reconstruct the incident. The road may be closed for hours. The SIO takes command, potentially leading to charges of causing death by dangerous driving or driving under the influence.

> **Example — RTI Attendance:**
>
> **RPU Officer:** "Control, Tango 2. On scene at the RTI on Route 68 near the petrol station. Two vehicles, head-on. One driver trapped, requesting LAS and LFB. Closing the westbound carriageway at the junction."
>
> `/me parks across the carriageway with blue lights active, deploys warning signs, then moves to the trapped driver to provide reassurance until paramedics arrive.`

---

## Terminology Reference

British roads policing uses specific terminology. Using the correct terms is essential for immersion on a British RP server.

| British Term | American Equivalent | British Term | American Equivalent |
|---|---|---|---|
| **Carriageway** | Roadway / highway | **Hard shoulder** | Shoulder / breakdown lane |
| **Nearside** | Passenger side (left in UK) | **Offside** | Driver side (right in UK) |
| **Slip road** | On-ramp / off-ramp | **Central reservation** | Median |
| **Dual carriageway** | Divided highway | **Roundabout** | Traffic circle / rotary |
| **Index** | License plate / tag | **Verge** | Roadside / shoulder |
| **RTI / RTC** | MVA / traffic accident | **Layby** | Pull-off / rest area |
| **LAS** | EMS / ambulance | **LFB** | Fire department |
| **MOT** | Vehicle inspection | **VED** | Vehicle registration fee |
| **PNC** | NCIC / database | **Blues and twos** | Lights and sirens |

---

## Adapting to GTA V RP

- **Drive on the left** if your server enforces British road rules.
- **Use ANPR roleplay** even without a scripted system — a `/me` checking the terminal followed by a radio call works.
- **Speed enforcement requires fairness.** Use speedometer mods where available; otherwise roleplay laser or ProVida with realistic readings.
- **Pursuits are not routine.** An Inspector must authorise continuation; pursuits are abandoned if risk is too high.
- **Section 59 is your anti-hooligan tool.** Graduated enforcement before seizure.
- **Fatal RTIs are major RP events.** Road closures, forensics, witness appeals. Do not rush them.
- **Terminology matters.** Say "carriageway," not "highway." Say "index," not "plate."

Roads policing is one of the most demanding and rewarding specialist roles on a British RP server. Master the craft, know the law, and drive like your life depends on it — because on these roads, it does.
