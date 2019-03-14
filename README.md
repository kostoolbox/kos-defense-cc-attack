# kos-defense-cc-attack
KOS云防C，是KOS工具箱推出的一款精准防C的免费服务。它完全支持Kangle EP主机系统并兼容基于Centos 6.x系统的其他Web面板。KOS云防C可防御众多的恶意IP CC攻击、轮循多IP CC攻击、代理IP CC攻击。每日自动更新KOS云黑名单IP列表，一次安装，永久生效。

安装启动帮助KOS云防C https://kos.qwblog.cn/kos-defense-cc-attack/

用户体验计划访问当前项目根目录 https://raw.githubusercontent.com/kostool/kos-defense-cc-attack/master/User-experience-and-log-sharing-plan.txt

误封解决IP黑名单标记 https://kos.qwblog.cn/kos-defense-cc-attack/#wufeng

KOS云防C恶意CC IP黑名单内容共享 https://kos.qwblog.cn/kos-defense-cc-attack/#api
获取最新列表调用时可增加当前唯一的 ?date-time
Linux系统本地随机生成字符串 date +%s%N echo 
$RANDOM 
cat /dev/urandom | head -n 10 | cksum | awk -F ' ' '{print $1}'
