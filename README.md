# zsh_theme
基于michelebologna主题做了小改动

# 安装说明

## 安装zsh
```
echo $SHELL
yum install -y zsh
chsh -s /bin/zsh
```

## 安装oh-my-zsh

安装地址：`https://github.com/ohmyzsh/ohmyzsh/wiki`
如果遇到访问慢，直接去`ip.cn`查询`github.com`的`ip`。


```
cd /data/src
sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## 下载主题
```
make /data/iresource && cd /data/iresource  
git clone https://github.com/Adger01/zsh_theme.git
cp /data/iresource/zsh_theme/lijie.zsh-theme /root/.oh-my-zsh/themes/
```

## 更换主题
```
vim /root/.zhsrc

修改
ZSH_THEME="lijie"


```
