## Getting a trigger menu:
 In a release set up on lxplus
  > hltGetConfiguration orcoff:/cdaq/physics/Run2018/2e34/v3.6.1/HLT/V2 > hlt_menu_2018.py

where `/cdaq/physics/Run2018/2e34/v3.6.1/HLT/V2` is the HLT key your interested in

The HLT Key can be found from the run report in data
eg:
https://cmsoms.cern.ch/cms/runs/report?cms_run=325117&cms_run_sequence=GLOBAL-RUN
(Not sure yet where to get this in MC)

## How to check L1 Prescales

https://cmsoms.cern.ch/cms/triggers/l1_rates?cms_run=324980&props.4809_4806.selected%5B0%5D=L1A%20Physics

Then click on the bottom left triangle of lines in the "L1 Algo Triggers" box. Then you can enter a string in the filter box.

## xrood prefixes

root://cmsxrootd-site.fnal.gov/ - to read from eos on FNAL
to write to eos on FNAL
root://cms-xrd-global.cern.ch/  - global redirect