#Install nfdump with sflow
create ramdisk for raw sflow


Install scripts
<code>
mkdir -p /opt/scripts/nfdump
</code>

##Каждый день создаем новую таблицу в mysql . Добавим в crontab

#new table for mysql
<code>
0	0	*	*	* root /opt/scripts/nfdump/nfdump-mysql-new-table
</code>













