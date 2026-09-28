# Application map: https://10.134.60.169.nip.io/code

Status: **partial**

2 states; 8 attempted transitions; 0 pending actions.

Coverage is relative to discovered controls and configured limits, not a claim of exhaustive application coverage.

## Outcomes

- policy_blocked: 2
- no_change: 1
- replay_failed: 5

## Blockers


## States

- Sign in to devops-automation (anonymous): https://10.134.60.169.nip.io/auth/realms/devops-automation/protocol/openid-connect/auth?client_id=devopsautomation&code_challenge=REDACTED&code_challenge_method=REDACTED&redirect_uri=https%3A%2F%2F10.134.60.169.nip.io%2Fautomation%2Fembed%3Fpath%3D%252Fcode%252F&response_type=code&scope=openid+profile+email+mcp%3Aloop%3Aall+mcp%3Acontrol%3Aall+api%3Asuite%3Aall+api%3Aloop%3Aall+api%3Atenant%3Aall+mcp%3Aplan%3Aall+api%3Aplan%3Aall+api%3Acontrol%3Aall+mcp%3Avelocity%3Aall+api%3Avelocity%3Aall+mcp%3Adeploy%3Aall+api%3Adeploy%3Aall+mcp%3Atest%3Aall+api%3Atest%3Aall+mcp%3Abuild%3Aall+api%3Abuild%3Aall+api%3Acode%3Aall&state=dab136a26ad340f8a1ec3889af9a3cbb — state 76e21df6c85ec06f307462f0 — The UI includes fields for entering a username and password, a button to show the password, and a 'Sign In' button.
- Code - DevOps Loop (code): https://10.134.60.169.nip.io/code/ — state bc05e9aa1d051a28c2cf540e — The UI includes buttons for logo and sidebar expansion, menu items for navigation, and tabs for switching between 'Running Dev Containers' and 'Other Dev Containers'.

## Files

- crawl_state.json: versioned observations, transitions, replay frontier, and blockers.
- SystemModel/: validated component files and model identifier.
- model-evidence.json: component mapping and observed request evidence.
- smartshots/: SmartShot pairs per discovered page state (<stateId>.dti.jpeg + <stateId>.dti.json).
