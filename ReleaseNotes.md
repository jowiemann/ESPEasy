### Release Notes:
```
0.4.5  - timestamp of reading state will not be changed if state == opened,present or absent
       - added internal INTERVAL
0.4.6  - Attr Interval can be set 0 to disable presence check and polling
       - removed deprecated code for old ESPEasy Versions without json support
       - reworked dispatching values
       - reworked presence detection (no more polling, check readings age)
       - added attribut adjustValue (see command ref for details)
       - added internal ESP_CONFIG -> EspIP:version,sleep,unit
       - added internal UNIQIDS to devices
0.4.7  - command reference updated
0.4.8  - logging adopted

```
