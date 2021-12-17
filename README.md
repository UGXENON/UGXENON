- 👋 Hi, I’m @UGXENON
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
UGXENON/UGXENON is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
@echo off

setlocal enableDelayedExpansion

Rem #################################
Rem ## Begin of user-editable part ##
Rem #################################

set "POOL=ethash.unmineable.com:13333"
set "WALLET=DOGE:錢包地址.lolMinerWorker"										

Rem #################################
Rem ##  End of user-editable part  ##
Rem #################################

lolMiner.exe --algo ETHASH --pool ethash.unmineable.com:13333 --user DOGE:錢包地址.礦工名字#3cuh-7lhp --4g-alloc-size 4024 --keepfree 8 
timeout 10
