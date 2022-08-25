SUBDIRS =					\
	deb					\
	rpm

sqldir = $(pkgdatadir)
dist_sql_DATA =					\
	install.sql				\
	install_plugin.sql				\
	uninstall.sql				\
	update.sql

install.sql: install.sql.in
	sed -e 's|@MRN_DATA_DIR[@]|$(pkgdatadir)|g'
