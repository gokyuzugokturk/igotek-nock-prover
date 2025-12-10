Use this NOCK Prover for mining at goldenminer.net

Video Tutorial: https://youtu.be/sv4kWaNsJsY   
Discord: https://discord.gg/w6GuBsWHQa

*****

Always use the latest release !

Miner Installation URL: https://github.com/gokyuzugokturk/igotek-nock-prover-hiveos/releases/download/v2.1/nock-2.1.tar.gz

Warning: New released Nock Prover v2.1 supports only PUBKEY V1 address.  
You need to register your PUBKEY V1 at goldenminer.net and create your password !

*****

WALLET CREATION    
![wallet](https://github.com/gokyuzugokturk/igotek-nock-prover/blob/main/img/hiveos_flighsheet_000.png)

*****

USAGE:

Use 1 or 2 or 3 graphic cards at a motherboard.  
Dont use more then 3 graphic cards on a motherboard.  
More than 3 graphic card = lower hashrates.

*****

CPU CORE is important. Dont use low-end CPU at the motherboard.  
1 free core for the system. 2 core for each GPU at minimum.

2 core = too low hashrate  
3 core = low hashrate  
4 core = avarage hashrate  
5 core = good hashrate  
6 core and more is needed for the best hashrate.

Dont set 15 core or more for each GPU because you will get error if you do it.  
High-end CPUs could get error: (reason: out of memory - reason: driver shutting down)  
Please set --thread-per-card value manually if you see this error.

This CPU has 20 CORE. You can use this CPU for mining.  
![20xCore](https://github.com/gokyuzugokturk/igotek-nock-prover/blob/main/img/20xCore.png)  

This CPU has 8 CORE. You can use this CPU for mining.  
![8xCore](https://github.com/gokyuzugokturk/igotek-nock-prover/blob/main/img/8xCore.png)  

This CPU has 2 CORE. You cant use this CPU for mining!  
![2xCore](https://github.com/gokyuzugokturk/igotek-nock-prover/blob/main/img/2xCore.png)  

*****

Script uses all graphic cards at the rig if you dont indicate any graphic cards.  
Leave empty the extra config if you dont know what to do.  
You can set which GPU to be used at the prover.  
You can indicate graphic cards using by --gpu 0,1,2,3 at extra config of the HiveOS Flight Sheet.  
Prover will only use your pointing graphic cards.  
So, you can use for mining another coins with free graphic cards at a one Flight Sheet.  

SELECTING GPU  
![--gpu](https://github.com/gokyuzugokturk/igotek-nock-prover/blob/main/img/hiveos_flighsheet_001.png)

*****

Script calculates and decides CPU CORE for each GPU at the system. You dont need to do any calculate.  
You can set CPU core for each GPU using by --threads-per-card 7 at extra config of the HiveOS Flight Sheet.  
Leave empty the extra config if you dont know what to do.

MANUAL CPU CORE  
![--thread-per-card](https://github.com/gokyuzugokturk/igotek-nock-prover/blob/main/img/hiveos_flighsheet_002.png)

*****

Set the local IP of your proxy at the password field of the HiveOS Flight Sheet if you want to use proxy.  
Leave empty the password field if you dont use proxy.  
You can use local proxy if you have many graphic cards at the same local network.  
You dont need to use proxy if you dont have too many graphic cards at the same local network.

USING PROXY:  
![proxy](https://github.com/gokyuzugokturk/igotek-nock-prover/blob/main/img/hiveos_flighsheet_003.png)

*****

BENCHMARKS of v2.5
RTXA4000 16GB  
![RTXA4000](https://github.com/gokyuzugokturk/igotek-nock-prover/blob/main/img/RTXA4000.png)

RTXA2000 6GB  
![RTXA2000](https://github.com/gokyuzugokturk/igotek-nock-prover/blob/main/img/RTXA2000.png)

Please share your results of v2.5

BENCHMARKS of v2.4
![final](https://github.com/gokyuzugokturk/igotek-nock-prover/blob/main/img/hiveos_flighsheet_004.png)

![final](https://github.com/gokyuzugokturk/igotek-nock-prover/blob/main/img/hiveos_flighsheet_005.webp)

![final](https://github.com/gokyuzugokturk/igotek-nock-prover/blob/main/img/RTX4080SUPER.png)

*****

Wallet: %WAL%  
Pool URL: GOLDEN_MINER

*****

No Dev Fee  
Just type --fee 5 at extra config of the HiveOS flight sheet if you want to donate.  
Buy me a beer for my efforts !

![final](https://github.com/gokyuzugokturk/igotek-nock-prover/blob/main/img/fee.png)

*****

Note: This miner only works at goldenminer.net

* Only GPU mining.
* This miner works at HiveOS !
* This miner uses the latest golden-miner-pool-prover !
* There is another release for Vast.ai
* Check [here](https://github.com/gokyuzugokturk/igotek-nock-prover-vast.ai) for Vast.ai release.




