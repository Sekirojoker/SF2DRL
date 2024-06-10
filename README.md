# 深度强化学习-街头霸王2
### 环境配置
python 3.8  
gym 0.21.0  
gym retro 0.8.0  
stable baselines3 1.7.0  

### 游戏配置
导入游戏rom后，在retro\data\stable\StreetFighterIISpecialChampionEdition-Genesis文件夹将配置文件和存档替换  
可以去 https://wowroms.com/ 下载其他游戏进行训练，比如doom，需改动动作空间，观测空间，奖励函数等  
存档可以使用Open AI推出的Gym Retro Integration抓取

### 训练曲线
用tensorboard查看logs文件夹下的训练日志，包括损失/奖励等曲线  
终端中运行tensorboard --logdir=.\logs
