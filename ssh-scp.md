# SSH and SCP

## Ssh is a tool that you can use for connecting remote linux servers.  You can find more detailed information on ssh's original webpage, You can install ssh client has been already enabled by default, you can

[Ssh documentation](https://www.ssh.com/academy/ssh)

- ssh USERNAME@SERVERIPADDRESS -p 22
  - p : PORT

## Scp is a  command line tool that you can use for copy files from your local windows to remote server. It is very straight forward tools, you could use

- scp -P 419 "LOCAL FILE(S)" "REMOTE PATH"
  - p : PORT