别人托我帮老师写的一个小程序，但是寄了

失败品，网站加载太逆天，根本爬不了



第一次启动：
打开PowerShell

python -m venv venv
./venv/Scripts/Activate.ps1

如果报错，输入Set-ExecutionPolicy RemoteSigned
再输入Y
再重新执行./venv/Scripts/Activate.ps1

pip install -r requirements.txt
python main.py

第一次启动会很慢，会安装chrome


之后启动：
打开PowerShell
./venv/Scripts/Activate.ps1
python main.py