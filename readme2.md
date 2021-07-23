1.Код состояния HTTP 301 или Moved Permanently (с англ. — «Перемещено навсегда») — стандартный код ответа HTTP, получаемый в ответ от сервера в ситуации, когда запрошенный ресурс был на постоянной основе перемещён в новое месторасположение, и указывающий на то, что текущие ссылки, использующие данный URL, должны быть обновлены. 


2.Status code 200. OK — успешный запрос. Время загрузки страницы примерно 2280 мс. Дольше всего обрабатывается первый запрос stackoverflow.com - 871.15 мс.


3.  95.79.111.239


4. Дом.ру AS42682


5.[sa@localhost bin]$ traceroute -An 8.8.8.8

traceroute to 8.8.8.8 (8.8.8.8), 30 hops max, 60 byte packets

 1  172.29.16.1 [*]  0.724 ms  0.690 ms  0.671 ms
 
 2  10.0.0.1 [*]  12.008 ms  12.343 ms  11.728 ms
 
 3  95.79.111.239 [AS42682]  14.532 ms  14.291 ms  14.319 ms
 
 4  91.144.185.248 [AS42682]  15.256 ms  15.804 ms  15.771 ms
 
 5  188.234.131.145 [AS9049]  22.293 ms  24.717 ms  22.205 ms
 
 6  188.234.131.144 [AS9049]  22.924 ms  15.080 ms  15.175 ms
 
 7  10.23.173.254 [*]  14.879 ms 10.23.174.126 [*]  17.898 ms 10.23.172.62 [*]  34.598 ms
 
 8  108.170.225.44 [AS15169]  15.866 ms 216.239.46.254 [AS15169]  19.310 ms 64.233.174.218 [AS15169]  34.308 ms
 
 9  108.170.250.83 [AS15169]  17.804 ms 108.170.250.130 [AS15169]  19.259 ms 108.170.250.146 [AS15169]  34.507 ms

10  142.251.49.24 [AS15169]  27.554 ms  46.274 ms *

11  209.85.254.6 [AS15169]  27.538 ms 172.253.65.159 [AS15169]  34.175 ms  25.868 ms

12  108.170.233.161 [AS15169]  25.153 ms 172.253.64.113 [AS15169]  26.489 ms 108.170.233.163 [AS15169]  29.760 ms

13  * * *
14  * * *
15  * * *
16  * * *
17  * * *
18  * * *
19  * * *
20  * * *
21  * * *

22  8.8.8.8 [AS15169]  29.727 ms  24.146 ms  25.039 ms



6.Наибольшая задержка на участке  11. AS15169 172.253.65.82 11.5% . В трассировке этого адреса нет - видимо поменялся маршрут.


7. 			27311	IN	NS	a.root-servers.net.

.			27311	IN	NS	b.root-servers.net.

.			27311	IN	NS	c.root-servers.net.

.			27311	IN	NS	d.root-servers.net.

.			27311	IN	NS	e.root-servers.net.

.			27311	IN	NS	f.root-servers.net.

.			27311	IN	NS	g.root-servers.net.

.			27311	IN	NS	h.root-servers.net.

.			27311	IN	NS	i.root-servers.net.

.			27311	IN	NS	j.root-servers.net.

.			27311	IN	NS	k.root-servers.net.

.			27311	IN	NS	l.root-servers.net.

.			27311	IN	NS	m.root-servers.net.

.			27311	IN	RRSIG	NS 8 0 518400 20210728200000 20210715190000 26838 . R3zS0Mw1XpI4He4LfLH+VzNkAnfXB6hljW/d6jrOQE3SgONaiRQ8q+Ha 3Xu3BXmLsGuU7LCKzdZZaYUKscj1OC7bYGlSV+6k8d+9d8WhrH6ZVFQY Y4OjB/o2F9GHjeIBLiFuBG61Ex1fr+35jct/ob7fegyQ5NDYUaMC6ueI XKQmBgjlJaDu7KEbyiw1dHVqjJZY7xCOqA9G7ZsDMtFwlif6KCuuo/Xu XUgsh2OK4GgKJryshp87vGUwsWIbMz50W6vWu4P3AeKx+JhlUIaPBJyp 0rqawkOol+ilJgCqVqV2xYUcAgV5t6hCB4pW6zZ/dJ6JraGR8Ai4yKDc 9moYXw==

;; Received 525 bytes from 8.8.8.8#53(8.8.8.8) in 42 ms

google.			172800	IN	NS	ns-tld1.charlestonroadregistry.com.

google.			172800	IN	NS	ns-tld2.charlestonroadregistry.com.

google.			172800	IN	NS	ns-tld3.charlestonroadregistry.com.

google.			172800	IN	NS	ns-tld4.charlestonroadregistry.com.

google.			172800	IN	NS	ns-tld5.charlestonroadregistry.com.

google.			86400	IN	DS	6125 8 2 80F8B78D23107153578BAD3800E9543500474E5C30C29698B40A3DB2 3ED9DA9F

google.			86400	IN	RRSIG	DS 8 1 86400 20210729050000 20210716040000 26838 
. c/XFz8ndNvlAqf1wfFUsL03ieHs6lFpl+uQLVLaxNN3TWvmnD3tjJ+L+ 
A2Xk2zzTdL/7pWsamwAwtlCujzaqGUmoFnOfMH9PZvcTD42mia/Hzvm9 1xMH6cgKq5a/81UTexCGUUxXbeDxG0SU5eJ8OeMMw74YziAhzo2mu9eE exITxakQQ5kYnCFJNGguTSbxR7yM7S4sGtNHLh3zDloLP81XzluE+ut5 pObkXEPjHwyrDkyOSGN8SsxQUQ9cAQDABN6i+24ZP5//iYE94WjtX8CX hWaoHB5a3yfclhh5wdeZHu5WiJf/R07YTDAR/PFQCcWH79WgPxTCak9N ku2ejg==

;; Received 730 bytes from 199.7.91.13#53(d.root-servers.net) in 48 ms

dns.google.		10800	IN	NS	ns4.zdns.google.

dns.google.		10800	IN	NS	ns3.zdns.google.

dns.google.		10800	IN	NS	ns2.zdns.google.

dns.google.		10800	IN	NS	ns1.zdns.google.

dns.google.		3600	IN	DS	56044 8 2 1B0A7E90AA6B1AC65AA5B573EFC44ABF6CB2559444251B997103D2E4 0C351B08

dns.google.		3600	IN	RRSIG	DS 8 2 3600 20210804202730 20210713202730 7144 google. 

L53w0/sRmCMcCf1fn6lBmulYuSY061uUoGkM/1moZ4bjeUxxketoQV7+ 
xqhqp9mSfPFSc8iJIAr2tSp2btWrfA/9JmshQF0plp1Gj47DHnbPH7cy 2ThP8R9WHKOUqkqe8vNks06hbsOdvk61y4PxLoc5pCtlijb4ZuLRchWA CMo=
;; Received 506 bytes from 216.239.36.105#53(ns-tld3.charlestonroadregistry.com) in 27 ms


dns.google.		900	IN	A	8.8.8.8

dns.google.		900	IN	A	8.8.4.4



8. 4.4.8.8.in-addr.arpa.	0	IN	PTR	dns.google.

   8.8.8.8.in-addr.arpa.	0	IN	PTR	dns.google.



 
