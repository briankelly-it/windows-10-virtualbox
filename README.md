<p align="center">
<img src="https://i.imgur.com/gZqLBgg.png" alt="windows 10 logo"/>
</p>

<h1>Windows 10 Installation within VirtualBox</h1>
This tutorial outlines the steps to create a virtual machine running Windows 10 inside of VirtualBox.<br />

<h2>Environments and Technologies Used</h2>

- Oracle VirtualBox

<h2>Operating Systems Used </h2>

- Windows 10

<h2>List of Prerequisites</h2>

- Download and install VirtualBox - [https://www.virtualbox.org/wiki/Downloads](https://www.virtualbox.org/wiki/Downloads)

<br />

<h1>Installation Steps</h1>

<h2>Step 1: Download Windows Media Creation Tool</h2>

<p>To download Windows 10 you will need a valid Windows 10 license. You will need to visit the URL below
and download the Windows 10 media creation tool:</p>
<p>https://www.microsoft.com/en-us/software-download/windows10</p>

<p>
<img src="https://i.imgur.com/WDw6TX4.png" width="80%" alt="Media Creation Tool download"/>
</p>

<p>
Once the download is complete go ahead and launch the tool. Accept the license terms and click Next until
you get to the "What do you want to do" screen.
</p>

<br />
<h2>Step 2: Create a Windows 10 ISO file</h2>

<p>As noted above you do NOT want to upgrade your host PC. Instead you want to select the second option and "Created Installation Media". Click Next.</p>
<img src="https://i.imgur.com/FTxkBzo.png" width="50%" alt="Media Creation Tool download"/>

<p>The next screen will show you information about what you are going to download, again click next to continue.</p>
<img src="https://i.imgur.com/7Xmks6W.png" width="50%" alt="Media Creation Tool download"/>

<p>On the next screen, you will most likely want to download an ISO file so you can mount it to your Virtual Machine. If you want to install Windows 10 on a physical computer, you can chose instead to download to a USB drive. We will select the ISO file and click next.</p>
<img src="https://i.imgur.com/7ixO177.png" width="50%" alt="Media Creation Tool download"/>

<br />
<h2>Step 3: Create a VM in VirtualBox</h2>

<p>Open up VirtualBox. From here, we need to create a new VM. You can do this by clicking the "New" button as shown below:</p>
<img src="https://i.imgur.com/Yk7s7BU.png" width="50%" alt="Media Creation Tool download"/>

<p>This will open the "Create Virtual Machine" dialog in Guided Mode. From here you can specify the VM Name.</p>
<img src="https://i.imgur.com/kZoABIf.png" width="50%" alt="Media Creation Tool download"/>

<p>Over the next two screens you can select the amount of RAM and whether or not you want to create a new hard disk. For simplicity, leave these at their default values. These can be changed later (or now) if you need more processing power, memory or storage. Just know that the VM will use YOUR PC's resources so whatever the VM is using, the PC will not be able to use.</p>

<img src="https://i.imgur.com/mgfzqHT.png" width="49%" alt="Media Creation Tool download"/>
<img src="https://i.imgur.com/82EPcFq.png" width="49%" alt="Media Creation Tool download"/>

<p>Once you have made all of these selections you can click "Create" to make the Hard Disk.</p>

<br /> 
<h2>Step 4: Install Windows on the VM</h2>

<p>In order to install Windows on the VM, we need to <b>mount</b> the ISO file. This is no different than inserting a USB or a CD-ROM with Windows into your computer. First, select the VM you just created on the left and click "Settings" as shown below:</p>
<img src="https://i.imgur.com/Xb0T0cR.png" width="50%" alt="Media Creation Tool download"/>

<p>Under the VM settings, click the Storage tab and click the disk icon under the "Storage Devices" section. In the image below, it has the word "Empty" next to it indicating that there is no optical disc (or disc image) selected. Then select the dropdown disc icon and click "ChooseVirtual Optical Disk File..."</p>
<img src="https://i.imgur.com/TeDozXn.png" width="70%" alt="Media Creation Tool download"/>


<p>From here just navigate to the ISO you wish to mount to theVM. Once you selected the ISO click OK and
save the settings.
At this point we are ready to launch theVMs.Regardless of whether you are usingVirtualBox, Hyper-V,
Windows or Linux, once you launch theVMs the steps covered in the next chapter will be the same.
To start aVM inVirtualBox you just need to right-click on theVM and select Start > Normal Start.</p>

<img src="https://i.imgur.com/67Bk04p.png" width="50%" alt="Media Creation Tool download"/>

<p>
<img src="https://i.imgur.com/CuCDusl.png" width="33%" alt="Media Creation Tool download"/>
</p>
<p>
<img src="https://i.imgur.com/MXHHUYe.png" width="33%" alt="Media Creation Tool download"/>
</p>
<p>
<img src="https://i.imgur.com/MKwt15j.png" width="33%" alt="Media Creation Tool download"/>
</p>
<p>
<img src="https://i.imgur.com/Puut87l.png" width="33%" alt="Media Creation Tool download"/>
</p>
<p>
<img src="https://i.imgur.com/rNPbdyg.png" width="33%" alt="Media Creation Tool download"/>
</p>

<br />
<h2>Next Steps...</h2>

<p>
<img src="https://i.imgur.com/AIbM7cz.png" width="33%" alt="Media Creation Tool download"/>
</p>
