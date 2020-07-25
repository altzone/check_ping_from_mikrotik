# check_ping_from_mikrotik
Nagios script with performance data to ping host from mikrotik throught API

## Usage:
check_ping_from_mikrotik -H <mikrotik_address> -u <username> -p <password> -h <ping_address> -n <numbers count of pings> -w <ping_warning>,<loss_warning%> -c <ping_critical>,<loss_critical%> [ -P <API_port>]
 
 Use -d for API debug output
