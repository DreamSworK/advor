# Advanced Onion Router

## Description
Advanced Onion Router is a portable client for the OR network and is intended to be an improved alternative for Tor+Vidalia+Privoxy bundle for Windows users. Some of the improvements include UNICODE paths, support for HTTP and HTTPS proxy protocols on the same Socks4/Socks5 port with HTTP header filtering that generates fake identity-dependent headers every time the identity is changed (proxy chains are also supported), support for NTLM proxies, a User Interface that makes Tor's options and actions more accessible, local banlist for forbidden addresses, private identity isolation, a point-and-click process interceptor that can redirect connections from programs that don't support proxies, also giving them fake information about the local system and support for .onion addresses.

Also, it can estimate AS paths for all circuits and prevent AS path intersections, it can restrict circuits to be built using only nodes from different countries, can change circuit lengths and more.

## Features
* Portable: writes settings to application folder, does not write to the system registry
* Read-only mode, when running from read-only media - no files are written
* All configuration files can be encrypted with AES
* All-In-One application - it can replace Tor, Vidalia, Privoxy/Polipo, cntlm, and more
* Supported proxy protocols: Socks5, Socks4, HTTP, HTTPS (all on the same port, autodetected)
* Support for corporate (NTLM) proxies
* Point and click process interceptor that can redirect all connections of a program, disallow non-supported protocols and restrict some information about the local system (fake system time, fake local hostname, etc.)
* Banlist for addresses and routers
* HTTP header filtering that generates fake identity-dependent headers every time the identity is changed
* Circuit builder that allows building circuits by specifying a node list and that can estimate good circuits
* Nodes can be banned / added to favorites from any existing circuit or from router selection dialogs
* Circuit priorities can be changed from the "OR network" page
* AS path estimations for all circuits with the option to build only circuits that don't have AS path intersections
* Avoid using in same circuit nodes from the same countries
* Circuit length is optional and can be changed to have between 1 and 10 routers
* Better isolation between private identities (delete cookies from 5 supported browsers, expire an internal cookie cache, delete Flash/Silverlight cookies, generate new fake browser identity information, and more)
* A list of favorite processes that can be started and intercepted at startup
* All child processes created by a process that is intercepted are also intercepted
* Plugin support
* Hot keys
* Multi-language support
* Onion address generator that can generate .onion addresses with a given prefix
* Automatic IP / identity changes that can use a configurable exit selection algorithm