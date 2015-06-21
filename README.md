# Note
note description  how to install cocoapods

gem sources -l  显示所有gem 资源 

仅需安装一次

# 添加源
$ sudo gem sources -a http://ruby.taobao.org/
# 删除源
$ sudo gem sources -r https://rubygems.org/
# 安装
$ sudo gem install cocoapods
# 设置
$ pod setup

👇经常使用

# 搜索
$ pod search AFNetworking
# 生成 Podfile
$ echo "pod 'AFNetworking'" > Podfile
# 安装
$ pod install
# 升级
$ pod update


git 操作👇经常使用

# 将修改添加到暂存区
$ git add .

# 提交修改
$ git commit -m "添加 AFN框架程序"
gem 常用命令

# 查看gem源
$ gem sources –l
# gem自身升级
$ sudo gem update --system
# 查看版本
$ gem --version
# 清除过期的gem
$ sudo gem cleanup
# 安装包
$ sudo gem install cocoapods
# 删除包
$ gem uninstall cocoapods
# 更新包
$ sudo gem update
# 列出本地安装的包
$ gem list
