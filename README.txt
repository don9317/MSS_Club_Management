MSS Club Management Suite Demo v0.57 — Team-Driven Payment Plans

PAYMENT PLAN WORKFLOW
- Payment Plans no longer creates or re-enters teams.
- Team selector is populated only from actual teams created in Team Setup.
- Team selector displays grade + team name (for example 3rd Gold), avoiding ambiguity between Gold teams in different grades.
- Season cost, season start, season end, coach and team status are inherited automatically from Team Setup.
- Season cost and dates are read-only on Payment Plans.
- Edit Team Setup takes the administrator back to the source team record.

PAYMENT OPTIONS
- Administrator selects which parent options are allowed for each team:
  Pay in Full, Fixed Installments, Monthly.
- Billing day and all existing payment-plan rules remain editable.
- Settings are stored by unique Team ID, so 3rd Gold and 5th Gold can have different plans.

PARENT WORKFLOW
- Parent Portal now resolves payment plans using the player's actual grade/team record.
- Parent plan selection and financial fallback calculations use the same team-specific settings.

Existing v0.56 browser data migrates automatically; legacy team-name payment settings are copied forward when an actual team first loads.
