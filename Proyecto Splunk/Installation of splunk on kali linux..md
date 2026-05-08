**First we enter the page of https://www.splunk.com/ and we make an account and then we search for splunk enterprise , and we download the debian file since we're gonna be using kali linux** 
**![Pasted image 20260501144437](./Pasted%20image%2020260501144437.png) the debian version of splunk its the most common one for kali linux**.

# Next Steps

- **First we need to be root on kali linux , to be root in kali linux we use the command sudo su**

![Pasted image 20260501151356](./Pasted%20image%2020260501151356.png)

**And then we use the command wget provided by the splunk page , you can also download the deb.file manually**

![Pasted image 20260501151524](./Pasted%20image%2020260501151524.png)

**And then we use the command in the terminal of kali linux**

![Pasted image 20260501151943](./Pasted%20image%2020260501151943.png)

**Once the download its finish , we need to decompress the file , whit the command dpkg -i and the name of the splunk file**

![Pasted image 20260501153746](./Pasted%20image%2020260501153746.png)

**Once the decompress its finish , we're gonna make sure the file has been saved correctly , and we're gonna use the command :  *cd /opt/splunk/bin***

![Pasted image 20260501152522](./Pasted%20image%2020260501152522.png)

**After we enter the directory we are gonna use the command *ls* to list all the files from splunk , and then we can be sure that splunk has been downloaded correctly. **

![Pasted image 20260501152702](./Pasted%20image%2020260501152702.png)

**Now we need to install splunk  , whit the command *cd /opt/splunk/bin/splunk enable boot-start***


![Pasted image 20260501154451](./Pasted%20image%2020260501154451.png)

**After hit enter whit the command , a terms and conditions contract its gonna be displayed on the output**


![Pasted image 20260501154926](./Pasted%20image%2020260501154926.png)


![Pasted image 20260501155832](./Pasted%20image%2020260501155832.png)

**After we made our username and password , we start splunk whit the command: *./splunk start --run-as-root***

![Pasted image 20260501160959](./Pasted%20image%2020260501160959.png)

**The splunk web interface is running on the port 8000 , so we enter the next url: http://kali:8000**

**![Pasted image 20260501161350](./Pasted%20image%2020260501161350.png)**

**After we type our user and the password , we can use splunk whit no problems.**

![Pasted image 20260501161446](./Pasted%20image%2020260501161446.png)
