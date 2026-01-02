# altiboks_UDMP
Oppskrift på oppsett av altiboks mot Unifi Dream Machine Pro

Innledning

Altiboks distribuerer internett over VLAN 102. Vedlagt følger de viktigste innstillingene som må settes på UDM Pro. Skjermbilder tatt November 2023. Dette omhandler kun internett, ikke IPTV.

## Generelle nettverksinnstillinger:
![Dream Machine Pro](Dream%20machine%20pro.png)

IPV6 forklaring: https://help.ui.com/hc/en-us/articles/115005868927-UniFi-Gateway-Static-IPv6-and-DHCPv6-Prefix-Delegation

## Innstillinger på ditt nettverk:
![Nettverk](Nettverk.png)
## Klone macadressen fra Altiboks sin ruter
![Altiboks](Altiboks.png)

Forklaring SLAAC: https://www.networkacademy.io/ccna/ipv6/stateless-address-autoconfiguration-slaac

Anbefalte offentlige DNS-servere:

    Google: 8.8.8.8 & 8.8.4.4.
    Quad9: 9.9.9.9 & 149.112.112.112.
    OpenDNS: 208.67.222.222 & 208.67.220.220.
    Cloudflare: 1.1.1.1 & 1.0.0.1.
    CleanBrowsing: 185.228.168.9 & 185.228.169.9.
    Alternate DNS: 76.76.19.19 & 76.223.122.150.
    AdGuard DNS: 94.140.14.14 & 94.140.15.15.

Cloudflare og sikkert andre har local peering i Oslo om du bor i umiddelbar nærhet til hovedstaden kan man vurdere også å sette custom dns og velge en av de i listen over. For de i Nor-Norge så vil det i de aller fleste tilfellene være fornuftig å la DNS stå til auto.

IPV6 forklaring: https://help.ui.com/hc/en-us/articles/115005868927-UniFi-Gateway-Static-IPv6-and-DHCPv6-Prefix-Delegation

## Tilleggsinformasjon:

Om du tidligere har hatt din UDM bak ruter fra altiboks, kan det være behov for å klone MAC, sen lengre opp hvordan du finner den hos Altiboks
 


Kilder:


* https://www.diskusjon.no/topic/1886075-ubiquiti-dream-machine-pro-mot-altibox-fiber/#comment-25607541

* https://www.diskusjon.no/topic/1886075-ubiquiti-dream-machine-pro-mot-altibox-fiber/page/3/#comment-26013562

* https://www.diskusjon.no/topic/1886075-ubiquiti-dream-machine-pro-mot-altibox-fiber/page/5/#comment-26509430

* https://www.diskusjon.no/topic/1886075-ubiquiti-dream-machine-pro-mot-altibox-fiber/page/6/#comment-26622994

* https://www.altibox.no/privat/kundeservice/hjelp-til-internett/hjemmesentral/vmg-2/

* https://www.diskusjon.no/topic/1886075-ubiquiti-dream-machine-pro-mot-altibox-fiber/page/7/#comment-26821629

* https://www.diskusjon.no/topic/1886075-ubiquiti-dream-machine-pro-mot-altibox-fiber/page/7/#comment-26822606
