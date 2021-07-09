# TJprojMain-explorer.exe-remover

This simple batch script will get rid of the annoying TJprojMain malware, also known as fake explorer.exe/svchost.exe, which infects all your exe files to spread and disguises itself as common system files.




Simple showcase: 

https://user-images.githubusercontent.com/66956355/125113378-44be6280-e0f1-11eb-8ff5-5d9f03f426b7.mp4

<br />
The virus drops the fake system files at Windows\Resources and Windows\Resources\Themes folders. <br />
All we need to do is enter a loop of ending the task and then deleting the files immediately, <br /> before they manage to open again or be restored by their "friends". <br />
When we make sure the files are not in the system anymore, the program finishes. <br />
Works for C:, D: and E: windows drive letters.
<br />
<br />
<br />
Fyi, if you have an infected file you need to recover, you can easily get the original file with a help of a tool called byte_stinker. (https://github.com/jack51706/byte_stinker)

Simple video so you can see how it works:

https://user-images.githubusercontent.com/66956355/125113641-9666ed00-e0f1-11eb-920d-30e6d759d478.mp4


Stay safe ;)
