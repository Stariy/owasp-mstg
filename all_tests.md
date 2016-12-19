# All Test Cases in the OWASP Mobile Security Testing Guide

| ID | Name | Howto | MASVS |
| --- | --- | --- | --- | --- | --- |
| OMTG-DATAST-001 | Test local storage of sensitive data |  Android iOS | [Data Storage](https://github.com/OWASP/owasp-masvs/blob/master/Document/0x07-V2-Data_Storage_and_Privacy_requirements.md) - V2.1 |
| OMTG-DATAST-002 | Test for sensitive data in logs |  Android iOS| [Data Storage](https://github.com/OWASP/owasp-masvs/blob/master/Document/0x07-V2-Data_Storage_and_Privacy_requirements.md) - V2.2 |
| OMTG-DATAST-003 | Test for sensitive data in cloud storage |  Android iOS| [Data Storage](https://github.com/OWASP/owasp-masvs/blob/master/Document/0x07-V2-Data_Storage_and_Privacy_requirements.md) - V2.3 |
| OMTG-DATAST-004 | Verify that no sensitive data is sent to third parties | [Data Storage](https://github.com/OWASP/owasp-masvs/blob/master/Document/0x07-V2-Data_Storage_and_Privacy_requirements.md) - V2.4 |
| OMTG-DATAST-005 | Test for sensitive data in the keyboard cache | [Data Storage](https://github.com/OWASP/owasp-masvs/blob/master/Document/0x07-V2-Data_Storage_and_Privacy_requirements.md) - V2.5 |
| OMTG-DATAST-006 | Test for sensitive Data in the clipboard  | Android iOS | [Data Storage](https://github.com/OWASP/owasp-masvs/blob/master/Document/0x07-V2-Data_Storage_and_Privacy_requirements.md) - V2.6 |
| OMTG-DATAST-007 | Test IPC mechanisms for sensitive data exposure | Android iOS | [Data Storage](https://github.com/OWASP/owasp-masvs/blob/master/Document/0x07-V2-Data_Storage_and_Privacy_requirements.md) - V2.7 |
| OMTG-DATAST-008 | Test for sensitive Data in screenshots |  Android iOS| [Data Storage](https://github.com/OWASP/owasp-masvs/blob/master/Document/0x07-V2-Data_Storage_and_Privacy_requirements.md) - V2.8 |
| OMTG-DATAST-009 | Test for sensitive Data in backups |  Android iOS| [Data Storage](https://github.com/OWASP/owasp-masvs/blob/master/Document/0x07-V2-Data_Storage_and_Privacy_requirements.md) - V2.9 |
| OMTG-DATAST-010 | Verify that memory is cleared when the app is backgrounded |  Android iOS| [Data Storage](https://github.com/OWASP/owasp-masvs/blob/master/Document/0x07-V2-Data_Storage_and_Privacy_requirements.md) - V2.10 |
| OMTG-DATAST-011 | Test for sensitive data in memory |  Android iOS| [Data Storage](https://github.com/OWASP/owasp-masvs/blob/master/Document/0x07-V2-Data_Storage_and_Privacy_requirements.md) - V2.11 |
| OMTG-DATAST-012 | Test remote locking and wiping | Android iOS| [Data Storage](https://github.com/OWASP/owasp-masvs/blob/master/Document/0x07-V2-Data_Storage_and_Privacy_requirements.md) - V2.12 |
| OMTG-DATAST-013 | Verify that a device-access-security policy is Enforced |  Android iOS| Data Storage - V2.13 |
| OMTG-CRYPTO-001 | Verify that the app does not rely on symmetric cryptography with hardcoded keys as a sole method of encryption. |  Android iOS | [Cryptography](https://github.com/OWASP/owasp-masvs/blob/master/Document/0x08-V3-Cryptography_Verification_Requirements.md) - V3.1 |
| OMTG-CRYPTO-002 | Verify that the app uses proven implementations of cryptographic primitives. |  Android iOS| [Cryptography](https://github.com/OWASP/owasp-masvs/blob/master/Document/0x08-V3-Cryptography_Verification_Requirements.md) - V3.2 |
| OMTG-CRYPTO-003 | Test for depreciated cryptographic protocols and algorithms. |  Android iOS| [Cryptography](https://github.com/OWASP/owasp-masvs/blob/master/Document/0x08-V3-Cryptography_Verification_Requirements.md) - V3.3 |
| OMTG-CRYPTO-004 | Verify that cryptographic modules use parameters that adhere to current industry best practices. |  Android iOS| [Cryptography](https://github.com/OWASP/owasp-masvs/blob/master/Document/0x08-V3-Cryptography_Verification_Requirements.md) -  V3.4 |
| OMTG-CRYPTO-005 | Verify that the app doesn't re-use the same cryptographic key for multiple purposes. |  Android iOS| [Cryptography](https://github.com/OWASP/owasp-masvs/blob/master/Document/0x08-V3-Cryptography_Verification_Requirements.md) -  V3.5 |
| OMTG-CRYPTO-006 | Verify that all random values are generated using a sufficiently secure random number generator.  | Android iOS| [Cryptography](https://github.com/OWASP/owasp-masvs/blob/master/Document/0x08-V3-Cryptography_Verification_Requirements.md) - V3.6 |
| OMTG-CRYPTO-007 | Verify that all keys and passwords are changeable, and are generated or replaced at installation time. | Android iOS | [Cryptography](https://github.com/OWASP/owasp-masvs/blob/master/Document/0x08-V3-Cryptography_Verification_Requirements.md) - V3.7 |
| OMTG-CRYPTO-008 | Test for leftover cryptographic keys in memory |  Android iOS | Data Storage -  V3.8 |