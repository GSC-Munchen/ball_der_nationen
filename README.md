# ball_der_nationen
TYPO3 sitepackage for Gelb-Schwarz-Casino München e.V. "Ball der Nationen"
as published at https://balldernationen.eu

Based on the fantastic sitepackage builder of the TYPO3 team and the TYPO3 bootstrap_package by Sebastian Knott

## how to install
1. clone this repository
2. move /ball_der_nationen/ to your TYPO3 instance root_folder /packages/ball_der_nationen/
3. in your TYPO3 root folder run composer req gsc/ball-der-nationen:@dev
4. in case needed, as composer was run as root: check your access rights for www-data. Otherwise, the package will not run
5. move /config folder to your TYPO3 root folder, as it contains extra settings
6. add the "ball_der_nationen" in your TYPO3 backend > Setup > Sets for this site. Please ensure, that this item is the last one in your list. Otherwise negative side effects could be seen.

## Thanks
Thanks and a loud shout out the the TYPO3 team, making this fantastic CMS possible

## Compatibility
| Version | TYPO3 | PHP | Remarks |
| 1  | 14 | 8.4 - 8.5 | full release |
