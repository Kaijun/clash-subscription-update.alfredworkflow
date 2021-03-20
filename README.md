
# clash-subscription-update.alfredworkflow

> 通过 Alfred 更新 Subscription，并且支持自定义规则追加

## 配置

#### 1. 双击，填写自定义的订阅地址

![Screen Shot 2021-03-20 at 6 43 31 PM](https://user-images.githubusercontent.com/1693027/111867326-2bf93800-89ae-11eb-9bd3-a073b99db003.png)

![Screen Shot 2021-03-20 at 6 44 26 PM](https://user-images.githubusercontent.com/1693027/111867408-a629bc80-89ae-11eb-8f20-f27d1d798fa1.png)

注意：Arg 内，填写 `配置文件名 | 订阅URL` 其中分隔符` | `不要删除，必须保留

#### 2. 填写追加配置

![Screen Shot 2021-03-20 at 6 47 47 PM](https://user-images.githubusercontent.com/1693027/111867435-dbcea580-89ae-11eb-971b-64419b7e2a82.png)
![Screen Shot 2021-03-20 at 6 49 22 PM](https://user-images.githubusercontent.com/1693027/111867436-de30ff80-89ae-11eb-99c1-59220fd78ff7.png)

注意：
- 配置会默认追加到 rules 最前面。
- 如果配置路径有改动则修改 CLASH_CONFIG_PATH 
- 默认拉取超时 15秒，如果需要修改更长或者更短，则修改 `curl -m 15` 的值

## 使用截图
![WX20210320-190705](https://user-images.githubusercontent.com/1693027/111867567-d58cf900-89af-11eb-8d6c-9d46f71c38e1.png)
![WX20210320-190741](https://user-images.githubusercontent.com/1693027/111867569-d756bc80-89af-11eb-9e50-396687eacff5.png)
![WX20210320-190919](https://user-images.githubusercontent.com/1693027/111867571-d9b91680-89af-11eb-952c-eb6d76d5cd15.png)

