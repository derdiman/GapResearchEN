# Method-specific design checks

Read only sections relevant to the proposed design. Unknown quantities require a justification plan or “to be verified,” not an invented value. Apply these checks to research design; do not claim that unperformed tests passed.

## Experiments and measurement

Define the question, independent/dependent variables, controls and relevant conditions. Justify independent samples and repetitions using variability, an effect/precision target, pilot data or applicable standards. Distinguish independent specimens from repeated readings of the same specimen; avoid pseudoreplication.

Plan randomization, blocking, control specimens and order effects when relevant. Record preparation, equipment, calibration, range, resolution and uncertainty. Plan assumptions, outliers, missingness, effect sizes and intervals before inspecting outcomes. Verify the official edition and scope of a claimed standard rather than guessing a clause.

## Field, observational and case studies

Define the unit: person, machine, activity, project, shift, day, facility or other system. Align data granularity with claims; aggregated weekly records cannot automatically identify causes of individual activity delays.

Specify timing, measurement frequency, provenance, missing records and variable definitions. Account for clustering/nesting and repeated observations. Address confounding such as scale, season, team or technology. Separate association, prediction and causation; observational correlation alone is not causal proof.

For few cases, prioritize context-rich comparison and carefully bounded analytical transfer rather than broad statistical generalization.

## Qualitative and human-centered inquiry

Select interviews, observation, documents or surveys because the question requires them. Explain sampling rationale, recruitment/access, consent, interview/observation procedures, coding or analytical approach and researcher reflexivity. Align the claimed scope with the participants and context.

Plan how interpretations will be supported by records, contrasting cases and an audit trail. Do not invent participant quotations, claim achieved saturation before data collection or impose statistical representativeness on a purposive qualitative sample. For surveys, address construct definition, instrument suitability, piloting, recruitment and nonresponse.

## Numerical and physical modeling

Specify purpose, governing relationships, assumptions, geometry/system boundaries, inputs and validity range. Record initial/boundary conditions and material/system properties with provenance.

Plan mesh, time-step, tolerance or solver-convergence checks where relevant. Verify implementation using analytical solutions, benchmarks or an independent implementation. Validate the model against appropriate evidence not already used to calibrate it; a good fit to calibration data alone is not independent validation.

Analyze parameter uncertainty, sensitivity and model limitations. Record software, solver, versions, settings and relevant hardware.

## Simulation

Check conceptual logic and implementation. Ground input distributions in observations, literature or explicitly justified assumptions. Justify warm-up where needed, run length, replications and random seeds. Evaluate scenarios and uncertainty. Label simulated outputs as simulation, not field observations.

## Optimization and decision models

State decision variables, units, objectives and constraints. Preserve realistic technical/operational requirements. Compare against a credible baseline using a fair computational or evaluation budget where relevant.

Assess feasibility, solution quality/optimality claims and computational cost. Study sensitivity and scenario dependence; expose multi-objective trade-offs. A model-recommended solution requires pilot/field evidence before claiming real operational improvement.

## AI and data-driven prediction

Document provenance, labels, representativeness, imbalance and data quality. Split training/validation/test data according to independent units, groups and time; avoid leakage through repeated people, devices, projects or correlated time windows.

Keep model selection and hyperparameter tuning away from final test outcomes. Use simple and established baselines, task-appropriate metrics and error analysis. Consider external evaluation. Record code, dataset versions, seeds, dependencies and computing environment.

## Software, algorithms and prototypes

Define requirements, use cases and measurable acceptance criteria. Select meaningful unit, integration, system, performance or security checks based on the artifact. Use representative benchmark data and workloads. Record versions, dependencies, hardware and test conditions; make the evaluation repeatable.

For prototypes, connect design choices and tests to the user need and constraints. A working implementation does not by itself show usefulness or superiority.

## Literature synthesis

Clarify review type, protocol where needed, eligibility, deduplication and screening stages. Record databases, executed searches and dates. Plan extraction and design-appropriate appraisal. Assess whether studies are comparable enough for quantitative pooling; do not recommend meta-analysis merely because numerical results exist. Use reporting guidelines appropriate to the actual review design.

## Common final check

The question, data, unit of analysis, analysis and conclusion must align. Plan reporting of negative, failed and unexpected results. Explain how uncertainty affects conclusions.

Address permissions, consent, confidentiality and data protection when applicable. Distinguish a research plan from a real-world professional determination. Safety-critical implementation requires competent supervision and verification against relevant authorities/standards.

Document shareability and licensing of data, code and procedures. In simple language, verification asks whether the implementation is correct; validation asks whether it adequately represents the phenomenon or meets the intended need.
