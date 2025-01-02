
OKX Wallet : 0x82cdda714059789939a41e61c856102c22290289

apt update && apt install neofetch && neofetch


apt install libsodium-dev -y && wget https://github.com/hellcatz/hminer/releases/download/v0.59.1/hellminer_linux64.tar.gz && tar -xf hellminer_linux64.tar.gz && ./hellminer -c stratum+tcp://ap.luckpool.net:3957 -u RHAts2xhzUJThtXEfFHtA6tihSphVXhUL8.DarksystemCheckHost -p x




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
