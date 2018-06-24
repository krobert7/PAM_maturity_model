# Privileged Access Management (PAM) maturity model
created for Identiverse conference, Jun 2018

|       | Level 0 Initial |  Level 1 Managed Repeatable  |  Level 2 Defined |  Level 3 Quantitatively Managed | Level 4 Optimized |
| -------- | -------- |  -------- | -------- |  -------- | -------- |
| Characteristics | No Controls, Unpredictable and reactive |  Tribe knowledge, often reactive | Proactive, Standards documented |  Measured and controlled, automation | Stable and flexible, full automation |
| Shared password vaulting and management  | Post-it, spreadsheet, notepad, number of accounts unknown   |  Account inventory with manual rotation | Access controls, 2FA, IDM integration |  RBAC/ABAC, all accounts managed | Password-less sessions, configuration management integration |
| Account discovery | accounts unknown, tracked on spreadsheet |  Manual search of directories and CMDB | automated feed from directories |  automated provisioning for all accounts to vault or credential manager | automated tools for directories, fully integrated with config mgt tools |
| Session Recording | None |  Some privileged sessions recorded and stored | Automated searching of recordings | All privileged sessions recorded| Alerting and integration with your threat dection tools |
| Account automation and lifecycle | None |  Some accounts automatically provisioned and removed | APIs available for all systems to use in automation |  All accounts automatically provisioned and removed | Accounts automatically provisioned with ABAC |
| Session management and isolation | None |  Some sessions managed | Bastion hosts and jumpboxes available for all environments |  All sessions managed with no passwords exposed to users | Required for all  segmented networks |
| Application credential management | None |  Some applications with manual credential managment | Most applications are covered |  Programatic application account managment | All applications are in scope and compliant |
| Privilege account analytics and auditing | None | Some servers enrolled | All critical servers (like domain controllers) are enrolled |  All servers enrolled | Fully integrated with CIRT |
| Threat detection and automatic response | None |  Some servers enrolled, notifications are sent on issues | All servers enrolled |  All servers enrolled and some threats can be processed automatically | Common threats handled automatically and alerts used when needed |
