# combolists-tools
Toolkit for handling email:pass combolists. || Ensemble d'outils pour gérer les combolists email:pass

## USAGE

  **email.py <combolist_file> <result_file>** : This tool will read and extract all combos from <combolist_file> to <result_file>, creating a maillist from the given combolist.

  **cilter.py <maillist>** : This will sort all emails from <maillist> by domain and put them in the _Domains/_ folder. 
  
  For example, _"Domains/gmail.com"_ will contain emails like xxx@gmail.com, and _"Domains/comcast.net"_ will contain emails like xxx@comcast.net.
  
  **country.py** : This will sort all maillists in the _Domains_ folder by country.  
 
  Let's assume that the content of the _Domains_ folder contains the files _yahoo.co.uk, gmail.com, comcast.net, otakufr.com_.
  After running country.py, _"Domains"_ will contain folders like _Domains/com, Domains/uk and Domains/net_.
  
  ###### Made by m1ckT3sl4 ^_^
