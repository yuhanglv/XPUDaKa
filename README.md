# 如何使用：
## 1. fork本仓库（右上角）

## 2. 点击Actions --> 点击Workflows下的xpu_daka -- > Enable workflow

## 3. 需要在小程序中修改密码（因为直接运行有可能提示密码错误）

## 4.需要用到高德地图api查询经纬度
https://lbs.amap.com/tools/picker

## 5.需要在 Settings --> Secrets --> action 点击 New repository secret，并增加三个字段

#### 1. INFO ,格式如下：

账号

密码

维度

经度

#### 2. ANS ,格式如下（需查看小程序，每个问题的答案中第一条是0，第二条是1，以此类推）

0

1

1

1

0

xx地址（没有可以写无）

#### 3. AGENT ,格式如下(推荐写自己手机的，这个需要通过抓包获取，实在没有可以填写这个，涉及设备型号识别):

Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/81.0.4044.138 Safari/537.36 MicroMessenger/7.0.9.501 NetType/WIFI MiniProgramEnv/Windows WindowsWechat
