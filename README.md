# rancher-API
sh scripts for upgrade, restart containers


eval $(ssh-agent)
ssh-agent sh
export CATTLE_ACCESS_KEY="xx"  
export CATTLE_SECRET_KEY="xx" 
export RANCHER_API_URL="http://xx.xx.xx:9091/v1" 
./rancher.sh upgrade xx xx xx.xx.xx:5000/xx/xx

./rancher.sh finish_upgrade xx xx
