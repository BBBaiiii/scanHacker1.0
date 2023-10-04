# scanHacker1.0
Super port scanner based on Golang.

Usage: ./scanHacker [options]

Designed by BBBaiiii 

Options:

  -f string
        File containing IP addresses (one per line),The value can be IP or CIDR
        
  -ip string
        Host IP address or CIDR range,-ip 10.0.0.1 or -ip 10.0.0.0/24
        
  -p string
        Port range (e.g.,-p 1,2,3,4,1-65535) (default "22,80,443,3306")
        
  -rate int
         Maximum concurrent thread to run at a time (default 10000)
