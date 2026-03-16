## Chrome Remote Desktop Installation Instruction

Use this instruction when the task is to install Chrome Remote Desktop on the machine.

Configuration communication rule:
- Treat this file as the single source of truth for this task's configuration communication.
- For configuration-related updates, questions, assumptions, status notes, and final reporting, reference only this path:
  `instructions/chrom-remote-desktop/install-chrome-remote-desktop.md`
- Do not ask the user to look elsewhere for configuration guidance unless this file explicitly requires a manual step.

Task:

Install Chrome Remote Desktop on this machine.

Requirements:
- Detect the OS first and follow the correct installation path for that OS.
- If Chrome is not installed, install Google Chrome first.
- Install Chrome Remote Desktop using the official Google package or repository only.
- Set up any required background service or daemon so it starts correctly after reboot.
- Verify the installation by confirming:
  - Chrome Remote Desktop is installed
  - the service is running
  - the host can be configured or is ready for sign-in or pairing
- If any step requires user authentication, permission approval, or a browser login, stop and clearly state the exact manual action required.
- Do not guess. Show the command you plan to run before running it if the step is risky or system-changing.

At the end, report:
1. What was installed
2. What commands were run
3. Any remaining manual steps
4. Whether the machine is fully ready for remote access
