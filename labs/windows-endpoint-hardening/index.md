🔐 Windows Endpoint Hardening and Encryption
(A grouped showcase of 4 TestOut labs)

📁 Labs Covered:
3.4.3 Encrypt Files with EFS

3.4.8 Configure BitLocker with TPM

8.1.5 Configure Automatic Updates

8.1.7 Configure Microsoft Defender Firewall

🧪 Overview
This project demonstrates practical techniques to harden Windows endpoints using built-in security tools. Tasks include file encryption, full disk encryption, patch management, and firewall configuration — core responsibilities for both IT and cybersecurity professionals.

🔐 1. Encrypt Files with EFS
To protect sensitive data shared on a multi-user system, I encrypted the D:\Finances folder using Encrypting File System (EFS). Additionally, I authorized another user (John) by attaching their certificate to a specific file.

🧭 Scenario:
You share a computer at work. You want to secure the contents of the Finances folder and allow John access to one file.

✅ Key Steps:
Enabled encryption via File Properties → Advanced → “Encrypt contents to secure data”

Selected “Apply to this folder, subfolders, and files”

Added John’s certificate to 2023report.xlsx via file-level access control

📸 Screenshots:


💽 2. Configure BitLocker with TPM
I enabled BitLocker full disk encryption on the C: drive using TPM security. This ensures data is protected at rest, even if the hard drive is removed and accessed externally.

🧭 Scenario:
An employee is working on a sensitive project. If their PC is stolen, confidential data must remain inaccessible.

✅ Key Steps:
Enabled TPM in BIOS and activated it

Initiated BitLocker from Control Panel

Saved the recovery key to a shared network folder (\\CorpServer\BU-Office1)

Chose full drive encryption with modern encryption mode

Ran a system check to validate setup

📸 Screenshots:


🔄 3. Configure Automatic Updates
I customized Windows Update settings to ensure secure, controlled system updates — essential for minimizing vulnerability exposure.

✅ Key Settings:
Receive updates for other Microsoft products

Defer feature updates for 60 days

Defer quality/security updates for 30 days

Enabled automatic driver and icon updates for hardware

📸 Screenshots:


🔥 4. Configure Microsoft Defender Firewall
I enabled Windows Defender Firewall for public networks and configured application-level rules to allow specific apps through only the public profile.

🧭 Scenario:
You're traveling with your laptop and want protection on public Wi-Fi while allowing approved apps to work.

✅ Key Steps:
Enabled firewall for Domain, Private, and Public profiles

Allowed:

Key Management Service

Arch98

Apconf

Scoped each app to Public network only

📸 Screenshots:


💡 Skills Demonstrated
Endpoint hardening

Encryption configuration (EFS, BitLocker)

Secure update policies

Windows Firewall rule management

BIOS security configuration

🧠 Real-World Relevance
These tasks are commonly performed by:

Help Desk / IT Support for securing workstations

SOC Analysts / Cybersecurity Technicians as part of endpoint defense

Sysadmins for enforcing GPOs or hardening baseline images
