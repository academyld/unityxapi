# unityxapi
Sending xAPI statement from Unity to LRS

This is a collection of resources to help get started sending xAPI statements with Unity applications.

In addition to the C# script in this GitHub, you'll need the following files:

Newtonsoft - Json.NET
https://www.newtonsoft.com/json

Rustici Software - TinCan.NET
https://github.com/RusticiSoftware/TinCan.NET/releases
(Download the TinCan-net45-signed.dll file)



## Setting up Learning Locker (LRS)

##### Ports for AWS Security Group

UDP 27017

TCP 27017

HTTP 80

SSH 22

HTTPS 443

##### Download and Install PuTTY
http://hcv.academy/putty

##### SSH into Learning Locker AWS Instance
user: ubuntu

Connecting using Windows: https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/putty.html?icmpid=docs_ec2_console

Connecting using MacOS: https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AccessingInstancesLinux.html

Script to read creadentials: 

`sudo nano ll_credentials.txt`


