UserLand cloud on Cloud Phone

name rpm
password redpanda


https:// github.com/CypherpunkArmory/UserLAnd/releases/download/v2.8.3/app-release.apk

curl o -k https://raw.githubusercontent.com/TheRetroMike/VerusCliMining/main/install.sh | bash

cd ccminer

nano config.json

./start.sh

config.json 

{
	"pools":[
	{
		"name": "LuckPool",
        	"url": "stratum+tcp://na.luckpool.net:3960",
		"timeout": 150
	},
	{
		"name": "LuckPoolFailover1",
        	"url": "stratum+tcp://na.luckpool.net:3956",
		"timeout": 150
	},
	{
		"name": "LuckPoolFailover2",
        	"url": "stratum+tcp://na.luckpool.net:3957",
		"timeout": 150
	}
	],
	"user": "RHAts2xhzUJThtXEfFHtA6tihSphVXhUL8.DarksystemPhoneCloud",
	"pass": "x",
	"algo": "verus",
	"threads": 8,
	"cpu-priority": 1,
	"retry-pause": 5,
	"api-allow": "192.168.0.0/16",
	"api-bind": "0.0.0.0:4068"
}
