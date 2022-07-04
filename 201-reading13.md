# Local Storage and How to Use it on Websites

1. The main problem with HTTP as the main transport layer of the Web is that it is stateless. This means that when you use an application and then close it, its state will be reset the next time you open it. If you close an application on your desktop and re-open it, its most recent state is restored. This is why, as a developer, you need to store the state of your interface somewhere. Normally, this is done server-side, and you would check the user name to know which state to revert to

2. Objects as their data will not be stored correctly

3. Only strings can be stored in Local Storage. A way around this is by using the native JSON.stringify() and JSON.parse() methods

