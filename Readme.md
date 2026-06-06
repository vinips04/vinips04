# Windows Diagnostic Toolkit (.bat)

Windows automation toolkit developed with Batch Script to simplify system diagnostics, troubleshooting and infrastructure support operations.

This project centralizes common tasks performed by IT Support, NOC and Infrastructure teams during incident analysis, reducing manual effort and improving response time.

<img width="379" height="302" alt="image" src="https://github.com/user-attachments/assets/ea1cf56c-3695-49c9-b420-f0dceb5bcbd3" />

---

## Overview

In enterprise environments, analysts frequently execute repetitive troubleshooting procedures during incidents.

This toolkit provides a centralized command-line menu to execute Windows diagnostic and maintenance operations, helping with:

* Faster incident response (MTTR reduction)
* Standardized troubleshooting process
* System health validation
* Infrastructure support automation

## Features

### System Diagnostics

* Disk verification and repair (CHKDSK)
* System file integrity validation (SFC)
* Windows system information collection
* Windows Update verification

### Network Troubleshooting

* Connectivity tests (Ping)
* DNS cache cleanup
* Network services restart

### Maintenance Tasks

* Temporary files cleanup
* Driver backup
* Custom command execution

## Technologies Used

* Batch Script (.bat)
* Windows Command Prompt (CMD)
* Native Windows Administration Tools

## Project Structure

```text
windows-diagnostic-toolkit/

├── scripts/
│   └── windows-diagnostic-toolkit.bat
├── docs/
│   └── evidences/
└── README.md
```

---

## Operational Scenario

Incident example:

A workstation presents slow performance and intermittent network connectivity.

Troubleshooting workflow:

1. Collect system information
2. Validate network connectivity
3. Clear DNS cache
4. Restart network services
5. Execute Windows repair commands
6. Confirm service restoration

## How to Use

Clone this repository:

```bash
git clone https://github.com/vinips04/windows-diagnostic-toolkit.git
```

Access the project:

```bash
cd windows-diagnostic-toolkit/scripts
```

Run:

```cmd
windows-diagnostic-toolkit.bat
```

Note:

Run as Administrator to allow system repair operations.

## Available Options

```text
[1] Check and repair disk (CHKDSK)
[2] Repair system files (SFC)
[3] Clean temporary files
[4] Network connectivity test
[5] Restart network services
[6] Flush DNS cache
[7] Backup installed drivers
[8] Check Windows Updates
[9] Display system information
[10] Execute custom command
```

---

## Security Considerations

* No credentials are stored in the script
* Uses only native Windows commands
* Administrative permissions are required only for system-level operations

## Execution Evidence

Execution screenshots and validation results are available:

```text
/docs/evidences/
```

## Future Improvements

Planned improvements:

* PowerShell version
* Automatic diagnostic report generation
* Log export feature
* Remote troubleshooting support

---

## Author

**Vinicius Pereira**

[LinkedIn](https://www.linkedin.com/in/viniciuspereira27/) | [GitHub](https://github.com/vinips04)
