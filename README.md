# gfwsniproxy 一键脚本将GFWList转换为dnsmasq规则

#带ipset规则的dnsmasq规则：
  ```
wget https://raw.githubusercontent.com/yyingc/gfwsniproxy/master/gfwlist2dnsmasq.sh
chmod +x gfwlist2dnsmasq.sh
sh gfwlist2dnsmasq.sh -s gfwlist -o /root/dnsmasq_gfwlist_ipset.conf
  ```
#不带ipset规则的dnsmasq规则：
  ```
wget https://raw.githubusercontent.com/yyingc/gfwsniproxy/master/gfwlist2dnsmasq.sh
chmod +x gfwlist2dnsmasq.sh
sh gfwlist2dnsmasq.sh -o /root/dnsmasq_gfwlist.conf
  ```
#普通的GFWList域名列表：
  ```
wget https://raw.githubusercontent.com/yyingc/gfwsniproxy/master/gfwlist2dnsmasq.sh
chmod +x gfwlist2dnsmasq.sh
sh gfwlist2dnsmasq.sh -l -o /root/gfwlist_domain.txt
