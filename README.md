# sfgz-basics
## Description
Basic Extensions with design and re-used functions. Contains 6 Extension-files. Runs the User-Administration with import from Intranet-Sek II API and Downloads.

Basics to feed a Nexcloud with userdata. sfgz_udb is the main Extension.

Required by upcoming extensions as sfgz_kurs or sfgz_lsbacker

## Installation
Import the file within Typo3 as extensions.

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
