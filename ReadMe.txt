Cassini Web Server Sample v3.5 README.TXT
------------------------------------------

This Cassini version requires .NET Framework v3.5. 

It was originally downloaded from
http://blogs.msdn.com/dmitryr/archive/2008/10/03/cassini-for-framework-3-5.aspx
then updated to 3.5.0.2 from 
http://blogs.msdn.com/dmitryr/archive/2009/04/23/cassini-support-for-friendly-urls-routing.aspx
by Justin Dearing <zippy1981@gmail.com>. The intention is to make enhancements 
to it to improve upon it.

This sample illustrates using the ASP.NET hosting APIs (System.Web.Hosting)
to create a simple managed Web Server with System.Net APIs.

Changea merged from http://certivision.com/wordpress/?m=201002
* Support for remote connections (addition of optional commandline parameter loopback or any)

New in Cassini v3.5.0.2
* Fix for the default documents

New in Cassini v3.5.0.1
* Support for MVC friendly URLs (directory listing only overrides 404 responses for directories)

New in Cassini v3.5:
* Runs as a single EXE -- does not require an assembly in GAC
* Supported IPv6-only configurations
* Upgraded to support .NET Framework 3.5
* Includes VS project file
* License changed to Ms-PL

Instructions to Run Cassini
---------------------------

Cassini-v35 <physical-path> <port> <virtual-path> [<loopback|any>]
For example:
    Cassini-v35 c:\ 80 /
