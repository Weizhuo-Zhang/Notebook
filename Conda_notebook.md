# Conda command notebook

## conda常用命令
1. `conda -V　　　　　　　#查看当前conda版本`
2. `conda list　　　　　　#查看安装了哪些包`
3. `conda env list　　　 #查看当前存在哪些虚拟环境`
4. `conda info -e　　　　#查看当前存在哪些虚拟环境`
5. `conda update conda　#检查更新当前conda`

## conda虚拟环境操作
1. `conda create -n YOUR_ENV_NAME python=X.X (2.7 or 3.6) #创建虚拟环境`
2. `conda remove -n YOUR_ENV_NAME --all #删除虚拟环境`
3. `source activate YOUR_ENV_NAME #激活虚拟环境`
4. `source deactivate #关闭虚拟环境`
5. `conda install -n YOUR_ENV_NAME [PACKAGE] #安装包给指定环境`
6. `conda remove --name YOUR_ENV_NAME PACKAGE_NAME #删除环境中的指定包`
