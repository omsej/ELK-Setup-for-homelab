## ELK-Setup-for-homelab

Creating an Elastic SIEM homelab using ELK

Prerequisites:
1- Create a free Elastic Cloud account at https://cloud.elastic.co/
2- 


## After seting up the free account, follow the prompts to deploy.

**Watch out! The initial login credentials will be displayed during deployment!! Take note**

Once the deployment is complete you will see a welcome page. 
Feel free to browse but when ready, go to fleet by clickick the tri-bar button at the top left, scroll all the way down to "Management" and select "Fleet".

In fleet, select "Add agent" towards the upper right side of the screen.

![alt text](https://github.com/omsej/ELK-Setup-for-homelab/blob/main/Add%20agent.png)

In the popup window, you will see several options to name your agent policy and tags. We're just going to keep defaults in this excersize but if you are intending on using this lab for an extended period then I recomend you come up with a naming convention starting with the first policy.

Select "Enroll in Fleet" (Default)

Select the OS of the agent host.
Copy the relevant Bash/Powershell code. (I am using a Ubuntu VM but feel free to use your host PC or any other OS).

Once all files are updated you will see that the fleet dashboard updates with the agent hostname.
You can select the hostname and you'll see that you are already collecting data and logs on the host.

This is a basic setup that collects some network traffic and logs.
These tools are most useful when dashboards and data collection are tailored to your needs.

![alt text](https://github.com/omsej/ELK-Setup-for-homelab/blob/main/final.png)
