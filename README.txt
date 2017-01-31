README

Drop this configuration file in the /etc/logstash/conf.d and restart logstash, if you use Elastic via kibana, you'll see these events as *heartbeat
Oh, and make sure you specify the email fields in output. 

On input config file, be sure to set your check interval. Each should be fairly easy to do. 


jon2kx