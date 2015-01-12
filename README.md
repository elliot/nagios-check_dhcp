# Windows Server DHCP Monitoring

A set of Powershell NRPE checks for Windows DHCP Servers.


## Usage

#### Scope Usage
   ```check_dhcp_scopes.ps1 -Warning <85> -Critical <95>```

## Limitations

Only supports IPv4 scopes at this time, but IPv6 can be supported by changing the cmdlets to their IPv6 counterparts. (```s/Get-DhcpServerv4/Get-DhcpServerv6/```)

## Author

Elliot Anderson ([Email](mailto:elliot.a@gmail.com), [Twitter](http://www.twitter.com/elliotanderson))

## License

This project is licensed under the MIT license.
