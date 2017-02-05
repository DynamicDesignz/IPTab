		IPTab - Basic User Input/Output Scripts For Using IpTables.

IPTab is a collection of basic iptables scripts in Linux. Dynamic scripts that require user input
will ask for a source of desination IP address before they will execute, other scripts are static 
and will simply execute upon entering ./ before the script name. The IPTab directory is meant to
remain in your home folder for easy execution however you can place it in your /usr/local/bin dir
so that the commands can be executed system wide no matter what directory that you are in without
having to specify the ./ before each command filename.

Each command specified below is basically self-explanitory and taken from online tutorials.
If you are unsure of some of the commands you can Google each one below to get a better under
standing as these scripts are meant to teach the basics of cumbersome iptables through use. 


IPTabAllowHTTPTraffic         IPTabDropSpecificPort
IPTabAllowInboundEmail        IPTabLimitSSH
IPTabAllowInboundSMTP         IPTabLoadBalence
IPTabAllowIncomingSSHTunnels  IPTabLoadBalenceWebTraffic
IPTabAllowOutboundDNS         IPTabPortForward
IPTabAllowPingFromOutside     
IPTabAllowPingOutside         
IPTabAllowPingToOutside       
IPTabBlockRange
IPTabBlockIP                  



IPtables: Administration tool for IPv4/IPv6 packet filtering and NAT Network Address Translation
and RAW packet firewall rules. In case of brute force attempts against a server with SSH service
/etc/deny.hosts will suffice at stopping brute force attacks however RAW firewall rules from
iptables is HIGHLY recommended. 
