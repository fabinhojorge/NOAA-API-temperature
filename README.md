# NOAA-API-temperature
API para dados de temperatura da Base do NOAA (Aeroportos)



# Código ICAO de Aeroportos Brasileiros
[https://pt.wikipedia.org/wiki/C%C3%B3digos_ICAO_de_aeroportos_brasileiros](https://pt.wikipedia.org/wiki/C%C3%B3digos_ICAO_de_aeroportos_brasileiros)

http://tgftp.nws.noaa.gov/data/observations/metar/


# Aparentemente esta informação é atualizada varias vezes por dia. Não se sabe a frequencia nem o horário. 

"http://tgftp.nws.noaa.gov/data/observations/metar/stations/" + ICAO + ".TXT"

# Exemplo de request:
http://tgftp.nws.noaa.gov/data/observations/metar/decoded/SBBH.TXT
"
Belo Horizonte Aeroporto , Brazil (SBBH) 19-51S 043-57W 785M
Jun 19, 2017 - 07:00 PM EDT / 2017.06.19 2300 UTC
Wind: from the NE (050 degrees) at 1 MPH (1 KT):0
Visibility: greater than 7 mile(s):0
Temperature: 60 F (16 C)
Dew Point: 53 F (12 C)
Relative Humidity: 77%
Pressure (altimeter): 30.15 in. Hg (1021 hPa)
ob: SBBH 192300Z 05001KT CAVOK 16/12 Q1021
cycle: 23
"



# Outras opções/Sugestões:
- http://servicos.cptec.inpe.br/XML/#req-estacoes-meteorologicas
