# Entry X: [Short title of change]

# Date:

YYYY-MM-DD

# Change made:

[Describe exactly what was changed. Be specific about the board, firmware module, enclosure part, sensing method, layout, test setup, or whatever was touched.]

# Why:

[State the reason for the change. Focus on design intent: improve sensing stability, reduce noise, simplify routing, make assembly easier, improve ergonomics, fix a bug, reduce latency, etc.]

# How (settings/params):

[Document the actual technical details used. Examples below—keep only what applies.]

Electrical:
- MCU: [part number]
- Sensor method: [self-cap / mutual-cap / direct touch pad / etc.]
- Electrode material/layer: [copper layer, size, shape]
- Pull-up / pull-down values: [resistor values]
- Filter caps: [cap values]
- Scan rate: [Hz]
- Threshold(s): [touch / release / debounce]
- Supply voltage: [e.g. 3.3 V]
- Protection / filtering: [ESD, RC, shielding, guard ring, ground pour notes]

PCB/Layout:
- Board revision: [Rev A / Rev B / etc.]
- Stackup: [2-layer / 4-layer]
- Board thickness: [mm]
- Copper weight: [oz]
- Key pitch: [mm]
- Trace widths / clearances: [values]
- Ground strategy: [solid plane / split / local pours]
- Connector(s): [type / pin count]
- Any routing constraints: [USB diff pair, keepout, sensor spacing, etc.]

Mechanical:
- Plate material: [FR4 / aluminum / acrylic / etc.]
- Case material: [printed resin / PLA / PETG / machined aluminum / etc.]
- Mounting method: [top mount / tray mount / gasket / integrated]
- Fasteners: [size/type]
- Switch/key spacing: [if relevant]
- Prototype print settings: [layer height, infill, nozzle, etc.]

Firmware:
- Scan algorithm: [polling / interrupt / filtered delta / baseline tracking]
- Debounce time: [ms]
- Baseline update rule: [fixed / adaptive / decay-based]
- HID mode: [USB HID / BLE / etc.]
- Test firmware version/commit: [identifier]
- Logging / telemetry enabled: [yes/no and what was logged]

Validation / Test setup:
- Test method: [bench test / finger touch test / repeated tap test / long idle drift test / USB enumeration test / etc.]
- Tools used: [multimeter, scope, logic analyzer, serial logs, KiCad DRC/ERC, etc.]
- Conditions: [powered over USB, enclosure open, bare PCB, with keycap installed, etc.]

# Result:

[State what happened. Did it work, partially work, fail, or just pass CAD/bench checks? Keep this honest.]

# Next:

[State the immediate next task only. Not the five-year plan. One concrete next move.]

# Status: [Concept only / Implemented / Bench tested / CAD validated / PCB ordered / Assembled / Firmware tested / Validated in production]