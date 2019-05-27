# EUTelescope config files

Set of config files to be used for DESY Telescope track reconstruction. A virtual machine (configured from openstack.cern.ch) has been configured @ CERN running the necessary software to perform
the track reconstruction.

```sh
ssh -XY <USER>@lxplus.cern.ch
ssh -XY <USER>@pps-tb.cern.ch
cd /home/TelescopeReconstruction
source setup_env.sh
```
In case you would like access for that machine, please contact dmf<at>cern<dot>ch. More information at https://twiki.cern.ch/twiki/bin/viewauth/CMS/CTPPSTestBeam
