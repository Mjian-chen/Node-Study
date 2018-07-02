# Node的安装
#### 前提条件是是要先安装 n ,下面是安装低版本的node.
```
sudo n v6.10.0
```

#### 下面是升级npm到最新的版本,或者你也可以将npm安装到指定的版本。

```
sudo npm install npm -g
sudo npm install npm@xxxx -g
````

#### 最后将node升级到最新的版本或者指定的版本
```
sudo n stable
sudo n v9.3.0
```

#### 说明
先降级安装node的低版本，再安装最新的npm，是为了避免在高版本的node环境中升级npm中出现包找不到的问题。
