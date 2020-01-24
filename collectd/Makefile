
download:
	echo "Download the collectd types.db file and (MIT) License"
	wget -O COPYING "https://raw.githubusercontent.com/collectd/collectd/master/COPYING"
	wget -O types.db "https://raw.githubusercontent.com/collectd/collectd/master/src/types.db"
	grep '^stations' types.db || echo 'stations                value:GAUGE:0:256' >> types.db
	# wget "https://github.com/collectd/collectd/blob/2e6ab45f2758e7ffbedf385e0cf5fe33814a4d43/src/types.db"
