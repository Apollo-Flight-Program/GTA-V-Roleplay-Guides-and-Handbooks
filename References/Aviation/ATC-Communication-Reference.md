# ATC Communication Reference

Air Traffic Control communication procedures for GTA V civilian aviation roleplay. This covers how pilots communicate with ATC at controlled airports, what clearances look like, and how to properly execute standard aviation radio exchanges.

---

## Frequency Types

| Frequency Type | Purpose |
|---|---|
| **Ground** | Aircraft movement on the ground — taxiing to and from runways |
| **Tower** | Takeoffs and landings at controlled airports |
| **Approach** | Arriving aircraft descending and approaching the airport |
| **Departure** | Aircraft that have taken off transitioning to en route |
| **Center / En Route** | Aircraft flying between airports at altitude |
| **ATIS** | Automatic Terminal Information Service — recorded broadcast of current airport conditions |
| **Unicom** | Self-announced communication at uncontrolled airports — no ATC present |
| **Guard** | Emergency frequency monitored by all military and some civilian ATC |

---

## Standard Flight at a Controlled Airport

### Step 1: ATIS Before Calling

Before calling ATC, listen to the ATIS broadcast to get:
- Current altimeter setting
- Active runway
- Weather conditions
- Any NOTAMs
- A phonetic letter identifying the broadcast version (e.g., "Information Sierra")

### Step 2: Calling Clearance Delivery (IFR)

```
Pilot: "[Airport] Clearance, [Aircraft ID], request IFR clearance to [destination]."

ATC: "[Aircraft ID], cleared to [destination] via [route]. Climb and maintain [altitude]. 
      Departure frequency [freq]. Squawk [code]."

Pilot: "Cleared to [destination] via [route], climb and maintain [altitude], 
       departure [freq], squawking [code]. [Aircraft ID]."
```

### Step 3: Calling Ground

```
Pilot: "[Airport] Ground, [Aircraft ID], at [location], ready to taxi, Information [ATIS letter]."

ATC: "[Aircraft ID], taxi to runway [number] via [taxiways]."

Pilot: "Taxi runway [number] via [taxiways]. [Aircraft ID]."
```

### Step 4: Calling Tower

```
Pilot: "[Airport] Tower, [Aircraft ID], holding short runway [number], ready for departure."

ATC: "[Aircraft ID], winds [direction] at [speed], runway [number], cleared for takeoff."

Pilot: "Runway [number], cleared for takeoff. [Aircraft ID]."
```

### Step 5: Departure

After takeoff, when directed to contact departure:

```
Pilot: "[City] Departure, [Aircraft ID], passing [altitude], climbing to [altitude]."

ATC: "[Aircraft ID], radar contact. Fly heading [degrees], climb and maintain [altitude]."

Pilot: "Heading [degrees], climbing to [altitude]. [Aircraft ID]."
```

---

## Arrival Procedures

### Initial Contact with Approach

```
Pilot: "[Airport] Approach, [Aircraft ID], [position], [altitude], request [approach type]."

ATC: "[Aircraft ID], [Airport] Approach, descend and maintain [altitude], 
      expect runway [number], information [ATIS letter]."
```

### ILS / Instrument Approach Clearance

```
ATC: "[Aircraft ID], turn left heading [degrees], intercept the localizer, 
     cleared ILS runway [number] approach."

Pilot: "Left [degrees], intercept localizer, cleared ILS runway [number]. [Aircraft ID]."
```

### Cleared to Land

```
ATC: "[Aircraft ID], wind [direction] at [speed], runway [number], cleared to land."

Pilot: "Runway [number], cleared to land. [Aircraft ID]."
```

---

## Uncontrolled Airport (Unicom)

At airports without ATC, pilots self-announce position and intentions on the Unicom frequency.

```
"[Airport] traffic, [Aircraft ID], [position], [altitude], [intentions], [Airport]."
```

**Examples:**
> *"Sandy Shores traffic, Cessna N-4-4-Lima, 5 miles north, descending through 2,500, inbound for landing, Sandy Shores."*

> *"Sandy Shores traffic, Cessna N-4-4-Lima, downwind runway 21, touch and go, Sandy Shores."*

> *"Sandy Shores traffic, Cessna N-4-4-Lima, clear of the runway, Sandy Shores."*

---

## Special Situations

### Declaring an Emergency

Emergency calls have priority over all other traffic. Use MAYDAY for life-threatening emergencies, PAN-PAN for urgent non-emergency situations.

```
"MAYDAY MAYDAY MAYDAY. [Aircraft ID]. [Nature of emergency]. [Position]. 
 [Altitude]. [Intentions]. [Persons on board]."
```

**Example:**
> *"MAYDAY MAYDAY MAYDAY. Cessna N-4-4-Lima. Engine failure. Five miles east of LSIA. Altitude 3,000 descending. Attempting emergency landing. Two persons on board."*

### Requesting Radar Vectors

```
"[Facility], [Aircraft ID], request radar vectors for [purpose]."
```

### Reporting Traffic in Sight / Not in Sight

```
"Traffic in sight." — I see the other aircraft.
"Negative contact." — I do not see the other aircraft.
"Looking." — I am searching for the traffic.
```

---

## ATC Phraseology Quick Reference

| Phrase | Meaning |
|---|---|
| **"Cleared for takeoff"** | Authorization to enter the runway and depart |
| **"Cleared to land"** | Authorization to continue the approach to a full stop |
| **"Hold short of runway X"** | Stop before entering runway X |
| **"Line up and wait"** | Enter the runway and hold, do not depart yet |
| **"Go around"** | Abort the landing, climb and rejoin the pattern |
| **"Squawk XXXX"** | Set your transponder to the specified four-digit code |
| **"Squawk ident"** | Press the ident button on your transponder |
| **"Radar contact"** | ATC has your aircraft identified on radar |
| **"Radar service terminated"** | ATC is no longer tracking you on radar |
| **"Contact [frequency]"** | Change to the specified frequency |
| **"Say again"** | Repeat your last transmission |
| **"Unable"** | Cannot comply with the instruction |
| **"Wilco"** | Will comply |
| **"Roger"** | Message received |

---

*See also: [IC Aviation Glossary](Glossaries/IC-Aviation-Glossary.md) | [Military Aviation Terms](Military-Aviation-Terms-and-Jargon.md) | [Radio Etiquette](../Communication/Radio-Etiquette.md) | [NATO Alphabet](../Communication/NATO-Alphabet.md)*
