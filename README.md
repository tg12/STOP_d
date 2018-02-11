# STOP_d
SSH/IPTables Country Blocker

Pre Req's

apt-get install prips

Run as root


chmod u+x script1.sh


./script1.sh


Default Country Code is China (cn)


Change it to whatever you like, 


http://www.nationsonline.org/oneworld/country_code_list.htm


It takes a while.

To verify your iptables

iptables -L 

Clear your iptables log with:

sudo tee /var/log/kern.log </dev/null

Once complete, Grep your log files with this simple command

cat /var/log/kern.log | grep STOP_d

..... to see any blocked cyber nastys....


<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=WQ6V6K8ZY6D84">
  <img src="https://www.paypalobjects.com/en_US/GB/i/btn/btn_donateCC_LG.gif" alt="Donate with PayPal" />
</a>
