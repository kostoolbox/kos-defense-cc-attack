# kos-defense-cc-attack<br>
<p>KOS工具箱团队免费分享&维护。使用与否是你的自由，不愿招来“顾客式”用户，拒绝无脑喷子！</p>
<p>通过自研KOS云端-V2分析系统，获得基于当前用户圈儿恶意IP列表并存储；每小时更新至Light客户端，并通过IPTABLES扩展来哈希存储、极速读取；客户端MAIN组件秒级识别CC，并作出防御反应。适合防御大量代理IP攻击，缓解CC攻击效果显著！<br>
支持Kangle、宝塔、AMH、Lnmp、cPanel等使用；支持Linux Centos系列</p>

KOS云防C功能集成在KOS工具箱之中。复制SSH命令、运行KOS工具箱脚本，选择子菜单[4]项进行安装、启动（<a href="https://kostool.cn/screenshot/20181226190318.jpg" target="_blank"><i class="fa fa-file-image-o"></i>&nbsp;查看截图</a>）

安装启动帮助KOS云防C https://kos.qwblog.cn/kos-defense-cc-attack/

用户体验计划访问当前项目根目录 https://raw.githubusercontent.com/kostool/kos-defense-cc-attack/master/User-experience-and-log-sharing-plan.txt

误封解决IP黑名单标记 https://kos.qwblog.cn/kos-defense-cc-attack/#wufeng

KOS云防C恶意CC IP黑名单内容共享 https://kos.qwblog.cn/kos-defense-cc-attack/#api
获取最新列表调用时可增加当前唯一的 ?date-time
Linux系统 date +%s%N echo 
 $RANDOM 
 cat /dev/urandom | head -n 10 | cksum | awk -F ' ' '{print $1}'
