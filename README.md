# Stop-GCPInstancesByLabel
```bash
git clone https://github.com/bbz94/Stop-GCPInstancesByLabel
cd Stop-GCPInstancesByLabel
bash Stop-Instances.sh 'aisarch-test-project' '{"label":"env=dev"}' '{"label":"env=dev"}' '0 18 * * *' '0 18 * * *' 'Europe/London' 

#Arguments
projectId=$1
startBody=$2
stopBody=$3
startSchedule="$4" #https://crontab.guru/#0_18_*_*_*
stopSchedule="$5" #https://crontab.guru/#0_18_*_*_*
timeZone=$6
```
