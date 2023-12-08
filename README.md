<center>

# V2IpLimit
For Marzban, In the v2_ip_limit.py file I added these four lines of code that helps disconnecting the users from the banned account immediately. (in the marzban folder readme you can see that it explains that users may not disconnect immediately, but if we restart the marzban, they will. so I added these lines to the .py file:
    a = 'marzban restart'
    b = os.popen(a,'w')
    print(b)
    time.sleep(5)
<hr>

<b>Limiting the number of active users with IP</b><sub> (with xray logs)</sub>
<br>Currently only tested with
<br>[Marzban](https://github.com/Gozargah/Marzban) And [V2RayGen](https://github.com/SonyaCore/V2RayGen)

<b>

[Go to Marzban Version](Marzban/README.md) ♦️
[Go to V2RayGen Version](V2RayGen/README.md)

</b>

<hr>

### Donation

</center>
If you found V2IpLimit useful and would like to support its development, you can donate on the following crypto network:

- TRON network (TRX): `TLARb1Ns5vA7pH6wqSyZGreDbGooS85Mi5`

Thank you for your support!

<hr>

<b>
If this program was useful for you, please give it a star ⭐
</b>
