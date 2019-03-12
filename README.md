# NessusDebugParser_powershell
This powershell script will input a Nessus Debug file (bin/hex), parse it for various Plugins and output to a csv format. 
The output columns will include:

IP Address	Scan Last Observed	Scan Duration	Credentialed Scan	Scan Repository	Scanner IP	Credentialed CK	Scan Policy	Route Last Observed	Route Repository	Hops	Hop IPs	OS	OS ConLevel	OS Method	OS Last Observed
192.168.0.1	Jan 24, 2019 19:09:46 UTC	1825	TRUE	Individual Scan	192.168.0.30	Yes	aa9c4b8a-5ba7-5d18-b216-19c0a1a2388a-5149394/ACAS - Vulnerability Scan Policy V1.5 - Max Hosts:  10	Jan 24, 2019 19:09:46 UTC	Individual Scan	2	"
192.168.5.1
10.198.78.116 
137.198.10.28"	Microsoft Windows 10 Enterprise	100	SMB_OS	Jan 24, 2019 19:09:46 UTC
192.168.0.2	Jan 24, 2019 19:09:46 UTC	1418	TRUE	Individual Scan	192.168.0.31	Yes	aa9c4b8a-5ba7-5d18-b216-19c0a1a2388a-5149394/ACAS - Vulnerability Scan Policy V1.5 - Max Hosts:  10	Jan 24, 2019 19:09:46 UTC	Individual Scan	2	"
192.198.78.118 
10.198.78.116 
138.198.10.1"	Microsoft Windows 10 Enterprise	100	SMB_OS	Jan 24, 2019 19:09:46 UTC
192.168.0.3	Jan 24, 2019 19:09:46 UTC	1703	TRUE	Individual Scan	192.168.0.32	Yes	aa9c4b8a-5ba7-5d18-b216-19c0a1a2388a-5149394/ACAS - Vulnerability Scan Policy V1.5 - Max Hosts:  10	Jan 24, 2019 19:09:46 UTC	Individual Scan	2	"
5.198.78.118 
10.198.78.116 
192.198.11.25"	Microsoft Windows 10 Enterprise	100	SMB_OS	Jan 24, 2019 19:09:46 UTC
192.168.0.4	Jan 24, 2019 19:09:46 UTC	1700	TRUE	Individual Scan	192.168.0.33	Yes	aa9c4b8a-5ba7-5d18-b216-19c0a1a2388a-5149394/ACAS - Vulnerability Scan Policy V1.5 - Max Hosts:  10	Jan 24, 2019 19:09:46 UTC	Individual Scan	2	"
10.198.78.1 
10.198.78.5
10.2822.3"	Microsoft Windows 10 Enterprise	100	SMB_OS	Jan 24, 2019 19:09:46 UTC
192.168.0.5	Jan 24, 2019 19:09:46 UTC	1939	TRUE	Individual Scan	192.168.0.34	Yes	aa9c4b8a-5ba7-5d18-b216-19c0a1a2388a-5149394/ACAS - Vulnerability Scan Policy V1.5 - Max Hosts:  10	Jan 24, 2019 19:09:46 UTC	Individual Scan	2	"
2.2.78.15 
4.28.78.6
12.18.1.8"	Microsoft Windows 10 Enterprise	100	SMB_OS	Jan 24, 2019 19:09:46 UTC
192.168.0.6	Jan 24, 2019 19:09:46 UTC	1725	TRUE	Individual Scan	192.168.0.35	Yes	aa9c4b8a-5ba7-5d18-b216-19c0a1a2388a-5149394/ACAS - Vulnerability Scan Policy V1.5 - Max Hosts:  10	Jan 24, 2019 19:09:46 UTC	Individual Scan	2	"
14.18.78.19 
17.23.78.11 
17.1.13.12"	Microsoft Windows 10 Enterprise	100	SMB_OS	Jan 24, 2019 19:09:46 UTC

