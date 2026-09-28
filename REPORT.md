# Application map: https://10.134.60.169.nip.io/code

Status: **partial**

6 states; 42 attempted transitions; 0 pending actions.

Coverage is relative to discovered controls and configured limits, not a claim of exhaustive application coverage.

## Outcomes

- changed: 12
- no_change: 5
- replay_failed: 11
- policy_blocked: 12
- action_failed: 2

## Blockers

- code: budget_exhausted — State limit for https://10.134.60.169.nip.io/code/
- code: budget_exhausted — State limit for https://10.134.60.169.nip.io/code/devcontainerpage?devcontainer=Python&ref=main&teamspace=Team1
- code: budget_exhausted — State limit for https://10.134.60.169.nip.io/code/
- code: budget_exhausted — State limit for https://10.134.60.169.nip.io/code/
- code: budget_exhausted — State limit for https://10.134.60.169.nip.io/code/
- code: budget_exhausted — State limit for https://10.134.60.169.nip.io/code/

## States

- Code - DevOps Loop (code): https://10.134.60.169.nip.io/code/ — state 1a33b7fc2e5f8ab183a37af5 — The UI includes buttons for logo and navigation, a combobox for selecting container types, and tabs for viewing different categories of dev containers.
- Code - DevOps Loop (code): https://10.134.60.169.nip.io/code/ — state c2bf552ddbc2ca1f0320ca0e — The UI includes buttons for logo and sidebar expansion, a menu item for the DevOps Code home page, a combobox for branch selection, and tabs for managing running and other dev containers.
- Code - DevOps Loop (code): https://10.134.60.169.nip.io/code/ — state f5e619376fc7bde7f1943db7 — The UI includes buttons for navigation and actions such as expanding the sidebar, launching various development environments, and accessing the DevOps Code home page. It features a combobox for selecting branches and tabs for managing different dev containers.
- Code - DevOps Loop (code): https://10.134.60.169.nip.io/code/devcontainerpage?devcontainer=Data+Science+%26+ML&ref=main&teamspace=Team1 — state 575e07074259b262358a7a31 — The UI includes a logo button, a menu item for the DevOps Code home page, and a button for accessing the Dev Container related to Data Science and Machine Learning.
- Code - DevOps Loop (code): https://10.134.60.169.nip.io/code/devcontainerpage?devcontainer=Go&ref=main&teamspace=Team1 — state 4f6c661ac6466cabe1fdf424 — The UI includes a logo button, a menu item for the DevOps Code home page, and a button for the Dev Container related to Go.
- Code - DevOps Loop (code): https://10.134.60.169.nip.io/code/devcontainerpage?devcontainer=Cpp&ref=main&teamspace=Team1 — state 38c905d19117ceb4630c42a1 — The UI includes a logo button, a menu item for the DevOps Code home page, and a button for the Dev Container related to C++. These elements suggest navigation and interaction capabilities within the DevOps Loop interface.

## Files

- crawl_state.json: versioned observations, transitions, replay frontier, and blockers.
- SystemModel/: validated component files and model identifier.
- model-evidence.json: component mapping and observed request evidence.
- smartshots/: SmartShot pairs per discovered page state (<stateId>.dti.jpeg + <stateId>.dti.json).
