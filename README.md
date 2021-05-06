# okex-py
OKEx数字货币自动交易python语言SDK (非官方)  
OKEx Cryptocurrency Exchange python SDK (Unofficial)

本项目基于V5 API

## 使用例子 Example
``` python3
from okex import OkAPI
api = OkAPI(key, secret_key, passphrase)
candles = api.candles('ETH-USDT')
# print ETH current data
print(candles)
```

## 安装 Installation

1. Clone the repository
```
git clone https://github.com/quantmew/okex-py.git
```

2. Install the package
```
cd okex-py
pip install .
```


## 免责声明 Disclaimers
API接口尚不稳定  
API is not yet stable  
本项目不对软件运行的行为做任何保证，对于因使用本软件产生的损失均不承担任何责任。请充分测试软件后再酌情使用。  
This project does not guarantee the behavior of the software and is not responsible for any damages arising from the use of the software. Please test the software sufficiently before using it.  

## Donation 捐助
如果您觉得这个项目有价值的话，可以通过捐助帮助我们更好地维护这个项目。  
If you think this project is valuable, you can donate to us to better maintain this project.   
ETH Address: 0x4E59baf24bB6e7E8b935A32B33b6E6b8Abd67a2a   

