金瑞期货生产环境备份：
1. 实盘脚本、配置备份
	sh tool_[exchange]_backup_scripts_hzp.sh
2. 服务器备份
	tar --exclude=[exchange]_trade_hzp.tar.gz -cvzf [exchange]_trade_hzp.tar.gz ~/
3. crontab备份
	crontab -l > [exchange]_crontab_hzp.txt
4. xshell会话配置
