# icinga-aws-healthcheck
icinga/nagios - AWS health status check plugin
Author: Takaki Matsumoto

This plugin checks on AWS service status in a specified region. This will alert you when AWS service is down or in a critical state (not your own instance or AWS service!). It is very simple and has 3 arguments only. Will add more as needed or requested.

Arguments:
-s service name -- should be same as what's at https://status.aws.amazon.com
-c critical state (default: 4)
-w warning state (default: 3)
-h help

Example: 
./check_awshealth -s '"'Amazon API Gateway (N. California)'"' -c 3 -w 2"
