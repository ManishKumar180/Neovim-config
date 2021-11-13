
Vim is a text editor that's more powerful than notepad. 
<br>
It can do anything from editing small files to programming software. 
<br> <br>
It can increase your Productivity 😄

<br>
<div>
<a href="https://imgflip.com/i/5u1uh9"><img src="https://i.imgflip.com/5u1uh9.jpg" title="made at imgflip.com"/></a><div><a href="https://imgflip.com/memegenerator"></a></div>

<br>


All steps you need to install Neovim on your Linux and Windows Operating Systems

For windows Users:

First You have to install wsl (windows subsystem for linux) inorder to run neovim 

Proper Guide to install wsl  : 
-> first Turn on the  wsl as shown in the image below

![wsl](https://user-images.githubusercontent.com/86479387/141649129-95885ed6-e9bd-46e2-b05f-f140d32b6086.png)

Installing Linux distros using Microsoft Store
To install a distribution of Linux on Windows 10, use these steps:

Open Microsoft Store.
Search for the Linux distribution that you want to install.

Some of the distros available include:

Ubuntu.
OpenSuse Leap 15.
Kali Linux.
Debian.
Alpine WSL.
Suse Linux Enterprise 12.
Select the distro of Linux to install on your device.


![wslStore](https://user-images.githubusercontent.com/86479387/141649593-279ffe94-48ad-48ad-80e6-9af549d326e5.png)

-Click the Launch button.
-Create a username for the Linux distro and press Enter.
-Specify a password for the distro and press Enter.


![ubuntu](https://user-images.githubusercontent.com/86479387/141649882-119d7de8-a884-43e1-a308-998adba28cf0.png)


Repeat the password and press Enter to confirm.
After you complete the steps, you can start using the distro as any other flavor of Linux (without the graphical user interface, of course).
<br>
Important steps -> 
<br>
Restart The Terminal 


<br>
Update the system using -> <code>sudo apt-get update</code> 
<br>
Upgrade the system Using command -> <code>sudo apt-get upgrade</code>
<br>
Enter your Password ✔️
<br>
Install git using -> <code>sudo apt-get install git</code>

<p > <br>we need nodejs  npm in order to install required packages 
 <br> 
  Enable the NodeSource repository by running the following curl command as a user with sudo privileges :
<br>
  <code>curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -</code>
<br>
The command will add the NodeSource signing key to your system, create an apt sources repository file, install all necessary packages and refresh the apt cache.

If you need to install another version, for example 14.x, just change setup_12.x with setup_14.x

Once the NodeSource repository is enabled, install Node.js and npm by typing:

  <code>sudo apt install nodejs</code>
<br>
The nodejs package contains both the node and npm binaries.

Verify that the Node.js and npm were successfully installed by printing their versions:

  <code>node --version</code> or <code> node -v</code>

v12.16.
  <code>npm --version</code>

6.14.4

  
  <br></p>
   <h4> Must watch If you are new to vim </h4>
 <br>
 https://youtu.be/XguBRi4TDNc
 <br>
 <br>
 https://www.geeksforgeeks.org/getting-started-with-vim-editor-in-linux/
 <br>
 
  <br> 
  
  <p> Install neo vim using <code> sudo apt-get install neovim</code>
 <br> change the File path to home  <code > cd -- </code>
 <br> List out the hidden files using <code> ls -la </code>
 See if there is any .config  <br>if yes  then use command <code> cd .config/ </code></br>  <br>if not  
 then create  one <code> mkdir .config</code> <br>
 <code> cd .config </code> <br>
 Make a directory for our neovim <br>
 <code>mkdir nvim</code> <br>
 <code> cd nvim/</code>
 <br>
 <code> nvim init.vim</code>
 -this will be file for our configs 
 
 !!Watch the above given Tutorial for vim before editing the vim config <br>
 that will save your lot of time 😄
 
 <div> <p> You need a plugin Manager to Install plugins on neovim/vim
 here we are going to use  vim-plug 
 
 https://github.com/junegunn/vim-plug 
 
 choose this ⬇️<br>
 ![2021-11-13_22-40](https://user-images.githubusercontent.com/86479387/141652714-3a2b7816-e447-473a-9d43-dbc6e5164af5.png)
<br>
 First Install curl using 
 <br><code> sudo apt install curl</code>
 
 
 command -
 <br>
 
 
 <code> sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
 https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'</code>
 <br>
 pase this command on your terminal 
 <br>
 
 Example -> 
<br> 
 ![2021-11-13_22-45](https://user-images.githubusercontent.com/86479387/141652887-e2463098-5af4-4927-81eb-65c32796dfa9.png)
<br>

 copy the following text in your init.vim file 
 <br> 
 ![2021-11-13_22-54](https://user-images.githubusercontent.com/86479387/141653217-66a327ba-28ff-4af2-becc-53b68851c6c5.png)
 
 and save the file <br>
 
 Installing vim-airline
 add the below text in init.vim
 <br>
 ![2021-11-13_23-00](https://user-images.githubusercontent.com/86479387/141653378-c9e95b20-90b0-4c74-869d-8287e4462596.png)
 
 or simply copy these from my init.vim file 😄😄<br>
 
Add one more line <br>
 
 ![2021-11-13_23-04](https://user-images.githubusercontent.com/86479387/141653470-991cee54-5a99-4c01-8e5b-6f33626e6437.png)
 
 To Install all Plugins 
 copy this 
 <br>
 ![2021-11-13_23-07](https://user-images.githubusercontent.com/86479387/141653675-2cc8e038-0adb-492d-94a3-6c278e2c46a1.png)
<br>
 
 you might get some errors while opening the neovim 
 simply presss Enter or quit the neovim and remove the following Auto completiong Line
  from the init.vim and save <br>

 ![2021-11-13_23-17](https://user-images.githubusercontent.com/86479387/141653861-7e01f87d-7032-4cc2-95c2-9736c4a9fc0e.png)
 and restart the nvim to see the changes 
 <br>
 Install nerd fonts 
 https://www.nerdfonts.com/font-downloads <br>
 Dowload any zip and extract the fonts and install it 
 <br>
 
 To change fonts on windows ->
 
 <br>
 
 ![2021-11-13_23-24](https://user-images.githubusercontent.com/86479387/141654087-aa7cbfc8-92ef-4094-a51f-752639052ebb.png)
 


![2021-11-13_23-24](https://user-images.githubusercontent.com/86479387/141654242-cd337a79-c23e-4490-8e7b-137059fe21b7.png)
 
 
 
 ![2021-11-13_23-31](https://user-images.githubusercontent.com/86479387/141654325-0fd443b1-e401-4954-b274-5a42950073f2.png)



<br>
 
 
 
<br>
 
 <br>

 <br>

 <br>
 
 
 <br>
 
 
 
 <br>
 
 <br> 
 
 

</p>



  <h1> Guide: </h1>
https://www.computerhope.com/issues/ch001879.htm

https://youtu.be/X-DHaQLrBi8 



For Linux 

