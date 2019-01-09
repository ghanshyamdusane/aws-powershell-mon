# aws-powershell-mon
aws-powershell-mon

.\mon-put-metrics-mem.ps1 -EC2AccessKey <AccessKeyID> -EC2SecretKey <SecretKey> -mem_util -mem_avail -memory_units kilobytes

.\mon-put-metrics-disk.ps1  -aws_credential_file C:\awscreds.conf -disk_drive C:, d -disk_space_util -disk_space_used -disk_space_avail -disk_space_units gigabytes



* * * * * ~/aws-scripts-mon/mon-put-instance-data.pl --disk-path=/ --disk-space-util --disk-space-used --disk-space-avail
* * * * * ~/aws-scripts-mon/mon-put-instance-data.pl --mem-used-incl-cache-buff --mem-util --mem-used --mem-avail
* * * * * ~/aws-scripts-mon/mon-put-instance-data.pl --swap-util --swap-used



Cloudwatch monitoring
https://engageinteractive.co.uk/blog/aws-cloudwatch-reporting-ram-disk-usage-and-more
https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/mon-scripts.html

[‎5/‎23/‎2018 1:12 PM]  
https://github.com/shineyear/cloudwatch_autoscalegroup_powershell/blob/master/mon-put-metrics-disk.ps1 
 
[‎5/‎23/‎2018 1:13 PM]  
https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/mon-scripts.html 
 
http://test.busrun.net/Files/mon-powershell%20scripts.zip 
