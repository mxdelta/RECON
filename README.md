# RECON

https://чатгпт-в-россии.рф/   (чат жпт по русски)


«ключевое слово» site:domain.com — ищем ключевые слова на сайте

 @domain.com site:domain.com можно собрать адреса с доменным именем domain.com
 
 filetype:pdf site:domain.com  Ищем файлы на определённом сайте с помощью Google: «ключевое слово»
 
 https://www.tutorialspoint.com/google_hacking_tests.htm (автоматический посик всех запросов в гугл доркс)

 https://dnsdumpster.com/#hostanchor (поиск всех запросов nslookup)

 theHarvester -d yandex.ru -b all    (поиск поддоменов)
 
 (baidu,bing,bingapi,bufferoverun,certspotter,crtsh,dnsdumpster,duckduckgo,exalead,github-code,google,hackertarget,hunter,intelx,linkedin,linkedin_links,netcraft,otx,pentesttools,projectdiscovery,qwant,rapiddns,securityTrails,spyse,sublist3r,threatcrowd,threatminer,trello,twitter,urlscan,virustotal,yahoo)

sublist3r -d "yandex.ru" -v -t 2      (поиск поддоменов)



Censys и Shodan подскажут о сетевой информации (открытые порты), баннерах и ответах веб-сервера, Sublist3r и DNSDumpster помогут найти поддомены. Используя Google dorks можно найти все doc-файлы, доступные на веб-ресурсе (если их индексирование не запрещено в явном виде в robots.txt)

Для Censys:  

https://search.censys.io/search/definitions?resource=hosts&q=services.port%3A+445+banner.version%3ASMB+1+and+location.country_code%3ARU&sort=RELEVANCE&per_page=25&virtual_hosts=EXCLUDE    (справка)

services.port: 445 and services.banner: "SMB 1.0" and location.country_code:RU
services.port: 445 and services.banner: "SMB 1.0" and location.country_code:RU
