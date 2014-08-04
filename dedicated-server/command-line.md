---
layout: static
title: ManiaPlanet dedicated server command line
description: FAQ
---


<table>
  <tr>
    <th>Option Name</th><th>Role</th>
  </tr>
  <tr>
    <td>/dedicated_cfg=xxx</td><td>Specify a configuration file "dedicated_cfg.txt" to use. (xxx = name of the file in UserData/Config/)</td>
  </tr>
  <tr>
    <td>/game_settings=xxx </td><td>Specify a match settings file to use. (xxx = absolute file name or relative to UserData/Maps/MatchSettings)</td>
  </tr>
  <tr>
	<td colspan="2"></td>
  </tr>
  <tr>
    <td>/servername=xxx </td><td>Override the server name</td>
  </tr>
  <tr>
	<td colspan="2"></td>
  </tr>
  <tr>
	<td>/login=xxx</td><td>Dedicated login (required for internet server). Create one on your <a href="https://player.maniaplanet.com/advanced/dedicated-servers">PlayerPage</a></td>
  </tr>
  <tr>
	<td>/password=xxx</td><td>Dedicated password (required for internet server)</td>
  </tr>
  <tr>
	<td colspan="2"></td>
  </tr>
  <tr>
    <td>/lan</td><td>Must be specified to join or create a LAN game (that is, not an internet server)</td>
  </tr>
  <tr>
    <td>/forceip=xxx(:xx)</td><td>Forces the public ip address to this value. optionally with a port as well</td>
  </tr>
  <tr>
    <td>/bindip=xxx(:xx)</td><td>Chooses the ip to bind to, and sets the public ip to this value. (you still can use /forceip to chose a different public ip). This is used when the machine has several network interfaces.</td>
  </tr>
  <tr>
    <td>/nodaemon</td><td>(linux) Doesn't automatically detach the process</td>
  </tr>
  <tr>
	<td colspan="2"></td>
  </tr>
  <tr>
	<td>/loadcache</td><td>Loads the "checksum.txt" instead of recomputing it, to speed up first launch time if P2P is enabled. *DO NOT USE* if you run several servers in the same directory!</td>
  </tr>
  <tr>
	<td>/nologs</td><td>Disables the creation of "GameLog.txt" and "ConsoleLog.txt" in Logs/ directory.</td>
  </tr>
  <tr>
	<td>/noautoquit</td><td>Keeps the server running "waiting for rpc commands", even if it is not live (with a map loaded and ready to receive players). The default behaviour is to quit, because this situation is mostly caused by configuration errors</td>
  </tr>
  <tr>
	<td colspan="2"></td>
  </tr>
  <tr>
    <td>/verbose_rpc_full</td><td>(Debug option) Display the whole contents of the xml-rpc requests the dedicated server receives</td>
  </tr>
  <tr>
    <td>/verbose_rpc </td><td>(Debug option) Displays the xml-rpc requests the dedicated server receives, but only the name of the XmlRpc? command and some parameters</td>
  </tr>
  <tr>
	<td colspan="2"></td>
  </tr>
  <tr>
	<td>/spectate=xxx</td><td>Joins a server as spectator. (xxx = the server ip adress with optional port, or the server login.) (this is used to start a relay server)</td>
  </tr>
  <tr>
	<td>/serverpassword=xxx</td><td>Password to use to join the server if the server is private</td>
  </tr>
</table>

 
