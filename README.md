EPSG.io
=======

SpatialReference - transformace souřadnicových systémů používaných na našem území. Nýní služba běží na http://epsg.io/. Původně běžela na http://spatialreference.mzk.cz/.

Software vznikl díky projektu TEMAP (DF11P01OVV003), který se uskutečňuje díky laskavé podpoře Programu aplikovaného výzkumu a vývoje národní a kulturní identity NAKI.

EPSG.io napomáhá nalézt souřadnicové systémy používáné po celém světě pro vytváření map a geodat.

S jednoduše použitelnou mapovou aplikací je možné si zvolit jakýkoliv bod na planetě a transformovat souřadnice mezi zeměpisnou šířkou a délkou (WGS84) a vybraným referenčním systémem souřadnic - a přitom zobrazit toto místo na mapě.

Každý souřadnicový systém a transformace má krátký trvalý odkaz a je možné jej exportovat ve zvoleném formátu (WKT, XML, OGC GML, Proj4, JavaScript, SQL).

Webové rozhraní je postaveno na fulltextovém vyhledávání, které indexuje oficiální EPSG databázi plnou detailních geodetických dat z celé řady zdrojů a autorit. EPSG.io zjednodušuje přístup k přesným geodetickým parameterům pro tisíce souřadnicových referenčních systémů a geodických datumů, pro atributy transformací, elipsoidů, nultých poledníků, atd. Jedná se tedy o praktický nástroj pro kohokoliv, kdo se zajímá o kartografii a tvorbu map.


Instalace
---------

```
$ virtualenv venv
$ source venv/bin/activate
$ pip install -r requirements.txt
```
