# Armitage - A Visual representation of Metasploit
To show a brief exploration of Armitage
## Armitage is a great visual tool for carrying out both scanning and ethical attacks on targets to spot vulnerabilities.<br/><br/>
<img width="869" height="452" alt="armitage" src="https://github.com/user-attachments/assets/ac9cf53e-8d70-4147-89c7-197cdbbab476" /><br/>
## Let's start our exploration of Armitage
The armitage window ( see below ) has a menu on the top left and three panels. The metasploitable window is at the bottom. The Network targets that armitage knows about is on the right panel, but at the moment we have not scanned our network for any hosts.<br/><br/><br/>
<img width="1590" height="731" alt="arm 1" src="https://github.com/user-attachments/assets/5358d851-552e-45c5-919f-19439649c7c6" />

To begin, you will see below that in order to scan the local network you have to run nmap on the host with a ping scan. As you can see in the dialog box, we chose the range 10.0.2.0/24<br/><br/><img width="1594" height="759" alt="arm 2" src="https://github.com/user-attachments/assets/2285fb36-fe79-4e7d-b68f-63d984a12f62" /><img width="570" height="295" alt="arm 3" src="https://github.com/user-attachments/assets/ada868aa-e2ef-419b-8330-59333e8f115d" /><br/>

As you can see, we have a number of hosts now becasue Armitage has detected and added the hosts on our Network.<br/><br/>
<img width="1594" height="761" alt="arm 4" src="https://github.com/user-attachments/assets/3b0127d3-95c8-492e-89bb-bda27932c10e" /><br/>

We can select now one of them and go for a port scan. you just right click on one of the hosts and select scan and nmap results are displayed in the bottom panel.<br/><br/>
<img width="585" height="575" alt="arm 5" src="https://github.com/user-attachments/assets/97597eb7-f5ea-45cf-9de7-17246c5764db" />
<img width="1594" height="740" alt="arm 6" src="https://github.com/user-attachments/assets/82670ce9-60a3-4205-9476-5b27f839b3f7" /><br/><br/>

 We can also see the services that have been found on the host by right clicking and selecting services. Services are displayed on the bottom panel<br/><br/>

<img width="560" height="418" alt="arm 7" src="https://github.com/user-attachments/assets/f9900520-16e4-45fa-9a07-e8741541d7ba" />
<img width="1592" height="736" alt="arm 8" src="https://github.com/user-attachments/assets/7f861317-a74f-42b6-9d10-412f166baef4" /><br/><br/>
