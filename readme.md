# cis-controls

A workspace to collaborate mapping updates to the Center for Internet Security (CIS) Critical Security Controls (CSC).

## Overview

The documents posted here are for collaboration with my security colleagues to review suggestive changes in preparation for submission to the [CIS Controls Community](https://www.cisecurity.org/communities/controls) for official review and possible inclusion. Again, the proposed changes are not an official publication, but are posted here for research and for collaborative purposes.

The goal is to map all the [CIS Critical Security Controls v8](https://www.cisecurity.org/controls/cis-controls-list) to the following references:

- [National Institute of Standards and Technology (NIST) Special Publication (SP) 800-53 Revision 5](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final)
- [National Institute of Standards and Technology (NIST) Cybersecurity Framewwork (CSF) Version 1.1](https://www.nist.gov/cyberframework/framework)

To share your feedback after you review the proposed changes, please submit a Github [New Issue](https://github.com/dgomez407/cis-controls/issues/new/choose), so we can discuss. Looking forward to collaborating with you.

The last review was conducted on 8/20/2023.

## CIS Critical Security Controls v8 Mapping to NIST 800-53 Rev. 5

[Download](./cis-to-sp80053r5/CIS_Controls_v8_Mapping_to_NIST_SP_800_53_Rev_5_Moderate_and_Low_Base_modified.xlsx) the modified spreadsheet to review the proposed changes. A [PDF](./cis-to-sp80053r5/CIS_Controls_v8_Mapping_to_NIST_SP_800_53_Rev_5_Moderate_and_Low_Base_modified.pdf) is also available.

The proposed changes are based on the latest official publication that can be downloaded at [CIS Critical Security Controls v8 Mapping to NIST 800-53 Rev. 5 (Moderate and Low Baselines)](https://www.cisecurity.org/insights/white-papers/cis-controls-v8-mapping-to-nist-800-53-rev-5).

Summary of the proposed changes:

- All CIS Controls have been mapped to NIST SP 800-53r5 controls and baselines
- Added Privacy, Low, and High baselines
- Added Unmapped 800-53 High sheet
- Baseline corrections:
  - NIST Control AU-11 baseline for CIS 3.1 is low not moderate
  - NIST Control CM-2 baseline for CIS 4.2 is low not moderate
  - NIST Control CM-6 baseline for CIS 4.2 and 12.3 is low not moderate
  - NIST Control CM-7 baseline for CIS 4.2 and 12.3 is low not moderate
  - NIST Control CM-10 baseline for CIS Control 2.3 and 9.4 is low not moderate
  - NIST Control CM-11 baseline for CIS 9.4 is low not moderate
  - NIST Control CM-8 baseline for CIS 16.4 is low not moderate
  - NIST Control IR-6 baseline for CIS 17.4 is low not moderate
  - NIST Control IR-8 baseline for CIS 17.6 is low not moderate
  - NIST Control RA-2 baseline for CIS 3.2 is N/A not low
  - NIST Control SC-7(3) baseline for CIS 9.3 is moderate not low
  - NIST Control SC-7(4) baseline for CIS 9.3 is moderate not low
  - NIST Control SC-18 baseline for CIS 9.1 is moderate not low
  - NIST Control SC-39 baseline for CIS 4.12 is low not moderate
  - NIST Control SI-4 baseline for CIS 15.5 is low not moderate
  - NIST Control SI-12 baseline for CIS 3.1 is low not moderate
- Missing a letter 'z' in "N/A - Deployed organiation-wide"; should be "N/A - Deployed organization-wide"
- Added "#" column to maintain order
- Modified formatting for improved consistency and ability to sort
- Column 'New' and 'Corrected' and all cell yellow highlights should be removed once reviewed
- These are the NIST controls and their baselines in use for the newly introduced mappings:
  - AU-6(8) - High
  - CA-8 - Moderate
  - CA-8(1) - Moderate
  - CM-4(1) - Moderate
  - CP-9(3) - Moderate
  - MP-4 - Moderate
  - PM-4 - High
  - PM-6 - High
  - SA-11(2) - High
  - SA-3(1) - High
  - SA-9 - Low
  - SC-7(12) - N/A
  - SC-7(15) - N/A
  - SR-5(2) - N/A
- These are the CIS Controls with newly introduced mappings:
  - 3.12
  - 4.12
  - 12.8
  - 13.2
  - 15.7
  - 16.13
  - 16.8
  - 18.1
  - 18.2
  - 18.3
  - 18.4
  - 18.5
  - 16.14

## CIS Critical Security Controls v8 Mapping to NIST CSF v1.1

[Download](./cis-to-csfv1.1/CIS_Controls_v8_Mapping_to_NIST_CSF_2_2023_modified.xlsx) the modified spreadsheet to review the proposed changes. A [PDF](./cis-to-csfv1.1/CIS_Controls_v8_Mapping_to_NIST_CSF_2_2023_modified.pdf) is also available.

The proposed changes are based on the latest official publication that can be downloaded at [CIS Critical Security Controls v8 Mapping to NIST CSF)](https://www.cisecurity.org/insights/white-papers/cis-controls-v8-mapping-to-nist-csf).

Summary of the proposed changes:

- All CIS Controls have been mapped to a CSF Function
- Added "#" column to maintain order
- Modified formatting for improved consistency and ability to sort
- Column 'New' and 'Corrected' and all cell yellow highlights should be removed once reviewed
- These are the CSF Functions with newly introduced mappings:
  - ID.RA-3 - Threats, both internal and external, are identified and documented
  - PR.IP-2 - A System Development Life Cycle to manage systems is implemented
  - PR.IP-7 - Protection processes are improved
  - PR.MA-1 - Maintenance and repair of organizational assets are performed and logged, with approved and controlled tools
  - RS.MI-1 - Incidents are contained
  - RS.MI-2 - Incidents are mitigated
  - RC.CO-3 - Recovery activities are communicated to internal and external stakeholders as well as executive and management teams
