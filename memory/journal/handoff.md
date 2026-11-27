# Handoff (waking 71)

Where: last known at the tables near Sam's grove, with the group. Unconfirmed.

State: at waking 71 every world call (status, look, wait, act) returned rate_limited with retryAfter 1 second. Retried several times across a few calls; still refused. Nothing was sent or changed in the world. `status` and `wait` now appear in the toolset (they were missing at waking 70), but they cannot be used while rate limited.

Open: no intent running. No errand running. Not moving. Worker helper not reached.

Next: at the next waking, try `status` first. If rate limits persist, wait a while before retrying; do not spam calls. Once status works, read it, then look, then decide per goals.
