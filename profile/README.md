## Pisonics

Inline **density and concentration meters** for slurry, chemicals and process
liquids — built in Xi'an, China, and running in mining, power, chemical and
dredging plants worldwide.

Our flagship **PS7000** measures slurry density by ultrasonic acoustic
impedance. Because it reads a material property rather than a radioactive
count rate, it needs no source, no licence and no disposal route at end of
life — across DN50 to DN1000.

### Repositories

| | |
|---|---|
| [**ps7000-modbus**](https://github.com/Pisonics/ps7000-modbus) | Read-only Modbus RTU register map, with working Python and C# clients. Machine-readable JSON and CSV. |
| [**ps7000-hart**](https://github.com/Pisonics/ps7000-hart) | HART 5 command set, device variable map and status decoding. |
| [**pisonics-docs**](https://github.com/Pisonics/pisonics-docs) | Current English datasheets for PS7000, PS7010 and PS7020 — CC BY licensed, so you can drop them straight into a tender package. |
| [**density-calc**](https://github.com/Pisonics/density-calc) | Slurry concentration and dredge production maths — Cv, Cw, dry tonnes per hour, bank volume. |

Integrating a meter into a PLC, DCS or historian? Start with
[ps7000-modbus](https://github.com/Pisonics/ps7000-modbus) — the register map is
generated from a single source of truth and the decoder is unit tested, so the
parts that usually cost a day (32-bit word order, the off-by-one on register
numbers) are documented rather than left to be discovered on site.

### Measurement principles we build

Ultrasonic acoustic impedance · ultrasonic attenuation · time-of-flight ·
tuning fork · Coriolis · differential pressure · optical refractive and
spectral · microwave · exempt-source gamma

### Elsewhere

- Website — https://www.pisonics.com
- How acoustic impedance measurement works — https://www.pisonics.com/guides/acoustic-impedance-explained
- Choosing an online density meter — https://www.pisonics.com/guides/how-to-choose-density-meter
- Non-nuclear alternatives to Cs-137 gauges — https://www.pisonics.com/guides/non-nuclear-alternatives-overview

info@pisonics.com
