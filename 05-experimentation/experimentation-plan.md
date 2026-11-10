# A/B Experiment Brief, RouteLogic (B2B)

## Parameters
| Parameter | Decision |
|---|---|
| Feature under test | One-Click Compliance Checklist |
| Persona | Frontline Dispatcher / Logistics Coordinator who coordinates daily deliveries, manages route changes, monitors driver progress, and completes required compliance workflows. |
| Expected outcome | Expected outcome: Frontline coordinators complete compliance work faster and within RouteLogic Velocity, reducing manual effort and reliance on workarounds while maintaining compliance accuracy and completeness. |
| Primary success metric | Target: ~20% reduction, from 31 minutes to ≤25 minutes per coordinator per day. |
| Baseline rate | Baseline rate: 31 minutes per coordinator per day spent on manual workarounds. |
| Guardrail metric | Manager Reporting CSAT must remain at or above 4.5/5. |
| Guardrail boundary | If CSAT falls below 4.5/5 during the experiment, investigate before scaling to ensure the compliance simplification is not degrading the reporting experience. |
| Second guardrail | · |
| Minimum Detectable Effect | 20%reduction |
| Sample size per arm | 978 |
| Traffic split | 50/50 |
| Test duration | 4 weeks |
| Significance threshold | p<0.05 |

## Control vs. Variant
- **Control (A):** Current RouteLogic Velocity compliance workflow: Coordinators manually enter and verify compliance information through the existing multi-step process. The workflow currently takes 14.6 minutes on average versus a 3-minute benchmark.
- **Variant (B):** One-Click Compliance Checklist, using the exact three-screen flow from the M4 PRD:

Entry Point: Compliance Queue
 Coordinator sees today’s routes, compliance status, and a clear “Complete Checklist” action for items requiring attention.

Feature Core: One-Click Compliance Checklist
 Pre-filled driver/route data, required checks, editable fields, validation flags, and one clear “Review & Submit” action.

Success / Confirmation: Compliance Complete
 Show “Checklist Submitted,” completion status, timestamp, submitter, and a “Return to Fleet View” action.
- **Held constant (isolation check):** Isolation check: Everything except the compliance checklist experience remains identical between Control A and Variant B.

Same RouteLogic Velocity app version and navigation
Same Frontline Dispatcher / Logistics Coordinator population
Same 3 pilot accounts
Same driver, route, vehicle, and fleet data
Same compliance requirements and validation rules
Same route optimizer and dispatch functionality
Same driver notifications and route-change behavior
Same reporting and manager experience
Same onboarding and training
Same user permissions
Same experiment period and measurement methodology

Only change: Variant B replaces the existing manual compliance checklist with the One-Click Compliance

## Hypothesis
> I believe that One-Click Compliance Checklist for Frontline Dispatcher / Logistics Coordinator who coordinates daily deliveries, manages route changes, monitors driver progress, and completes required compliance workflows. will result in Expected outcome: Frontline coordinators complete compliance work faster and within RouteLogic Velocity, reducing manual effort and reliance on workarounds while maintaining compliance accuracy and completeness., as measured by a 20%reduction change in Target: ~20% reduction, from 31 minutes to ≤25 minutes per coordinator per day. within 4 weeks. We will protect Manager Reporting CSAT must remain at or above 4.5/5. throughout the test.

## Shipping criteria
> We will **ship** if Target: ~20% reduction, from 31 minutes to ≤25 minutes per coordinator per day. improves by ≥ 20%reduction at p<0.05 and Manager Reporting CSAT must remain at or above 4.5/5. does not reach If CSAT falls below 4.5/5 during the experiment, investigate before scaling to ensure the compliance simplification is not degrading the reporting experience. after 4 weeks.
> We will **iterate** if direction is positive but lift is below the MDE.
> We will **kill** if the primary metric shows no improvement or moves negatively.
> The read date is fixed at the end of 4 weeks, no results reviewed before this date.
