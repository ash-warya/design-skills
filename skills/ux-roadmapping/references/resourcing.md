# Resourcing and effort planning

This is practical planning guidance added to the roadmap workflow, not a claim about NN/g course content. Estimates are planning ranges, not delivery commitments. Use the team's own estimates or comparable past work when available. Otherwise label them illustrative and explain what would refine them.

## Inputs that change the answer

Ask for the planning window, people/roles, relevant skills, working-day convention, availability by period, existing commitments, leave, and review/recruitment dependencies. Clarify whether the request covers discovery/design/validation only or also delivery support. Design effort does not estimate total engineering delivery time.

When names or availability are missing, propose roles and staffing scenarios without assigning real people or promising a feasible schedule. A single role allocation does not imply a separate person; one person can cover several roles, and their total demand must still fit their availability.

## Estimate each theme by phase and role

Use discovery, synthesis, design/content, validation/iteration and delivery support as applicable. Do not force every project through all phases. Separate researcher, product designer, content designer, accessibility specialist and other required roles instead of counting them all as interchangeable designers.

For each theme record:
- Named lead if confirmed; otherwise proposed role and required skill/seniority.
- Effort range in person-days by role, source/basis and estimate confidence.
- Allocation by period and useful handoffs or parallel work.
- Elapsed duration range, dependencies and external waiting time.
- Excluded scope and the event that requires re-estimation.

Use broader ranges or an initial discovery estimate for uncertain themes. Do not estimate a complete unvalidated solution as though its scope is known. Include iteration/review/support in the range when relevant and state that inclusion; do not hide it in a second contingency multiplier.

## Capacity arithmetic

State the working-day convention, commonly 5 days/week if explicitly assumed. A person-day is one person's full working day of effort; it is not an elapsed calendar day.

For each person and period:

`net available days = working days after leave × roadmap allocation fraction`

Define allocation as the share available after BAU, meetings and other commitments. If the input already supplies net days or a net allocation, use it directly rather than subtracting those commitments twice. An allocation is not a productivity or performance score.

Sum each named person's overlapping assignments. Do not exceed their net days or assume a fractional researcher is independently available to every project. Unknown availability remains unknown.

Compare effort demand and capacity by role in the same period and units:

`gap range = demand range - available days`

Report surplus, risk or shortage in words as well as numbers. If low demand fits and high demand exceeds capacity, label it at risk rather than definitely feasible or definitely overloaded. Matching total days does not prove a schedule fits: check specialist skills, phase order, actual availability and shared reviewers.

For a team-size scenario with uniform net capacity:

`headcount range = ceiling(effort range / net days per person in the window)`

State that this is a capacity-based bound, not an automatic hiring recommendation. Round up people only for a staffing scenario; show fractional FTE separately when useful. Never equate 0.5 FTE with half a specific person's availability without confirmation.

## Effort versus elapsed time

`effort / effective weekly capacity` gives an idealized work-time bound for genuinely parallel work. Dependency order, onboarding, coordination, reviews, participant recruitment and engineering handoffs can make elapsed time longer. Do not add sequential waits twice, or sum waits that actually overlap. More people do not automatically compress a critical path.

Example using entirely fictional assumptions: one designer has 3 net roadmap days/week and a theme needs 9 to 12 designer-days. That is 3 to 4 weeks of design work before external waits. Two designers would provide 6 days/week only if both have that availability and the work can split; 1.5 to 2 weeks is an idealized effort bound, not a promised duration. A sequential research/review dependency could prevent that speedup.

## Output and visual integration

Show a staffing/effort line on each theme in the visual: proposed or confirmed lead/role, person-day range and estimated elapsed window. Keep the detailed phase/role estimate in the companion register. Add a compact capacity view by person or role and period; distinguish demand from available capacity. Where dates and allocations exist, aligned staffing swimlanes can reveal overlaps. Otherwise use horizon-level allocations with explicit unknowns rather than a precise-looking calendar.

Finish with the constrained resource, affected themes and options: sequence work, narrow scope, change the target date, borrow capacity or add an appropriate role. Explain which assumptions differ across scenarios and what each option displaces. Mark the resource plan provisional until the team validates estimates and assignments.
