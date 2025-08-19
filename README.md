# DIY-Mesh-Network
Documentation for my own DIY mesh network using OpenWRT and DD-WRT

I came across an issue in my own home network recently, and wanted to come up with a solution to my problem. My printer, which is located upstairs, has really spotty connection to my main router (displays a single bar on the signal strength) so, I'm coming up with a solution to my problem. My wife was out thrift shopping and found a Linksys WRT54G V8 for really cheap, so I thought, why not? I can make a solution with this.

After a lot of research, I found that OpenWRT doesn't work on this model of router, so I decided to go with DD-WRT instead for that router. So, I did a factory reset on the router and was able to access the admin interface.

<img width="825" height="634" alt="Image" src="https://github.com/user-attachments/assets/56c8b198-c7ca-4a1c-ab1f-3488afbe2789" />

With that step out of the way, now I have to flash the router with DD-WRT follwing the instructions on this website:
https://wiki.dd-wrt.com/wiki/index.php/How_To_Flash_the_WRT54Gv8

Now that DD-WRT is flashed onto the router, I configured it to be on the same subnet with a static IP address of 192.168.1.2 on the same subnet as my main router running OpenWRT

<img width="803" height="636" alt="Image" src="https://github.com/user-attachments/assets/8d6d3870-9303-430e-b9cf-6d7d118a5514" />
