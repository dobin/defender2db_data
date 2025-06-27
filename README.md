# Defender2db_data

Data extracted with [defender2db](https://github.com/dobin/defender2db/). 

* `engine/` and `vdm/`: Defender VDM files
* `threats.db`: the threats (with signatures) as sqlite DB. [Format](https://github.com/dobin/defender2db/blob/main/defender2yara/defender/dbthreat.py)
* `mpas.vdm.pickle` and `mpav.vdm.pickle` Signatures as gigantic pickle in defender2db. [Format](https://github.com/dobin/defender2db/blob/main/defender2yara/defender/dbthreat.py)
* `asr_lua`: ASR (addres surface reduction) rules in LUA

Repo is using [git-lfs](https://git-lfs.com/). 
