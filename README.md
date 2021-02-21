# Brook 转发一键脚本
> 逗比的 brook-pf 转发脚本备份，适配最新版。

- 去除了添加防火墙规则（不喜欢被乱改系统）
- wget 进行证书验证
- 禁止更新
- 只下载指定版本
- 所有文件均在该repo里面

解决证书问题
```
# Debian
apt-get install ca-certificates -y
# CentOS
yum install ca-certificates -y
```

下载使用
```
wget -N --no-check-certificate https://gitee.com/ten/Brook/raw/master/brook-pf.sh && chmod +x brook-pf.sh && bash brook-pf.sh
```
