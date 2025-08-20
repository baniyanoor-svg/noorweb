# 1)IP Address
    a)Type nslookup in terminal.
    b)Check DNS IP Address.
 # 2)DNS server
    a)Type scutil--dns in terminal.
    b)Check DNS server IP address.
  # 3)Checking the status codes 
    a)Open Developer Tools (Ctrl+Shift+I).
    b)Select the Networks.
    c)Click on the request you want inspect.
  # 4)Changing your DNS server
     a)Open system settings(network).
     b)Select your active network (wifi).
     c)Click details(DNS).
     d)Remove old entries and add:
      Google DNS: 8.8.8.8 and 8.8.4.4
       Cloudflare DNS: 1.1.1.1 and 1.0.0.1
      e)Click OK and then apply.
  # 5)Public Available DNS 
     a) Google Public DNS: IPv4 addresses (8.8.8.8 and 8.8.4.4) or IPv6 addresses (2001:4860:4860::8888 and 2001:4860:4860::8844). 
     b) Cloudflare DNS: IPv4 address is 1.1.1.1, and they also offer an IPv6 address, 2606:4700:4700::1111. 
     c) OpenDNS (Cisco): IPv4 208.67.222.222
                             208.67.220.220
                        IPv6 2620:119:35::35
                             2620:119:53::53
