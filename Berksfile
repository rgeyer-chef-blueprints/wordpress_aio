site :opscode

cookbook "logging",
  git: "git://github.com/rgeyer/rightscale_cookbooks-1.git",
  branch: "release_20121219",
  rel: "cookbooks/logging"

cookbook "logging_rsyslog",
  git: "git://github.com/rgeyer/rightscale_cookbooks-1.git",
  branch: "release_20121219",
  rel: "cookbooks/logging_rsyslog"

cookbook "logging_syslog_ng",
  git: "git://github.com/rgeyer/rightscale_cookbooks-1.git",
  branch: "release_20121219",
  rel: "cookbooks/logging_syslog_ng"

cookbook "db",
  git: "git://github.com/rgeyer/rightscale_cookbooks-1.git",
  branch: "release_20121219",
  rel: "cookbooks/db"

cookbook "db_mysql",
  git: "git://github.com/rgeyer/rightscale_cookbooks-1.git",
  branch: "release_20121219",
  rel: "cookbooks/db_mysql"

cookbook "db_postgres",
  git: "git://github.com/rgeyer/rightscale_cookbooks-1.git",
  branch: "release_20121219",
  rel: "cookbooks/db_postgres"

cookbook "block_device",
  git: "git://github.com/rgeyer/rightscale_cookbooks-1.git",
  branch: "release_20121219",
  rel: "cookbooks/block_device"

cookbook "rightscale",
  git: "git://github.com/rgeyer/rightscale_cookbooks-1.git",
  branch: "release_20121219",
  rel: "cookbooks/rightscale"

cookbook "sys",
  git: "git://github.com/rgeyer/rightscale_cookbooks-1.git",
  branch: "release_20121219",
  rel: "cookbooks/sys"

cookbook "sys_dns",
  git: "git://github.com/rgeyer/rightscale_cookbooks-1.git",
  branch: "release_20121219",
  rel: "cookbooks/sys_dns"

cookbook "sys_ntp",
  git: "git://github.com/rgeyer/rightscale_cookbooks-1.git",
  branch: "release_20121219",
  rel: "cookbooks/sys_ntp"

cookbook "sys_firewall",
  git: "git://github.com/rgeyer/rightscale_cookbooks-1.git",
  branch: "release_20121219",
  rel: "cookbooks/sys_firewall"

cookbook "web_apache",
  git: "git://github.com/rgeyer/rightscale_cookbooks-1.git",
  branch: "release_20121219",
  rel: "cookbooks/web_apache"

cookbook "app_wordpress",
  git: "git://github.com/rgeyer-rs-cookbooks/app_wordpress.git"

cookbook "php5",
  git: "git://github.com/rgeyer-rs-cookbooks/php5.git"

cookbook "nginx",
  git: "git://github.com/rgeyer-rs-cookbooks/nginx.git"

cookbook "utils",
  git: "git://github.com/rgeyer/cookbooks.git",
  rel: "cookbooks/utils"

cookbook "rightscale_sandbox",
  git: "https://github.com/rgeyer-rs-cookbooks/rightscale_sandbox.git"

cookbook "lnmp_aio",
  git: "git://github.com/rgeyer-rs-cookbooks/cookbooks_st.git",
  branch: "release_20120709",
  rel: "cookbooks/lnmp_aio"

cookbook "phpmyadmin",
  git: "git://github.com/rgeyer-rs-cookbooks/phpmyadmin.git"

cookbook "mail_postfix",
  git: "git://github.com/rgeyer-rs-cookbooks/mail_postfix.git"

cookbook "mysql",
  git: "git://github.com/rgeyer-rs-cookbooks/mysql.git"

cookbook "system",
  git: "git://github.com/flaccid/cookbooks.git",
  rel: "cookbooks/system"

group :aio_extensions_role do
  cookbook "rightscale",
    git: "git://github.com/rgeyer/rightscale_cookbooks-1.git",
    branch: "release_20121219",
    rel: "cookbooks/rightscale"

  cookbook "git",
    git: "git://github.com/rgeyer-rs-cookbooks/git.git",
    branch: "server_enhancements"

  cookbook "gitolite",
    git: "git://github.com/rgeyer-rs-cookbooks/gitolite.git"
end

group :vagrant_only do
  cookbook "rs_vagrant_shim",
    git: "https://github.com/rgeyer-rs-cookbooks/rs_vagrant_shim.git",
    rel: "cookbooks/rs_vagrant_shim"
end
