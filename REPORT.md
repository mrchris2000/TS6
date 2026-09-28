# Application map: https://10.134.60.169.nip.io/code

Status: **partial**

9 states; 100 attempted transitions; 0 pending actions.

Coverage is relative to discovered controls and configured limits, not a claim of exhaustive application coverage.

## Outcomes

- policy_blocked: 4
- no_change: 3
- changed: 26
- action_failed: 40
- replay_failed: 26
- scope_blocked: 1

## Blockers

- code: budget_exhausted — State limit for https://10.134.60.169.nip.io/code/
- code: budget_exhausted — State limit for https://10.134.60.169.nip.io/code/
- code: budget_exhausted — State limit for https://10.134.60.169.nip.io/code/
- code: budget_exhausted — State limit for https://10.134.60.169.nip.io/code/
- code: budget_exhausted — State limit for https://10.134.60.169.nip.io/code/
- code: budget_exhausted — State limit for https://10.134.60.169.nip.io/code/

## States

- Sign in to devops-automation (anonymous): https://10.134.60.169.nip.io/auth/realms/devops-automation/protocol/openid-connect/auth?client_id=devopsautomation&code_challenge=REDACTED&code_challenge_method=REDACTED&redirect_uri=https%3A%2F%2F10.134.60.169.nip.io%2Fautomation%2Fembed%3Fpath%3D%252Fcode%252F&response_type=code&scope=openid+profile+email+mcp%3Aloop%3Aall+mcp%3Acontrol%3Aall+api%3Asuite%3Aall+api%3Aloop%3Aall+api%3Atenant%3Aall+mcp%3Aplan%3Aall+api%3Aplan%3Aall+api%3Acontrol%3Aall+mcp%3Avelocity%3Aall+api%3Avelocity%3Aall+mcp%3Adeploy%3Aall+api%3Adeploy%3Aall+mcp%3Atest%3Aall+api%3Atest%3Aall+mcp%3Abuild%3Aall+api%3Abuild%3Aall+api%3Acode%3Aall&state=REDACTED — state 08bbf2c1f516bea3ee61587e — The UI includes fields for entering a username and password, a button to show the password, and a 'Sign In' button.
- Code - DevOps Loop (code): https://10.134.60.169.nip.io/code/ — state 1a33b7fc2e5f8ab183a37af5 — The UI includes buttons for navigation and actions, such as a logo button, a home page menu item, and a button to expand the sidebar. There is a combobox for selecting container types and tabs for viewing different categories of dev containers.
- Code - DevOps Loop (code): https://10.134.60.169.nip.io/code/ — state c2bf552ddbc2ca1f0320ca0e — The UI includes buttons for logo and sidebar expansion, a menu item for the DevOps Code home page, a combobox for branch selection, and tabs for managing running and other dev containers.
- Code - DevOps Loop (code): https://10.134.60.169.nip.io/code/ — state eeaa1423f537f2712da6e242 — The UI includes buttons for logo and navigation, a combobox for branch selection, and tabs for managing dev containers.
- Code - DevOps Loop (code): https://10.134.60.169.nip.io/code/ — state fc859a205f27a7bf3974a003 — The UI includes various menu items for different stages of the DevOps loop such as Plan, Code, Test, Model, Build, Release, Control, Deploy, and Measure. There are buttons for logo, team selection, and sidebar expansion. Tabs are available for 'Running Dev Containers' and 'Other Dev Containers'. Multiple 'Launch' links are present for initiating different development environments. A combobox is available for selecting the main branch.
- Code - DevOps Loop (code): https://10.134.60.169.nip.io/code/ — state 429bd278462aa64755d5f871 — The UI includes buttons for navigation and actions such as launching dev containers, expanding the sidebar, and accessing the home page. It features a combobox for selecting branches and tabs for different categories of dev containers. The layout is designed for easy access to various development environments and tools.
- Code - DevOps Loop (code): https://10.134.60.169.nip.io/code/ — state b85cb7577b3ea70eaa8a6adc — The UI includes buttons for navigation and actions, such as a logo, a home page link, a team selection button, and a sidebar collapse option. There are also comboboxes for branch selection and tabs for viewing different categories of dev containers.
- Code - DevOps Loop (code): https://10.134.60.169.nip.io/code/ — state f417f0dbe318281752262b6a — The UI includes buttons for navigation and actions, a menu item for the home page, a combobox for branch selection, and tabs for managing dev containers.
- Code - DevOps Loop (code): https://10.134.60.169.nip.io/code/ — state d5b3977585aab791e3cdeec6 — The UI includes a navigation menu with items for various stages of the DevOps process such as Plan, Code, Test, Model, Build, Release, Control, Deploy, and Measure. There are buttons for team selection and sidebar management, as well as a combobox for branch selection. Additionally, there are tabs for viewing running and other dev containers.

## Files

- crawl_state.json: versioned observations, transitions, replay frontier, and blockers.
- SystemModel/: validated component files and model identifier.
- model-evidence.json: component mapping and observed request evidence.
- smartshots/: SmartShot pairs per discovered page state (<stateId>.dti.jpeg + <stateId>.dti.json).
