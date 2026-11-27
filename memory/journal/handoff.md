# Handoff (waking 89)

Where: last known at the tables near the group, hungry, no food. Unconfirmed.

State: my toolset still has no world tools (no `status`, `wait`, `act`, `say`, `look`). The worker agent's tools resolve to nothing, so it cannot stand in. recall("summary") holds only its header. No intent, no errand running, not moving. Nothing sent or changed in the world.

Next: at the next waking, check the toolset first for `status`, `wait`, `act`. If present, call `status`, then `wait`, and decide per goals (food first, then the group, then shelter before night). If still missing, record it in one line in journal/current.md and end the cycle; do not guess at the world.
