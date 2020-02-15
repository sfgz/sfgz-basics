# sfgz-basics
## Description
Basic Extensions contains 6 Extension-files including design. 

Basics to feed a Nexcloud with userdata. sfgz_udb is the main Extension, it imports Userdata from Intranet-Sek II API.

sfgz_udb is also required by upcoming extensions as »sfgz_kurs« or »sfgz_lsbacker«

The extension »sfgz_csvconvert« is mandatory, It converts uploaded tables to custom formatted-tables

## Installation
Import each file within Typo3 as extension.

## Requirements
### Depends on Typo3 9.5.13

release info: https://get.typo3.org/version/9.5.13

download: https://get.typo3.org/9.5.13/tar.gz

### Affored Typo3 Extensions:
#### from TER:

- external_import 4.1.3 https://extensions.typo3.org/extension/external_import 
 
- svconnector 3.3.1 https://extensions.typo3.org/extension/svconnector
 
- svconnector_csv 2.3.0 https://extensions.typo3.org/extension/svconnector_csv
 
- scheduler 9.5.13 (fix installed on typo3 as system extension. Disabled by default, enable it! )
 
#### own Extension:

- sdb_adminer https://github.com/daten-sfgz/sdb_adminer
 
### Affored own standalone scripts:
#### cloudApiAdmin:
- cloudApiAdmin https://github.com/daten-sfgz/cloudApiAdmin

#### Install script:
affored for installing over ftp acces but without ssh access.
- t3InstallHelper.php https://github.com/daten-sfgz/t3_installHelp
