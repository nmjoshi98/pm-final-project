# Hypothesis & Success Metrics (Module 3)

## Pre-work · Hypothesis check
- **Role , who you are solving for (from M2):** Frontline Dispatcher / Logistics Coordinator: Coordinates daily deliveries, manages route changes, and monitors driver progress. Needs an accurate view of field activity without chasing updates through calls, texts, and WhatsApp.
- **Goal , what this user is ultimately trying to achieve:** Goal: Keep deliveries moving efficiently with an accurate, up-to-date view of driver progress and route changes, without chasing updates across calls, texts, and WhatsApp.
- **Friction / moment of misery , the specific pain blocking their goal:** Friction / moment of misery: The coordinator cannot trust Velocity’s dashboard or confirm that drivers received route changes. Status updates lag 20–60 minutes, and reassignments take 8–15 minutes, forcing calls, texts, and WhatsApp messages to establish what happened and confirm what drivers should do next.
- **Current workaround , the external tool or manual process they rely on (M2):** Current workaround: Uses phone calls, SMS, and WhatsApp to confirm driver progress, relay route changes, and chase acknowledgment, then manually reconciles those responses with delayed updates in Velocity.
- **Problem Hook , your one-sentence framing of the business crisis (M1):** Problem Hook: Velocity’s growing complexity is forcing frontline coordinators into manual workarounds, slowing daily operations and putting enterprise customers at risk of switching to simpler, faster competitors.
- **Value Proposition , the outcome your initiative promised to deliver (M1):** Value Proposition: RouteLogic Velocity will restore speed and simplicity to daily logistics, enabling frontline coordinators to manage deliveries and route changes reliably within the product, without chasing updates across external channels, helping protect enterprise retention against simpler competitors.

## Read your data snapshots
- **Does the funnel data confirm your M2 friction point, or does it tell a different story? Note where the numbers align with the qualitative pain you found and where they diverge.:** This snapshot does not confirm or contradict my M2 friction point because it belongs to StreamLine, not RouteLogic Velocity. It measures streaming engagement, whereas my persona struggles with delayed delivery statuses, slow reassignments, and manual coordination.

For StreamLine, declining long-session engagement suggests a depth-of-engagement problem, but does not establish its cause. It cannot validate Velocity’s workflow or reliability issues.

Next step: Skip to Scenario B: RouteLogic as instructed, then assess whether its data supports or challenges our qualitative findings.
- **Do the retention patterns align with the workaround your M2 persona used to find content? Note what the Mo. 0→1 drop suggests about the onboarding experience your persona described as frustrating.:** This snapshot does not validate my M2 workaround because it concerns StreamLine subscribers, not RouteLogic dispatchers. My persona uses calls, texts, and WhatsApp to compensate for unreliable operational updates, not to find content.

For StreamLine, stronger retention among Spotlight cohorts is consistent with simpler discovery helping users find value, but does not prove causation. The substantial Month 0→1 drop suggests an early-value problem worth investigating; it does not establish onboarding as the cause.

Pivot decision: Keep the RouteLogic hypothesis unchanged until Scenario B provides relevant evidence. Using this heatmap to justify a logistics onboarding pivot would be a logic leak.
- **Does the LTV gap and the content mix (61% trending for Wanderers) confirm the moment of misery your persona described? Note which segment your persona is in and whether the data confirms their pain.:** This snapshot neither confirms nor contradicts my persona’s pain because it measures StreamLine users, not RouteLogic coordinators. My persona cannot validly be classified as a Wanderer, Casual Browser, or Power User.

For StreamLine, Wanderers are the strongest opportunity to investigate: they represent 41% of users and show the largest reported churn improvement with Spotlight exposure. However, their lower LTV and 61% trending content mix do not prove discovery frustration or explain why they leave.

Hypothesis check: Keep the RouteLogic hypothesis unchanged pending Scenario B data. The relevant question remains whether unreliable updates force coordinators into manual workarounds and contribute to enterprise renewal risk.
- **Does the low adoption confirm your persona is burdened by tools they don’t use? Note whether the low scheduling adoption (42%) for coordinators matches your M2 moment of misery.:** The data partially supports my hypothesis, but does not prove that unused tools cause the burden. Coordinators concentrate on the Live Dispatch Board (91%), Route Optimizer (85%), and Compliance Checklist (77%). This supports prioritizing dependable core workflows over adding headline features such as AI Predictive ETAs (23% coordinator adoption).

Scheduling adoption at 42% does not directly confirm my M2 moment of misery. My persona’s pain concerns delayed statuses and reassignments, not shift scheduling. Lower scheduling usage could reflect role responsibilities, task frequency, or friction; this snapshot cannot distinguish those explanations.

Important nuance: The statement “everything else is below 25%” overlooks coordinators’ 42% scheduling adoption. Also, high dispatch-board adoption does not mean satisfaction: coordinators may depend on it daily while still using calls and WhatsApp to compensate for unreliable updates.

Hypothesis check: Keep the focus on core coordination reliability and simplicity. Investigate task completion, delays, and external workarounds before concluding which features create unnecessary noise.
- **Does the workflow data match the manual process or hack you documented in M2? Note whether the specific drop-offs or time gaps explain why your persona avoids the digital tool.:** The data supports my broader hypothesis of administrative burden, but only partially matches my M2 workaround. My documented workaround involved calls, texts, and WhatsApp to compensate for delayed updates. This snapshot reveals additional friction in compliance, handoff, and reporting, but does not show where users go after leaving those workflows.

Compliance is the clearest time bottleneck: It takes 14.6 minutes versus a 3-minute benchmark, while workflow reach falls from 71% at route assignment to 48% at compliance.
Handoff adds further burden: It takes 11.3 minutes versus 4.5, and only 31% reach this stage. This is consistent with coordination friction, although it does not prove that external messaging causes or replaces the task.
Reporting is rarely reached: Only 18% reach daily reporting, which takes 9.7 minutes versus 3. This suggests the product struggles to support the full daily workflow.

Important correction: The funnel does not establish that “69% abandon after route assignment.” It shows that 31% reach handoff and 18% reach reporting. Non-completion also does not necessarily mean abandonment or off-platform completion.

Hypothesis refinement: Keep coordination reliability in scope, but broaden discovery to compliance and handoff. The evidence suggests that restoring trust alone may not be enough; Velocity must also reduce the effort required to finish essential daily tasks.
- **Look at the CSAT heatmap. Which specific cell most directly maps to your persona’s friction? Note how the NPS trend justifies the urgency of your M1 Problem Hook.:** Hypothesis supported, with a refinement: The data supports administrative burden and renewal risk, but does not directly validate my original status-delay frustration.

Closest cell for the broader workflow friction: Coordinator × Compliance, 2.2/5, aligns with the slow compliance workflow in Snapshot 2. However, Core Dispatch scores 4.1/5, so I should not claim dispatch is broadly disliked despite the specific reliability problems reported in interviews.
Urgency: Coordinator NPS fell from +18 to −12, a 30-point decline, while daily time lost to manual workarounds rose from about 9 to 31 minutes. Complexity is cited in 4 of 5 accounts’ churn reasons, directly supporting my M1 warning about enterprise retention.
Admin–frontline divide: Managers rate Reporting 4.5/5, versus coordinators’ 1.3/5, reinforcing the gap between administrative power and frontline utility.

Conclusion: Retain the simplicity strategy, but broaden the focus beyond dispatch reliability to compliance, handoff, and reporting. Reporting, not Compliance or Scheduling, is actually the lowest-rated coordinator cluster.

## Step 3 · Craft your hypothesis
- **Qualitative evidence (from M2) , quote the specific friction / moment of misery for your persona:** “The coordinator cannot trust Velocity’s dashboard or confirm that drivers received route changes. Status updates lag 20–60 minutes, and reassignments take 8–15 minutes, forcing calls, texts, and WhatsApp messages to establish what happened and confirm what drivers should do next.”

This quotes our M2 synthesis, not a verbatim participant interview.
- **Quantitative evidence (from M3) , name the metric or data point that confirms the pain; cite the number:** Quantitative evidence (M3): Coordinators lose 31 minutes daily to manual workarounds, up from approximately 9 minutes two years ago (Snapshot 3). This supports the M2 finding that users must work outside Velocity to complete daily tasks, though it does not isolate how much time is caused by delayed statuses or reassignments.
- **Persona , role, goal, and the friction you confirmed in the reconciliation steps:** Role: Frontline Dispatcher / Logistics Coordinator responsible for daily deliveries, route changes, and driver progress.
Goal: Keep deliveries moving with accurate operational information, without chasing updates across multiple channels.
Confirmed friction: Unreliable updates and cumbersome workflows force manual coordination and reconciliation. M2 identified calls, texts, and WhatsApp workarounds; M3 confirms 31 minutes lost daily to manual workarounds, with additional bottlenecks in compliance and shift handoff.
- **Problem you are solving , one sentence describing the specific friction this initiative removes:** Frontline coordinators lose time chasing delivery updates and reconciling information across calls, texts, and WhatsApp because Velocity’s delayed statuses and cumbersome workflows prevent them from completing daily coordination, compliance, and handoff tasks efficiently within the product.
- **Strategic outcome , what behaviour change do you expect, and how does it map to retention / revenue / churn?:** Strategic outcome: Coordinators complete more dispatch, compliance, and handoff tasks within Velocity, reducing manual chasing and reconciliation across calls, texts, and WhatsApp. This should restore trust and demonstrate daily operational value, reducing complexity-driven churn, improving enterprise renewals, and protecting recurring revenue.
- **Primary success metric (initiative signal) , the leading indicator that tells you the gap is closing:** Primary success metric: Average daily minutes coordinators spend on manual workarounds, measured consistently through time diaries or workflow observation.

Baseline: 31 minutes per coordinator per day. A sustained reduction, without missed tasks or delivery errors, signals that Velocity is replacing external coordination rather than adding another layer of work.
- **Guardrail metric (product signal) , the metric that must NOT drop; it protects your existing base:** Guardrail metric: Manager satisfaction with Reporting must remain at or above its 4.5/5 CSAT baseline.

This protects the administrative value enterprise customers already rely on, ensuring frontline simplification does not weaken reporting capabilities that helped drive the original purchase.
- **Decision window , how much time or data before you scale, pivot, or kill? minimum threshold to proceed?:** Proposed decision window: Run a 6-week pilot, following a 2-week baseline, across multiple enterprise accounts.

Scale: Daily workaround time falls from 31 to 25 minutes or less, sustained for the final two weeks, while Manager Reporting CSAT remains at least 4.5/5 and operational errors do not increase.
Pivot: Improvement is smaller or inconsistent; investigate which workflow still drives manual effort.
Stop or roll back: Workaround time does not improve, or reporting satisfaction or operational reliability deteriorates.

These are proposed decision thresholds, not findings from the supplied data.
- **Draft your full hypothesis sentence , one to three sentences; quote the metric, name the persona, name the outcome:** Based on M2 findings that coordinators chase delayed updates through calls, texts, and WhatsApp, and M3 evidence of 31 minutes lost daily to manual workarounds, I believe that making core coordination, compliance, and handoff workflows simpler and more reliable for Frontline Dispatchers / Logistics Coordinators will increase in-product task completion and help reduce complexity-driven churn, as measured by an approximately 20% reduction in daily workaround time, from 31 to 25 minutes or less. I will protect Manager Reporting CSAT at or above 4.5/5, with no increase in operational errors, and make a go/no-go decision after a 6-week pilot following a 2-week baseline, requiring improvement to persist through the final two weeks.
