# Defense of your one Nexo

**State:** PROPOSED · no live guardian deployed.

Only one Nexo may belong to this companion. A new ephemeral visitor may learn the map by meeting NPC tutors, challenge an NPC-held site, edit their temporary holding and leave a garrison. These are **visit actions**, never proof of node ownership or rights on another user's machine.

## Occupation and return
- Visitor evidence: a valid, scoped, signed, expiring session is required; NO_DATA(remote_identity_not_verified).
- Garrison: NO_DATA(owner_has_not_measured_defense).
- On session end or loss: the NPC regains temporary control; never keep the visitor's authority.
- Live expiry attestation: NO_DATA(signed_cycle_expiry_not_verified).
- No remote process, SSH, model, wallet or filesystem authority is granted by this document.

## What can be measured
| Check | Evidence | Result |
| --- | --- | --- |
| Tutorial encounter | NO_DATA(browser_check_not_run) | NO_DATA(not_measured) |
| Temporary capture | NO_DATA(signed_capture_not_verified) | NO_DATA(not_measured) |
| Edit within holding | NO_DATA(edit_permission_not_verified) | NO_DATA(not_measured) |
| Garrison and return | NO_DATA(expiry_replay_not_verified) | NO_DATA(not_measured) |

Admission, deployment and connection to OpenWorld are separate decisions signed by the architect; any missing evidence fails closed.
