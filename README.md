<h1 align=center>TTL-Changer</h1>
<br>
<img src="/cmd.jpg">
<h2>What is TTL?</h2>
<p>TTL (Time to Live) - the lifetime of the packets that are transmitted over the network.</p>
<br>
<h2>What is TTL?</h2>
<p>First, let's understand what it is. The TTL (Time to Live) is the lifetime of the packets which are transmitted over the network. Each packet contains a certain amount of information. After the specified time has elapsed the packet is discarded, even if it has not yet reached its destination, which in turn makes it possible for the data not to "walk" around the network forever. Packet lifetime is not measured in seconds but in hops. The hop limit determines how many sections between routers one packet can go through. The maximum number of hops is 255. 
</p>
<br>
<h2>How do I know the TTL on my device?</h2>
<p>Before you can change the TTL, you need to know what value is currently set on the device. To do this, you will need to use the command line with administrator privileges. <br>
1. Using the built-in Windows 10 search, find the "Command Prompt" application. <br>
2. Right-click on it and select "Run as administrator". <br>
3. Type in ping 127.0.0.1 and hit Enter. <br>
4. After the network status analysis is complete, we will get the packet exchange data, which will contain the TTL.<br>
</p>
<br>
<h2>Why would you change the TTL?</h2>
<p>By changing the TTL you can bypass the restrictions of mobile operators to distribute mobile Internet.</p>
<br>
<h2>To change TTL you only need to execute of one bat files. No need to restart of logout!</h2>
