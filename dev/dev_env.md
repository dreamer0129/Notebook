# 软件开发环境配置

## git 

```
apt-get install git
```

## java

+ 使用sdkman管理java https://sdkman.io/

```
curl -s "https://get.sdkman.io" | bash
```

### java 安装

```
https://sdkman.io/jdks/graal

sdk install java 26.ea.10-graal Oracle GraalVM
sdk install java 21.0.8-ms     OpenJDK (Microsoft) 
```

## Node.js

```
curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
sudo apt install -y nodejs
```


## maven 安装

```
apt install maven
```

## uv 

```
curl -LsSf https://astral.sh/uv/install.sh | less
```

# web3j

安装web3j cli

```
curl -L get.web3j.io | sh && source ~/.web3j/source.sh
```