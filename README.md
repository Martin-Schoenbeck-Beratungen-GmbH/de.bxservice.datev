A fork of:
[BX Service GmbH](https://www.bx-service.com/) accounting interface for [DATEV](http://www.datev.de/)

**Functional Documentation:** [iDempiere Plugin: BX Service DATEV](https://wiki.idempiere.org/en/Plugin:_BX_Service_DATEV)

---

## Installation
When installing the plugin, the pack-in will fail once, while trying to import `2Pack 1.0.6`.
To fix this, drop the DB View `RV_BX_Datev` and restart iDempiere to retrigger the pack-in process.

## Modifications
- PrintFormat: Instead of ID 1000034, this fork looks for the PrintFormat with search key `DATEV`.
