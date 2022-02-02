# NixCan
Linpeas Optimization Tool

NixCan helps consolidate the Linpeas scan results so you see the most critical vulnerablities. The script will automatically download linpeas.sh onto your system, run it, sort the output, and create two files for your reference. One of these files will be the total output of Linpeas, and the other will contain only critical vulnerabilities and their corresponding line number in case you need to find them in the larger file. As NixCan is wrapping up, it will remove linpeas.sh from your system, leaving you only with the scan results that you were looking for. 

***Contributors: ZikNik, taplummer, timchancyber***

***NOTE: On some distros, the initial version ("NixCan") will not work. It is advised that you run the newer version ("nixcan")***
## Using This Tool

```git clone https://github.com/ZikNik/NixCan.git```

```chmod +x nixcan```

```./nixcan```
