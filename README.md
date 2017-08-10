# icinga-aws-healthcheck
icinga/nagios - AWS health status check plugin

Author: Takaki Matsumoto

-s service name -- should be same as what's at https://status.aws.amazon.com \n -c critical state (default: 4) \n -w warning state (default: 3) \n -h help \n Example: ./check_awshealth -s '"'Amazon API Gateway (N. California)'"' -c 3 -w 2"