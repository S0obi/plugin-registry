# OWASP CRS Plugin Registry
Registry for OWASP CRS plugins, official and 3rd party.

OWASP CRS allows for plugins. Yet the rule ID namespace needs to be coordinated. This repo serves as the official 
place to register plugins and reserve rule ID ranges.

The rule ID range from 9,500,000 - 9,999,999 is reserved for CRS plugins.

Plugins usually get a range of 1,000 IDs with the notable exception of the incubator plugin that
maps the regular CRS IDs from 900K for each rule to the range 9,900,000 - 9,999,999.

| *Plugin Name*                       | *Rule ID Range*       | *Repository*                                                                                                               | *Type*    | *Status*            | *CI* |
|-------------------------------------|-----------------------|----------------------------------------------------------------------------------------------------------------------------|-----------|---------------------| -----|
| template                            | 9,500,000 - 9,500,999 | [coreruleset/template-plugin](https://github.com/coreruleset/template-plugin)                                              | official  | &#9989;&nbsp;tested | ![Integration tests](https://github.com/coreruleset/template-plugin/actions/workflows/integration.yml/badge.svg) |
| auto-decoding                       | 9,501,000 - 9,501,999 | [coreruleset/auto-decoding-plugin](/https://github.com/coreruleset/auto-decoding-plugin)                                   | official  | untested            |      |
| antivirus                           | 9,502,000 - 9,502,999 | [coreruleset/antivirus-plugin](https://github.com/coreruleset/antivirus-plugin)                                            | official  | being tested        |      |
| body-decompress                     | 9,503,000 - 9,503,999 | [coreruleset/body-decompress-plugin](https://github.com/coreruleset/body-decompress-plugin)                                | official  | being tested        |      |
| fake-bot                            | 9,504,000 - 9,504,999 | [coreruleset/fake-bot-plugin](https://github.com/coreruleset/fake-bot-plugin)                                              | official  | being tested        |      |
| google-oauth2                       | 9,505,000 - 9,505,999 | [coreruleset/google-oauth2-plugin](https://github.com/coreruleset/google-oauth2-plugin)                                    | official  | being tested        |      |
| drupal-rule-exclusions              | 9,506,000 - 9,506,999 | [coreruleset/drupal-rule-exclusions-plugin](https://github.com/coreruleset/drupal-rule-exclusions-plugin)                  | official  | untested            |      |
| wordpress-rule-exclusions           | 9,507,000 - 9,507,999 | [coreruleset/wordpress-rule-exclusions-plugin](https://github.com/coreruleset/wordpress-rule-exclusions-plugin)            | official  | &#9989;&nbsp;tested | ![Integration tests](https://github.com/coreruleset/wordpress-rule-exclusions-plugin/actions/workflows/integration.yml/badge.svg) |
| nextcloud-rule-exclusions           | 9,508,000 - 9,508,999 | [coreruleset/nextcloud-rule-exclusions-plugin](https://github.com/coreruleset/nextcloud-rule-exclusions-plugin)            | official  | &#9989;&nbsp;tested | ![Integration tests](https://github.com/coreruleset/nextcloud-rule-exclusions-plugin/actions/workflows/integration.yml/badge.svg) |
| dokuwiki-rule-exclusions            | 9,509,000 - 9,509,999 | [coreruleset/dokuwki-rule-exclusions-plugin](https://github.com/coreruleset/dokuwiki-rule-exclusions-plugin)               | official  | untested            |      |
| cpanel-rule-exclusions              | 9,510,000 - 9,510,999 | [coreruleset/cpanel-rule-exclusions-plugin](https://github.com/coreruleset/cpanel-rule-exclusions-plugin)                  | official  | untested            |      |
| xenforo-rule-exclusions             | 9,511,000 - 9,511,999 | [coreruleset/xenforo-rule-exclusions-plugin](https://github.com/coreruleset/xenforo-rule-exclusions-plugin)                | official  | being tested        |      |
| phpbb-rule-exclusions               | 9,512,000 - 9,512,999 | [coreruleset/phpbb-rule-exclusions-plugin](https://github.com/coreruleset/phpbb-rule-exclusions-plugin)                    | official  | being tested        |      |
| phpmyadmin-rule-exclusions          | 9,513,000 - 9,513,999 | [coreruleset/phpmyadmin-rule-exclusions-plugin](https://github.com/coreruleset/phpmyadmin-rule-exclusions-plugin)          | official  | being tested        |      |
| dos-protection-modsecurity-v2       | 9,514,000 - 9,514,999 | [coreruleset/dos-protection-plugin-modsecurity-v2](https://github.com/coreruleset/dos-protection-plugin-modsecurity-v2)    | official  | untested            |      |
| dos-protection-modsecurity-v3       | 9,515,000 - 9,515,999 | [coreruleset/dos-protection-plugin-modsecurity-v3](https://github.com/coreruleset/dos-protection-plugin-modsecurity-v3)    | official  | draft               |      |
| machine-learning-integration-plugin | 9,516,000 - 9,516,999 | [coreruleset/machine-learning-integration-plugin](https://github.com/coreruleset/machine-learning-integration-plugin)      | official  | draft               |      |
| performance-plugin                  | 9,517,000 - 9,517,999 | [coreruleset/performance-plugin](https://github.com/coreruleset/performance-plugin)                                        | official  | draft               |      |
| ghost-rule-exclusions               | 9,518,000 - 9,518,999 | [coreruleset/ghost-rule-exclusions-plugin](https://github.com/coreruleset/ghost-rule-exclusions-plugin)                    | official  | draft               |      |
| roundcube-rule-exclusions-plugin    | 9,519,000 - 9,519,999 | [EsadCetiner/roundcube-rule-exclusions-plugin](https://github.com/EsadCetiner/roundcube-rule-exclusions-plugin)            | 3rd party | &#9989;&nbsp;tested | ![Integration tests](https://github.com/EsadCetiner/roundcube-rule-exclusions-plugin/actions/workflows/integration.yml/badge.svg)|
| sogo-rule-exclusions-plugin         | 9,520,000 - 9,520,999 | [EsadCetiner/sogo-rule-exclusions-plugin](https://github.com/EsadCetiner/sogo-rule-exclusions-plugin)                      | 3rd party | &#9989;&nbsp;tested | ![Integration tests](https://github.com/EsadCetiner/sogo-rule-exclusions-plugin/actions/workflows/integration.yml/badge.svg) |
| iredadmin-rule-exclusions-plugin    | 9,521,000 - 9,521,999 | [EsadCetiner/iredadmin-rule-exclusions-plugin](https://github.com/EsadCetiner/iredadmin-rule-exclusions-plugin)            | 3rd party | &#9989;&nbsp;tested | ![Integration tests](https://github.com/EsadCetiner/iredadmin-rule-exclusions-plugin/actions/workflows/integration.yml/badge.svg) |
| wordpress-hardening-plugin          | 9,522,000 - 9,522,999 | [eilandert/wordpress-hardening-plugin](https://github.com/eilandert/wordpress-hardening-plugin)                            | 3rd party | untested            |      |
| incubator                           | 9,900,000 - 9,999,999 | [coreruleset/incubator-plugin](https://github.com/coreruleset/incubator-plugin)                                            | official  | -                   |      |
