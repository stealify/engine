# engine
A Generic engine that works on most hardware based on the nodejs project so runs on every NodeJS Supported Operating System and Arch.

## What does it do?
It is a Standard Distribution of NodeJS + main Stealify Stack designed to run System Wide on Developer Machines or even Production machines that do a lot of generic tasks

It can be seen as OS Indipendent layer of Stealify designed to offer a full Desktop Expirence while it also supports headless.

as the main package /packages/@stealify/engine does not directly include binarys it can be used with NodeJS Directly to work with the server only engine api and additional the /packages/@stealify/engine-desktop package can be used to add the full headless and desktop capabilitys directly to NodeJS if it is a current NodeJS Version. 

## Note
On OS like IOS / Android or Fuchsia is no engine-desktop support as it does not fit into the UI Concept of this Operating Systems
The Genral way to Creat Apps with Stealify for mobile like devices is to use the cordova framework for NodeJS and if needed the cordova-nodejs-mobile package from Jaina Systems. The @stealify/engine does not offer you any benefits on such devices as they are not designed for Authoring Stealify Applications they are runner only targets for the @stealify/compiler
