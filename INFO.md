Type: Structural Audit & Stochastic Monte Carlo Simulation Scope: Finnish Employment Policy (TE24 / 2026 Reforms)

1. Overview
This repository contains a mathematical and structural audit of the Finnish government's current employment and social security reforms. The project moves away from ideological debate and applies standard system-testing methodologies to measure whether the public infrastructure operates according to its declared specifications.
The simulation utilizes empirical parameters derived directly from Finlex, Kela, and the OECD to model the economic and cognitive outcomes of a sanctions-based policy versus an asset-based "Skills" paradigm.

2. The Baseline (System Under Test)
The current legislative framework (including the TE24 reform and 2026 Kela reductions) operates as a punitive bureaucracy. Key parameters tested in this simulation include:
Sanctions: Immediate 7-day benefit suspensions (karenssi) for minor technical errors, and up to 50% cuts to basic social assistance for non-compliance.
Cognitive Load: The constant threat of financial ruin activates the biological "threat system". The simulation tracks how this pushes individuals past the clinical exhaustion threshold (KEDS score > 19).
Systemic Friction: Forced mechanical job applications from cognitively exhausted individuals create massive friction for employers' HR departments, resulting in severe resource waste and market mismatch.

3. Simulation Findings (The Math)
Using a stochastic Monte Carlo engine running hundreds of thousands of iterations, we calculated the true systemic costs by factoring in the secondary crisis multipliers (such as healthcare interventions and evictions) triggered by the sanctions model.
Sanctions Model (Current): Total systemic cost of €27.7 million within the test population, driven by the explosive cost of crisis management.
Common Good Model (Proposed): Total systemic cost of €4.5 million, achieved by minimizing the crisis multiplier and focusing on asset utilization.

4. The Alternative Architecture: Skills Blazed
Instead of a deficit-based model that punishes non-compliance, this repository proposes an Asset-Based Community Development (ABCD) framework. The "Skills Blazed" model replaces the bureaucracy with structural efficiency:
Micro-Skills Matching: Utilizes AI to identify and deploy informal and lived-experience skills with a 98% match rate to local needs.
Direct Rewards: Replaces the rigid system of benefit cuts with local, cost-indexed rewards (Common Good credits) that allow individuals to meet basic needs without activating the biological threat response.

5. Methodology & Certification
This is not a political statement; it is a non-conformity report. The methodology mirrors VTT/Eurofins certification standards for system audits: it measures the system against its own specifications, identifies deviations, and reports them with quantified uncertainty. The engine hunts for structural failure modes in the welfare state just as one would test physical infrastructure.

6. Licensing: Commons Clause
License: MIT License + Commons Clause. This project is released as an open-source public utility. The source code, parameter tables, and simulation engine are fully transparent for peer review and municipal implementation. However, the Commons Clause strictly prohibits commercialization. No private entity, startup, or investor may wrap this code in a subscription model or sell it back to the public sector.

7. Parameter Audit Challenge
Every parameter in this simulation is sourced from public data. You are invited to:
Clone this repository.
Review the parameters in /data/simulation_parameters.csv against the source documents.
Run the simulation yourself.
If you can find a mathematically sound parameter set where the sanctions model outperforms the Skills Blazed model, submit a pull request.
The data is public. The math is calculated. The tool is on the table.
