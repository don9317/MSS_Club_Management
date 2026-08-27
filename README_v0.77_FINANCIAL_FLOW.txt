MSS Club Management v0.77 — Team-Specific Financial Flow

CORE MODEL
- Team Type (Black, White, Academy, etc.) is a category/template only.
- The actual saved team is the financial entity and source of truth.
- Each actual team has its own budget, donations, approved season cost, payment plans, and offer readiness.

TEAM ACCOUNTING
- Actual teams populate the Team Accounting selector.
- Build projected expenses for that specific team.
- Donations reduce net amount to recover.
- Calculated Cost / Player = net budget divided by minimum paid players.
- "Use Calculated Cost" places the calculated value into the proposed charge.
- "Approve Season Cost" makes that fee authoritative for the team.
- Changing/approving Season Cost clears old generated payment plans so they must be regenerated for the new cost.

PAYMENT PLANS
- Season Cost is inherited from Team Accounting and is read-only.
- Payment plans cannot be saved until Season Cost has been approved.
- At least one payment choice must be saved.

OFFER READINESS GATE
Offers cannot be created/sent until the actual team has:
- Coach
- Season dates
- Team budget
- Approved Season Cost > $0
- At least one saved Payment Plan
Blocked offers explain what is missing.

TEAM WORKSPACE
- Adds Financial Setup Flow: Team Accounting → Approve Season Cost → Payment Plans → Offers Ready.

Existing v0.76 browser data migrates forward.
