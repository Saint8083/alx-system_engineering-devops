The hosts file is a plain text file that all operating systems use to translate hostnames (also known as web addresses or URLs) into IP addresses. When you type in a hostname, such as wikipedia.org, your system will look into the hosts file to get the IP address needed to connect to the appropriate server.

If you open the hosts file, you'll quickly notice that it doesn't have the directory of the entire internet in there. Instead, there might be just a couple of lines and that's it. What gives?

Turns out, your system will check the hosts file first before looking up a site on the DNS servers defined in your network settings (usually your ISP's DNS servers).
