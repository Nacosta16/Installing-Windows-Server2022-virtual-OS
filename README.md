# Installing Windows Server 2022 Virtual OS

- <b> Step 1 Finding the Windows Server ISO </b>

  - You can find the ISO for Windows Server 2022 at [Windows Server Evaluation](https://www.microsoft.com/en-us/evalcenter/download-windows-server-2022?msockid=03e1b23576c16b9513c4a79e775e6a0d)
     
   <p>
  <img src="https://sigmawire.net/i/03/UOpMlh.png" height="40%" width="40%" alt="VirtualBox set up wizard"/>
  </p>

  - Download the 64bit ISO for windows server 2022 and proceed back to the virtual box manager (See my step by step on [virtual box](https://github.com/Nacosta16/Installing-Vms-on-Virtual-Bo) if you have not installed the manager yet)
  
- <b> Step 2 Configuring the ISO in VirtualBox </b>


  - Similar to installing windows 10, you want to open the Virtualbox manager and select new and name the file "Windows Server 2022" while selecting the file you just downloaded for the ISO
    
  - However, you must select "skip unattended installation". Since this is technically a "trail" it will try to configure the settings on its own, causing it to fail
           
   <p>
  <img src="https://sigmawire.net/i/03/Uy8vRa.png" height="40%" width="40%" alt="VirtualBox set up wizard"/>
  </p>

  - Having RAM set to 8 Gb and 1-2 cores will suffice for this VM although I personally like to have 16 and 4
 
   <p>
  <img src="https://sigmawire.net/i/03/d7Hmes.png" height="40%" width="40%" alt="VirtualBox set up wizard"/>
  </p>
  
  - And finally around 50 Gb is suitable since the purpose of this VM is for practice, not for storing data
 
   <p>
  <img src="https://sigmawire.net/i/03/1OGMrh.png" height="40%" width="40%" alt="VirtualBox set up wizard"/>
  </p>

  - You are now ready to start up the Windows 2022 Server and configure the start up settings.
 
    <img src= "https://sigmawire.net/i/03/IHpu4K.png" height="40%" width="40%" />
 
- <b> Step 3 Configuring the start up settings </b>

   - Go through the startup until you get to "Micosoft Server Operating System Start Up" and select standard evaluation desktop edition so you can get the full windows graphical environment (If you just need the command lines because you are working specifically on something such as security concepts, then just the standard without the desktop will be fine)

      <img src= "https://sigmawire.net/i/03/DS4mzu.png" height="40%" width="40%" />
     
   - Proceed until you see the options to either upgrade or custom install. Select custom.

     <img src= "https://sigmawire.net/i/03/OVsDKC.png" height="40%" width="40%" />

   - Select drive 0, allocating 50 Gb, then continue and allow it to finish installing

      <img src= "https://sigmawire.net/i/03/Nw1WkG.png" height="40%" width="40%" />

- <b> Step 4 setting up Windows server 2022 IP </b>

   - After turning on the machine and making your login informaition, make sure you select no to opening it to a public network and close out the dialog box behind it
 
      <img src= "https://sigmawire.net/i/03/Nw1WkG.png" height="40%" width="40%" />

   - Now you will configure the IP. A general practice is to always give a server a static IP rather than a public one due to provide reliability, accessibility, and security for critical network services
   - Close the server manager and right click the icon on the bottom right to configure network and internet settings

  <img src= "https://sigmawire.net/i/03/tfdrxO.png" height="40%" width="40%" />

  - Select change adapter option

  <img src= "https://sigmawire.net/i/03/ymBhT1.png" height="40%" width="40%" />

  - You then right click the Ethernet option, select properties 

  <img src= "https://sigmawire.net/i/03/ySG0JZ.png" height="40%" width="40%" />

  - Now you can select Ipv4 select properties give it a staic Ip and input the following private IP into the static ipv4 and DNS
 
  <img src= "https://sigmawire.net/i/03/uCz8hv.png" height="40%" width="40%" />

  <img src= "https://sigmawire.net/i/03/gvfVOl.png" height="40%" width="40%" />

  
