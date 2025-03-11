# Installing Windows Server2022 Virtual OS

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
 
- <b> Step 3 Configuring the start up settings </b>

  <img src= "https://sigmawire.net/i/03/IHpu4K.png" height="40%" width="40%" />
  
