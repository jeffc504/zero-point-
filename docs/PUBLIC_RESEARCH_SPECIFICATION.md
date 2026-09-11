# Public Research Specification

## 1. Research question

Can controlled electromagnetic boundary conditions in carefully instrumented cavities produce measurable dynamical-Casimir or related quantum-vacuum effects beyond known backgrounds and measurement artifacts?

This is an experimental question. The apparatus should therefore be designed first as a **measurement platform**, not as a commercial generator.

## 2. Core experimental architecture

A public test platform may combine:

- a sealed vacuum-compatible test chamber;
- a replaceable cavity or resonator cartridge;
- planar and/or toroidal conductive boundary geometries;
- low-loss dielectric support structures;
- optional graphene-based thermal or interface layers;
- controlled boundary actuation or electromagnetic modulation;
- cryogenic cooling where required by the detector system;
- superconducting or other ultra-low-noise photon/field sensors;
- isolated voltage, current, temperature, pressure, vibration, magnetic-field, and vacuum sensing;
- synchronized data acquisition;
- electromagnetic shielding and filtered feedthroughs;
- independent input/output power measurement;
- hardware emergency shutdown and stored-energy discharge.

The cartridge concept is useful because different geometries and materials can be compared inside the same measurement infrastructure.

## 3. Casimir / dynamical-Casimir research path

A conservative experimental program should progress in stages:

1. **Static calibration**
   - Characterize geometry, separation, surface quality, chamber pressure, thermal state, vibration, and detector noise.
   - Verify known electrostatic and electromagnetic backgrounds before looking for anomalous signals.

2. **Static Casimir measurement**
   - Reproduce a conventional Casimir-force measurement where possible.
   - Compare the measured force against accepted theory with quantified uncertainty.

3. **Controlled boundary modulation**
   - Modulate a cavity boundary using a calibrated actuator or tunable boundary element.
   - Record total actuator/driver input power, mechanical motion, electromagnetic leakage, and detector output synchronously.

4. **Photon / field detection**
   - Search for statistically significant correlated signals while using blank runs, detuned controls, dummy loads, and shielded reference detectors.

5. **Energy-balance measurement**
   - Any recovered electrical signal must be compared against **all** supplied energy.
   - A credible result requires uncertainty bounds and independent metrology.

6. **Independent replication**
   - Release geometry, test conditions, raw data, calibration files, and analysis scripts for any claimed anomaly.

## 4. Toroidal cavity concept

A toroidal geometry is proposed as an experimental comparison to planar cavities because a closed-loop geometry can reduce certain edge effects and provide a convenient platform for distributed sensing and field-control elements.

The public release deliberately does not include protected resonant-frequency tuning information. Researchers should characterize their own cavity modes experimentally and document them independently.

Potential comparative measurements include:

- background electromagnetic mode structure;
- cavity losses and quality factor;
- thermal stability;
- spatial field distribution;
- photon-count correlations;
- mechanical-vibration coupling;
- sensitivity to chamber pressure and temperature;
- comparison against equivalent planar test structures.

## 5. Materials and interfaces

Candidate experimental materials may include conventional conductive metals, superconducting materials, dielectric spacers, ceramic supports, graphene-enhanced thermal interfaces, and mechanically stable substrate materials.

Graphene should be treated as an experimental variable rather than as a guaranteed performance enhancer. Useful comparisons include otherwise-identical devices with and without graphene-containing interfaces.

## 6. Measurement discipline

Every run should log, at minimum:

- timestamp and test configuration;
- vacuum pressure;
- relevant temperatures;
- actuator/driver input voltage and current;
- total electrical input power;
- coolant/pump/control-system power;
- detector outputs;
- electromagnetic-field probes;
- vibration data;
- cavity state and geometry;
- shielding configuration;
- load-bank or output measurement;
- calibration state;
- fault and interlock events.

## 7. Controls that should be mandatory

Use:

- powered and unpowered controls;
- detuned or disabled-cavity controls;
- dummy loads;
- detector dark-count characterization;
- thermal-equivalent controls;
- EMI injection tests;
- mechanical-vibration injection tests;
- randomized/blinded run labels where practical;
- independent power analyzers;
- repeated measurements by a second team.

## 8. What would count as an interesting result?

A signal becomes scientifically interesting only after known explanations are aggressively eliminated.

A strong result would be:

- repeatable;
- synchronized with a controlled experimental variable;
- absent in appropriate controls;
- above detector and calibration uncertainty;
- independently measured by redundant instruments;
- independently replicated;
- consistent with a closed energy audit.

## 9. Safety

Experimental versions may involve vacuum systems, cryogens, superconducting hardware, high stored electrical energy, strong electromagnetic fields, high-voltage drivers, and sensitive instrumentation.

Use appropriate engineering controls, guarding, grounding, interlocks, emergency stops, pressure relief, capacitor discharge systems, trained personnel, and applicable laboratory/electrical safety standards.

## 10. Invitation

Researchers are invited to reproduce, falsify, improve, or replace any public concept in this release. Null results are welcome. The goal is to move the question from speculation toward measurable evidence.
