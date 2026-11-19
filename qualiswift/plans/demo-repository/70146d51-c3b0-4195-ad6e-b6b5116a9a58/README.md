Qualiswift approved plan: GitHubPlan
Version 2 · SHA-256 a1579aa44acaef32e83dc2eb5b726b5c74eef26fa7c80c5203bcea5445ce0bd9
1. Navigate to Project Settings
Case ID: TC-001
Story IDs: R001
Preconditions: User is logged in with access to Project Settings.
1. Login to the application.
2. Open the main navigation menu.
3. Click on 'Settings'.
4. Select 'Project Settings' from the submenu.
Step Expected: User should successfully reach the Project Settings page.
Expected: User should successfully reach the Project Settings page.
2. Verify Action Dropdown Options
Case ID: TC-002
Story IDs: R002
Preconditions: User is on the Project Settings page.
1. Navigate to the Project Settings page.
2. Locate and click the 'Action' dropdown.
Step Expected: The Action dropdown should contain options: 'Create Project', 'Rename Project'.
Expected: The Action dropdown should contain options: 'Create Project', 'Rename Project'.
3. Select Create Project Action
Case ID: TC-003
Story IDs: R003
Preconditions: Action dropdown options are present.
1. On the Project Settings page, open the Action dropdown.
2. Select the 'Create Project' option.
Step Expected: 'Create Project' option should be selectable and selected.
Expected: 'Create Project' option should be selectable and selected.
4. Check Workspace Dropdown Presence and Options
Case ID: TC-004
Story IDs: R004
Preconditions: User has opened 'Create Project' in Project Settings.
1. In 'Create Project' mode on Project Settings, locate the Workspace dropdown.
2. Click the Workspace dropdown to view options.
Step Expected: Workspace dropdown should be present and display correct available workspace options.
Expected: Workspace dropdown should be present and display correct available workspace options.
5. Select Required Workspace
Case ID: TC-005
Story IDs: R005
Preconditions: Workspace dropdown is visible with options.
1. In Workspace dropdown, select 'Workspace_A'.
Step Expected: The selected workspace 'Workspace_A' should be accepted and shown as chosen.
Test Data: Workspace_A
Expected: The selected workspace 'Workspace_A' should be accepted and shown as chosen.
6. Check Project Name Input Field Presence
Case ID: TC-006
Story IDs: R006
Preconditions: User is in Create Project mode with workspace selected.
1. Locate the Project Name input field in the Create Project form.
Step Expected: Project Name input field should be present and enabled for text entry.
Expected: Project Name input field should be present and enabled for text entry.
7. Enter Valid Project Name
Case ID: TC-007
Story IDs: R007
Preconditions: Project Name input field is visible and enabled.
1. Enter 'NewProject_02112026' into the Project Name input field.
Step Expected: Project Name input field should accept and display 'NewProject_02112026'.
Test Data: NewProject_02112026
Expected: Project Name input field should accept and display 'NewProject_02112026'.
8. Save Project After Providing Details
Case ID: TC-008
Story IDs: R008
Preconditions: Project name and workspace are filled in Create Project form.
1. After selecting 'Workspace_A' and entering 'NewProject_02112026' as project name, click the Save button.
Step Expected: System should accept the data and process saving the new project.
Test Data: Workspace_A, NewProject_02112026
Expected: System should accept the data and process saving the new project.
9. Verify Success Message After Project Creation
Case ID: TC-009
Story IDs: R009
Preconditions: Project creation request was submitted.
1. After saving a new project, observe for feedback messages.
Step Expected: A success message should be displayed confirming project creation.
Expected: A success message should be displayed confirming project creation.
10. Verify New Project Present in Selected Workspace
Case ID: TC-010
Story IDs: R010
Preconditions: Project was successfully created.
1. Navigate to the workspace 'Workspace_A' project list.
2. Look for project named 'NewProject_02112026'.
Step Expected: The newly created project 'NewProject_02112026' should appear under the selected workspace.
Test Data: NewProject_02112026
Expected: The newly created project 'NewProject_02112026' should appear under the selected workspace.
11. Attempt Save Project With Empty Project Name
Case ID: TC-011
Story IDs: R008
Preconditions: User is in Create Project form.
1. Select 'Create Project' action.
2. Select workspace 'Workspace_A'.
3. Leave Project Name input field empty.
4. Click Save.
Step Expected: System should prevent saving and display a validation error for empty project name.
Test Data: Workspace_A, ""
Expected: System should prevent saving and display a validation error for empty project name.
12. Verify Action Dropdown Contains Only Specified Options
Case ID: TC-012
Story IDs: R002
Preconditions: User is on Project Settings page.
1. Open Action dropdown in Project Settings.
Step Expected: Dropdown options should be exactly 'Create Project' and 'Rename Project', no additional options.
Expected: Dropdown options should be exactly 'Create Project' and 'Rename Project', no additional options.
13. Attempt Entering Invalid Project Name Characters
Case ID: TC-013
Story IDs: R007, R008
Preconditions: User is in Create Project form.
1. Select 'Create Project' action.
2. Select workspace 'Workspace_A'.
3. Enter invalid characters (e.g., '!@#$%') into Project Name input field.
4. Attempt to save project.
Step Expected: System should reject invalid characters and display an appropriate validation error.
Test Data: !@#$%
Expected: System should reject invalid characters and display an appropriate validation error.
14. Verify Workspace Dropdown Disabled When No Workspaces Available
Case ID: TC-014
Story IDs: R004
Preconditions: User has no workspaces assigned.
1. Go to Create Project form when user has no workspaces.
2. Check if Workspace dropdown is disabled or shows no options.
Step Expected: Workspace dropdown should be disabled or indicate no available workspaces.
Expected: Workspace dropdown should be disabled or indicate no available workspaces.
15. Rename Project Option Selectability
Case ID: TC-015
Story IDs: R003
Preconditions: Action dropdown is present.
1. Open Action dropdown.
2. Select 'Rename Project'.
Step Expected: 'Rename Project' option should be selectable and selected without error.
Expected: 'Rename Project' option should be selectable and selected without error.
16. Verify Project Name Input Field Max Length
Case ID: TC-016
Story IDs: R006, R008
Preconditions: User is in Create Project form.
1. Attempt to enter a project name exceeding maximum length (e.g., 256 characters).
Step Expected: Input should restrict entry to maximum allowed length or display validation error on save.
Test Data: A string of 256 'a' characters
Expected: Input should restrict entry to maximum allowed length or display validation error on save.
