# cnpj2sql

Scripts PHP para download da base de dados do CNPJ da receita federal e conversão em arquivos SQL para importação em banco de dados MySQL.

Esse projeto visa fazer o download da base da dados de CNPJ da receita federal diretamente através do portal dados abertos, utilizando o wget na função mirror.
Após o download será feita a descompactação dos arquivos zip, seguidos alteração da codificação de caracteres para UTF8.
Um Script PHP (cli) será usado para montar os arquivos SQL a partir dos arquivos CSV.

## Por que PHP?

Optei por usar PHP no modo command line interface (cli) visto que não é uma linguagem fortemente tipada e facilita a conversão de dados necessária para o formato banco de dados proposto aqui.

# Como usar

```bash
./download_cnpj.sh
```

```bash
./converter_cnpj.sh
```

# Requisitos

- wget2
- unzip
- php-cli

## Licença GNU GPL v3

Você pode fazer quase qualquer coisa que você queira com esse projeto, exceto distribuir o código fonte em projetos de código fechado.

## Dúuvidas sobre o projeto

O projeto foi desenvolvido para fins de estudo e prova de conceito. O projeto está disponibilizado como está, sem garantias de funcionamento. Devido ao meu tempo limitado e compromisso com outros projetos somente poderei prestar qualquer tipo de auxilio mediante compensação financeira, caso seja de seu interesse entrar em contato [via telegram](https://t.me/r3n4t0), somente tenho condições de responder texto e não sou capaz ouvir mensagens de áudio.

## Contribuições

### Com o código

Se você quiser contribuir com o código, você pode fazer um fork do projeto e enviar um pull request.

### Financeiras

Se esse projeto te auxiliou de alguma forma, você pode contribuir financeiramente para que eu possa continuar a desenvolver projetos open source. As contribuições podem ser:

# PIX:
    b230c7a8-8743-459f-bae5-541ea46a3533

![302100763-dc530122-d9fb-41e4-9edf-dc9c32e74adc](https://github.com/fredroo/cnpj2sql/assets/6863089/1a6505e5-5039-4609-87af-ba84f03d4b08)

        DOMINGO
        SEGUNDA-FEIRA
        TERÇA-FEIRA
        QUARTA-FEIRA
        QUINTA-FEIRA
        SEXTA-FEIRA
        SÁBADO
        JANEIRO, FEVEREIRO, MARÇO, ABRIL, MAIO, JUNHO, JULHO, AGOSTO, SETEMBRO, OUTUBRO, NOVEMBRO, DEZEMBRO DE 2024, 2025, 2026
        Janeiro 
        Fevereiro
        Março
        Abril
        Maio
        Junho
        Julho
        Agosto
        Setembro
        Outubro
        Novembro
        Dezembro


COD UF,COD,NOME
11,1100015,Alta Floresta D'oeste
11,1100023,Ariquemes
11,1100031,Cabixi
11,1100049,Cacoal
11,1100056,Cerejeiras
11,1100064,Colorado do Oeste
11,1100072,Corumbiara
11,1100080,Costa Marques
11,1100098,Espigão D'oeste
11,1100106,Guajará-Mirim
11,1100114,Jaru
11,1100122,Ji-Paraná
11,1100130,Machadinho D'oeste
11,1100148,Nova Brasilândia D'oeste
11,1100155,Ouro Preto do Oeste
11,1100189,Pimenta Bueno
11,1100205,Porto Velho
11,1100254,Presidente Médici
11,1100262,Rio Crespo
11,1100288,Rolim de Moura
11,1100296,Santa Luzia D'oeste
11,1100304,Vilhena
11,1100320,São Miguel do Guaporé
11,1100338,Nova Mamoré
11,1100346,Alvorada D'oeste
11,1100379,Alto Alegre dos Parecis
11,1100403,Alto Paraíso
11,1100452,Buritis
11,1100502,Novo Horizonte do Oeste
11,1100601,Cacaulândia
11,1100700,Campo Novo de Rondônia
11,1100809,Candeias do Jamari
11,1100908,Castanheiras
11,1100924,Chupinguaia
11,1100940,Cujubim
11,1101005,Governador Jorge Teixeira
11,1101104,Itapuã do Oeste
11,1101203,Ministro Andreazza
11,1101302,Mirante da Serra
11,1101401,Monte Negro
11,1101435,Nova União
11,1101450,Parecis
11,1101468,Pimenteiras do Oeste
11,1101476,Primavera de Rondônia
11,1101484,São Felipe D'oeste
11,1101492,São Francisco do Guaporé
11,1101500,Seringueiras
11,1101559,Teixeirópolis
11,1101609,Theobroma
11,1101708,Urupá
11,1101757,Vale do Anari
11,1101807,Vale do Paraíso
12,1200013,Acrelândia
12,1200054,Assis Brasil
12,1200104,Brasiléia
12,1200138,Bujari
12,1200179,Capixaba
12,1200203,Cruzeiro do Sul
12,1200252,Epitaciolândia
12,1200302,Feijó
12,1200328,Jordão
12,1200336,Mâncio Lima
12,1200344,Manoel Urbano
12,1200351,Marechal Thaumaturgo
12,1200385,Plácido de Castro
12,1200393,Porto Walter
12,1200401,Rio Branco
12,1200427,Rodrigues Alves
12,1200435,Santa Rosa do Purus
12,1200450,Senador Guiomard
12,1200500,Sena Madureira
12,1200609,Tarauacá
12,1200708,Xapuri
12,1200807,Porto Acre
13,1300029,Alvarães
13,1300060,Amaturá
13,1300086,Anamã
13,1300102,Anori
13,1300144,Apuí
13,1300201,Atalaia do Norte
13,1300300,Autazes
13,1300409,Barcelos
13,1300508,Barreirinha
13,1300607,Benjamin Constant
13,1300631,Beruri
13,1300680,Boa Vista do Ramos
13,1300706,Boca do Acre
13,1300805,Borba
13,1300839,Caapiranga
13,1300904,Canutama
13,1301001,Carauari
13,1301100,Careiro
13,1301159,Careiro da Várzea
13,1301209,Coari
13,1301308,Codajás
13,1301407,Eirunepé
13,1301506,Envira
13,1301605,Fonte Boa
13,1301654,Guajará
13,1301704,Humaitá
13,1301803,Ipixuna
13,1301852,Iranduba
13,1301902,Itacoatiara
13,1301951,Itamarati
13,1302009,Itapiranga
13,1302108,Japurá
13,1302207,Juruá
13,1302306,Jutaí
13,1302405,Lábrea
13,1302504,Manacapuru
13,1302553,Manaquiri
13,1302603,Manaus
13,1302702,Manicoré
13,1302801,Maraã
13,1302900,Maués
13,1303007,Nhamundá
13,1303106,Nova Olinda do Norte
13,1303205,Novo Airão
13,1303304,Novo Aripuanã
13,1303403,Parintins
13,1303502,Pauini
13,1303536,Presidente Figueiredo
13,1303569,Rio Preto da Eva
13,1303601,Santa Isabel do Rio Negro
13,1303700,Santo Antônio do Içá
13,1303809,São Gabriel da Cachoeira
13,1303908,São Paulo de Olivença
13,1303957,São Sebastião do Uatumã
13,1304005,Silves
13,1304062,Tabatinga
13,1304104,Tapauá
13,1304203,Tefé
13,1304237,Tonantins
13,1304260,Uarini
13,1304302,Urucará
13,1304401,Urucurituba
14,1400027,Amajari
14,1400050,Alto Alegre
14,1400100,Boa Vista
14,1400159,Bonfim
14,1400175,Cantá
14,1400209,Caracaraí
14,1400233,Caroebe
14,1400282,Iracema
14,1400308,Mucajaí
14,1400407,Normandia
14,1400456,Pacaraima
14,1400472,Rorainópolis
14,1400506,São João da Baliza
14,1400605,São Luiz
14,1400704,Uiramutã
15,1500107,Abaetetuba
15,1500131,Abel Figueiredo
15,1500206,Acará
15,1500305,Afuá
15,1500347,Água Azul do Norte
15,1500404,Alenquer
15,1500503,Almeirim
15,1500602,Altamira
15,1500701,Anajás
15,1500800,Ananindeua
15,1500859,Anapu
15,1500909,Augusto Corrêa
15,1500958,Aurora do Pará
15,1501006,Aveiro
15,1501105,Bagre
15,1501204,Baião
15,1501253,Bannach
15,1501303,Barcarena
15,1501402,Belém
15,1501451,Belterra
15,1501501,Benevides
15,1501576,Bom Jesus do Tocantins
15,1501600,Bonito
15,1501709,Bragança
15,1501725,Brasil Novo
15,1501758,Brejo Grande do Araguaia
15,1501782,Breu Branco
15,1501808,Breves
15,1501907,Bujaru
15,1501956,Cachoeira do Piriá
15,1502004,Cachoeira do Arari
15,1502103,Cametá
15,1502152,Canaã dos Carajás
15,1502202,Capanema
15,1502301,Capitão Poço
15,1502400,Castanhal
15,1502509,Chaves
15,1502608,Colares
15,1502707,Conceição do Araguaia
15,1502756,Concórdia do Pará
15,1502764,Cumaru do Norte
15,1502772,Curionópolis
15,1502806,Curralinho
15,1502855,Curuá
15,1502905,Curuçá
15,1502939,dom Eliseu
15,1502954,Eldorado do Carajás
15,1503002,Faro
15,1503044,Floresta do Araguaia
15,1503077,Garrafão do Norte
15,1503093,Goianésia do Pará
15,1503101,Gurupá
15,1503200,Igarapé-Açu
15,1503309,Igarapé-Miri
15,1503408,Inhangapi
15,1503457,Ipixuna do Pará
15,1503507,Irituia
15,1503606,Itaituba
15,1503705,Itupiranga
15,1503754,Jacareacanga
15,1503804,Jacundá
15,1503903,Juruti
15,1504000,Limoeiro do Ajuru
15,1504059,Mãe do Rio
15,1504109,Magalhães Barata
15,1504208,Marabá
15,1504307,Maracanã
15,1504406,Marapanim
15,1504422,Marituba
15,1504455,Medicilândia
15,1504505,Melgaço
15,1504604,Mocajuba
15,1504703,Moju
15,1504752,Mojuí dos Campos
15,1504802,Monte Alegre
15,1504901,Muaná
15,1504950,Nova Esperança do Piriá
15,1504976,Nova Ipixuna
15,1505007,Nova Timboteua
15,1505031,Novo Progresso
15,1505064,Novo Repartimento
15,1505106,Óbidos
15,1505205,Oeiras do Pará
15,1505304,Oriximiná
15,1505403,Ourém
15,1505437,Ourilândia do Norte
15,1505486,Pacajá
15,1505494,Palestina do Pará
15,1505502,Paragominas
15,1505536,Parauapebas
15,1505551,Pau D'arco
15,1505601,Peixe-Boi
15,1505635,Piçarra
15,1505650,Placas
15,1505700,Ponta de Pedras
15,1505809,Portel
15,1505908,Porto de Moz
15,1506005,Prainha
15,1506104,Primavera
15,1506112,Quatipuru
15,1506138,Redenção
15,1506161,Rio Maria
15,1506187,Rondon do Pará
15,1506195,Rurópolis
15,1506203,Salinópolis
15,1506302,Salvaterra
15,1506351,Santa Bárbara do Pará
15,1506401,Santa Cruz do Arari
15,1506500,Santa Izabel do Pará
15,1506559,Santa Luzia do Pará
15,1506583,Santa Maria das Barreiras
15,1506609,Santa Maria do Pará
15,1506708,Santana do Araguaia
15,1506807,Santarém
15,1506906,Santarém Novo
15,1507003,Santo Antônio do Tauá
15,1507102,São Caetano de Odivelas
15,1507151,São domingos do Araguaia
15,1507201,São domingos do Capim
15,1507300,São Félix do Xingu
15,1507409,São Francisco do Pará
15,1507458,São Geraldo do Araguaia
15,1507466,São João da Ponta
15,1507474,São João de Pirabas
15,1507508,São João do Araguaia
15,1507607,São Miguel do Guamá
15,1507706,São Sebastião da Boa Vista
15,1507755,Sapucaia
15,1507805,Senador José Porfírio
15,1507904,Soure
15,1507953,Tailândia
15,1507961,Terra Alta
15,1507979,Terra Santa
15,1508001,Tomé-Açu
15,1508035,Tracuateua
15,1508050,Trairão
15,1508084,Tucumã
15,1508100,Tucuruí
15,1508126,Ulianópolis
15,1508159,Uruará
15,1508209,Vigia
15,1508308,Viseu
15,1508357,Vitória do Xingu
15,1508407,Xinguara
16,1600055,Serra do Navio
16,1600105,Amapá
16,1600154,Pedra Branca do Amapari
16,1600204,Calçoene
16,1600212,Cutias
16,1600238,Ferreira Gomes
16,1600253,Itaubal
16,1600279,Laranjal do Jari
16,1600303,Macapá
16,1600402,Mazagão
16,1600501,Oiapoque
16,1600535,Porto Grande
16,1600550,Pracuúba
16,1600600,Santana
16,1600709,Tartarugalzinho
16,1600808,Vitória do Jari
17,1700251,Abreulândia
17,1700301,Aguiarnópolis
17,1700350,Aliança do Tocantins
17,1700400,Almas
17,1700707,Alvorada
17,1701002,Ananás
17,1701051,Angico
17,1701101,Aparecida do Rio Negro
17,1701309,Aragominas
17,1701903,Araguacema
17,1702000,Araguaçu
17,1702109,Araguaína
17,1702158,Araguanã
17,1702208,Araguatins
17,1702307,Arapoema
17,1702406,Arraias
17,1702554,Augustinópolis
17,1702703,Aurora do Tocantins
17,1702901,Axixá do Tocantins
17,1703008,Babaçulândia
17,1703057,Bandeirantes do Tocantins
17,1703073,Barra do Ouro
17,1703107,Barrolândia
17,1703206,Bernardo Sayão
17,1703305,Bom Jesus do Tocantins
17,1703602,Brasilândia do Tocantins
17,1703701,Brejinho de Nazaré
17,1703800,Buriti do Tocantins
17,1703826,Cachoeirinha
17,1703842,Campos Lindos
17,1703867,Cariri do Tocantins
17,1703883,Carmolândia
17,1703891,Carrasco Bonito
17,1703909,Caseara
17,1704105,Centenário
17,1704600,Chapada de Areia
17,1705102,Chapada da Natividade
17,1705508,Colinas do Tocantins
17,1705557,Combinado
17,1705607,Conceição do Tocantins
17,1706001,Couto Magalhães
17,1706100,Cristalândia
17,1706258,Crixás do Tocantins
17,1706506,darcinópolis
17,1707009,Dianópolis
17,1707108,Divinópolis do Tocantins
17,1707207,dois Irmãos do Tocantins
17,1707306,Dueré
17,1707405,Esperantina
17,1707553,Fátima
17,1707652,Figueirópolis
17,1707702,Filadélfia
17,1708205,Formoso do Araguaia
17,1708254,Fortaleza do Tabocão
17,1708304,Goianorte
17,1709005,Goiatins
17,1709302,Guaraí
17,1709500,Gurupi
17,1709807,Ipueiras
17,1710508,Itacajá
17,1710706,Itaguatins
17,1710904,Itapiratins
17,1711100,Itaporã do Tocantins
17,1711506,Jaú do Tocantins
17,1711803,Juarina
17,1711902,Lagoa da Confusão
17,1711951,Lagoa do Tocantins
17,1712009,Lajeado
17,1712157,Lavandeira
17,1712405,Lizarda
17,1712454,Luzinópolis
17,1712504,Marianópolis do Tocantins
17,1712702,Mateiros
17,1712801,Maurilândia do Tocantins
17,1713205,Miracema do Tocantins
17,1713304,Miranorte
17,1713601,Monte do Carmo
17,1713700,Monte Santo do Tocantins
17,1713809,Palmeiras do Tocantins
17,1713957,Muricilândia
17,1714203,Natividade
17,1714302,Nazaré
17,1714880,Nova Olinda
17,1715002,Nova Rosalândia
17,1715101,Novo Acordo
17,1715150,Novo Alegre
17,1715259,Novo Jardim
17,1715507,Oliveira de Fátima
17,1715705,Palmeirante
17,1715754,Palmeirópolis
17,1716109,Paraíso do Tocantins
17,1716208,Paranã
17,1716307,Pau D'arco
17,1716505,Pedro Afonso
17,1716604,Peixe
17,1716653,Pequizeiro
17,1716703,Colméia
17,1717008,Pindorama do Tocantins
17,1717206,Piraquê
17,1717503,Pium
17,1717800,Ponte Alta do Bom Jesus
17,1717909,Ponte Alta do Tocantins
17,1718006,Porto Alegre do Tocantins
17,1718204,Porto Nacional
17,1718303,Praia Norte
17,1718402,Presidente Kennedy
17,1718451,Pugmil
17,1718501,Recursolândia
17,1718550,Riachinho
17,1718659,Rio da Conceição
17,1718709,Rio dos Bois
17,1718758,Rio Sono
17,1718808,Sampaio
17,1718840,Sandolândia
17,1718865,Santa Fé do Araguaia
17,1718881,Santa Maria do Tocantins
17,1718899,Santa Rita do Tocantins
17,1718907,Santa Rosa do Tocantins
17,1719004,Santa Tereza do Tocantins
17,1720002,Santa Terezinha do Tocantins
17,1720101,São Bento do Tocantins
17,1720150,São Félix do Tocantins
17,1720200,São Miguel do Tocantins
17,1720259,São Salvador do Tocantins
17,1720309,São Sebastião do Tocantins
17,1720499,São Valério
17,1720655,Silvanópolis
17,1720804,Sítio Novo do Tocantins
17,1720853,Sucupira
17,1720903,Taguatinga
17,1720937,Taipas do Tocantins
17,1720978,Talismã
17,1721000,Palmas
17,1721109,Tocantínia
17,1721208,Tocantinópolis
17,1721257,Tupirama
17,1721307,Tupiratins
17,1722081,Wanderlândia
17,1722107,Xambioá
21,2100055,Açailândia
21,2100105,Afonso Cunha
21,2100154,Água doce do Maranhão
21,2100204,Alcântara
21,2100303,Aldeias Altas
21,2100402,Altamira do Maranhão
21,2100436,Alto Alegre do Maranhão
21,2100477,Alto Alegre do Pindaré
21,2100501,Alto Parnaíba
21,2100550,Amapá do Maranhão
21,2100600,Amarante do Maranhão
21,2100709,Anajatuba
21,2100808,Anapurus
21,2100832,Apicum-Açu
21,2100873,Araguanã
21,2100907,Araioses
21,2100956,Arame
21,2101004,Arari
21,2101103,Axixá
21,2101202,Bacabal
21,2101251,Bacabeira
21,2101301,Bacuri
21,2101350,Bacurituba
21,2101400,Balsas
21,2101509,Barão de Grajaú
21,2101608,Barra do Corda
21,2101707,Barreirinhas
21,2101731,Belágua
21,2101772,Bela Vista do Maranhão
21,2101806,Benedito Leite
21,2101905,Bequimão
21,2101939,Bernardo do Mearim
21,2101970,Boa Vista do Gurupi
21,2102002,Bom Jardim
21,2102036,Bom Jesus das Selvas
21,2102077,Bom Lugar
21,2102101,Brejo
21,2102150,Brejo de Areia
21,2102200,Buriti
21,2102309,Buriti Bravo
21,2102325,Buriticupu
21,2102358,Buritirana
21,2102374,Cachoeira Grande
21,2102408,Cajapió
21,2102507,Cajari
21,2102556,Campestre do Maranhão
21,2102606,Cândido Mendes
21,2102705,Cantanhede
21,2102754,Capinzal do Norte
21,2102804,Carolina
21,2102903,Carutapera
21,2103000,Caxias
21,2103109,Cedral
21,2103125,Central do Maranhão
21,2103158,Centro do Guilherme
21,2103174,Centro Novo do Maranhão
21,2103208,Chapadinha
21,2103257,Cidelândia
21,2103307,Codó
21,2103406,Coelho Neto
21,2103505,Colinas
21,2103554,Conceição do Lago-Açu
21,2103604,Coroatá
21,2103703,Cururupu
21,2103752,davinópolis
21,2103802,dom Pedro
21,2103901,Duque Bacelar
21,2104008,Esperantinópolis
21,2104057,Estreito
21,2104073,Feira Nova do Maranhão
21,2104081,Fernando Falcão
21,2104099,Formosa da Serra Negra
21,2104107,Fortaleza dos Nogueiras
21,2104206,Fortuna
21,2104305,Godofredo Viana
21,2104404,Gonçalves Dias
21,2104503,Governador Archer
21,2104552,Governador Edison Lobão
21,2104602,Governador Eugênio Barros
21,2104628,Governador Luiz Rocha
21,2104651,Governador Newton Bello
21,2104677,Governador Nunes Freire
21,2104701,Graça Aranha
21,2104800,Grajaú
21,2104909,Guimarães
21,2105005,Humberto de Campos
21,2105104,Icatu
21,2105153,Igarapé do Meio
21,2105203,Igarapé Grande
21,2105302,Imperatriz
21,2105351,Itaipava do Grajaú
21,2105401,Itapecuru Mirim
21,2105427,Itinga do Maranhão
21,2105450,Jatobá
21,2105476,Jenipapo dos Vieiras
21,2105500,João Lisboa
21,2105609,Joselândia
21,2105658,Junco do Maranhão
21,2105708,Lago da Pedra
21,2105807,Lago do Junco
21,2105906,Lago Verde
21,2105922,Lagoa do Mato
21,2105948,Lago dos Rodrigues
21,2105963,Lagoa Grande do Maranhão
21,2105989,Lajeado Novo
21,2106003,Lima Campos
21,2106102,Loreto
21,2106201,Luís domingues
21,2106300,Magalhães de Almeida
21,2106326,Maracaçumé
21,2106359,Marajá do Sena
21,2106375,Maranhãozinho
21,2106409,Mata Roma
21,2106508,Matinha
21,2106607,Matões
21,2106631,Matões do Norte
21,2106672,Milagres do Maranhão
21,2106706,Mirador
21,2106755,Miranda do Norte
21,2106805,Mirinzal
21,2106904,Monção
21,2107001,Montes Altos
21,2107100,Morros
21,2107209,Nina Rodrigues
21,2107258,Nova Colinas
21,2107308,Nova Iorque
21,2107357,Nova Olinda do Maranhão
21,2107407,Olho D'água das Cunhãs
21,2107456,Olinda Nova do Maranhão
21,2107506,Paço do Lumiar
21,2107605,Palmeirândia
21,2107704,Paraibano
21,2107803,Parnarama
21,2107902,Passagem Franca
21,2108009,Pastos Bons
21,2108058,Paulino Neves
21,2108108,Paulo Ramos
21,2108207,Pedreiras
21,2108256,Pedro do Rosário
21,2108306,Penalva
21,2108405,Peri Mirim
21,2108454,Peritoró
21,2108504,Pindaré-Mirim
21,2108603,Pinheiro
21,2108702,Pio Xii
21,2108801,Pirapemas
21,2108900,Poção de Pedras
21,2109007,Porto Franco
21,2109056,Porto Rico do Maranhão
21,2109106,Presidente Dutra
21,2109205,Presidente Juscelino
21,2109239,Presidente Médici
21,2109270,Presidente Sarney
21,2109304,Presidente Vargas
21,2109403,Primeira Cruz
21,2109452,Raposa
21,2109502,Riachão
21,2109551,Ribamar Fiquene
21,2109601,Rosário
21,2109700,Sambaíba
21,2109759,Santa Filomena do Maranhão
21,2109809,Santa Helena
21,2109908,Santa Inês
21,2110005,Santa Luzia
21,2110039,Santa Luzia do Paruá
21,2110104,Santa Quitéria do Maranhão
21,2110203,Santa Rita
21,2110237,Santana do Maranhão
21,2110278,Santo Amaro do Maranhão
21,2110302,Santo Antônio dos Lopes
21,2110401,São Benedito do Rio Preto
21,2110500,São Bento
21,2110609,São Bernardo
21,2110658,São domingos do Azeitão
21,2110708,São domingos do Maranhão
21,2110807,São Félix de Balsas
21,2110856,São Francisco do Brejão
21,2110906,São Francisco do Maranhão
21,2111003,São João Batista
21,2111029,São João do Carú
21,2111052,São João do Paraíso
21,2111078,São João do Soter
21,2111102,São João dos Patos
21,2111201,São José de Ribamar
21,2111250,São José dos Basílios
21,2111300,São Luís
21,2111409,São Luís Gonzaga do Maranhão
21,2111508,São Mateus do Maranhão
21,2111532,São Pedro da Água Branca
21,2111573,São Pedro dos Crentes
21,2111607,São Raimundo das Mangabeiras
21,2111631,São Raimundo do doca Bezerra
21,2111672,São Roberto
21,2111706,São Vicente Ferrer
21,2111722,Satubinha
21,2111748,Senador Alexandre Costa
21,2111763,Senador La Rocque
21,2111789,Serrano do Maranhão
21,2111805,Sítio Novo
21,2111904,Sucupira do Norte
21,2111953,Sucupira do Riachão
21,2112001,Tasso Fragoso
21,2112100,Timbiras
21,2112209,Timon
21,2112233,Trizidela do Vale
21,2112274,Tufilândia
21,2112308,Tuntum
21,2112407,Turiaçu
21,2112456,Turilândia
21,2112506,Tutóia
21,2112605,Urbano Santos
21,2112704,Vargem Grande
21,2112803,Viana
21,2112852,Vila Nova dos Martírios
21,2112902,Vitória do Mearim
21,2113009,Vitorino Freire
21,2114007,Zé doca
22,2200053,Acauã
22,2200103,Agricolândia
22,2200202,Água Branca
22,2200251,Alagoinha do Piauí
22,2200277,Alegrete do Piauí
22,2200301,Alto Longá
22,2200400,Altos
22,2200459,Alvorada do Gurguéia
22,2200509,Amarante
22,2200608,Angical do Piauí
22,2200707,Anísio de Abreu
22,2200806,Antônio Almeida
22,2200905,Aroazes
22,2200954,Aroeiras do Itaim
22,2201002,Arraial
22,2201051,Assunção do Piauí
22,2201101,Avelino Lopes
22,2201150,Baixa Grande do Ribeiro
22,2201176,Barra D'alcântara
22,2201200,Barras
22,2201309,Barreiras do Piauí
22,2201408,Barro Duro
22,2201507,Batalha
22,2201556,Bela Vista do Piauí
22,2201572,Belém do Piauí
22,2201606,Beneditinos
22,2201705,Bertolínia
22,2201739,Betânia do Piauí
22,2201770,Boa Hora
22,2201804,Bocaina
22,2201903,Bom Jesus
22,2201919,Bom Princípio do Piauí
22,2201929,Bonfim do Piauí
22,2201945,Boqueirão do Piauí
22,2201960,Brasileira
22,2201988,Brejo do Piauí
22,2202000,Buriti dos Lopes
22,2202026,Buriti dos Montes
22,2202059,Cabeceiras do Piauí
22,2202075,Cajazeiras do Piauí
22,2202083,Cajueiro da Praia
22,2202091,Caldeirão Grande do Piauí
22,2202109,Campinas do Piauí
22,2202117,Campo Alegre do Fidalgo
22,2202133,Campo Grande do Piauí
22,2202174,Campo Largo do Piauí
22,2202208,Campo Maior
22,2202251,Canavieira
22,2202307,Canto do Buriti
22,2202406,Capitão de Campos
22,2202455,Capitão Gervásio Oliveira
22,2202505,Caracol
22,2202539,Caraúbas do Piauí
22,2202554,Caridade do Piauí
22,2202604,Castelo do Piauí
22,2202653,Caxingó
22,2202703,Cocal
22,2202711,Cocal de Telha
22,2202729,Cocal dos Alves
22,2202737,Coivaras
22,2202752,Colônia do Gurguéia
22,2202778,Colônia do Piauí
22,2202802,Conceição do Canindé
22,2202851,Coronel José Dias
22,2202901,Corrente
22,2203008,Cristalândia do Piauí
22,2203107,Cristino Castro
22,2203206,Curimatá
22,2203230,Currais
22,2203255,Curralinhos
22,2203271,Curral Novo do Piauí
22,2203305,demerval Lobão
22,2203354,Dirceu Arcoverde
22,2203404,dom Expedito Lopes
22,2203420,domingos Mourão
22,2203453,dom Inocêncio
22,2203503,Elesbão Veloso
22,2203602,Eliseu Martins
22,2203701,Esperantina
22,2203750,Fartura do Piauí
22,2203800,Flores do Piauí
22,2203859,Floresta do Piauí
22,2203909,Floriano
22,2204006,Francinópolis
22,2204105,Francisco Ayres
22,2204154,Francisco Macedo
22,2204204,Francisco Santos
22,2204303,Fronteiras
22,2204352,Geminiano
22,2204402,Gilbués
22,2204501,Guadalupe
22,2204550,Guaribas
22,2204600,Hugo Napoleão
22,2204659,Ilha Grande
22,2204709,Inhuma
22,2204808,Ipiranga do Piauí
22,2204907,Isaías Coelho
22,2205003,Itainópolis
22,2205102,Itaueira
22,2205151,Jacobina do Piauí
22,2205201,Jaicós
22,2205250,Jardim do Mulato
22,2205276,Jatobá do Piauí
22,2205300,Jerumenha
22,2205359,João Costa
22,2205409,Joaquim Pires
22,2205458,Joca Marques
22,2205508,José de Freitas
22,2205516,Juazeiro do Piauí
22,2205524,Júlio Borges
22,2205532,Jurema
22,2205540,Lagoinha do Piauí
22,2205557,Lagoa Alegre
22,2205565,Lagoa do Barro do Piauí
22,2205573,Lagoa de São Francisco
22,2205581,Lagoa do Piauí
22,2205599,Lagoa do Sítio
22,2205607,Landri Sales
22,2205706,Luís Correia
22,2205805,Luzilândia
22,2205854,Madeiro
22,2205904,Manoel Emídio
22,2205953,Marcolândia
22,2206001,Marcos Parente
22,2206050,Massapê do Piauí
22,2206100,Matias Olímpio
22,2206209,Miguel Alves
22,2206308,Miguel Leão
22,2206357,Milton Brandão
22,2206407,Monsenhor Gil
22,2206506,Monsenhor Hipólito
22,2206605,Monte Alegre do Piauí
22,2206654,Morro Cabeça No Tempo
22,2206670,Morro do Chapéu do Piauí
22,2206696,Murici dos Portelas
22,2206704,Nazaré do Piauí
22,2206720,Nazária
22,2206753,Nossa Senhora de Nazaré
22,2206803,Nossa Senhora dos Remédios
22,2206902,Novo Oriente do Piauí
22,2206951,Novo Santo Antônio
22,2207009,Oeiras
22,2207108,Olho D'água do Piauí
22,2207207,Padre Marcos
22,2207306,Paes Landim
22,2207355,Pajeú do Piauí
22,2207405,Palmeira do Piauí
22,2207504,Palmeirais
22,2207553,Paquetá
22,2207603,Parnaguá
22,2207702,Parnaíba
22,2207751,Passagem Franca do Piauí
22,2207777,Patos do Piauí
22,2207793,Pau D'arco do Piauí
22,2207801,Paulistana
22,2207850,Pavussu
22,2207900,Pedro Ii
22,2207934,Pedro Laurentino
22,2207959,Nova Santa Rita
22,2208007,Picos
22,2208106,Pimenteiras
22,2208205,Pio Ix
22,2208304,Piracuruca
22,2208403,Piripiri
22,2208502,Porto
22,2208551,Porto Alegre do Piauí
22,2208601,Prata do Piauí
22,2208650,Queimada Nova
22,2208700,Redenção do Gurguéia
22,2208809,Regeneração
22,2208858,Riacho Frio
22,2208874,Ribeira do Piauí
22,2208908,Ribeiro Gonçalves
22,2209005,Rio Grande do Piauí
22,2209104,Santa Cruz do Piauí
22,2209153,Santa Cruz dos Milagres
22,2209203,Santa Filomena
22,2209302,Santa Luz
22,2209351,Santana do Piauí
22,2209377,Santa Rosa do Piauí
22,2209401,Santo Antônio de Lisboa
22,2209450,Santo Antônio dos Milagres
22,2209500,Santo Inácio do Piauí
22,2209559,São Braz do Piauí
22,2209609,São Félix do Piauí
22,2209658,São Francisco de Assis do Piauí
22,2209708,São Francisco do Piauí
22,2209757,São Gonçalo do Gurguéia
22,2209807,São Gonçalo do Piauí
22,2209856,São João da Canabrava
22,2209872,São João da Fronteira
22,2209906,São João da Serra
22,2209955,São João da Varjota
22,2209971,São João do Arraial
22,2210003,São João do Piauí
22,2210052,São José do Divino
22,2210102,São José do Peixe
22,2210201,São José do Piauí
22,2210300,São Julião
22,2210359,São Lourenço do Piauí
22,2210375,São Luis do Piauí
22,2210383,São Miguel da Baixa Grande
22,2210391,São Miguel do Fidalgo
22,2210409,São Miguel do Tapuio
22,2210508,São Pedro do Piauí
22,2210607,São Raimundo Nonato
22,2210623,Sebastião Barros
22,2210631,Sebastião Leal
22,2210656,Sigefredo Pacheco
22,2210706,Simões
22,2210805,Simplício Mendes
22,2210904,Socorro do Piauí
22,2210938,Sussuapara
22,2210953,Tamboril do Piauí
22,2210979,Tanque do Piauí
22,2211001,Teresina
22,2211100,União
22,2211209,Uruçuí
22,2211308,Valença do Piauí
22,2211357,Várzea Branca
22,2211407,Várzea Grande
22,2211506,Vera Mendes
22,2211605,Vila Nova do Piauí
22,2211704,Wall Ferraz
23,2300101,Abaiara
23,2300150,Acarape
23,2300200,Acaraú
23,2300309,Acopiara
23,2300408,Aiuaba
23,2300507,Alcântaras
23,2300606,Altaneira
23,2300705,Alto Santo
23,2300754,Amontada
23,2300804,Antonina do Norte
23,2300903,Apuiarés
23,2301000,Aquiraz
23,2301109,Aracati
23,2301208,Aracoiaba
23,2301257,Ararendá
23,2301307,Araripe
23,2301406,Aratuba
23,2301505,Arneiroz
23,2301604,Assaré
23,2301703,Aurora
23,2301802,Baixio
23,2301851,Banabuiú
23,2301901,Barbalha
23,2301950,Barreira
23,2302008,Barro
23,2302057,Barroquinha
23,2302107,Baturité
23,2302206,Beberibe
23,2302305,Bela Cruz
23,2302404,Boa Viagem
23,2302503,Brejo Santo
23,2302602,Camocim
23,2302701,Campos Sales
23,2302800,Canindé
23,2302909,Capistrano
23,2303006,Caridade
23,2303105,Cariré
23,2303204,Caririaçu
23,2303303,Cariús
23,2303402,Carnaubal
23,2303501,Cascavel
23,2303600,Catarina
23,2303659,Catunda
23,2303709,Caucaia
23,2303808,Cedro
23,2303907,Chaval
23,2303931,Choró
23,2303956,Chorozinho
23,2304004,Coreaú
23,2304103,Crateús
23,2304202,Crato
23,2304236,Croatá
23,2304251,Cruz
23,2304269,deputado Irapuan Pinheiro
23,2304277,Ererê
23,2304285,Eusébio
23,2304301,Farias Brito
23,2304350,Forquilha
23,2304400,Fortaleza
23,2304459,Fortim
23,2304509,Frecheirinha
23,2304608,General Sampaio
23,2304657,Graça
23,2304707,Granja
23,2304806,Granjeiro
23,2304905,Groaíras
23,2304954,Guaiúba
23,2305001,Guaraciaba do Norte
23,2305100,Guaramiranga
23,2305209,Hidrolândia
23,2305233,Horizonte
23,2305266,Ibaretama
23,2305308,Ibiapina
23,2305332,Ibicuitinga
23,2305357,Icapuí
23,2305407,Icó
23,2305506,Iguatu
23,2305605,Independência
23,2305654,Ipaporanga
23,2305704,Ipaumirim
23,2305803,Ipu
23,2305902,Ipueiras
23,2306009,Iracema
23,2306108,Irauçuba
23,2306207,Itaiçaba
23,2306256,Itaitinga
23,2306306,Itapajé
23,2306405,Itapipoca
23,2306504,Itapiúna
23,2306553,Itarema
23,2306603,Itatira
23,2306702,Jaguaretama
23,2306801,Jaguaribara
23,2306900,Jaguaribe
23,2307007,Jaguaruana
23,2307106,Jardim
23,2307205,Jati
23,2307254,Jijoca de Jericoacoara
23,2307304,Juazeiro do Norte
23,2307403,Jucás
23,2307502,Lavras da Mangabeira
23,2307601,Limoeiro do Norte
23,2307635,Madalena
23,2307650,Maracanaú
23,2307700,Maranguape
23,2307809,Marco
23,2307908,Martinópole
23,2308005,Massapê
23,2308104,Mauriti
23,2308203,Meruoca
23,2308302,Milagres
23,2308351,Milhã
23,2308377,Miraíma
23,2308401,Missão Velha
23,2308500,Mombaça
23,2308609,Monsenhor Tabosa
23,2308708,Morada Nova
23,2308807,Moraújo
23,2308906,Morrinhos
23,2309003,Mucambo
23,2309102,Mulungu
23,2309201,Nova Olinda
23,2309300,Nova Russas
23,2309409,Novo Oriente
23,2309458,Ocara
23,2309508,Orós
23,2309607,Pacajus
23,2309706,Pacatuba
23,2309805,Pacoti
23,2309904,Pacujá
23,2310001,Palhano
23,2310100,Palmácia
23,2310209,Paracuru
23,2310258,Paraipaba
23,2310308,Parambu
23,2310407,Paramoti
23,2310506,Pedra Branca
23,2310605,Penaforte
23,2310704,Pentecoste
23,2310803,Pereiro
23,2310852,Pindoretama
23,2310902,Piquet Carneiro
23,2310951,Pires Ferreira
23,2311009,Poranga
23,2311108,Porteiras
23,2311207,Potengi
23,2311231,Potiretama
23,2311264,Quiterianópolis
23,2311306,Quixadá
23,2311355,Quixelô
23,2311405,Quixeramobim
23,2311504,Quixeré
23,2311603,Redenção
23,2311702,Reriutaba
23,2311801,Russas
23,2311900,Saboeiro
23,2311959,Salitre
23,2312007,Santana do Acaraú
23,2312106,Santana do Cariri
23,2312205,Santa Quitéria
23,2312304,São Benedito
23,2312403,São Gonçalo do Amarante
23,2312502,São João do Jaguaribe
23,2312601,São Luís do Curu
23,2312700,Senador Pompeu
23,2312809,Senador Sá
23,2312908,Sobral
23,2313005,Solonópole
23,2313104,Tabuleiro do Norte
23,2313203,Tamboril
23,2313252,Tarrafas
23,2313302,Tauá
23,2313351,Tejuçuoca
23,2313401,Tianguá
23,2313500,Trairi
23,2313559,Tururu
23,2313609,Ubajara
23,2313708,Umari
23,2313757,Umirim
23,2313807,Uruburetama
23,2313906,Uruoca
23,2313955,Varjota
23,2314003,Várzea Alegre
23,2314102,Viçosa do Ceará
24,2400109,Acari
24,2400208,Açu
24,2400307,Afonso Bezerra
24,2400406,Água Nova
24,2400505,Alexandria
24,2400604,Almino Afonso
24,2400703,Alto do Rodrigues
24,2400802,Angicos
24,2400901,Antônio Martins
24,2401008,Apodi
24,2401107,Areia Branca
24,2401206,Arês
24,2401305,Augusto Severo
24,2401404,Baía Formosa
24,2401453,Baraúna
24,2401503,Barcelona
24,2401602,Bento Fernandes
24,2401651,Bodó
24,2401701,Bom Jesus
24,2401800,Brejinho
24,2401859,Caiçara do Norte
24,2401909,Caiçara do Rio do Vento
24,2402006,Caicó
24,2402105,Campo Redondo
24,2402204,Canguaretama
24,2402303,Caraúbas
24,2402402,Carnaúba dos dantas
24,2402501,Carnaubais
24,2402600,Ceará-Mirim
24,2402709,Cerro Corá
24,2402808,Coronel Ezequiel
24,2402907,Coronel João Pessoa
24,2403004,Cruzeta
24,2403103,Currais Novos
24,2403202,doutor Severiano
24,2403251,Parnamirim
24,2403301,Encanto
24,2403400,Equador
24,2403509,Espírito Santo
24,2403608,Extremoz
24,2403707,Felipe Guerra
24,2403756,Fernando Pedroza
24,2403806,Florânia
24,2403905,Francisco dantas
24,2404002,Frutuoso Gomes
24,2404101,Galinhos
24,2404200,Goianinha
24,2404309,Governador Dix-Sept Rosado
24,2404408,Grossos
24,2404507,Guamaré
24,2404606,Ielmo Marinho
24,2404705,Ipanguaçu
24,2404804,Ipueira
24,2404853,Itajá
24,2404903,Itaú
24,2405009,Jaçanã
24,2405108,Jandaíra
24,2405207,Janduís
24,2405306,Januário Cicco
24,2405405,Japi
24,2405504,Jardim de Angicos
24,2405603,Jardim de Piranhas
24,2405702,Jardim do Seridó
24,2405801,João Câmara
24,2405900,João Dias
24,2406007,José da Penha
24,2406106,Jucurutu
24,2406155,Jundiá
24,2406205,Lagoa D'anta
24,2406304,Lagoa de Pedras
24,2406403,Lagoa de Velhos
24,2406502,Lagoa Nova
24,2406601,Lagoa Salgada
24,2406700,Lajes
24,2406809,Lajes Pintadas
24,2406908,Lucrécia
24,2407005,Luís Gomes
24,2407104,Macaíba
24,2407203,Macau
24,2407252,Major Sales
24,2407302,Marcelino Vieira
24,2407401,Martins
24,2407500,Maxaranguape
24,2407609,Messias Targino
24,2407708,Montanhas
24,2407807,Monte Alegre
24,2407906,Monte das Gameleiras
24,2408003,Mossoró
24,2408102,Natal
24,2408201,Nísia Floresta
24,2408300,Nova Cruz
24,2408409,Olho-D'água do Borges
24,2408508,Ouro Branco
24,2408607,Paraná
24,2408706,Paraú
24,2408805,Parazinho
24,2408904,Parelhas
24,2408953,Rio do Fogo
24,2409100,Passa E Fica
24,2409209,Passagem
24,2409308,Patu
24,2409332,Santa Maria
24,2409407,Pau dos Ferros
24,2409506,Pedra Grande
24,2409605,Pedra Preta
24,2409704,Pedro Avelino
24,2409803,Pedro Velho
24,2409902,Pendências
24,2410009,Pilões
24,2410108,Poço Branco
24,2410207,Portalegre
24,2410256,Porto do Mangue
24,2410306,Serra Caiada
24,2410405,Pureza
24,2410504,Rafael Fernandes
24,2410603,Rafael Godeiro
24,2410702,Riacho da Cruz
24,2410801,Riacho de Santana
24,2410900,Riachuelo
24,2411007,Rodolfo Fernandes
24,2411056,Tibau
24,2411106,Ruy Barbosa
24,2411205,Santa Cruz
24,2411403,Santana do Matos
24,2411429,Santana do Seridó
24,2411502,Santo Antônio
24,2411601,São Bento do Norte
24,2411700,São Bento do Trairí
24,2411809,São Fernando
24,2411908,São Francisco do Oeste
24,2412005,São Gonçalo do Amarante
24,2412104,São João do Sabugi
24,2412203,São José de Mipibu
24,2412302,São José do Campestre
24,2412401,São José do Seridó
24,2412500,São Miguel
24,2412559,São Miguel do Gostoso
24,2412609,São Paulo do Potengi
24,2412708,São Pedro
24,2412807,São Rafael
24,2412906,São Tomé
24,2413003,São Vicente
24,2413102,Senador Elói de Souza
24,2413201,Senador Georgino Avelino
24,2413300,Serra de São Bento
24,2413359,Serra do Mel
24,2413409,Serra Negra do Norte
24,2413508,Serrinha
24,2413557,Serrinha dos Pintos
24,2413607,Severiano Melo
24,2413706,Sítio Novo
24,2413805,Taboleiro Grande
24,2413904,Taipu
24,2414001,Tangará
24,2414100,Tenente Ananias
24,2414159,Tenente Laurentino Cruz
24,2414209,Tibau do Sul
24,2414308,Timbaúba dos Batistas
24,2414407,Touros
24,2414456,Triunfo Potiguar
24,2414506,Umarizal
24,2414605,Upanema
24,2414704,Várzea
24,2414753,Venha-Ver
24,2414803,Vera Cruz
24,2414902,Viçosa
24,2415008,Vila Flor
25,2500106,Água Branca
25,2500205,Aguiar
25,2500304,Alagoa Grande
25,2500403,Alagoa Nova
25,2500502,Alagoinha
25,2500536,Alcantil
25,2500577,Algodão de Jandaíra
25,2500601,Alhandra
25,2500700,São João do Rio do Peixe
25,2500734,Amparo
25,2500775,Aparecida
25,2500809,Araçagi
25,2500908,Arara
25,2501005,Araruna
25,2501104,Areia
25,2501153,Areia de Baraúnas
25,2501203,Areial
25,2501302,Aroeiras
25,2501351,Assunção
25,2501401,Baía da Traição
25,2501500,Bananeiras
25,2501534,Baraúna
25,2501575,Barra de Santana
25,2501609,Barra de Santa Rosa
25,2501708,Barra de São Miguel
25,2501807,Bayeux
25,2501906,Belém
25,2502003,Belém do Brejo do Cruz
25,2502052,Bernardino Batista
25,2502102,Boa Ventura
25,2502151,Boa Vista
25,2502201,Bom Jesus
25,2502300,Bom Sucesso
25,2502409,Bonito de Santa Fé
25,2502508,Boqueirão
25,2502607,Igaracy
25,2502706,Borborema
25,2502805,Brejo do Cruz
25,2502904,Brejo dos Santos
25,2503001,Caaporã
25,2503100,Cabaceiras
25,2503209,Cabedelo
25,2503308,Cachoeira dos Índios
25,2503407,Cacimba de Areia
25,2503506,Cacimba de dentro
25,2503555,Cacimbas
25,2503605,Caiçara
25,2503704,Cajazeiras
25,2503753,Cajazeirinhas
25,2503803,Caldas Brandão
25,2503902,Camalaú
25,2504009,Campina Grande
25,2504033,Capim
25,2504074,Caraúbas
25,2504108,Carrapateira
25,2504157,Casserengue
25,2504207,Catingueira
25,2504306,Catolé do Rocha
25,2504355,Caturité
25,2504405,Conceição
25,2504504,Condado
25,2504603,Conde
25,2504702,Congo
25,2504801,Coremas
25,2504850,Coxixola
25,2504900,Cruz do Espírito Santo
25,2505006,Cubati
25,2505105,Cuité
25,2505204,Cuitegi
25,2505238,Cuité de Mamanguape
25,2505279,Curral de Cima
25,2505303,Curral Velho
25,2505352,damião
25,2505402,desterro
25,2505501,Vista Serrana
25,2505600,Diamante
25,2505709,dona Inês
25,2505808,Duas Estradas
25,2505907,Emas
25,2506004,Esperança
25,2506103,Fagundes
25,2506202,Frei Martinho
25,2506251,Gado Bravo
25,2506301,Guarabira
25,2506400,Gurinhém
25,2506509,Gurjão
25,2506608,Ibiara
25,2506707,Imaculada
25,2506806,Ingá
25,2506905,Itabaiana
25,2507002,Itaporanga
25,2507101,Itapororoca
25,2507200,Itatuba
25,2507309,Jacaraú
25,2507408,Jericó
25,2507507,João Pessoa
25,2507606,Juarez Távora
25,2507705,Juazeirinho
25,2507804,Junco do Seridó
25,2507903,Juripiranga
25,2508000,Juru
25,2508109,Lagoa
25,2508208,Lagoa de dentro
25,2508307,Lagoa Seca
25,2508406,Lastro
25,2508505,Livramento
25,2508554,Logradouro
25,2508604,Lucena
25,2508703,Mãe D'água
25,2508802,Malta
25,2508901,Mamanguape
25,2509008,Manaíra
25,2509057,Marcação
25,2509107,Mari
25,2509156,Marizópolis
25,2509206,Massaranduba
25,2509305,Mataraca
25,2509339,Matinhas
25,2509370,Mato Grosso
25,2509396,Maturéia
25,2509404,Mogeiro
25,2509503,Montadas
25,2509602,Monte Horebe
25,2509701,Monteiro
25,2509800,Mulungu
25,2509909,Natuba
25,2510006,Nazarezinho
25,2510105,Nova Floresta
25,2510204,Nova Olinda
25,2510303,Nova Palmeira
25,2510402,Olho D'água
25,2510501,Olivedos
25,2510600,Ouro Velho
25,2510659,Parari
25,2510709,Passagem
25,2510808,Patos
25,2510907,Paulista
25,2511004,Pedra Branca
25,2511103,Pedra Lavrada
25,2511202,Pedras de Fogo
25,2511301,Piancó
25,2511400,Picuí
25,2511509,Pilar
25,2511608,Pilões
25,2511707,Pilõezinhos
25,2511806,Pirpirituba
25,2511905,Pitimbu
25,2512002,Pocinhos
25,2512036,Poço dantas
25,2512077,Poço de José de Moura
25,2512101,Pombal
25,2512200,Prata
25,2512309,Princesa Isabel
25,2512408,Puxinanã
25,2512507,Queimadas
25,2512606,Quixaba
25,2512705,Remígio
25,2512721,Pedro Régis
25,2512747,Riachão
25,2512754,Riachão do Bacamarte
25,2512762,Riachão do Poço
25,2512788,Riacho de Santo Antônio
25,2512804,Riacho dos Cavalos
25,2512903,Rio Tinto
25,2513000,Salgadinho
25,2513109,Salgado de São Félix
25,2513158,Santa Cecília
25,2513208,Santa Cruz
25,2513307,Santa Helena
25,2513356,Santa Inês
25,2513406,Santa Luzia
25,2513505,Santana de Mangueira
25,2513604,Santana dos Garrotes
25,2513653,Joca Claudino
25,2513703,Santa Rita
25,2513802,Santa Teresinha
25,2513851,Santo André
25,2513901,São Bento
25,2513927,São Bentinho
25,2513943,São domingos do Cariri
25,2513968,São domingos
25,2513984,São Francisco
25,2514008,São João do Cariri
25,2514107,São João do Tigre
25,2514206,São José da Lagoa Tapada
25,2514305,São José de Caiana
25,2514404,São José de Espinharas
25,2514453,São José dos Ramos
25,2514503,São José de Piranhas
25,2514552,São José de Princesa
25,2514602,São José do Bonfim
25,2514651,São José do Brejo do Cruz
25,2514701,São José do Sabugi
25,2514800,São José dos Cordeiros
25,2514909,São Mamede
25,2515005,São Miguel de Taipu
25,2515104,São Sebastião de Lagoa de Roça
25,2515203,São Sebastião do Umbuzeiro
25,2515302,Sapé
25,2515401,São Vicente do Seridó
25,2515500,Serra Branca
25,2515609,Serra da Raiz
25,2515708,Serra Grande
25,2515807,Serra Redonda
25,2515906,Serraria
25,2515930,Sertãozinho
25,2515971,Sobrado
25,2516003,Solânea
25,2516102,Soledade
25,2516151,Sossêgo
25,2516201,Sousa
25,2516300,Sumé
25,2516409,Tacima
25,2516508,Taperoá
25,2516607,Tavares
25,2516706,Teixeira
25,2516755,Tenório
25,2516805,Triunfo
25,2516904,Uiraúna
25,2517001,Umbuzeiro
25,2517100,Várzea
25,2517209,Vieirópolis
25,2517407,Zabelê
26,2600054,Abreu E Lima
26,2600104,Afogados da Ingazeira
26,2600203,Afrânio
26,2600302,Agrestina
26,2600401,Água Preta
26,2600500,Águas Belas
26,2600609,Alagoinha
26,2600708,Aliança
26,2600807,Altinho
26,2600906,Amaraji
26,2601003,Angelim
26,2601052,Araçoiaba
26,2601102,Araripina
26,2601201,Arcoverde
26,2601300,Barra de Guabiraba
26,2601409,Barreiros
26,2601508,Belém de Maria
26,2601607,Belém do São Francisco
26,2601706,Belo Jardim
26,2601805,Betânia
26,2601904,Bezerros
26,2602001,Bodocó
26,2602100,Bom Conselho
26,2602209,Bom Jardim
26,2602308,Bonito
26,2602407,Brejão
26,2602506,Brejinho
26,2602605,Brejo da Madre de deus
26,2602704,Buenos Aires
26,2602803,Buíque
26,2602902,Cabo de Santo Agostinho
26,2603009,Cabrobó
26,2603108,Cachoeirinha
26,2603207,Caetés
26,2603306,Calçado
26,2603405,Calumbi
26,2603454,Camaragibe
26,2603504,Camocim de São Félix
26,2603603,Camutanga
26,2603702,Canhotinho
26,2603801,Capoeiras
26,2603900,Carnaíba
26,2603926,Carnaubeira da Penha
26,2604007,Carpina
26,2604106,Caruaru
26,2604155,Casinhas
26,2604205,Catende
26,2604304,Cedro
26,2604403,Chã de Alegria
26,2604502,Chã Grande
26,2604601,Condado
26,2604700,Correntes
26,2604809,Cortês
26,2604908,Cumaru
26,2605004,Cupira
26,2605103,Custódia
26,2605152,dormentes
26,2605202,Escada
26,2605301,Exu
26,2605400,Feira Nova
26,2605459,Fernando de Noronha
26,2605509,Ferreiros
26,2605608,Flores
26,2605707,Floresta
26,2605806,Frei Miguelinho
26,2605905,Gameleira
26,2606002,Garanhuns
26,2606101,Glória do Goitá
26,2606200,Goiana
26,2606309,Granito
26,2606408,Gravatá
26,2606507,Iati
26,2606606,Ibimirim
26,2606705,Ibirajuba
26,2606804,Igarassu
26,2606903,Iguaracy
26,2607000,Inajá
26,2607109,Ingazeira
26,2607208,Ipojuca
26,2607307,Ipubi
26,2607406,Itacuruba
26,2607505,Itaíba
26,2607604,Ilha de Itamaracá
26,2607653,Itambé
26,2607703,Itapetim
26,2607752,Itapissuma
26,2607802,Itaquitinga
26,2607901,Jaboatão dos Guararapes
26,2607950,Jaqueira
26,2608008,Jataúba
26,2608057,Jatobá
26,2608107,João Alfredo
26,2608206,Joaquim Nabuco
26,2608255,Jucati
26,2608305,Jupi
26,2608404,Jurema
26,2608453,Lagoa do Carro
26,2608503,Lagoa de Itaenga
26,2608602,Lagoa do Ouro
26,2608701,Lagoa dos Gatos
26,2608750,Lagoa Grande
26,2608800,Lajedo
26,2608909,Limoeiro
26,2609006,Macaparana
26,2609105,Machados
26,2609154,Manari
26,2609204,Maraial
26,2609303,Mirandiba
26,2609402,Moreno
26,2609501,Nazaré da Mata
26,2609600,Olinda
26,2609709,Orobó
26,2609808,Orocó
26,2609907,Ouricuri
26,2610004,Palmares
26,2610103,Palmeirina
26,2610202,Panelas
26,2610301,Paranatama
26,2610400,Parnamirim
26,2610509,Passira
26,2610608,Paudalho
26,2610707,Paulista
26,2610806,Pedra
26,2610905,Pesqueira
26,2611002,Petrolândia
26,2611101,Petrolina
26,2611200,Poção
26,2611309,Pombos
26,2611408,Primavera
26,2611507,Quipapá
26,2611533,Quixaba
26,2611606,Recife
26,2611705,Riacho das Almas
26,2611804,Ribeirão
26,2611903,Rio Formoso
26,2612000,Sairé
26,2612109,Salgadinho
26,2612208,Salgueiro
26,2612307,Saloá
26,2612406,Sanharó
26,2612455,Santa Cruz
26,2612471,Santa Cruz da Baixa Verde
26,2612505,Santa Cruz do Capibaribe
26,2612554,Santa Filomena
26,2612604,Santa Maria da Boa Vista
26,2612703,Santa Maria do Cambucá
26,2612802,Santa Terezinha
26,2612901,São Benedito do Sul
26,2613008,São Bento do Una
26,2613107,São Caitano
26,2613206,São João
26,2613305,São Joaquim do Monte
26,2613404,São José da Coroa Grande
26,2613503,São José do Belmonte
26,2613602,São José do Egito
26,2613701,São Lourenço da Mata
26,2613800,São Vicente Ferrer
26,2613909,Serra Talhada
26,2614006,Serrita
26,2614105,Sertânia
26,2614204,Sirinhaém
26,2614303,Moreilândia
26,2614402,Solidão
26,2614501,Surubim
26,2614600,Tabira
26,2614709,Tacaimbó
26,2614808,Tacaratu
26,2614857,Tamandaré
26,2615003,Taquaritinga do Norte
26,2615102,Terezinha
26,2615201,Terra Nova
26,2615300,Timbaúba
26,2615409,Toritama
26,2615508,Tracunhaém
26,2615607,Trindade
26,2615706,Triunfo
26,2615805,Tupanatinga
26,2615904,Tuparetama
26,2616001,Venturosa
26,2616100,Verdejante
26,2616183,Vertente do Lério
26,2616209,Vertentes
26,2616308,Vicência
26,2616407,Vitória de Santo Antão
26,2616506,Xexéu
27,2700102,Água Branca
27,2700201,Anadia
27,2700300,Arapiraca
27,2700409,Atalaia
27,2700508,Barra de Santo Antônio
27,2700607,Barra de São Miguel
27,2700706,Batalha
27,2700805,Belém
27,2700904,Belo Monte
27,2701001,Boca da Mata
27,2701100,Branquinha
27,2701209,Cacimbinhas
27,2701308,Cajueiro
27,2701357,Campestre
27,2701407,Campo Alegre
27,2701506,Campo Grande
27,2701605,Canapi
27,2701704,Capela
27,2701803,Carneiros
27,2701902,Chã Preta
27,2702009,Coité do Nóia
27,2702108,Colônia Leopoldina
27,2702207,Coqueiro Seco
27,2702306,Coruripe
27,2702355,Craíbas
27,2702405,delmiro Gouveia
27,2702504,dois Riachos
27,2702553,Estrela de Alagoas
27,2702603,Feira Grande
27,2702702,Feliz deserto
27,2702801,Flexeiras
27,2702900,Girau do Ponciano
27,2703007,Ibateguara
27,2703106,Igaci
27,2703205,Igreja Nova
27,2703304,Inhapi
27,2703403,Jacaré dos Homens
27,2703502,Jacuípe
27,2703601,Japaratinga
27,2703700,Jaramataia
27,2703759,Jequiá da Praia
27,2703809,Joaquim Gomes
27,2703908,Jundiá
27,2704005,Junqueiro
27,2704104,Lagoa da Canoa
27,2704203,Limoeiro de Anadia
27,2704302,Maceió
27,2704401,Major Isidoro
27,2704500,Maragogi
27,2704609,Maravilha
27,2704708,Marechal deodoro
27,2704807,Maribondo
27,2704906,Mar Vermelho
27,2705002,Mata Grande
27,2705101,Matriz de Camaragibe
27,2705200,Messias
27,2705309,Minador do Negrão
27,2705408,Monteirópolis
27,2705507,Murici
27,2705606,Novo Lino
27,2705705,Olho D'água das Flores
27,2705804,Olho D'água do Casado
27,2705903,Olho D'água Grande
27,2706000,Olivença
27,2706109,Ouro Branco
27,2706208,Palestina
27,2706307,Palmeira dos Índios
27,2706406,Pão de Açúcar
27,2706422,Pariconha
27,2706448,Paripueira
27,2706505,Passo de Camaragibe
27,2706604,Paulo Jacinto
27,2706703,Penedo
27,2706802,Piaçabuçu
27,2706901,Pilar
27,2707008,Pindoba
27,2707107,Piranhas
27,2707206,Poço das Trincheiras
27,2707305,Porto Calvo
27,2707404,Porto de Pedras
27,2707503,Porto Real do Colégio
27,2707602,Quebrangulo
27,2707701,Rio Largo
27,2707800,Roteiro
27,2707909,Santa Luzia do Norte
27,2708006,Santana do Ipanema
27,2708105,Santana do Mundaú
27,2708204,São Brás
27,2708303,São José da Laje
27,2708402,São José da Tapera
27,2708501,São Luís do Quitunde
27,2708600,São Miguel dos Campos
27,2708709,São Miguel dos Milagres
27,2708808,São Sebastião
27,2708907,Satuba
27,2708956,Senador Rui Palmeira
27,2709004,Tanque D'arca
27,2709103,Taquarana
27,2709152,Teotônio Vilela
27,2709202,Traipu
27,2709301,União dos Palmares
27,2709400,Viçosa
28,2800100,Amparo de São Francisco
28,2800209,Aquidabã
28,2800308,Aracaju
28,2800407,Arauá
28,2800506,Areia Branca
28,2800605,Barra dos Coqueiros
28,2800670,Boquim
28,2800704,Brejo Grande
28,2801009,Campo do Brito
28,2801108,Canhoba
28,2801207,Canindé de São Francisco
28,2801306,Capela
28,2801405,Carira
28,2801504,Carmópolis
28,2801603,Cedro de São João
28,2801702,Cristinápolis
28,2801900,Cumbe
28,2802007,Divina Pastora
28,2802106,Estância
28,2802205,Feira Nova
28,2802304,Frei Paulo
28,2802403,Gararu
28,2802502,General Maynard
28,2802601,Gracho Cardoso
28,2802700,Ilha das Flores
28,2802809,Indiaroba
28,2802908,Itabaiana
28,2803005,Itabaianinha
28,2803104,Itabi
28,2803203,Itaporanga D'ajuda
28,2803302,Japaratuba
28,2803401,Japoatã
28,2803500,Lagarto
28,2803609,Laranjeiras
28,2803708,Macambira
28,2803807,Malhada dos Bois
28,2803906,Malhador
28,2804003,Maruim
28,2804102,Moita Bonita
28,2804201,Monte Alegre de Sergipe
28,2804300,Muribeca
28,2804409,Neópolis
28,2804458,Nossa Senhora Aparecida
28,2804508,Nossa Senhora da Glória
28,2804607,Nossa Senhora das dores
28,2804706,Nossa Senhora de Lourdes
28,2804805,Nossa Senhora do Socorro
28,2804904,Pacatuba
28,2805000,Pedra Mole
28,2805109,Pedrinhas
28,2805208,Pinhão
28,2805307,Pirambu
28,2805406,Poço Redondo
28,2805505,Poço Verde
28,2805604,Porto da Folha
28,2805703,Propriá
28,2805802,Riachão do dantas
28,2805901,Riachuelo
28,2806008,Ribeirópolis
28,2806107,Rosário do Catete
28,2806206,Salgado
28,2806305,Santa Luzia do Itanhy
28,2806404,Santana do São Francisco
28,2806503,Santa Rosa de Lima
28,2806602,Santo Amaro das Brotas
28,2806701,São Cristóvão
28,2806800,São domingos
28,2806909,São Francisco
28,2807006,São Miguel do Aleixo
28,2807105,Simão Dias
28,2807204,Siriri
28,2807303,Telha
28,2807402,Tobias Barreto
28,2807501,Tomar do Geru
28,2807600,Umbaúba
29,2900108,Abaíra
29,2900207,Abaré
29,2900306,Acajutiba
29,2900355,Adustina
29,2900405,Água Fria
29,2900504,Érico Cardoso
29,2900603,Aiquara
29,2900702,Alagoinhas
29,2900801,Alcobaça
29,2900900,Almadina
29,2901007,Amargosa
29,2901106,Amélia Rodrigues
29,2901155,América dourada
29,2901205,Anagé
29,2901304,Andaraí
29,2901353,Andorinha
29,2901403,Angical
29,2901502,Anguera
29,2901601,Antas
29,2901700,Antônio Cardoso
29,2901809,Antônio Gonçalves
29,2901908,Aporá
29,2901957,Apuarema
29,2902005,Aracatu
29,2902054,Araças
29,2902104,Araci
29,2902203,Aramari
29,2902252,Arataca
29,2902302,Aratuípe
29,2902401,Aurelino Leal
29,2902500,Baianópolis
29,2902609,Baixa Grande
29,2902658,Banzaê
29,2902708,Barra
29,2902807,Barra da Estiva
29,2902906,Barra do Choça
29,2903003,Barra do Mendes
29,2903102,Barra do Rocha
29,2903201,Barreiras
29,2903235,Barro Alto
29,2903276,Barrocas
29,2903300,Barro Preto
29,2903409,Belmonte
29,2903508,Belo Campo
29,2903607,Biritinga
29,2903706,Boa Nova
29,2903805,Boa Vista do Tupim
29,2903904,Bom Jesus da Lapa
29,2903953,Bom Jesus da Serra
29,2904001,Boninal
29,2904050,Bonito
29,2904100,Boquira
29,2904209,Botuporã
29,2904308,Brejões
29,2904407,Brejolândia
29,2904506,Brotas de Macaúbas
29,2904605,Brumado
29,2904704,Buerarema
29,2904753,Buritirama
29,2904803,Caatiba
29,2904852,Cabaceiras do Paraguaçu
29,2904902,Cachoeira
29,2905008,Caculé
29,2905107,Caém
29,2905156,Caetanos
29,2905206,Caetité
29,2905305,Cafarnaum
29,2905404,Cairu
29,2905503,Caldeirão Grande
29,2905602,Camacan
29,2905701,Camaçari
29,2905800,Camamu
29,2905909,Campo Alegre de Lourdes
29,2906006,Campo Formoso
29,2906105,Canápolis
29,2906204,Canarana
29,2906303,Canavieiras
29,2906402,Candeal
29,2906501,Candeias
29,2906600,Candiba
29,2906709,Cândido Sales
29,2906808,Cansanção
29,2906824,Canudos
29,2906857,Capela do Alto Alegre
29,2906873,Capim Grosso
29,2906899,Caraíbas
29,2906907,Caravelas
29,2907004,Cardeal da Silva
29,2907103,Carinhanha
29,2907202,Casa Nova
29,2907301,Castro Alves
29,2907400,Catolândia
29,2907509,Catu
29,2907558,Caturama
29,2907608,Central
29,2907707,Chorrochó
29,2907806,Cícero dantas
29,2907905,Cipó
29,2908002,Coaraci
29,2908101,Cocos
29,2908200,Conceição da Feira
29,2908309,Conceição do Almeida
29,2908408,Conceição do Coité
29,2908507,Conceição do Jacuípe
29,2908606,Conde
29,2908705,Condeúba
29,2908804,Contendas do Sincorá
29,2908903,Coração de Maria
29,2909000,Cordeiros
29,2909109,Coribe
29,2909208,Coronel João Sá
29,2909307,Correntina
29,2909406,Cotegipe
29,2909505,Cravolândia
29,2909604,Crisópolis
29,2909703,Cristópolis
29,2909802,Cruz das Almas
29,2909901,Curaçá
29,2910008,Dário Meira
29,2910057,Dias D'ávila
29,2910107,dom Basílio
29,2910206,dom Macedo Costa
29,2910305,Elísio Medrado
29,2910404,Encruzilhada
29,2910503,Entre Rios
29,2910602,Esplanada
29,2910701,Euclides da Cunha
29,2910727,Eunápolis
29,2910750,Fátima
29,2910776,Feira da Mata
29,2910800,Feira de Santana
29,2910859,Filadélfia
29,2910909,Firmino Alves
29,2911006,Floresta Azul
29,2911105,Formosa do Rio Preto
29,2911204,Gandu
29,2911253,Gavião
29,2911303,Gentio do Ouro
29,2911402,Glória
29,2911501,Gongogi
29,2911600,Governador Mangabeira
29,2911659,Guajeru
29,2911709,Guanambi
29,2911808,Guaratinga
29,2911857,Heliópolis
29,2911907,Iaçu
29,2912004,Ibiassucê
29,2912103,Ibicaraí
29,2912202,Ibicoara
29,2912301,Ibicuí
29,2912400,Ibipeba
29,2912509,Ibipitanga
29,2912608,Ibiquera
29,2912707,Ibirapitanga
29,2912806,Ibirapuã
29,2912905,Ibirataia
29,2913002,Ibitiara
29,2913101,Ibititá
29,2913200,Ibotirama
29,2913309,Ichu
29,2913408,Igaporã
29,2913457,Igrapiúna
29,2913507,Iguaí
29,2913606,Ilhéus
29,2913705,Inhambupe
29,2913804,Ipecaetá
29,2913903,Ipiaú
29,2914000,Ipirá
29,2914109,Ipupiara
29,2914208,Irajuba
29,2914307,Iramaia
29,2914406,Iraquara
29,2914505,Irará
29,2914604,Irecê
29,2914653,Itabela
29,2914703,Itaberaba
29,2914802,Itabuna
29,2914901,Itacaré
29,2915007,Itaeté
29,2915106,Itagi
29,2915205,Itagibá
29,2915304,Itagimirim
29,2915353,Itaguaçu da Bahia
29,2915403,Itaju do Colônia
29,2915502,Itajuípe
29,2915601,Itamaraju
29,2915700,Itamari
29,2915809,Itambé
29,2915908,Itanagra
29,2916005,Itanhém
29,2916104,Itaparica
29,2916203,Itapé
29,2916302,Itapebi
29,2916401,Itapetinga
29,2916500,Itapicuru
29,2916609,Itapitanga
29,2916708,Itaquara
29,2916807,Itarantim
29,2916856,Itatim
29,2916906,Itiruçu
29,2917003,Itiúba
29,2917102,Itororó
29,2917201,Ituaçu
29,2917300,Ituberá
29,2917334,Iuiú
29,2917359,Jaborandi
29,2917409,Jacaraci
29,2917508,Jacobina
29,2917607,Jaguaquara
29,2917706,Jaguarari
29,2917805,Jaguaripe
29,2917904,Jandaíra
29,2918001,Jequié
29,2918100,Jeremoabo
29,2918209,Jiquiriçá
29,2918308,Jitaúna
29,2918357,João dourado
29,2918407,Juazeiro
29,2918456,Jucuruçu
29,2918506,Jussara
29,2918555,Jussari
29,2918605,Jussiape
29,2918704,Lafaiete Coutinho
29,2918753,Lagoa Real
29,2918803,Laje
29,2918902,Lajedão
29,2919009,Lajedinho
29,2919058,Lajedo do Tabocal
29,2919108,Lamarão
29,2919157,Lapão
29,2919207,Lauro de Freitas
29,2919306,Lençóis
29,2919405,Licínio de Almeida
29,2919504,Livramento de Nossa Senhora
29,2919553,Luís Eduardo Magalhães
29,2919603,Macajuba
29,2919702,Macarani
29,2919801,Macaúbas
29,2919900,Macururé
29,2919926,Madre de deus
29,2919959,Maetinga
29,2920007,Maiquinique
29,2920106,Mairi
29,2920205,Malhada
29,2920304,Malhada de Pedras
29,2920403,Manoel Vitorino
29,2920452,Mansidão
29,2920502,Maracás
29,2920601,Maragogipe
29,2920700,Maraú
29,2920809,Marcionílio Souza
29,2920908,Mascote
29,2921005,Mata de São João
29,2921054,Matina
29,2921104,Medeiros Neto
29,2921203,Miguel Calmon
29,2921302,Milagres
29,2921401,Mirangaba
29,2921450,Mirante
29,2921500,Monte Santo
29,2921609,Morpará
29,2921708,Morro do Chapéu
29,2921807,Mortugaba
29,2921906,Mucugê
29,2922003,Mucuri
29,2922052,Mulungu do Morro
29,2922102,Mundo Novo
29,2922201,Muniz Ferreira
29,2922250,Muquém de São Francisco
29,2922300,Muritiba
29,2922409,Mutuípe
29,2922508,Nazaré
29,2922607,Nilo Peçanha
29,2922656,Nordestina
29,2922706,Nova Canaã
29,2922730,Nova Fátima
29,2922755,Nova Ibiá
29,2922805,Nova Itarana
29,2922854,Nova Redenção
29,2922904,Nova Soure
29,2923001,Nova Viçosa
29,2923035,Novo Horizonte
29,2923050,Novo Triunfo
29,2923100,Olindina
29,2923209,Oliveira dos Brejinhos
29,2923308,Ouriçangas
29,2923357,Ourolândia
29,2923407,Palmas de Monte Alto
29,2923506,Palmeiras
29,2923605,Paramirim
29,2923704,Paratinga
29,2923803,Paripiranga
29,2923902,Pau Brasil
29,2924009,Paulo Afonso
29,2924058,Pé de Serra
29,2924108,Pedrão
29,2924207,Pedro Alexandre
29,2924306,Piatã
29,2924405,Pilão Arcado
29,2924504,Pindaí
29,2924603,Pindobaçu
29,2924652,Pintadas
29,2924678,Piraí do Norte
29,2924702,Piripá
29,2924801,Piritiba
29,2924900,Planaltino
29,2925006,Planalto
29,2925105,Poções
29,2925204,Pojuca
29,2925253,Ponto Novo
29,2925303,Porto Seguro
29,2925402,Potiraguá
29,2925501,Prado
29,2925600,Presidente Dutra
29,2925709,Presidente Jânio Quadros
29,2925758,Presidente Tancredo Neves
29,2925808,Queimadas
29,2925907,Quijingue
29,2925931,Quixabeira
29,2925956,Rafael Jambeiro
29,2926004,Remanso
29,2926103,Retirolândia
29,2926202,Riachão das Neves
29,2926301,Riachão do Jacuípe
29,2926400,Riacho de Santana
29,2926509,Ribeira do Amparo
29,2926608,Ribeira do Pombal
29,2926657,Ribeirão do Largo
29,2926707,Rio de Contas
29,2926806,Rio do Antônio
29,2926905,Rio do Pires
29,2927002,Rio Real
29,2927101,Rodelas
29,2927200,Ruy Barbosa
29,2927309,Salinas da Margarida
29,2927408,Salvador
29,2927507,Santa Bárbara
29,2927606,Santa Brígida
29,2927705,Santa Cruz Cabrália
29,2927804,Santa Cruz da Vitória
29,2927903,Santa Inês
29,2928000,Santaluz
29,2928059,Santa Luzia
29,2928109,Santa Maria da Vitória
29,2928208,Santana
29,2928307,Santanópolis
29,2928406,Santa Rita de Cássia
29,2928505,Santa Teresinha
29,2928604,Santo Amaro
29,2928703,Santo Antônio de Jesus
29,2928802,Santo Estêvão
29,2928901,São desidério
29,2928950,São domingos
29,2929008,São Félix
29,2929057,São Félix do Coribe
29,2929107,São Felipe
29,2929206,São Francisco do Conde
29,2929255,São Gabriel
29,2929305,São Gonçalo dos Campos
29,2929354,São José da Vitória
29,2929370,São José do Jacuípe
29,2929404,São Miguel das Matas
29,2929503,São Sebastião do Passé
29,2929602,Sapeaçu
29,2929701,Sátiro Dias
29,2929750,Saubara
29,2929800,Saúde
29,2929909,Seabra
29,2930006,Sebastião Laranjeiras
29,2930105,Senhor do Bonfim
29,2930154,Serra do Ramalho
29,2930204,Sento Sé
29,2930303,Serra dourada
29,2930402,Serra Preta
29,2930501,Serrinha
29,2930600,Serrolândia
29,2930709,Simões Filho
29,2930758,Sítio do Mato
29,2930766,Sítio do Quinto
29,2930774,Sobradinho
29,2930808,Souto Soares
29,2930907,Tabocas do Brejo Velho
29,2931004,Tanhaçu
29,2931053,Tanque Novo
29,2931103,Tanquinho
29,2931202,Taperoá
29,2931301,Tapiramutá
29,2931350,Teixeira de Freitas
29,2931400,Teodoro Sampaio
29,2931509,Teofilândia
29,2931608,Teolândia
29,2931707,Terra Nova
29,2931806,Tremedal
29,2931905,Tucano
29,2932002,Uauá
29,2932101,Ubaíra
29,2932200,Ubaitaba
29,2932309,Ubatã
29,2932408,Uibaí
29,2932457,Umburanas
29,2932507,Una
29,2932606,Urandi
29,2932705,Uruçuca
29,2932804,Utinga
29,2932903,Valença
29,2933000,Valente
29,2933059,Várzea da Roça
29,2933109,Várzea do Poço
29,2933158,Várzea Nova
29,2933174,Varzedo
29,2933208,Vera Cruz
29,2933257,Vereda
29,2933307,Vitória da Conquista
29,2933406,Wagner
29,2933455,Wanderley
29,2933505,Wenceslau Guimarães
29,2933604,Xique-Xique
31,3100104,Abadia dos dourados
31,3100203,Abaeté
31,3100302,Abre Campo
31,3100401,Acaiaca
31,3100500,Açucena
31,3100609,Água Boa
31,3100708,Água Comprida
31,3100807,Aguanil
31,3100906,Águas Formosas
31,3101003,Águas Vermelhas
31,3101102,Aimorés
31,3101201,Aiuruoca
31,3101300,Alagoa
31,3101409,Albertina
31,3101508,Além Paraíba
31,3101607,Alfenas
31,3101631,Alfredo Vasconcelos
31,3101706,Almenara
31,3101805,Alpercata
31,3101904,Alpinópolis
31,3102001,Alterosa
31,3102050,Alto Caparaó
31,3102100,Alto Rio doce
31,3102209,Alvarenga
31,3102308,Alvinópolis
31,3102407,Alvorada de Minas
31,3102506,Amparo do Serra
31,3102605,Andradas
31,3102704,Cachoeira de Pajeú
31,3102803,Andrelândia
31,3102852,Angelândia
31,3102902,Antônio Carlos
31,3103009,Antônio Dias
31,3103108,Antônio Prado de Minas
31,3103207,Araçaí
31,3103306,Aracitaba
31,3103405,Araçuaí
31,3103504,Araguari
31,3103603,Arantina
31,3103702,Araponga
31,3103751,Araporã
31,3103801,Arapuá
31,3103900,Araújos
31,3104007,Araxá
31,3104106,Arceburgo
31,3104205,Arcos
31,3104304,Areado
31,3104403,Argirita
31,3104452,Aricanduva
31,3104502,Arinos
31,3104601,Astolfo Dutra
31,3104700,Ataléia
31,3104809,Augusto de Lima
31,3104908,Baependi
31,3105004,Baldim
31,3105103,Bambuí
31,3105202,Bandeira
31,3105301,Bandeira do Sul
31,3105400,Barão de Cocais
31,3105509,Barão de Monte Alto
31,3105608,Barbacena
31,3105707,Barra Longa
31,3105905,Barroso
31,3106002,Bela Vista de Minas
31,3106101,Belmiro Braga
31,3106200,Belo Horizonte
31,3106309,Belo Oriente
31,3106408,Belo Vale
31,3106507,Berilo
31,3106606,Bertópolis
31,3106655,Berizal
31,3106705,Betim
31,3106804,Bias Fortes
31,3106903,Bicas
31,3107000,Biquinhas
31,3107109,Boa Esperança
31,3107208,Bocaina de Minas
31,3107307,Bocaiúva
31,3107406,Bom despacho
31,3107505,Bom Jardim de Minas
31,3107604,Bom Jesus da Penha
31,3107703,Bom Jesus do Amparo
31,3107802,Bom Jesus do Galho
31,3107901,Bom Repouso
31,3108008,Bom Sucesso
31,3108107,Bonfim
31,3108206,Bonfinópolis de Minas
31,3108255,Bonito de Minas
31,3108305,Borda da Mata
31,3108404,Botelhos
31,3108503,Botumirim
31,3108552,Brasilândia de Minas
31,3108602,Brasília de Minas
31,3108701,Brás Pires
31,3108800,Braúnas
31,3108909,Brazópolis
31,3109006,Brumadinho
31,3109105,Bueno Brandão
31,3109204,Buenópolis
31,3109253,Bugre
31,3109303,Buritis
31,3109402,Buritizeiro
31,3109451,Cabeceira Grande
31,3109501,Cabo Verde
31,3109600,Cachoeira da Prata
31,3109709,Cachoeira de Minas
31,3109808,Cachoeira dourada
31,3109907,Caetanópolis
31,3110004,Caeté
31,3110103,Caiana
31,3110202,Cajuri
31,3110301,Caldas
31,3110400,Camacho
31,3110509,Camanducaia
31,3110608,Cambuí
31,3110707,Cambuquira
31,3110806,Campanário
31,3110905,Campanha
31,3111002,Campestre
31,3111101,Campina Verde
31,3111150,Campo Azul
31,3111200,Campo Belo
31,3111309,Campo do Meio
31,3111408,Campo Florido
31,3111507,Campos Altos
31,3111606,Campos Gerais
31,3111705,Canaã
31,3111804,Canápolis
31,3111903,Cana Verde
31,3112000,Candeias
31,3112059,Cantagalo
31,3112109,Caparaó
31,3112208,Capela Nova
31,3112307,Capelinha
31,3112406,Capetinga
31,3112505,Capim Branco
31,3112604,Capinópolis
31,3112653,Capitão Andrade
31,3112703,Capitão Enéas
31,3112802,Capitólio
31,3112901,Caputira
31,3113008,Caraí
31,3113107,Caranaíba
31,3113206,Carandaí
31,3113305,Carangola
31,3113404,Caratinga
31,3113503,Carbonita
31,3113602,Careaçu
31,3113701,Carlos Chagas
31,3113800,Carmésia
31,3113909,Carmo da Cachoeira
31,3114006,Carmo da Mata
31,3114105,Carmo de Minas
31,3114204,Carmo do Cajuru
31,3114303,Carmo do Paranaíba
31,3114402,Carmo do Rio Claro
31,3114501,Carmópolis de Minas
31,3114550,Carneirinho
31,3114600,Carrancas
31,3114709,Carvalhópolis
31,3114808,Carvalhos
31,3114907,Casa Grande
31,3115003,Cascalho Rico
31,3115102,Cássia
31,3115201,Conceição da Barra de Minas
31,3115300,Cataguases
31,3115359,Catas Altas
31,3115409,Catas Altas da Noruega
31,3115458,Catuji
31,3115474,Catuti
31,3115508,Caxambu
31,3115607,Cedro do Abaeté
31,3115706,Central de Minas
31,3115805,Centralina
31,3115904,Chácara
31,3116001,Chalé
31,3116100,Chapada do Norte
31,3116159,Chapada Gaúcha
31,3116209,Chiador
31,3116308,Cipotânea
31,3116407,Claraval
31,3116506,Claro dos Poções
31,3116605,Cláudio
31,3116704,Coimbra
31,3116803,Coluna
31,3116902,Comendador Gomes
31,3117009,Comercinho
31,3117108,Conceição da Aparecida
31,3117207,Conceição das Pedras
31,3117306,Conceição das Alagoas
31,3117405,Conceição de Ipanema
31,3117504,Conceição do Mato dentro
31,3117603,Conceição do Pará
31,3117702,Conceição do Rio Verde
31,3117801,Conceição dos Ouros
31,3117836,Cônego Marinho
31,3117876,Confins
31,3117900,Congonhal
31,3118007,Congonhas
31,3118106,Congonhas do Norte
31,3118205,Conquista
31,3118304,Conselheiro Lafaiete
31,3118403,Conselheiro Pena
31,3118502,Consolação
31,3118601,Contagem
31,3118700,Coqueiral
31,3118809,Coração de Jesus
31,3118908,Cordisburgo
31,3119005,Cordislândia
31,3119104,Corinto
31,3119203,Coroaci
31,3119302,Coromandel
31,3119401,Coronel Fabriciano
31,3119500,Coronel Murta
31,3119609,Coronel Pacheco
31,3119708,Coronel Xavier Chaves
31,3119807,Córrego danta
31,3119906,Córrego do Bom Jesus
31,3119955,Córrego Fundo
31,3120003,Córrego Novo
31,3120102,Couto de Magalhães de Minas
31,3120151,Crisólita
31,3120201,Cristais
31,3120300,Cristália
31,3120409,Cristiano Otoni
31,3120508,Cristina
31,3120607,Crucilândia
31,3120706,Cruzeiro da Fortaleza
31,3120805,Cruzília
31,3120839,Cuparaque
31,3120870,Curral de dentro
31,3120904,Curvelo
31,3121001,datas
31,3121100,delfim Moreira
31,3121209,delfinópolis
31,3121258,delta
31,3121308,descoberto
31,3121407,desterro de Entre Rios
31,3121506,desterro do Melo
31,3121605,Diamantina
31,3121704,Diogo de Vasconcelos
31,3121803,Dionísio
31,3121902,Divinésia
31,3122009,Divino
31,3122108,Divino das Laranjeiras
31,3122207,Divinolândia de Minas
31,3122306,Divinópolis
31,3122355,Divisa Alegre
31,3122405,Divisa Nova
31,3122454,Divisópolis
31,3122470,dom Bosco
31,3122504,dom Cavati
31,3122603,dom Joaquim
31,3122702,dom Silvério
31,3122801,dom Viçoso
31,3122900,dona Eusébia
31,3123007,dores de Campos
31,3123106,dores de Guanhães
31,3123205,dores do Indaiá
31,3123304,dores do Turvo
31,3123403,doresópolis
31,3123502,douradoquara
31,3123528,Durandé
31,3123601,Elói Mendes
31,3123700,Engenheiro Caldas
31,3123809,Engenheiro Navarro
31,3123858,Entre Folhas
31,3123908,Entre Rios de Minas
31,3124005,Ervália
31,3124104,Esmeraldas
31,3124203,Espera Feliz
31,3124302,Espinosa
31,3124401,Espírito Santo do dourado
31,3124500,Estiva
31,3124609,Estrela dalva
31,3124708,Estrela do Indaiá
31,3124807,Estrela do Sul
31,3124906,Eugenópolis
31,3125002,Ewbank da Câmara
31,3125101,Extrema
31,3125200,Fama
31,3125309,Faria Lemos
31,3125408,Felício dos Santos
31,3125507,São Gonçalo do Rio Preto
31,3125606,Felisburgo
31,3125705,Felixlândia
31,3125804,Fernandes Tourinho
31,3125903,Ferros
31,3125952,Fervedouro
31,3126000,Florestal
31,3126109,Formiga
31,3126208,Formoso
31,3126307,Fortaleza de Minas
31,3126406,Fortuna de Minas
31,3126505,Francisco Badaró
31,3126604,Francisco Dumont
31,3126703,Francisco Sá
31,3126752,Franciscópolis
31,3126802,Frei Gaspar
31,3126901,Frei Inocêncio
31,3126950,Frei Lagonegro
31,3127008,Fronteira
31,3127057,Fronteira dos Vales
31,3127073,Fruta de Leite
31,3127107,Frutal
31,3127206,Funilândia
31,3127305,Galiléia
31,3127339,Gameleiras
31,3127354,Glaucilândia
31,3127370,Goiabeira
31,3127388,Goianá
31,3127404,Gonçalves
31,3127503,Gonzaga
31,3127602,Gouveia
31,3127701,Governador Valadares
31,3127800,Grão Mogol
31,3127909,Grupiara
31,3128006,Guanhães
31,3128105,Guapé
31,3128204,Guaraciaba
31,3128253,Guaraciama
31,3128303,Guaranésia
31,3128402,Guarani
31,3128501,Guarará
31,3128600,Guarda-Mor
31,3128709,Guaxupé
31,3128808,Guidoval
31,3128907,Guimarânia
31,3129004,Guiricema
31,3129103,Gurinhatã
31,3129202,Heliodora
31,3129301,Iapu
31,3129400,Ibertioga
31,3129509,Ibiá
31,3129608,Ibiaí
31,3129657,Ibiracatu
31,3129707,Ibiraci
31,3129806,Ibirité
31,3129905,Ibitiúra de Minas
31,3130002,Ibituruna
31,3130051,Icaraí de Minas
31,3130101,Igarapé
31,3130200,Igaratinga
31,3130309,Iguatama
31,3130408,Ijaci
31,3130507,Ilicínea
31,3130556,Imbé de Minas
31,3130606,Inconfidentes
31,3130655,Indaiabira
31,3130705,Indianópolis
31,3130804,Ingaí
31,3130903,Inhapim
31,3131000,Inhaúma
31,3131109,Inimutaba
31,3131158,Ipaba
31,3131208,Ipanema
31,3131307,Ipatinga
31,3131406,Ipiaçu
31,3131505,Ipuiúna
31,3131604,Iraí de Minas
31,3131703,Itabira
31,3131802,Itabirinha
31,3131901,Itabirito
31,3132008,Itacambira
31,3132107,Itacarambi
31,3132206,Itaguara
31,3132305,Itaipé
31,3132404,Itajubá
31,3132503,Itamarandiba
31,3132602,Itamarati de Minas
31,3132701,Itambacuri
31,3132800,Itambé do Mato dentro
31,3132909,Itamogi
31,3133006,Itamonte
31,3133105,Itanhandu
31,3133204,Itanhomi
31,3133303,Itaobim
31,3133402,Itapagipe
31,3133501,Itapecerica
31,3133600,Itapeva
31,3133709,Itatiaiuçu
31,3133758,Itaú de Minas
31,3133808,Itaúna
31,3133907,Itaverava
31,3134004,Itinga
31,3134103,Itueta
31,3134202,Ituiutaba
31,3134301,Itumirim
31,3134400,Iturama
31,3134509,Itutinga
31,3134608,Jaboticatubas
31,3134707,Jacinto
31,3134806,Jacuí
31,3134905,Jacutinga
31,3135001,Jaguaraçu
31,3135050,Jaíba
31,3135076,Jampruca
31,3135100,Janaúba
31,3135209,Januária
31,3135308,Japaraíba
31,3135357,Japonvar
31,3135407,Jeceaba
31,3135456,Jenipapo de Minas
31,3135506,Jequeri
31,3135605,Jequitaí
31,3135704,Jequitibá
31,3135803,Jequitinhonha
31,3135902,Jesuânia
31,3136009,Joaíma
31,3136108,Joanésia
31,3136207,João Monlevade
31,3136306,João Pinheiro
31,3136405,Joaquim Felício
31,3136504,Jordânia
31,3136520,José Gonçalves de Minas
31,3136553,José Raydan
31,3136579,Josenópolis
31,3136603,Nova União
31,3136652,Juatuba
31,3136702,Juiz de Fora
31,3136801,Juramento
31,3136900,Juruaia
31,3136959,Juvenília
31,3137007,Ladainha
31,3137106,Lagamar
31,3137205,Lagoa da Prata
31,3137304,Lagoa dos Patos
31,3137403,Lagoa dourada
31,3137502,Lagoa Formosa
31,3137536,Lagoa Grande
31,3137601,Lagoa Santa
31,3137700,Lajinha
31,3137809,Lambari
31,3137908,Lamim
31,3138005,Laranjal
31,3138104,Lassance
31,3138203,Lavras
31,3138302,Leandro Ferreira
31,3138351,Leme do Prado
31,3138401,Leopoldina
31,3138500,Liberdade
31,3138609,Lima Duarte
31,3138625,Limeira do Oeste
31,3138658,Lontra
31,3138674,Luisburgo
31,3138682,Luislândia
31,3138708,Luminárias
31,3138807,Luz
31,3138906,Machacalis
31,3139003,Machado
31,3139102,Madre de deus de Minas
31,3139201,Malacacheta
31,3139250,Mamonas
31,3139300,Manga
31,3139409,Manhuaçu
31,3139508,Manhumirim
31,3139607,Mantena
31,3139706,Maravilhas
31,3139805,Mar de Espanha
31,3139904,Maria da Fé
31,3140001,Mariana
31,3140100,Marilac
31,3140159,Mário Campos
31,3140209,Maripá de Minas
31,3140308,Marliéria
31,3140407,Marmelópolis
31,3140506,Martinho Campos
31,3140530,Martins Soares
31,3140555,Mata Verde
31,3140605,Materlândia
31,3140704,Mateus Leme
31,3140803,Matias Barbosa
31,3140852,Matias Cardoso
31,3140902,Matipó
31,3141009,Mato Verde
31,3141108,Matozinhos
31,3141207,Matutina
31,3141306,Medeiros
31,3141405,Medina
31,3141504,Mendes Pimentel
31,3141603,Mercês
31,3141702,Mesquita
31,3141801,Minas Novas
31,3141900,Minduri
31,3142007,Mirabela
31,3142106,Miradouro
31,3142205,Miraí
31,3142254,Miravânia
31,3142304,Moeda
31,3142403,Moema
31,3142502,Monjolos
31,3142601,Monsenhor Paulo
31,3142700,Montalvânia
31,3142809,Monte Alegre de Minas
31,3142908,Monte Azul
31,3143005,Monte Belo
31,3143104,Monte Carmelo
31,3143153,Monte Formoso
31,3143203,Monte Santo de Minas
31,3143302,Montes Claros
31,3143401,Monte Sião
31,3143450,Montezuma
31,3143500,Morada Nova de Minas
31,3143609,Morro da Garça
31,3143708,Morro do Pilar
31,3143807,Munhoz
31,3143906,Muriaé
31,3144003,Mutum
31,3144102,Muzambinho
31,3144201,Nacip Raydan
31,3144300,Nanuque
31,3144359,Naque
31,3144375,Natalândia
31,3144409,Natércia
31,3144508,Nazareno
31,3144607,Nepomuceno
31,3144656,Ninheira
31,3144672,Nova Belém
31,3144706,Nova Era
31,3144805,Nova Lima
31,3144904,Nova Módica
31,3145000,Nova Ponte
31,3145059,Nova Porteirinha
31,3145109,Nova Resende
31,3145208,Nova Serrana
31,3145307,Novo Cruzeiro
31,3145356,Novo Oriente de Minas
31,3145372,Novorizonte
31,3145406,Olaria
31,3145455,Olhos-D'água
31,3145505,Olímpio Noronha
31,3145604,Oliveira
31,3145703,Oliveira Fortes
31,3145802,Onça de Pitangui
31,3145851,Oratórios
31,3145877,Orizânia
31,3145901,Ouro Branco
31,3146008,Ouro Fino
31,3146107,Ouro Preto
31,3146206,Ouro Verde de Minas
31,3146255,Padre Carvalho
31,3146305,Padre Paraíso
31,3146404,Paineiras
31,3146503,Pains
31,3146552,Pai Pedro
31,3146602,Paiva
31,3146701,Palma
31,3146750,Palmópolis
31,3146909,Papagaios
31,3147006,Paracatu
31,3147105,Pará de Minas
31,3147204,Paraguaçu
31,3147303,Paraisópolis
31,3147402,Paraopeba
31,3147501,Passabém
31,3147600,Passa Quatro
31,3147709,Passa Tempo
31,3147808,Passa-Vinte
31,3147907,Passos
31,3147956,Patis
31,3148004,Patos de Minas
31,3148103,Patrocínio
31,3148202,Patrocínio do Muriaé
31,3148301,Paula Cândido
31,3148400,Paulistas
31,3148509,Pavão
31,3148608,Peçanha
31,3148707,Pedra Azul
31,3148756,Pedra Bonita
31,3148806,Pedra do Anta
31,3148905,Pedra do Indaiá
31,3149002,Pedra dourada
31,3149101,Pedralva
31,3149150,Pedras de Maria da Cruz
31,3149200,Pedrinópolis
31,3149309,Pedro Leopoldo
31,3149408,Pedro Teixeira
31,3149507,Pequeri
31,3149606,Pequi
31,3149705,Perdigão
31,3149804,Perdizes
31,3149903,Perdões
31,3149952,Periquito
31,3150000,Pescador
31,3150109,Piau
31,3150158,Piedade de Caratinga
31,3150208,Piedade de Ponte Nova
31,3150307,Piedade do Rio Grande
31,3150406,Piedade dos Gerais
31,3150505,Pimenta
31,3150539,Pingo-D'água
31,3150570,Pintópolis
31,3150604,Piracema
31,3150703,Pirajuba
31,3150802,Piranga
31,3150901,Piranguçu
31,3151008,Piranguinho
31,3151107,Pirapetinga
31,3151206,Pirapora
31,3151305,Piraúba
31,3151404,Pitangui
31,3151503,Piumhi
31,3151602,Planura
31,3151701,Poço Fundo
31,3151800,Poços de Caldas
31,3151909,Pocrane
31,3152006,Pompéu
31,3152105,Ponte Nova
31,3152131,Ponto Chique
31,3152170,Ponto dos Volantes
31,3152204,Porteirinha
31,3152303,Porto Firme
31,3152402,Poté
31,3152501,Pouso Alegre
31,3152600,Pouso Alto
31,3152709,Prados
31,3152808,Prata
31,3152907,Pratápolis
31,3153004,Pratinha
31,3153103,Presidente Bernardes
31,3153202,Presidente Juscelino
31,3153301,Presidente Kubitschek
31,3153400,Presidente Olegário
31,3153509,Alto Jequitibá
31,3153608,Prudente de Morais
31,3153707,Quartel Geral
31,3153806,Queluzito
31,3153905,Raposos
31,3154002,Raul Soares
31,3154101,Recreio
31,3154150,Reduto
31,3154200,Resende Costa
31,3154309,Resplendor
31,3154408,Ressaquinha
31,3154457,Riachinho
31,3154507,Riacho dos Machados
31,3154606,Ribeirão das Neves
31,3154705,Ribeirão Vermelho
31,3154804,Rio Acima
31,3154903,Rio Casca
31,3155009,Rio doce
31,3155108,Rio do Prado
31,3155207,Rio Espera
31,3155306,Rio Manso
31,3155405,Rio Novo
31,3155504,Rio Paranaíba
31,3155603,Rio Pardo de Minas
31,3155702,Rio Piracicaba
31,3155801,Rio Pomba
31,3155900,Rio Preto
31,3156007,Rio Vermelho
31,3156106,Ritápolis
31,3156205,Rochedo de Minas
31,3156304,Rodeiro
31,3156403,Romaria
31,3156452,Rosário da Limeira
31,3156502,Rubelita
31,3156601,Rubim
31,3156700,Sabará
31,3156809,Sabinópolis
31,3156908,Sacramento
31,3157005,Salinas
31,3157104,Salto da Divisa
31,3157203,Santa Bárbara
31,3157252,Santa Bárbara do Leste
31,3157278,Santa Bárbara do Monte Verde
31,3157302,Santa Bárbara do Tugúrio
31,3157336,Santa Cruz de Minas
31,3157377,Santa Cruz de Salinas
31,3157401,Santa Cruz do Escalvado
31,3157500,Santa Efigênia de Minas
31,3157609,Santa Fé de Minas
31,3157658,Santa Helena de Minas
31,3157708,Santa Juliana
31,3157807,Santa Luzia
31,3157906,Santa Margarida
31,3158003,Santa Maria de Itabira
31,3158102,Santa Maria do Salto
31,3158201,Santa Maria do Suaçuí
31,3158300,Santana da Vargem
31,3158409,Santana de Cataguases
31,3158508,Santana de Pirapama
31,3158607,Santana do deserto
31,3158706,Santana do Garambéu
31,3158805,Santana do Jacaré
31,3158904,Santana do Manhuaçu
31,3158953,Santana do Paraíso
31,3159001,Santana do Riacho
31,3159100,Santana dos Montes
31,3159209,Santa Rita de Caldas
31,3159308,Santa Rita de Jacutinga
31,3159357,Santa Rita de Minas
31,3159407,Santa Rita de Ibitipoca
31,3159506,Santa Rita do Itueto
31,3159605,Santa Rita do Sapucaí
31,3159704,Santa Rosa da Serra
31,3159803,Santa Vitória
31,3159902,Santo Antônio do Amparo
31,3160009,Santo Antônio do Aventureiro
31,3160108,Santo Antônio do Grama
31,3160207,Santo Antônio do Itambé
31,3160306,Santo Antônio do Jacinto
31,3160405,Santo Antônio do Monte
31,3160454,Santo Antônio do Retiro
31,3160504,Santo Antônio do Rio Abaixo
31,3160603,Santo Hipólito
31,3160702,Santos Dumont
31,3160801,São Bento Abade
31,3160900,São Brás do Suaçuí
31,3160959,São domingos das dores
31,3161007,São domingos do Prata
31,3161056,São Félix de Minas
31,3161106,São Francisco
31,3161205,São Francisco de Paula
31,3161304,São Francisco de Sales
31,3161403,São Francisco do Glória
31,3161502,São Geraldo
31,3161601,São Geraldo da Piedade
31,3161650,São Geraldo do Baixio
31,3161700,São Gonçalo do Abaeté
31,3161809,São Gonçalo do Pará
31,3161908,São Gonçalo do Rio Abaixo
31,3162005,São Gonçalo do Sapucaí
31,3162104,São Gotardo
31,3162203,São João Batista do Glória
31,3162252,São João da Lagoa
31,3162302,São João da Mata
31,3162401,São João da Ponte
31,3162450,São João das Missões
31,3162500,São João del Rei
31,3162559,São João do Manhuaçu
31,3162575,São João do Manteninha
31,3162609,São João do Oriente
31,3162658,São João do Pacuí
31,3162708,São João do Paraíso
31,3162807,São João Evangelista
31,3162906,São João Nepomuceno
31,3162922,São Joaquim de Bicas
31,3162948,São José da Barra
31,3162955,São José da Lapa
31,3163003,São José da Safira
31,3163102,São José da Varginha
31,3163201,São José do Alegre
31,3163300,São José do Divino
31,3163409,São José do Goiabal
31,3163508,São José do Jacuri
31,3163607,São José do Mantimento
31,3163706,São Lourenço
31,3163805,São Miguel do Anta
31,3163904,São Pedro da União
31,3164001,São Pedro dos Ferros
31,3164100,São Pedro do Suaçuí
31,3164209,São Romão
31,3164308,São Roque de Minas
31,3164407,São Sebastião da Bela Vista
31,3164431,São Sebastião da Vargem Alegre
31,3164472,São Sebastião do Anta
31,3164506,São Sebastião do Maranhão
31,3164605,São Sebastião do Oeste
31,3164704,São Sebastião do Paraíso
31,3164803,São Sebastião do Rio Preto
31,3164902,São Sebastião do Rio Verde
31,3165008,São Tiago
31,3165107,São Tomás de Aquino
31,3165206,São Thomé das Letras
31,3165305,São Vicente de Minas
31,3165404,Sapucaí-Mirim
31,3165503,Sardoá
31,3165537,Sarzedo
31,3165552,Setubinha
31,3165560,Sem-Peixe
31,3165578,Senador Amaral
31,3165602,Senador Cortes
31,3165701,Senador Firmino
31,3165800,Senador José Bento
31,3165909,Senador Modestino Gonçalves
31,3166006,Senhora de Oliveira
31,3166105,Senhora do Porto
31,3166204,Senhora dos Remédios
31,3166303,Sericita
31,3166402,Seritinga
31,3166501,Serra Azul de Minas
31,3166600,Serra da Saudade
31,3166709,Serra dos Aimorés
31,3166808,Serra do Salitre
31,3166907,Serrania
31,3166956,Serranópolis de Minas
31,3167004,Serranos
31,3167103,Serro
31,3167202,Sete Lagoas
31,3167301,Silveirânia
31,3167400,Silvianópolis
31,3167509,Simão Pereira
31,3167608,Simonésia
31,3167707,Sobrália
31,3167806,Soledade de Minas
31,3167905,Tabuleiro
31,3168002,Taiobeiras
31,3168051,Taparuba
31,3168101,Tapira
31,3168200,Tapiraí
31,3168309,Taquaraçu de Minas
31,3168408,Tarumirim
31,3168507,Teixeiras
31,3168606,Teófilo Otoni
31,3168705,Timóteo
31,3168804,Tiradentes
31,3168903,Tiros
31,3169000,Tocantins
31,3169059,Tocos do Moji
31,3169109,Toledo
31,3169208,Tombos
31,3169307,Três Corações
31,3169356,Três Marias
31,3169406,Três Pontas
31,3169505,Tumiritinga
31,3169604,Tupaciguara
31,3169703,Turmalina
31,3169802,Turvolândia
31,3169901,Ubá
31,3170008,Ubaí
31,3170057,Ubaporanga
31,3170107,Uberaba
31,3170206,Uberlândia
31,3170305,Umburatiba
31,3170404,Unaí
31,3170438,União de Minas
31,3170479,Uruana de Minas
31,3170503,Urucânia
31,3170529,Urucuia
31,3170578,Vargem Alegre
31,3170602,Vargem Bonita
31,3170651,Vargem Grande do Rio Pardo
31,3170701,Varginha
31,3170750,Varjão de Minas
31,3170800,Várzea da Palma
31,3170909,Varzelândia
31,3171006,Vazante
31,3171030,Verdelândia
31,3171071,Veredinha
31,3171105,Veríssimo
31,3171154,Vermelho Novo
31,3171204,Vespasiano
31,3171303,Viçosa
31,3171402,Vieiras
31,3171501,Mathias Lobato
31,3171600,Virgem da Lapa
31,3171709,Virgínia
31,3171808,Virginópolis
31,3171907,Virgolândia
31,3172004,Visconde do Rio Branco
31,3172103,Volta Grande
31,3172202,Wenceslau Braz
32,3200102,Afonso Cláudio
32,3200136,Águia Branca
32,3200169,Água doce do Norte
32,3200201,Alegre
32,3200300,Alfredo Chaves
32,3200359,Alto Rio Novo
32,3200409,Anchieta
32,3200508,Apiacá
32,3200607,Aracruz
32,3200706,Atilio Vivacqua
32,3200805,Baixo Guandu
32,3200904,Barra de São Francisco
32,3201001,Boa Esperança
32,3201100,Bom Jesus do Norte
32,3201159,Brejetuba
32,3201209,Cachoeiro de Itapemirim
32,3201308,Cariacica
32,3201407,Castelo
32,3201506,Colatina
32,3201605,Conceição da Barra
32,3201704,Conceição do Castelo
32,3201803,Divino de São Lourenço
32,3201902,domingos Martins
32,3202009,dores do Rio Preto
32,3202108,Ecoporanga
32,3202207,Fundão
32,3202256,Governador Lindenberg
32,3202306,Guaçuí
32,3202405,Guarapari
32,3202454,Ibatiba
32,3202504,Ibiraçu
32,3202553,Ibitirama
32,3202603,Iconha
32,3202652,Irupi
32,3202702,Itaguaçu
32,3202801,Itapemirim
32,3202900,Itarana
32,3203007,Iúna
32,3203056,Jaguaré
32,3203106,Jerônimo Monteiro
32,3203130,João Neiva
32,3203163,Laranja da Terra
32,3203205,Linhares
32,3203304,Mantenópolis
32,3203320,Marataízes
32,3203346,Marechal Floriano
32,3203353,Marilândia
32,3203403,Mimoso do Sul
32,3203502,Montanha
32,3203601,Mucurici
32,3203700,Muniz Freire
32,3203809,Muqui
32,3203908,Nova Venécia
32,3204005,Pancas
32,3204054,Pedro Canário
32,3204104,Pinheiros
32,3204203,Piúma
32,3204252,Ponto Belo
32,3204302,Presidente Kennedy
32,3204351,Rio Bananal
32,3204401,Rio Novo do Sul
32,3204500,Santa Leopoldina
32,3204559,Santa Maria de Jetibá
32,3204609,Santa Teresa
32,3204658,São domingos do Norte
32,3204708,São Gabriel da Palha
32,3204807,São José do Calçado
32,3204906,São Mateus
32,3204955,São Roque do Canaã
32,3205002,Serra
32,3205010,Sooretama
32,3205036,Vargem Alta
32,3205069,Venda Nova do Imigrante
32,3205101,Viana
32,3205150,Vila Pavão
32,3205176,Vila Valério
32,3205200,Vila Velha
32,3205309,Vitória
33,3300100,Angra dos Reis
33,3300159,Aperibé
33,3300209,Araruama
33,3300225,Areal
33,3300233,Armação dos Búzios
33,3300258,Arraial do Cabo
33,3300308,Barra do Piraí
33,3300407,Barra Mansa
33,3300456,Belford Roxo
33,3300506,Bom Jardim
33,3300605,Bom Jesus do Itabapoana
33,3300704,Cabo Frio
33,3300803,Cachoeiras de Macacu
33,3300902,Cambuci
33,3300936,Carapebus
33,3300951,Comendador Levy Gasparian
33,3301009,Campos dos Goytacazes
33,3301108,Cantagalo
33,3301157,Cardoso Moreira
33,3301207,Carmo
33,3301306,Casimiro de Abreu
33,3301405,Conceição de Macabu
33,3301504,Cordeiro
33,3301603,Duas Barras
33,3301702,Duque de Caxias
33,3301801,Engenheiro Paulo de Frontin
33,3301850,Guapimirim
33,3301876,Iguaba Grande
33,3301900,Itaboraí
33,3302007,Itaguaí
33,3302056,Italva
33,3302106,Itaocara
33,3302205,Itaperuna
33,3302254,Itatiaia
33,3302270,Japeri
33,3302304,Laje do Muriaé
33,3302403,Macaé
33,3302452,Macuco
33,3302502,Magé
33,3302601,Mangaratiba
33,3302700,Maricá
33,3302809,Mendes
33,3302858,Mesquita
33,3302908,Miguel Pereira
33,3303005,Miracema
33,3303104,Natividade
33,3303203,Nilópolis
33,3303302,Niterói
33,3303401,Nova Friburgo
33,3303500,Nova Iguaçu
33,3303609,Paracambi
33,3303708,Paraíba do Sul
33,3303807,Paraty
33,3303856,Paty do Alferes
33,3303906,Petrópolis
33,3303955,Pinheiral
33,3304003,Piraí
33,3304102,Porciúncula
33,3304110,Porto Real
33,3304128,Quatis
33,3304144,Queimados
33,3304151,Quissamã
33,3304201,Resende
33,3304300,Rio Bonito
33,3304409,Rio Claro
33,3304508,Rio das Flores
33,3304524,Rio das Ostras
33,3304557,Rio de Janeiro
33,3304607,Santa Maria Madalena
33,3304706,Santo Antônio de Pádua
33,3304755,São Francisco de Itabapoana
33,3304805,São Fidélis
33,3304904,São Gonçalo
33,3305000,São João da Barra
33,3305109,São João de Meriti
33,3305133,São José de Ubá
33,3305158,São José do Vale do Rio Preto
33,3305208,São Pedro da Aldeia
33,3305307,São Sebastião do Alto
33,3305406,Sapucaia
33,3305505,Saquarema
33,3305554,Seropédica
33,3305604,Silva Jardim
33,3305703,Sumidouro
33,3305752,Tanguá
33,3305802,Teresópolis
33,3305901,Trajano de Moraes
33,3306008,Três Rios
33,3306107,Valença
33,3306156,Varre-Sai
33,3306206,Vassouras
33,3306305,Volta Redonda
35,3500105,Adamantina
35,3500204,Adolfo
35,3500303,Aguaí
35,3500402,Águas da Prata
35,3500501,Águas de Lindóia
35,3500550,Águas de Santa Bárbara
35,3500600,Águas de São Pedro
35,3500709,Agudos
35,3500758,Alambari
35,3500808,Alfredo Marcondes
35,3500907,Altair
35,3501004,Altinópolis
35,3501103,Alto Alegre
35,3501152,Alumínio
35,3501202,Álvares Florence
35,3501301,Álvares Machado
35,3501400,Álvaro de Carvalho
35,3501509,Alvinlândia
35,3501608,Americana
35,3501707,Américo Brasiliense
35,3501806,Américo de Campos
35,3501905,Amparo
35,3502002,Analândia
35,3502101,Andradina
35,3502200,Angatuba
35,3502309,Anhembi
35,3502408,Anhumas
35,3502507,Aparecida
35,3502606,Aparecida D'oeste
35,3502705,Apiaí
35,3502754,Araçariguama
35,3502804,Araçatuba
35,3502903,Araçoiaba da Serra
35,3503000,Aramina
35,3503109,Arandu
35,3503158,Arapeí
35,3503208,Araraquara
35,3503307,Araras
35,3503356,Arco-Íris
35,3503406,Arealva
35,3503505,Areias
35,3503604,Areiópolis
35,3503703,Ariranha
35,3503802,Artur Nogueira
35,3503901,Arujá
35,3503950,Aspásia
35,3504008,Assis
35,3504107,Atibaia
35,3504206,Auriflama
35,3504305,Avaí
35,3504404,Avanhandava
35,3504503,Avaré
35,3504602,Bady Bassitt
35,3504701,Balbinos
35,3504800,Bálsamo
35,3504909,Bananal
35,3505005,Barão de Antonina
35,3505104,Barbosa
35,3505203,Bariri
35,3505302,Barra Bonita
35,3505351,Barra do Chapéu
35,3505401,Barra do Turvo
35,3505500,Barretos
35,3505609,Barrinha
35,3505708,Barueri
35,3505807,Bastos
35,3505906,Batatais
35,3506003,Bauru
35,3506102,Bebedouro
35,3506201,Bento de Abreu
35,3506300,Bernardino de Campos
35,3506359,Bertioga
35,3506409,Bilac
35,3506508,Birigui
35,3506607,Biritiba-Mirim
35,3506706,Boa Esperança do Sul
35,3506805,Bocaina
35,3506904,Bofete
35,3507001,Boituva
35,3507100,Bom Jesus dos Perdões
35,3507159,Bom Sucesso de Itararé
35,3507209,Borá
35,3507308,Boracéia
35,3507407,Borborema
35,3507456,Borebi
35,3507506,Botucatu
35,3507605,Bragança Paulista
35,3507704,Braúna
35,3507753,Brejo Alegre
35,3507803,Brodowski
35,3507902,Brotas
35,3508009,Buri
35,3508108,Buritama
35,3508207,Buritizal
35,3508306,Cabrália Paulista
35,3508405,Cabreúva
35,3508504,Caçapava
35,3508603,Cachoeira Paulista
35,3508702,Caconde
35,3508801,Cafelândia
35,3508900,Caiabu
35,3509007,Caieiras
35,3509106,Caiuá
35,3509205,Cajamar
35,3509254,Cajati
35,3509304,Cajobi
35,3509403,Cajuru
35,3509452,Campina do Monte Alegre
35,3509502,Campinas
35,3509601,Campo Limpo Paulista
35,3509700,Campos do Jordão
35,3509809,Campos Novos Paulista
35,3509908,Cananéia
35,3509957,Canas
35,3510005,Cândido Mota
35,3510104,Cândido Rodrigues
35,3510153,Canitar
35,3510203,Capão Bonito
35,3510302,Capela do Alto
35,3510401,Capivari
35,3510500,Caraguatatuba
35,3510609,Carapicuíba
35,3510708,Cardoso
35,3510807,Casa Branca
35,3510906,Cássia dos Coqueiros
35,3511003,Castilho
35,3511102,Catanduva
35,3511201,Catiguá
35,3511300,Cedral
35,3511409,Cerqueira César
35,3511508,Cerquilho
35,3511607,Cesário Lange
35,3511706,Charqueada
35,3511904,Clementina
35,3512001,Colina
35,3512100,Colômbia
35,3512209,Conchal
35,3512308,Conchas
35,3512407,Cordeirópolis
35,3512506,Coroados
35,3512605,Coronel Macedo
35,3512704,Corumbataí
35,3512803,Cosmópolis
35,3512902,Cosmorama
35,3513009,Cotia
35,3513108,Cravinhos
35,3513207,Cristais Paulista
35,3513306,Cruzália
35,3513405,Cruzeiro
35,3513504,Cubatão
35,3513603,Cunha
35,3513702,descalvado
35,3513801,Diadema
35,3513850,Dirce Reis
35,3513900,Divinolândia
35,3514007,dobrada
35,3514106,dois Córregos
35,3514205,dolcinópolis
35,3514304,dourado
35,3514403,Dracena
35,3514502,Duartina
35,3514601,Dumont
35,3514700,Echaporã
35,3514809,Eldorado
35,3514908,Elias Fausto
35,3514924,Elisiário
35,3514957,Embaúba
35,3515004,Embu das Artes
35,3515103,Embu-Guaçu
35,3515129,Emilianópolis
35,3515152,Engenheiro Coelho
35,3515186,Espírito Santo do Pinhal
35,3515194,Espírito Santo do Turvo
35,3515202,Estrela D'oeste
35,3515301,Estrela do Norte
35,3515350,Euclides da Cunha Paulista
35,3515400,Fartura
35,3515509,Fernandópolis
35,3515608,Fernando Prestes
35,3515657,Fernão
35,3515707,Ferraz de Vasconcelos
35,3515806,Flora Rica
35,3515905,Floreal
35,3516002,Flórida Paulista
35,3516101,Florínia
35,3516200,Franca
35,3516309,Francisco Morato
35,3516408,Franco da Rocha
35,3516507,Gabriel Monteiro
35,3516606,Gália
35,3516705,Garça
35,3516804,Gastão Vidigal
35,3516853,Gavião Peixoto
35,3516903,General Salgado
35,3517000,Getulina
35,3517109,Glicério
35,3517208,Guaiçara
35,3517307,Guaimbê
35,3517406,Guaíra
35,3517505,Guapiaçu
35,3517604,Guapiara
35,3517703,Guará
35,3517802,Guaraçaí
35,3517901,Guaraci
35,3518008,Guarani D'oeste
35,3518107,Guarantã
35,3518206,Guararapes
35,3518305,Guararema
35,3518404,Guaratinguetá
35,3518503,Guareí
35,3518602,Guariba
35,3518701,Guarujá
35,3518800,Guarulhos
35,3518859,Guatapará
35,3518909,Guzolândia
35,3519006,Herculândia
35,3519055,Holambra
35,3519071,Hortolândia
35,3519105,Iacanga
35,3519204,Iacri
35,3519253,Iaras
35,3519303,Ibaté
35,3519402,Ibirá
35,3519501,Ibirarema
35,3519600,Ibitinga
35,3519709,Ibiúna
35,3519808,Icém
35,3519907,Iepê
35,3520004,Igaraçu do Tietê
35,3520103,Igarapava
35,3520202,Igaratá
35,3520301,Iguape
35,3520400,Ilhabela
35,3520426,Ilha Comprida
35,3520442,Ilha Solteira
35,3520509,Indaiatuba
35,3520608,Indiana
35,3520707,Indiaporã
35,3520806,Inúbia Paulista
35,3520905,Ipaussu
35,3521002,Iperó
35,3521101,Ipeúna
35,3521150,Ipiguá
35,3521200,Iporanga
35,3521309,Ipuã
35,3521408,Iracemápolis
35,3521507,Irapuã
35,3521606,Irapuru
35,3521705,Itaberá
35,3521804,Itaí
35,3521903,Itajobi
35,3522000,Itaju
35,3522109,Itanhaém
35,3522158,Itaóca
35,3522208,Itapecerica da Serra
35,3522307,Itapetininga
35,3522406,Itapeva
35,3522505,Itapevi
35,3522604,Itapira
35,3522653,Itapirapuã Paulista
35,3522703,Itápolis
35,3522802,Itaporanga
35,3522901,Itapuí
35,3523008,Itapura
35,3523107,Itaquaquecetuba
35,3523206,Itararé
35,3523305,Itariri
35,3523404,Itatiba
35,3523503,Itatinga
35,3523602,Itirapina
35,3523701,Itirapuã
35,3523800,Itobi
35,3523909,Itu
35,3524006,Itupeva
35,3524105,Ituverava
35,3524204,Jaborandi
35,3524303,Jaboticabal
35,3524402,Jacareí
35,3524501,Jaci
35,3524600,Jacupiranga
35,3524709,Jaguariúna
35,3524808,Jales
35,3524907,Jambeiro
35,3525003,Jandira
35,3525102,Jardinópolis
35,3525201,Jarinu
35,3525300,Jaú
35,3525409,Jeriquara
35,3525508,Joanópolis
35,3525607,João Ramalho
35,3525706,José Bonifácio
35,3525805,Júlio Mesquita
35,3525854,Jumirim
35,3525904,Jundiaí
35,3526001,Junqueirópolis
35,3526100,Juquiá
35,3526209,Juquitiba
35,3526308,Lagoinha
35,3526407,Laranjal Paulista
35,3526506,Lavínia
35,3526605,Lavrinhas
35,3526704,Leme
35,3526803,Lençóis Paulista
35,3526902,Limeira
35,3527009,Lindóia
35,3527108,Lins
35,3527207,Lorena
35,3527256,Lourdes
35,3527306,Louveira
35,3527405,Lucélia
35,3527504,Lucianópolis
35,3527603,Luís Antônio
35,3527702,Luiziânia
35,3527801,Lupércio
35,3527900,Lutécia
35,3528007,Macatuba
35,3528106,Macaubal
35,3528205,Macedônia
35,3528304,Magda
35,3528403,Mairinque
35,3528502,Mairiporã
35,3528601,Manduri
35,3528700,Marabá Paulista
35,3528809,Maracaí
35,3528858,Marapoama
35,3528908,Mariápolis
35,3529005,Marília
35,3529104,Marinópolis
35,3529203,Martinópolis
35,3529302,Matão
35,3529401,Mauá
35,3529500,Mendonça
35,3529609,Meridiano
35,3529658,Mesópolis
35,3529708,Miguelópolis
35,3529807,Mineiros do Tietê
35,3529906,Miracatu
35,3530003,Mira Estrela
35,3530102,Mirandópolis
35,3530201,Mirante do Paranapanema
35,3530300,Mirassol
35,3530409,Mirassolândia
35,3530508,Mococa
35,3530607,Mogi das Cruzes
35,3530706,Mogi Guaçu
35,3530805,Mogi Mirim
35,3530904,Mombuca
35,3531001,Monções
35,3531100,Mongaguá
35,3531209,Monte Alegre do Sul
35,3531308,Monte Alto
35,3531407,Monte Aprazível
35,3531506,Monte Azul Paulista
35,3531605,Monte Castelo
35,3531704,Monteiro Lobato
35,3531803,Monte Mor
35,3531902,Morro Agudo
35,3532009,Morungaba
35,3532058,Motuca
35,3532108,Murutinga do Sul
35,3532157,Nantes
35,3532207,Narandiba
35,3532306,Natividade da Serra
35,3532405,Nazaré Paulista
35,3532504,Neves Paulista
35,3532603,Nhandeara
35,3532702,Nipoã
35,3532801,Nova Aliança
35,3532827,Nova Campina
35,3532843,Nova Canaã Paulista
35,3532868,Nova Castilho
35,3532900,Nova Europa
35,3533007,Nova Granada
35,3533106,Nova Guataporanga
35,3533205,Nova Independência
35,3533254,Novais
35,3533304,Nova Luzitânia
35,3533403,Nova Odessa
35,3533502,Novo Horizonte
35,3533601,Nuporanga
35,3533700,Ocauçu
35,3533809,Óleo
35,3533908,Olímpia
35,3534005,Onda Verde
35,3534104,Oriente
35,3534203,Orindiúva
35,3534302,Orlândia
35,3534401,Osasco
35,3534500,Oscar Bressane
35,3534609,Osvaldo Cruz
35,3534708,Ourinhos
35,3534757,Ouroeste
35,3534807,Ouro Verde
35,3534906,Pacaembu
35,3535002,Palestina
35,3535101,Palmares Paulista
35,3535200,Palmeira D'oeste
35,3535309,Palmital
35,3535408,Panorama
35,3535507,Paraguaçu Paulista
35,3535606,Paraibuna
35,3535705,Paraíso
35,3535804,Paranapanema
35,3535903,Paranapuã
35,3536000,Parapuã
35,3536109,Pardinho
35,3536208,Pariquera-Açu
35,3536257,Parisi
35,3536307,Patrocínio Paulista
35,3536406,Paulicéia
35,3536505,Paulínia
35,3536570,Paulistânia
35,3536604,Paulo de Faria
35,3536703,Pederneiras
35,3536802,Pedra Bela
35,3536901,Pedranópolis
35,3537008,Pedregulho
35,3537107,Pedreira
35,3537156,Pedrinhas Paulista
35,3537206,Pedro de Toledo
35,3537305,Penápolis
35,3537404,Pereira Barreto
35,3537503,Pereiras
35,3537602,Peruíbe
35,3537701,Piacatu
35,3537800,Piedade
35,3537909,Pilar do Sul
35,3538006,Pindamonhangaba
35,3538105,Pindorama
35,3538204,Pinhalzinho
35,3538303,Piquerobi
35,3538501,Piquete
35,3538600,Piracaia
35,3538709,Piracicaba
35,3538808,Piraju
35,3538907,Pirajuí
35,3539004,Pirangi
35,3539103,Pirapora do Bom Jesus
35,3539202,Pirapozinho
35,3539301,Pirassununga
35,3539400,Piratininga
35,3539509,Pitangueiras
35,3539608,Planalto
35,3539707,Platina
35,3539806,Poá
35,3539905,Poloni
35,3540002,Pompéia
35,3540101,Pongaí
35,3540200,Pontal
35,3540259,Pontalinda
35,3540309,Pontes Gestal
35,3540408,Populina
35,3540507,Porangaba
35,3540606,Porto Feliz
35,3540705,Porto Ferreira
35,3540754,Potim
35,3540804,Potirendaba
35,3540853,Pracinha
35,3540903,Pradópolis
35,3541000,Praia Grande
35,3541059,Pratânia
35,3541109,Presidente Alves
35,3541208,Presidente Bernardes
35,3541307,Presidente Epitácio
35,3541406,Presidente Prudente
35,3541505,Presidente Venceslau
35,3541604,Promissão
35,3541653,Quadra
35,3541703,Quatá
35,3541802,Queiroz
35,3541901,Queluz
35,3542008,Quintana
35,3542107,Rafard
35,3542206,Rancharia
35,3542305,Redenção da Serra
35,3542404,Regente Feijó
35,3542503,Reginópolis
35,3542602,Registro
35,3542701,Restinga
35,3542800,Ribeira
35,3542909,Ribeirão Bonito
35,3543006,Ribeirão Branco
35,3543105,Ribeirão Corrente
35,3543204,Ribeirão do Sul
35,3543238,Ribeirão dos Índios
35,3543253,Ribeirão Grande
35,3543303,Ribeirão Pires
35,3543402,Ribeirão Preto
35,3543501,Riversul
35,3543600,Rifaina
35,3543709,Rincão
35,3543808,Rinópolis
35,3543907,Rio Claro
35,3544004,Rio das Pedras
35,3544103,Rio Grande da Serra
35,3544202,Riolândia
35,3544251,Rosana
35,3544301,Roseira
35,3544400,Rubiácea
35,3544509,Rubinéia
35,3544608,Sabino
35,3544707,Sagres
35,3544806,Sales
35,3544905,Sales Oliveira
35,3545001,Salesópolis
35,3545100,Salmourão
35,3545159,Saltinho
35,3545209,Salto
35,3545308,Salto de Pirapora
35,3545407,Salto Grande
35,3545506,Sandovalina
35,3545605,Santa Adélia
35,3545704,Santa Albertina
35,3545803,Santa Bárbara D'oeste
35,3546009,Santa Branca
35,3546108,Santa Clara D'oeste
35,3546207,Santa Cruz da Conceição
35,3546256,Santa Cruz da Esperança
35,3546306,Santa Cruz das Palmeiras
35,3546405,Santa Cruz do Rio Pardo
35,3546504,Santa Ernestina
35,3546603,Santa Fé do Sul
35,3546702,Santa Gertrudes
35,3546801,Santa Isabel
35,3546900,Santa Lúcia
35,3547007,Santa Maria da Serra
35,3547106,Santa Mercedes
35,3547205,Santana da Ponte Pensa
35,3547304,Santana de Parnaíba
35,3547403,Santa Rita D'oeste
35,3547502,Santa Rita do Passa Quatro
35,3547601,Santa Rosa de Viterbo
35,3547650,Santa Salete
35,3547700,Santo Anastácio
35,3547809,Santo André
35,3547908,Santo Antônio da Alegria
35,3548005,Santo Antônio de Posse
35,3548054,Santo Antônio do Aracanguá
35,3548104,Santo Antônio do Jardim
35,3548203,Santo Antônio do Pinhal
35,3548302,Santo Expedito
35,3548401,Santópolis do Aguapeí
35,3548500,Santos
35,3548609,São Bento do Sapucaí
35,3548708,São Bernardo do Campo
35,3548807,São Caetano do Sul
35,3548906,São Carlos
35,3549003,São Francisco
35,3549102,São João da Boa Vista
35,3549201,São João das Duas Pontes
35,3549250,São João de Iracema
35,3549300,São João do Pau D'alho
35,3549409,São Joaquim da Barra
35,3549508,São José da Bela Vista
35,3549607,São José do Barreiro
35,3549706,São José do Rio Pardo
35,3549805,São José do Rio Preto
35,3549904,São José dos Campos
35,3549953,São Lourenço da Serra
35,3550001,São Luís do Paraitinga
35,3550100,São Manuel
35,3550209,São Miguel Arcanjo
35,3550308,São Paulo
35,3550407,São Pedro
35,3550506,São Pedro do Turvo
35,3550605,São Roque
35,3550704,São Sebastião
35,3550803,São Sebastião da Grama
35,3550902,São Simão
35,3551009,São Vicente
35,3551108,Sarapuí
35,3551207,Sarutaiá
35,3551306,Sebastianópolis do Sul
35,3551405,Serra Azul
35,3551504,Serrana
35,3551603,Serra Negra
35,3551702,Sertãozinho
35,3551801,Sete Barras
35,3551900,Severínia
35,3552007,Silveiras
35,3552106,Socorro
35,3552205,Sorocaba
35,3552304,Sud Mennucci
35,3552403,Sumaré
35,3552502,Suzano
35,3552551,Suzanápolis
35,3552601,Tabapuã
35,3552700,Tabatinga
35,3552809,Taboão da Serra
35,3552908,Taciba
35,3553005,Taguaí
35,3553104,Taiaçu
35,3553203,Taiúva
35,3553302,Tambaú
35,3553401,Tanabi
35,3553500,Tapiraí
35,3553609,Tapiratiba
35,3553658,Taquaral
35,3553708,Taquaritinga
35,3553807,Taquarituba
35,3553856,Taquarivaí
35,3553906,Tarabai
35,3553955,Tarumã
35,3554003,Tatuí
35,3554102,Taubaté
35,3554201,Tejupá
35,3554300,Teodoro Sampaio
35,3554409,Terra Roxa
35,3554508,Tietê
35,3554607,Timburi
35,3554656,Torre de Pedra
35,3554706,Torrinha
35,3554755,Trabiju
35,3554805,Tremembé
35,3554904,Três Fronteiras
35,3554953,Tuiuti
35,3555000,Tupã
35,3555109,Tupi Paulista
35,3555208,Turiúba
35,3555307,Turmalina
35,3555356,Ubarana
35,3555406,Ubatuba
35,3555505,Ubirajara
35,3555604,Uchoa
35,3555703,União Paulista
35,3555802,Urânia
35,3555901,Uru
35,3556008,Urupês
35,3556107,Valentim Gentil
35,3556206,Valinhos
35,3556305,Valparaíso
35,3556354,Vargem
35,3556404,Vargem Grande do Sul
35,3556453,Vargem Grande Paulista
35,3556503,Várzea Paulista
35,3556602,Vera Cruz
35,3556701,Vinhedo
35,3556800,Viradouro
35,3556909,Vista Alegre do Alto
35,3556958,Vitória Brasil
35,3557006,Votorantim
35,3557105,Votuporanga
35,3557154,Zacarias
35,3557204,Chavantes
35,3557303,Estiva Gerbi
41,4100103,Abatiá
41,4100202,Adrianópolis
41,4100301,Agudos do Sul
41,4100400,Almirante Tamandaré
41,4100459,Altamira do Paraná
41,4100509,Altônia
41,4100608,Alto Paraná
41,4100707,Alto Piquiri
41,4100806,Alvorada do Sul
41,4100905,Amaporã
41,4101002,Ampére
41,4101051,Anahy
41,4101101,Andirá
41,4101150,Ângulo
41,4101200,Antonina
41,4101309,Antônio Olinto
41,4101408,Apucarana
41,4101507,Arapongas
41,4101606,Arapoti
41,4101655,Arapuã
41,4101705,Araruna
41,4101804,Araucária
41,4101853,Ariranha do Ivaí
41,4101903,Assaí
41,4102000,Assis Chateaubriand
41,4102109,Astorga
41,4102208,Atalaia
41,4102307,Balsa Nova
41,4102406,Bandeirantes
41,4102505,Barbosa Ferraz
41,4102604,Barracão
41,4102703,Barra do Jacaré
41,4102752,Bela Vista da Caroba
41,4102802,Bela Vista do Paraíso
41,4102901,Bituruna
41,4103008,Boa Esperança
41,4103024,Boa Esperança do Iguaçu
41,4103040,Boa Ventura de São Roque
41,4103057,Boa Vista da Aparecida
41,4103107,Bocaiúva do Sul
41,4103156,Bom Jesus do Sul
41,4103206,Bom Sucesso
41,4103222,Bom Sucesso do Sul
41,4103305,Borrazópolis
41,4103354,Braganey
41,4103370,Brasilândia do Sul
41,4103404,Cafeara
41,4103453,Cafelândia
41,4103479,Cafezal do Sul
41,4103503,Califórnia
41,4103602,Cambará
41,4103701,Cambé
41,4103800,Cambira
41,4103909,Campina da Lagoa
41,4103958,Campina do Simão
41,4104006,Campina Grande do Sul
41,4104055,Campo Bonito
41,4104105,Campo do Tenente
41,4104204,Campo Largo
41,4104253,Campo Magro
41,4104303,Campo Mourão
41,4104402,Cândido de Abreu
41,4104428,Candói
41,4104451,Cantagalo
41,4104501,Capanema
41,4104600,Capitão Leônidas Marques
41,4104659,Carambeí
41,4104709,Carlópolis
41,4104808,Cascavel
41,4104907,Castro
41,4105003,Catanduvas
41,4105102,Centenário do Sul
41,4105201,Cerro Azul
41,4105300,Céu Azul
41,4105409,Chopinzinho
41,4105508,Cianorte
41,4105607,Cidade Gaúcha
41,4105706,Clevelândia
41,4105805,Colombo
41,4105904,Colorado
41,4106001,Congonhinhas
41,4106100,Conselheiro Mairinck
41,4106209,Contenda
41,4106308,Corbélia
41,4106407,Cornélio Procópio
41,4106456,Coronel domingos Soares
41,4106506,Coronel Vivida
41,4106555,Corumbataí do Sul
41,4106571,Cruzeiro do Iguaçu
41,4106605,Cruzeiro do Oeste
41,4106704,Cruzeiro do Sul
41,4106803,Cruz Machado
41,4106852,Cruzmaltina
41,4106902,Curitiba
41,4107009,Curiúva
41,4107108,Diamante do Norte
41,4107124,Diamante do Sul
41,4107157,Diamante D'oeste
41,4107207,dois Vizinhos
41,4107256,douradina
41,4107306,doutor Camargo
41,4107405,Enéas Marques
41,4107504,Engenheiro Beltrão
41,4107520,Esperança Nova
41,4107538,Entre Rios do Oeste
41,4107546,Espigão Alto do Iguaçu
41,4107553,Farol
41,4107603,Faxinal
41,4107652,Fazenda Rio Grande
41,4107702,Fênix
41,4107736,Fernandes Pinheiro
41,4107751,Figueira
41,4107801,Floraí
41,4107850,Flor da Serra do Sul
41,4107900,Floresta
41,4108007,Florestópolis
41,4108106,Flórida
41,4108205,Formosa do Oeste
41,4108304,Foz do Iguaçu
41,4108320,Francisco Alves
41,4108403,Francisco Beltrão
41,4108452,Foz do Jordão
41,4108502,General Carneiro
41,4108551,Godoy Moreira
41,4108601,Goioerê
41,4108650,Goioxim
41,4108700,Grandes Rios
41,4108809,Guaíra
41,4108908,Guairaçá
41,4108957,Guamiranga
41,4109005,Guapirama
41,4109104,Guaporema
41,4109203,Guaraci
41,4109302,Guaraniaçu
41,4109401,Guarapuava
41,4109500,Guaraqueçaba
41,4109609,Guaratuba
41,4109658,Honório Serpa
41,4109708,Ibaiti
41,4109757,Ibema
41,4109807,Ibiporã
41,4109906,Icaraíma
41,4110003,Iguaraçu
41,4110052,Iguatu
41,4110078,Imbaú
41,4110102,Imbituva
41,4110201,Inácio Martins
41,4110300,Inajá
41,4110409,Indianópolis
41,4110508,Ipiranga
41,4110607,Iporã
41,4110656,Iracema do Oeste
41,4110706,Irati
41,4110805,Iretama
41,4110904,Itaguajé
41,4110953,Itaipulândia
41,4111001,Itambaracá
41,4111100,Itambé
41,4111209,Itapejara D'oeste
41,4111258,Itaperuçu
41,4111308,Itaúna do Sul
41,4111407,Ivaí
41,4111506,Ivaiporã
41,4111555,Ivaté
41,4111605,Ivatuba
41,4111704,Jaboti
41,4111803,Jacarezinho
41,4111902,Jaguapitã
41,4112009,Jaguariaíva
41,4112108,Jandaia do Sul
41,4112207,Janiópolis
41,4112306,Japira
41,4112405,Japurá
41,4112504,Jardim Alegre
41,4112603,Jardim Olinda
41,4112702,Jataizinho
41,4112751,Jesuítas
41,4112801,Joaquim Távora
41,4112900,Jundiaí do Sul
41,4112959,Juranda
41,4113007,Jussara
41,4113106,Kaloré
41,4113205,Lapa
41,4113254,Laranjal
41,4113304,Laranjeiras do Sul
41,4113403,Leópolis
41,4113429,Lidianópolis
41,4113452,Lindoeste
41,4113502,Loanda
41,4113601,Lobato
41,4113700,Londrina
41,4113734,Luiziana
41,4113759,Lunardelli
41,4113809,Lupionópolis
41,4113908,Mallet
41,4114005,Mamborê
41,4114104,Mandaguaçu
41,4114203,Mandaguari
41,4114302,Mandirituba
41,4114351,Manfrinópolis
41,4114401,Mangueirinha
41,4114500,Manoel Ribas
41,4114609,Marechal Cândido Rondon
41,4114708,Maria Helena
41,4114807,Marialva
41,4114906,Marilândia do Sul
41,4115002,Marilena
41,4115101,Mariluz
41,4115200,Maringá
41,4115309,Mariópolis
41,4115358,Maripá
41,4115408,Marmeleiro
41,4115457,Marquinho
41,4115507,Marumbi
41,4115606,Matelândia
41,4115705,Matinhos
41,4115739,Mato Rico
41,4115754,Mauá da Serra
41,4115804,Medianeira
41,4115853,Mercedes
41,4115903,Mirador
41,4116000,Miraselva
41,4116059,Missal
41,4116109,Moreira Sales
41,4116208,Morretes
41,4116307,Munhoz de Melo
41,4116406,Nossa Senhora das Graças
41,4116505,Nova Aliança do Ivaí
41,4116604,Nova América da Colina
41,4116703,Nova Aurora
41,4116802,Nova Cantu
41,4116901,Nova Esperança
41,4116950,Nova Esperança do Sudoeste
41,4117008,Nova Fátima
41,4117057,Nova Laranjeiras
41,4117107,Nova Londrina
41,4117206,Nova Olímpia
41,4117214,Nova Santa Bárbara
41,4117222,Nova Santa Rosa
41,4117255,Nova Prata do Iguaçu
41,4117271,Nova Tebas
41,4117297,Novo Itacolomi
41,4117305,Ortigueira
41,4117404,Ourizona
41,4117453,Ouro Verde do Oeste
41,4117503,Paiçandu
41,4117602,Palmas
41,4117701,Palmeira
41,4117800,Palmital
41,4117909,Palotina
41,4118006,Paraíso do Norte
41,4118105,Paranacity
41,4118204,Paranaguá
41,4118303,Paranapoema
41,4118402,Paranavaí
41,4118451,Pato Bragado
41,4118501,Pato Branco
41,4118600,Paula Freitas
41,4118709,Paulo Frontin
41,4118808,Peabiru
41,4118857,Perobal
41,4118907,Pérola
41,4119004,Pérola D'oeste
41,4119103,Piên
41,4119152,Pinhais
41,4119202,Pinhalão
41,4119251,Pinhal de São Bento
41,4119301,Pinhão
41,4119400,Piraí do Sul
41,4119509,Piraquara
41,4119608,Pitanga
41,4119657,Pitangueiras
41,4119707,Planaltina do Paraná
41,4119806,Planalto
41,4119905,Ponta Grossa
41,4119954,Pontal do Paraná
41,4120002,Porecatu
41,4120101,Porto Amazonas
41,4120150,Porto Barreiro
41,4120200,Porto Rico
41,4120309,Porto Vitória
41,4120333,Prado Ferreira
41,4120358,Pranchita
41,4120408,Presidente Castelo Branco
41,4120507,Primeiro de Maio
41,4120606,Prudentópolis
41,4120655,Quarto Centenário
41,4120705,Quatiguá
41,4120804,Quatro Barras
41,4120853,Quatro Pontes
41,4120903,Quedas do Iguaçu
41,4121000,Querência do Norte
41,4121109,Quinta do Sol
41,4121208,Quitandinha
41,4121257,Ramilândia
41,4121307,Rancho Alegre
41,4121356,Rancho Alegre D'oeste
41,4121406,Realeza
41,4121505,Rebouças
41,4121604,Renascença
41,4121703,Reserva
41,4121752,Reserva do Iguaçu
41,4121802,Ribeirão Claro
41,4121901,Ribeirão do Pinhal
41,4122008,Rio Azul
41,4122107,Rio Bom
41,4122156,Rio Bonito do Iguaçu
41,4122172,Rio Branco do Ivaí
41,4122206,Rio Branco do Sul
41,4122305,Rio Negro
41,4122404,Rolândia
41,4122503,Roncador
41,4122602,Rondon
41,4122651,Rosário do Ivaí
41,4122701,Sabáudia
41,4122800,Salgado Filho
41,4122909,Salto do Itararé
41,4123006,Salto do Lontra
41,4123105,Santa Amélia
41,4123204,Santa Cecília do Pavão
41,4123303,Santa Cruz de Monte Castelo
41,4123402,Santa Fé
41,4123501,Santa Helena
41,4123600,Santa Inês
41,4123709,Santa Isabel do Ivaí
41,4123808,Santa Izabel do Oeste
41,4123824,Santa Lúcia
41,4123857,Santa Maria do Oeste
41,4123907,Santa Mariana
41,4123956,Santa Mônica
41,4124004,Santana do Itararé
41,4124020,Santa Tereza do Oeste
41,4124053,Santa Terezinha de Itaipu
41,4124103,Santo Antônio da Platina
41,4124202,Santo Antônio do Caiuá
41,4124301,Santo Antônio do Paraíso
41,4124400,Santo Antônio do Sudoeste
41,4124509,Santo Inácio
41,4124608,São Carlos do Ivaí
41,4124707,São Jerônimo da Serra
41,4124806,São João
41,4124905,São João do Caiuá
41,4125001,São João do Ivaí
41,4125100,São João do Triunfo
41,4125209,São Jorge D'oeste
41,4125308,São Jorge do Ivaí
41,4125357,São Jorge do Patrocínio
41,4125407,São José da Boa Vista
41,4125456,São José das Palmeiras
41,4125506,São José dos Pinhais
41,4125555,São Manoel do Paraná
41,4125605,São Mateus do Sul
41,4125704,São Miguel do Iguaçu
41,4125753,São Pedro do Iguaçu
41,4125803,São Pedro do Ivaí
41,4125902,São Pedro do Paraná
41,4126009,São Sebastião da Amoreira
41,4126108,São Tomé
41,4126207,Sapopema
41,4126256,Sarandi
41,4126272,Saudade do Iguaçu
41,4126306,Sengés
41,4126355,Serranópolis do Iguaçu
41,4126405,Sertaneja
41,4126504,Sertanópolis
41,4126603,Siqueira Campos
41,4126652,Sulina
41,4126678,Tamarana
41,4126702,Tamboara
41,4126801,Tapejara
41,4126900,Tapira
41,4127007,Teixeira Soares
41,4127106,Telêmaco Borba
41,4127205,Terra Boa
41,4127304,Terra Rica
41,4127403,Terra Roxa
41,4127502,Tibagi
41,4127601,Tijucas do Sul
41,4127700,Toledo
41,4127809,Tomazina
41,4127858,Três Barras do Paraná
41,4127882,Tunas do Paraná
41,4127908,Tuneiras do Oeste
41,4127957,Tupãssi
41,4127965,Turvo
41,4128005,Ubiratã
41,4128104,Umuarama
41,4128203,União da Vitória
41,4128302,Uniflor
41,4128401,Uraí
41,4128500,Wenceslau Braz
41,4128534,Ventania
41,4128559,Vera Cruz do Oeste
41,4128609,Verê
41,4128625,Alto Paraíso
41,4128633,doutor Ulysses
41,4128658,Virmond
41,4128708,Vitorino
41,4128807,Xambrê
42,4200051,Abdon Batista
42,4200101,Abelardo Luz
42,4200200,Agrolândia
42,4200309,Agronômica
42,4200408,Água doce
42,4200507,Águas de Chapecó
42,4200556,Águas Frias
42,4200606,Águas Mornas
42,4200705,Alfredo Wagner
42,4200754,Alto Bela Vista
42,4200804,Anchieta
42,4200903,Angelina
42,4201000,Anita Garibaldi
42,4201109,Anitápolis
42,4201208,Antônio Carlos
42,4201257,Apiúna
42,4201273,Arabutã
42,4201307,Araquari
42,4201406,Araranguá
42,4201505,Armazém
42,4201604,Arroio Trinta
42,4201653,Arvoredo
42,4201703,Ascurra
42,4201802,Atalanta
42,4201901,Aurora
42,4201950,Balneário Arroio do Silva
42,4202008,Balneário Camboriú
42,4202057,Balneário Barra do Sul
42,4202073,Balneário Gaivota
42,4202081,Bandeirante
42,4202099,Barra Bonita
42,4202107,Barra Velha
42,4202131,Bela Vista do Toldo
42,4202156,Belmonte
42,4202206,Benedito Novo
42,4202305,Biguaçu
42,4202404,Blumenau
42,4202438,Bocaina do Sul
42,4202453,Bombinhas
42,4202503,Bom Jardim da Serra
42,4202537,Bom Jesus
42,4202578,Bom Jesus do Oeste
42,4202602,Bom Retiro
42,4202701,Botuverá
42,4202800,Braço do Norte
42,4202859,Braço do Trombudo
42,4202875,Brunópolis
42,4202909,Brusque
42,4203006,Caçador
42,4203105,Caibi
42,4203154,Calmon
42,4203204,Camboriú
42,4203253,Capão Alto
42,4203303,Campo Alegre
42,4203402,Campo Belo do Sul
42,4203501,Campo Erê
42,4203600,Campos Novos
42,4203709,Canelinha
42,4203808,Canoinhas
42,4203907,Capinzal
42,4203956,Capivari de Baixo
42,4204004,Catanduvas
42,4204103,Caxambu do Sul
42,4204152,Celso Ramos
42,4204178,Cerro Negro
42,4204194,Chapadão do Lageado
42,4204202,Chapecó
42,4204251,Cocal do Sul
42,4204301,Concórdia
42,4204350,Cordilheira Alta
42,4204400,Coronel Freitas
42,4204459,Coronel Martins
42,4204509,Corupá
42,4204558,Correia Pinto
42,4204608,Criciúma
42,4204707,Cunha Porã
42,4204756,Cunhataí
42,4204806,Curitibanos
42,4204905,descanso
42,4205001,Dionísio Cerqueira
42,4205100,dona Emma
42,4205159,doutor Pedrinho
42,4205175,Entre Rios
42,4205191,Ermo
42,4205209,Erval Velho
42,4205308,Faxinal dos Guedes
42,4205357,Flor do Sertão
42,4205407,Florianópolis
42,4205431,Formosa do Sul
42,4205456,Forquilhinha
42,4205506,Fraiburgo
42,4205555,Frei Rogério
42,4205605,Galvão
42,4205704,Garopaba
42,4205803,Garuva
42,4205902,Gaspar
42,4206009,Governador Celso Ramos
42,4206108,Grão Pará
42,4206207,Gravatal
42,4206306,Guabiruba
42,4206405,Guaraciaba
42,4206504,Guaramirim
42,4206603,Guarujá do Sul
42,4206652,Guatambú
42,4206702,Herval D'oeste
42,4206751,Ibiam
42,4206801,Ibicaré
42,4206900,Ibirama
42,4207007,Içara
42,4207106,Ilhota
42,4207205,Imaruí
42,4207304,Imbituba
42,4207403,Imbuia
42,4207502,Indaial
42,4207577,Iomerê
42,4207601,Ipira
42,4207650,Iporã do Oeste
42,4207684,Ipuaçu
42,4207700,Ipumirim
42,4207759,Iraceminha
42,4207809,Irani
42,4207858,Irati
42,4207908,Irineópolis
42,4208005,Itá
42,4208104,Itaiópolis
42,4208203,Itajaí
42,4208302,Itapema
42,4208401,Itapiranga
42,4208450,Itapoá
42,4208500,Ituporanga
42,4208609,Jaborá
42,4208708,Jacinto Machado
42,4208807,Jaguaruna
42,4208906,Jaraguá do Sul
42,4208955,Jardinópolis
42,4209003,Joaçaba
42,4209102,Joinville
42,4209151,José Boiteux
42,4209177,Jupiá
42,4209201,Lacerdópolis
42,4209300,Lages
42,4209409,Laguna
42,4209458,Lajeado Grande
42,4209508,Laurentino
42,4209607,Lauro Muller
42,4209706,Lebon Régis
42,4209805,Leoberto Leal
42,4209854,Lindóia do Sul
42,4209904,Lontras
42,4210001,Luiz Alves
42,4210035,Luzerna
42,4210050,Macieira
42,4210100,Mafra
42,4210209,Major Gercino
42,4210308,Major Vieira
42,4210407,Maracajá
42,4210506,Maravilha
42,4210555,Marema
42,4210605,Massaranduba
42,4210704,Matos Costa
42,4210803,Meleiro
42,4210852,Mirim doce
42,4210902,Modelo
42,4211009,Mondaí
42,4211058,Monte Carlo
42,4211108,Monte Castelo
42,4211207,Morro da Fumaça
42,4211256,Morro Grande
42,4211306,Navegantes
42,4211405,Nova Erechim
42,4211454,Nova Itaberaba
42,4211504,Nova Trento
42,4211603,Nova Veneza
42,4211652,Novo Horizonte
42,4211702,Orleans
42,4211751,Otacílio Costa
42,4211801,Ouro
42,4211850,Ouro Verde
42,4211876,Paial
42,4211892,Painel
42,4211900,Palhoça
42,4212007,Palma Sola
42,4212056,Palmeira
42,4212106,Palmitos
42,4212205,Papanduva
42,4212239,Paraíso
42,4212254,Passo de Torres
42,4212270,Passos Maia
42,4212304,Paulo Lopes
42,4212403,Pedras Grandes
42,4212502,Penha
42,4212601,Peritiba
42,4212650,Pescaria Brava
42,4212700,Petrolândia
42,4212809,Balneário Piçarras
42,4212908,Pinhalzinho
42,4213005,Pinheiro Preto
42,4213104,Piratuba
42,4213153,Planalto Alegre
42,4213203,Pomerode
42,4213302,Ponte Alta
42,4213351,Ponte Alta do Norte
42,4213401,Ponte Serrada
42,4213500,Porto Belo
42,4213609,Porto União
42,4213708,Pouso Redondo
42,4213807,Praia Grande
42,4213906,Presidente Castello Branco
42,4214003,Presidente Getúlio
42,4214102,Presidente Nereu
42,4214151,Princesa
42,4214201,Quilombo
42,4214300,Rancho Queimado
42,4214409,Rio das Antas
42,4214508,Rio do Campo
42,4214607,Rio do Oeste
42,4214706,Rio dos Cedros
42,4214805,Rio do Sul
42,4214904,Rio Fortuna
42,4215000,Rio Negrinho
42,4215059,Rio Rufino
42,4215075,Riqueza
42,4215109,Rodeio
42,4215208,Romelândia
42,4215307,Salete
42,4215356,Saltinho
42,4215406,Salto Veloso
42,4215455,Sangão
42,4215505,Santa Cecília
42,4215554,Santa Helena
42,4215604,Santa Rosa de Lima
42,4215653,Santa Rosa do Sul
42,4215679,Santa Terezinha
42,4215687,Santa Terezinha do Progresso
42,4215695,Santiago do Sul
42,4215703,Santo Amaro da Imperatriz
42,4215752,São Bernardino
42,4215802,São Bento do Sul
42,4215901,São Bonifácio
42,4216008,São Carlos
42,4216057,São Cristovão do Sul
42,4216107,São domingos
42,4216206,São Francisco do Sul
42,4216255,São João do Oeste
42,4216305,São João Batista
42,4216354,São João do Itaperiú
42,4216404,São João do Sul
42,4216503,São Joaquim
42,4216602,São José
42,4216701,São José do Cedro
42,4216800,São José do Cerrito
42,4216909,São Lourenço do Oeste
42,4217006,São Ludgero
42,4217105,São Martinho
42,4217154,São Miguel da Boa Vista
42,4217204,São Miguel do Oeste
42,4217253,São Pedro de Alcântara
42,4217303,Saudades
42,4217402,Schroeder
42,4217501,Seara
42,4217550,Serra Alta
42,4217600,Siderópolis
42,4217709,Sombrio
42,4217758,Sul Brasil
42,4217808,Taió
42,4217907,Tangará
42,4217956,Tigrinhos
42,4218004,Tijucas
42,4218103,Timbé do Sul
42,4218202,Timbó
42,4218251,Timbó Grande
42,4218301,Três Barras
42,4218350,Treviso
42,4218400,Treze de Maio
42,4218509,Treze Tílias
42,4218608,Trombudo Central
42,4218707,Tubarão
42,4218756,Tunápolis
42,4218806,Turvo
42,4218855,União do Oeste
42,4218905,Urubici
42,4218954,Urupema
42,4219002,Urussanga
42,4219101,Vargeão
42,4219150,Vargem
42,4219176,Vargem Bonita
42,4219200,Vidal Ramos
42,4219309,Videira
42,4219358,Vitor Meireles
42,4219408,Witmarsum
42,4219507,Xanxerê
42,4219606,Xavantina
42,4219705,Xaxim
42,4219853,Zortéa
42,4220000,Balneário Rincão
43,4300034,Aceguá
43,4300059,Água Santa
43,4300109,Agudo
43,4300208,Ajuricaba
43,4300307,Alecrim
43,4300406,Alegrete
43,4300455,Alegria
43,4300471,Almirante Tamandaré do Sul
43,4300505,Alpestre
43,4300554,Alto Alegre
43,4300570,Alto Feliz
43,4300604,Alvorada
43,4300638,Amaral Ferrador
43,4300646,Ametista do Sul
43,4300661,André da Rocha
43,4300703,Anta Gorda
43,4300802,Antônio Prado
43,4300851,Arambaré
43,4300877,Araricá
43,4300901,Aratiba
43,4301008,Arroio do Meio
43,4301057,Arroio do Sal
43,4301073,Arroio do Padre
43,4301107,Arroio dos Ratos
43,4301206,Arroio do Tigre
43,4301305,Arroio Grande
43,4301404,Arvorezinha
43,4301503,Augusto Pestana
43,4301552,Áurea
43,4301602,Bagé
43,4301636,Balneário Pinhal
43,4301651,Barão
43,4301701,Barão de Cotegipe
43,4301750,Barão do Triunfo
43,4301800,Barracão
43,4301859,Barra do Guarita
43,4301875,Barra do Quaraí
43,4301909,Barra do Ribeiro
43,4301925,Barra do Rio Azul
43,4301958,Barra Funda
43,4302006,Barros Cassal
43,4302055,Benjamin Constant do Sul
43,4302105,Bento Gonçalves
43,4302154,Boa Vista das Missões
43,4302204,Boa Vista do Buricá
43,4302220,Boa Vista do Cadeado
43,4302238,Boa Vista do Incra
43,4302253,Boa Vista do Sul
43,4302303,Bom Jesus
43,4302352,Bom Princípio
43,4302378,Bom Progresso
43,4302402,Bom Retiro do Sul
43,4302451,Boqueirão do Leão
43,4302501,Bossoroca
43,4302584,Bozano
43,4302600,Braga
43,4302659,Brochier
43,4302709,Butiá
43,4302808,Caçapava do Sul
43,4302907,Cacequi
43,4303004,Cachoeira do Sul
43,4303103,Cachoeirinha
43,4303202,Cacique doble
43,4303301,Caibaté
43,4303400,Caiçara
43,4303509,Camaquã
43,4303558,Camargo
43,4303608,Cambará do Sul
43,4303673,Campestre da Serra
43,4303707,Campina das Missões
43,4303806,Campinas do Sul
43,4303905,Campo Bom
43,4304002,Campo Novo
43,4304101,Campos Borges
43,4304200,Candelária
43,4304309,Cândido Godói
43,4304358,Candiota
43,4304408,Canela
43,4304507,Canguçu
43,4304606,Canoas
43,4304614,Canudos do Vale
43,4304622,Capão Bonito do Sul
43,4304630,Capão da Canoa
43,4304655,Capão do Cipó
43,4304663,Capão do Leão
43,4304671,Capivari do Sul
43,4304689,Capela de Santana
43,4304697,Capitão
43,4304705,Carazinho
43,4304713,Caraá
43,4304804,Carlos Barbosa
43,4304853,Carlos Gomes
43,4304903,Casca
43,4304952,Caseiros
43,4305009,Catuípe
43,4305108,Caxias do Sul
43,4305116,Centenário
43,4305124,Cerrito
43,4305132,Cerro Branco
43,4305157,Cerro Grande
43,4305173,Cerro Grande do Sul
43,4305207,Cerro Largo
43,4305306,Chapada
43,4305355,Charqueadas
43,4305371,Charrua
43,4305405,Chiapetta
43,4305439,Chuí
43,4305447,Chuvisca
43,4305454,Cidreira
43,4305504,Ciríaco
43,4305587,Colinas
43,4305603,Colorado
43,4305702,Condor
43,4305801,Constantina
43,4305835,Coqueiro Baixo
43,4305850,Coqueiros do Sul
43,4305871,Coronel Barros
43,4305900,Coronel Bicaco
43,4305934,Coronel Pilar
43,4305959,Cotiporã
43,4305975,Coxilha
43,4306007,Crissiumal
43,4306056,Cristal
43,4306072,Cristal do Sul
43,4306106,Cruz Alta
43,4306130,Cruzaltense
43,4306205,Cruzeiro do Sul
43,4306304,david Canabarro
43,4306320,derrubadas
43,4306353,dezesseis de Novembro
43,4306379,Dilermando de Aguiar
43,4306403,dois Irmãos
43,4306429,dois Irmãos das Missões
43,4306452,dois Lajeados
43,4306502,dom Feliciano
43,4306551,dom Pedro de Alcântara
43,4306601,dom Pedrito
43,4306700,dona Francisca
43,4306734,doutor Maurício Cardoso
43,4306759,doutor Ricardo
43,4306767,Eldorado do Sul
43,4306809,Encantado
43,4306908,Encruzilhada do Sul
43,4306924,Engenho Velho
43,4306932,Entre-Ijuís
43,4306957,Entre Rios do Sul
43,4306973,Erebango
43,4307005,Erechim
43,4307054,Ernestina
43,4307104,Herval
43,4307203,Erval Grande
43,4307302,Erval Seco
43,4307401,Esmeralda
43,4307450,Esperança do Sul
43,4307500,Espumoso
43,4307559,Estação
43,4307609,Estância Velha
43,4307708,Esteio
43,4307807,Estrela
43,4307815,Estrela Velha
43,4307831,Eugênio de Castro
43,4307864,Fagundes Varela
43,4307906,Farroupilha
43,4308003,Faxinal do Soturno
43,4308052,Faxinalzinho
43,4308078,Fazenda Vilanova
43,4308102,Feliz
43,4308201,Flores da Cunha
43,4308250,Floriano Peixoto
43,4308300,Fontoura Xavier
43,4308409,Formigueiro
43,4308433,Forquetinha
43,4308458,Fortaleza dos Valos
43,4308508,Frederico Westphalen
43,4308607,Garibaldi
43,4308656,Garruchos
43,4308706,Gaurama
43,4308805,General Câmara
43,4308854,Gentil
43,4308904,Getúlio Vargas
43,4309001,Giruá
43,4309050,Glorinha
43,4309100,Gramado
43,4309126,Gramado dos Loureiros
43,4309159,Gramado Xavier
43,4309209,Gravataí
43,4309258,Guabiju
43,4309308,Guaíba
43,4309407,Guaporé
43,4309506,Guarani das Missões
43,4309555,Harmonia
43,4309571,Herveiras
43,4309605,Horizontina
43,4309654,Hulha Negra
43,4309704,Humaitá
43,4309753,Ibarama
43,4309803,Ibiaçá
43,4309902,Ibiraiaras
43,4309951,Ibirapuitã
43,4310009,Ibirubá
43,4310108,Igrejinha
43,4310207,Ijuí
43,4310306,Ilópolis
43,4310330,Imbé
43,4310363,Imigrante
43,4310405,Independência
43,4310413,Inhacorá
43,4310439,Ipê
43,4310462,Ipiranga do Sul
43,4310504,Iraí
43,4310538,Itaara
43,4310553,Itacurubi
43,4310579,Itapuca
43,4310603,Itaqui
43,4310652,Itati
43,4310702,Itatiba do Sul
43,4310751,Ivorá
43,4310801,Ivoti
43,4310850,Jaboticaba
43,4310876,Jacuizinho
43,4310900,Jacutinga
43,4311007,Jaguarão
43,4311106,Jaguari
43,4311122,Jaquirana
43,4311130,Jari
43,4311155,Jóia
43,4311205,Júlio de Castilhos
43,4311239,Lagoa Bonita do Sul
43,4311254,Lagoão
43,4311270,Lagoa dos Três Cantos
43,4311304,Lagoa Vermelha
43,4311403,Lajeado
43,4311429,Lajeado do Bugre
43,4311502,Lavras do Sul
43,4311601,Liberato Salzano
43,4311627,Lindolfo Collor
43,4311643,Linha Nova
43,4311700,Machadinho
43,4311718,Maçambará
43,4311734,Mampituba
43,4311759,Manoel Viana
43,4311775,Maquiné
43,4311791,Maratá
43,4311809,Marau
43,4311908,Marcelino Ramos
43,4311981,Mariana Pimentel
43,4312005,Mariano Moro
43,4312054,Marques de Souza
43,4312104,Mata
43,4312138,Mato Castelhano
43,4312153,Mato Leitão
43,4312179,Mato Queimado
43,4312203,Maximiliano de Almeida
43,4312252,Minas do Leão
43,4312302,Miraguaí
43,4312351,Montauri
43,4312377,Monte Alegre dos Campos
43,4312385,Monte Belo do Sul
43,4312401,Montenegro
43,4312427,Mormaço
43,4312443,Morrinhos do Sul
43,4312450,Morro Redondo
43,4312476,Morro Reuter
43,4312500,Mostardas
43,4312609,Muçum
43,4312617,Muitos Capões
43,4312625,Muliterno
43,4312658,Não-Me-Toque
43,4312674,Nicolau Vergueiro
43,4312708,Nonoai
43,4312757,Nova Alvorada
43,4312807,Nova Araçá
43,4312906,Nova Bassano
43,4312955,Nova Boa Vista
43,4313003,Nova Bréscia
43,4313011,Nova Candelária
43,4313037,Nova Esperança do Sul
43,4313060,Nova Hartz
43,4313086,Nova Pádua
43,4313102,Nova Palma
43,4313201,Nova Petrópolis
43,4313300,Nova Prata
43,4313334,Nova Ramada
43,4313359,Nova Roma do Sul
43,4313375,Nova Santa Rita
43,4313391,Novo Cabrais
43,4313409,Novo Hamburgo
43,4313425,Novo Machado
43,4313441,Novo Tiradentes
43,4313466,Novo Xingu
43,4313490,Novo Barreiro
43,4313508,Osório
43,4313607,Paim Filho
43,4313656,Palmares do Sul
43,4313706,Palmeira das Missões
43,4313805,Palmitinho
43,4313904,Panambi
43,4313953,Pantano Grande
43,4314001,Paraí
43,4314027,Paraíso do Sul
43,4314035,Pareci Novo
43,4314050,Parobé
43,4314068,Passa Sete
43,4314076,Passo do Sobrado
43,4314100,Passo Fundo
43,4314134,Paulo Bento
43,4314159,Paverama
43,4314175,Pedras Altas
43,4314209,Pedro Osório
43,4314308,Pejuçara
43,4314407,Pelotas
43,4314423,Picada Café
43,4314456,Pinhal
43,4314464,Pinhal da Serra
43,4314472,Pinhal Grande
43,4314498,Pinheirinho do Vale
43,4314506,Pinheiro Machado
43,4314548,Pinto Bandeira
43,4314555,Pirapó
43,4314605,Piratini
43,4314704,Planalto
43,4314753,Poço das Antas
43,4314779,Pontão
43,4314787,Ponte Preta
43,4314803,Portão
43,4314902,Porto Alegre
43,4315008,Porto Lucena
43,4315057,Porto Mauá
43,4315073,Porto Vera Cruz
43,4315107,Porto Xavier
43,4315131,Pouso Novo
43,4315149,Presidente Lucena
43,4315156,Progresso
43,4315172,Protásio Alves
43,4315206,Putinga
43,4315305,Quaraí
43,4315313,Quatro Irmãos
43,4315321,Quevedos
43,4315354,Quinze de Novembro
43,4315404,Redentora
43,4315453,Relvado
43,4315503,Restinga Seca
43,4315552,Rio dos Índios
43,4315602,Rio Grande
43,4315701,Rio Pardo
43,4315750,Riozinho
43,4315800,Roca Sales
43,4315909,Rodeio Bonito
43,4315958,Rolador
43,4316006,Rolante
43,4316105,Ronda Alta
43,4316204,Rondinha
43,4316303,Roque Gonzales
43,4316402,Rosário do Sul
43,4316428,Sagrada Família
43,4316436,Saldanha Marinho
43,4316451,Salto do Jacuí
43,4316477,Salvador das Missões
43,4316501,Salvador do Sul
43,4316600,Sananduva
43,4316709,Santa Bárbara do Sul
43,4316733,Santa Cecília do Sul
43,4316758,Santa Clara do Sul
43,4316808,Santa Cruz do Sul
43,4316907,Santa Maria
43,4316956,Santa Maria do Herval
43,4316972,Santa Margarida do Sul
43,4317004,Santana da Boa Vista
43,4317103,Sant'ana do Livramento
43,4317202,Santa Rosa
43,4317251,Santa Tereza
43,4317301,Santa Vitória do Palmar
43,4317400,Santiago
43,4317509,Santo Ângelo
43,4317558,Santo Antônio do Palma
43,4317608,Santo Antônio da Patrulha
43,4317707,Santo Antônio das Missões
43,4317756,Santo Antônio do Planalto
43,4317806,Santo Augusto
43,4317905,Santo Cristo
43,4317954,Santo Expedito do Sul
43,4318002,São Borja
43,4318051,São domingos do Sul
43,4318101,São Francisco de Assis
43,4318200,São Francisco de Paula
43,4318309,São Gabriel
43,4318408,São Jerônimo
43,4318424,São João da Urtiga
43,4318432,São João do Polêsine
43,4318440,São Jorge
43,4318457,São José das Missões
43,4318465,São José do Herval
43,4318481,São José do Hortêncio
43,4318499,São José do Inhacorá
43,4318507,São José do Norte
43,4318606,São José do Ouro
43,4318614,São José do Sul
43,4318622,São José dos Ausentes
43,4318705,São Leopoldo
43,4318804,São Lourenço do Sul
43,4318903,São Luiz Gonzaga
43,4319000,São Marcos
43,4319109,São Martinho
43,4319125,São Martinho da Serra
43,4319158,São Miguel das Missões
43,4319208,São Nicolau
43,4319307,São Paulo das Missões
43,4319356,São Pedro da Serra
43,4319364,São Pedro das Missões
43,4319372,São Pedro do Butiá
43,4319406,São Pedro do Sul
43,4319505,São Sebastião do Caí
43,4319604,São Sepé
43,4319703,São Valentim
43,4319711,São Valentim do Sul
43,4319737,São Valério do Sul
43,4319752,São Vendelino
43,4319802,São Vicente do Sul
43,4319901,Sapiranga
43,4320008,Sapucaia do Sul
43,4320107,Sarandi
43,4320206,Seberi
43,4320230,Sede Nova
43,4320263,Segredo
43,4320305,Selbach
43,4320321,Senador Salgado Filho
43,4320354,Sentinela do Sul
43,4320404,Serafina Corrêa
43,4320453,Sério
43,4320503,Sertão
43,4320552,Sertão Santana
43,4320578,Sete de Setembro
43,4320602,Severiano de Almeida
43,4320651,Silveira Martins
43,4320677,Sinimbu
43,4320701,Sobradinho
43,4320800,Soledade
43,4320859,Tabaí
43,4320909,Tapejara
43,4321006,Tapera
43,4321105,Tapes
43,4321204,Taquara
43,4321303,Taquari
43,4321329,Taquaruçu do Sul
43,4321352,Tavares
43,4321402,Tenente Portela
43,4321436,Terra de Areia
43,4321451,Teutônia
43,4321469,Tio Hugo
43,4321477,Tiradentes do Sul
43,4321493,Toropi
43,4321501,Torres
43,4321600,Tramandaí
43,4321626,Travesseiro
43,4321634,Três Arroios
43,4321667,Três Cachoeiras
43,4321709,Três Coroas
43,4321808,Três de Maio
43,4321832,Três Forquilhas
43,4321857,Três Palmeiras
43,4321907,Três Passos
43,4321956,Trindade do Sul
43,4322004,Triunfo
43,4322103,Tucunduva
43,4322152,Tunas
43,4322186,Tupanci do Sul
43,4322202,Tupanciretã
43,4322251,Tupandi
43,4322301,Tuparendi
43,4322327,Turuçu
43,4322343,Ubiretama
43,4322350,União da Serra
43,4322376,Unistalda
43,4322400,Uruguaiana
43,4322509,Vacaria
43,4322525,Vale Verde
43,4322533,Vale do Sol
43,4322541,Vale Real
43,4322558,Vanini
43,4322608,Venâncio Aires
43,4322707,Vera Cruz
43,4322806,Veranópolis
43,4322855,Vespasiano Correa
43,4322905,Viadutos
43,4323002,Viamão
43,4323101,Vicente Dutra
43,4323200,Victor Graeff
43,4323309,Vila Flores
43,4323358,Vila Lângaro
43,4323408,Vila Maria
43,4323457,Vila Nova do Sul
43,4323507,Vista Alegre
43,4323606,Vista Alegre do Prata
43,4323705,Vista Gaúcha
43,4323754,Vitória das Missões
43,4323770,Westfalia
43,4323804,Xangri-Lá
50,5000203,Água Clara
50,5000252,Alcinópolis
50,5000609,Amambai
50,5000708,Anastácio
50,5000807,Anaurilândia
50,5000856,Angélica
50,5000906,Antônio João
50,5001003,Aparecida do Taboado
50,5001102,Aquidauana
50,5001243,Aral Moreira
50,5001508,Bandeirantes
50,5001904,Bataguassu
50,5002001,Batayporã
50,5002100,Bela Vista
50,5002159,Bodoquena
50,5002209,Bonito
50,5002308,Brasilândia
50,5002407,Caarapó
50,5002605,Camapuã
50,5002704,Campo Grande
50,5002803,Caracol
50,5002902,Cassilândia
50,5002951,Chapadão do Sul
50,5003108,Corguinho
50,5003157,Coronel Sapucaia
50,5003207,Corumbá
50,5003256,Costa Rica
50,5003306,Coxim
50,5003454,deodápolis
50,5003488,dois Irmãos do Buriti
50,5003504,douradina
50,5003702,dourados
50,5003751,Eldorado
50,5003801,Fátima do Sul
50,5003900,Figueirão
50,5004007,Glória de dourados
50,5004106,Guia Lopes da Laguna
50,5004304,Iguatemi
50,5004403,Inocência
50,5004502,Itaporã
50,5004601,Itaquiraí
50,5004700,Ivinhema
50,5004809,Japorã
50,5004908,Jaraguari
50,5005004,Jardim
50,5005103,Jateí
50,5005152,Juti
50,5005202,Ladário
50,5005251,Laguna Carapã
50,5005400,Maracaju
50,5005608,Miranda
50,5005681,Mundo Novo
50,5005707,Naviraí
50,5005806,Nioaque
50,5006002,Nova Alvorada do Sul
50,5006200,Nova Andradina
50,5006259,Novo Horizonte do Sul
50,5006275,Paraíso das Águas
50,5006309,Paranaíba
50,5006358,Paranhos
50,5006408,Pedro Gomes
50,5006606,Ponta Porã
50,5006903,Porto Murtinho
50,5007109,Ribas do Rio Pardo
50,5007208,Rio Brilhante
50,5007307,Rio Negro
50,5007406,Rio Verde de Mato Grosso
50,5007505,Rochedo
50,5007554,Santa Rita do Pardo
50,5007695,São Gabriel do Oeste
50,5007703,Sete Quedas
50,5007802,Selvíria
50,5007901,Sidrolândia
50,5007935,Sonora
50,5007950,Tacuru
50,5007976,Taquarussu
50,5008008,Terenos
50,5008305,Três Lagoas
50,5008404,Vicentina
51,5100102,Acorizal
51,5100201,Água Boa
51,5100250,Alta Floresta
51,5100300,Alto Araguaia
51,5100359,Alto Boa Vista
51,5100409,Alto Garças
51,5100508,Alto Paraguai
51,5100607,Alto Taquari
51,5100805,Apiacás
51,5101001,Araguaiana
51,5101209,Araguainha
51,5101258,Araputanga
51,5101308,Arenápolis
51,5101407,Aripuanã
51,5101605,Barão de Melgaço
51,5101704,Barra do Bugres
51,5101803,Barra do Garças
51,5101852,Bom Jesus do Araguaia
51,5101902,Brasnorte
51,5102504,Cáceres
51,5102603,Campinápolis
51,5102637,Campo Novo do Parecis
51,5102678,Campo Verde
51,5102686,Campos de Júlio
51,5102694,Canabrava do Norte
51,5102702,Canarana
51,5102793,Carlinda
51,5102850,Castanheira
51,5103007,Chapada dos Guimarães
51,5103056,Cláudia
51,5103106,Cocalinho
51,5103205,Colíder
51,5103254,Colniza
51,5103304,Comodoro
51,5103353,Confresa
51,5103361,Conquista D'oeste
51,5103379,Cotriguaçu
51,5103403,Cuiabá
51,5103437,Curvelândia
51,5103452,denise
51,5103502,Diamantino
51,5103601,dom Aquino
51,5103700,Feliz Natal
51,5103809,Figueirópolis D'oeste
51,5103858,Gaúcha do Norte
51,5103908,General Carneiro
51,5103957,Glória D'oeste
51,5104104,Guarantã do Norte
51,5104203,Guiratinga
51,5104500,Indiavaí
51,5104526,Ipiranga do Norte
51,5104542,Itanhangá
51,5104559,Itaúba
51,5104609,Itiquira
51,5104807,Jaciara
51,5104906,Jangada
51,5105002,Jauru
51,5105101,Juara
51,5105150,Juína
51,5105176,Juruena
51,5105200,Juscimeira
51,5105234,Lambari D'oeste
51,5105259,Lucas do Rio Verde
51,5105309,Luciara
51,5105507,Vila Bela da Santíssima Trindade
51,5105580,Marcelândia
51,5105606,Matupá
51,5105622,Mirassol D'oeste
51,5105903,Nobres
51,5106000,Nortelândia
51,5106109,Nossa Senhora do Livramento
51,5106158,Nova Bandeirantes
51,5106174,Nova Nazaré
51,5106182,Nova Lacerda
51,5106190,Nova Santa Helena
51,5106208,Nova Brasilândia
51,5106216,Nova Canaã do Norte
51,5106224,Nova Mutum
51,5106232,Nova Olímpia
51,5106240,Nova Ubiratã
51,5106257,Nova Xavantina
51,5106265,Novo Mundo
51,5106273,Novo Horizonte do Norte
51,5106281,Novo São Joaquim
51,5106299,Paranaíta
51,5106307,Paranatinga
51,5106315,Novo Santo Antônio
51,5106372,Pedra Preta
51,5106422,Peixoto de Azevedo
51,5106455,Planalto da Serra
51,5106505,Poconé
51,5106653,Pontal do Araguaia
51,5106703,Ponte Branca
51,5106752,Pontes E Lacerda
51,5106778,Porto Alegre do Norte
51,5106802,Porto dos Gaúchos
51,5106828,Porto Esperidião
51,5106851,Porto Estrela
51,5107008,Poxoréu
51,5107040,Primavera do Leste
51,5107065,Querência
51,5107107,São José dos Quatro Marcos
51,5107156,Reserva do Cabaçal
51,5107180,Ribeirão Cascalheira
51,5107198,Ribeirãozinho
51,5107206,Rio Branco
51,5107248,Santa Carmem
51,5107263,Santo Afonso
51,5107297,São José do Povo
51,5107305,São José do Rio Claro
51,5107354,São José do Xingu
51,5107404,São Pedro da Cipa
51,5107578,Rondolândia
51,5107602,Rondonópolis
51,5107701,Rosário Oeste
51,5107743,Santa Cruz do Xingu
51,5107750,Salto do Céu
51,5107768,Santa Rita do Trivelato
51,5107776,Santa Terezinha
51,5107792,Santo Antônio do Leste
51,5107800,Santo Antônio do Leverger
51,5107859,São Félix do Araguaia
51,5107875,Sapezal
51,5107883,Serra Nova dourada
51,5107909,Sinop
51,5107925,Sorriso
51,5107941,Tabaporã
51,5107958,Tangará da Serra
51,5108006,Tapurah
51,5108055,Terra Nova do Norte
51,5108105,Tesouro
51,5108204,Torixoréu
51,5108303,União do Sul
51,5108352,Vale de São domingos
51,5108402,Várzea Grande
51,5108501,Vera
51,5108600,Vila Rica
51,5108808,Nova Guarita
51,5108857,Nova Marilândia
51,5108907,Nova Maringá
51,5108956,Nova Monte Verde
52,5200050,Abadia de Goiás
52,5200100,Abadiânia
52,5200134,Acreúna
52,5200159,Adelândia
52,5200175,Água Fria de Goiás
52,5200209,Água Limpa
52,5200258,Águas Lindas de Goiás
52,5200308,Alexânia
52,5200506,Aloândia
52,5200555,Alto Horizonte
52,5200605,Alto Paraíso de Goiás
52,5200803,Alvorada do Norte
52,5200829,Amaralina
52,5200852,Americano do Brasil
52,5200902,Amorinópolis
52,5201108,Anápolis
52,5201207,Anhanguera
52,5201306,Anicuns
52,5201405,Aparecida de Goiânia
52,5201454,Aparecida do Rio doce
52,5201504,Aporé
52,5201603,Araçu
52,5201702,Aragarças
52,5201801,Aragoiânia
52,5202155,Araguapaz
52,5202353,Arenópolis
52,5202502,Aruanã
52,5202601,Aurilândia
52,5202809,Avelinópolis
52,5203104,Baliza
52,5203203,Barro Alto
52,5203302,Bela Vista de Goiás
52,5203401,Bom Jardim de Goiás
52,5203500,Bom Jesus de Goiás
52,5203559,Bonfinópolis
52,5203575,Bonópolis
52,5203609,Brazabrantes
52,5203807,Britânia
52,5203906,Buriti Alegre
52,5203939,Buriti de Goiás
52,5203962,Buritinópolis
52,5204003,Cabeceiras
52,5204102,Cachoeira Alta
52,5204201,Cachoeira de Goiás
52,5204250,Cachoeira dourada
52,5204300,Caçu
52,5204409,Caiapônia
52,5204508,Caldas Novas
52,5204557,Caldazinha
52,5204607,Campestre de Goiás
52,5204656,Campinaçu
52,5204706,Campinorte
52,5204805,Campo Alegre de Goiás
52,5204854,Campo Limpo de Goiás
52,5204904,Campos Belos
52,5204953,Campos Verdes
52,5205000,Carmo do Rio Verde
52,5205059,Castelândia
52,5205109,Catalão
52,5205208,Caturaí
52,5205307,Cavalcante
52,5205406,Ceres
52,5205455,Cezarina
52,5205471,Chapadão do Céu
52,5205497,Cidade Ocidental
52,5205513,Cocalzinho de Goiás
52,5205521,Colinas do Sul
52,5205703,Córrego do Ouro
52,5205802,Corumbá de Goiás
52,5205901,Corumbaíba
52,5206206,Cristalina
52,5206305,Cristianópolis
52,5206404,Crixás
52,5206503,Cromínia
52,5206602,Cumari
52,5206701,damianópolis
52,5206800,damolândia
52,5206909,davinópolis
52,5207105,Diorama
52,5207253,doverlândia
52,5207352,Edealina
52,5207402,Edéia
52,5207501,Estrela do Norte
52,5207535,Faina
52,5207600,Fazenda Nova
52,5207808,Firminópolis
52,5207907,Flores de Goiás
52,5208004,Formosa
52,5208103,Formoso
52,5208152,Gameleira de Goiás
52,5208301,Divinópolis de Goiás
52,5208400,Goianápolis
52,5208509,Goiandira
52,5208608,Goianésia
52,5208707,Goiânia
52,5208806,Goianira
52,5208905,Goiás
52,5209101,Goiatuba
52,5209150,Gouvelândia
52,5209200,Guapó
52,5209291,Guaraíta
52,5209408,Guarani de Goiás
52,5209457,Guarinos
52,5209606,Heitoraí
52,5209705,Hidrolândia
52,5209804,Hidrolina
52,5209903,Iaciara
52,5209937,Inaciolândia
52,5209952,Indiara
52,5210000,Inhumas
52,5210109,Ipameri
52,5210158,Ipiranga de Goiás
52,5210208,Iporá
52,5210307,Israelândia
52,5210406,Itaberaí
52,5210562,Itaguari
52,5210604,Itaguaru
52,5210802,Itajá
52,5210901,Itapaci
52,5211008,Itapirapuã
52,5211206,Itapuranga
52,5211305,Itarumã
52,5211404,Itauçu
52,5211503,Itumbiara
52,5211602,Ivolândia
52,5211701,Jandaia
52,5211800,Jaraguá
52,5211909,Jataí
52,5212006,Jaupaci
52,5212055,Jesúpolis
52,5212105,Joviânia
52,5212204,Jussara
52,5212253,Lagoa Santa
52,5212303,Leopoldo de Bulhões
52,5212501,Luziânia
52,5212600,Mairipotaba
52,5212709,Mambaí
52,5212808,Mara Rosa
52,5212907,Marzagão
52,5212956,Matrinchã
52,5213004,Maurilândia
52,5213053,Mimoso de Goiás
52,5213087,Minaçu
52,5213103,Mineiros
52,5213400,Moiporá
52,5213509,Monte Alegre de Goiás
52,5213707,Montes Claros de Goiás
52,5213756,Montividiu
52,5213772,Montividiu do Norte
52,5213806,Morrinhos
52,5213855,Morro Agudo de Goiás
52,5213905,Mossâmedes
52,5214002,Mozarlândia
52,5214051,Mundo Novo
52,5214101,Mutunópolis
52,5214408,Nazário
52,5214507,Nerópolis
52,5214606,Niquelândia
52,5214705,Nova América
52,5214804,Nova Aurora
52,5214838,Nova Crixás
52,5214861,Nova Glória
52,5214879,Nova Iguaçu de Goiás
52,5214903,Nova Roma
52,5215009,Nova Veneza
52,5215207,Novo Brasil
52,5215231,Novo Gama
52,5215256,Novo Planalto
52,5215306,Orizona
52,5215405,Ouro Verde de Goiás
52,5215504,Ouvidor
52,5215603,Padre Bernardo
52,5215652,Palestina de Goiás
52,5215702,Palmeiras de Goiás
52,5215801,Palmelo
52,5215900,Palminópolis
52,5216007,Panamá
52,5216304,Paranaiguara
52,5216403,Paraúna
52,5216452,Perolândia
52,5216809,Petrolina de Goiás
52,5216908,Pilar de Goiás
52,5217104,Piracanjuba
52,5217203,Piranhas
52,5217302,Pirenópolis
52,5217401,Pires do Rio
52,5217609,Planaltina
52,5217708,Pontalina
52,5218003,Porangatu
52,5218052,Porteirão
52,5218102,Portelândia
52,5218300,Posse
52,5218391,Professor Jamil
52,5218508,Quirinópolis
52,5218607,Rialma
52,5218706,Rianápolis
52,5218789,Rio Quente
52,5218805,Rio Verde
52,5218904,Rubiataba
52,5219001,Sanclerlândia
52,5219100,Santa Bárbara de Goiás
52,5219209,Santa Cruz de Goiás
52,5219258,Santa Fé de Goiás
52,5219308,Santa Helena de Goiás
52,5219357,Santa Isabel
52,5219407,Santa Rita do Araguaia
52,5219456,Santa Rita do Novo destino
52,5219506,Santa Rosa de Goiás
52,5219605,Santa Tereza de Goiás
52,5219704,Santa Terezinha de Goiás
52,5219712,Santo Antônio da Barra
52,5219738,Santo Antônio de Goiás
52,5219753,Santo Antônio do descoberto
52,5219803,São domingos
52,5219902,São Francisco de Goiás
52,5220009,São João D'aliança
52,5220058,São João da Paraúna
52,5220108,São Luís de Montes Belos
52,5220157,São Luíz do Norte
52,5220207,São Miguel do Araguaia
52,5220264,São Miguel do Passa Quatro
52,5220280,São Patrício
52,5220405,São Simão
52,5220454,Senador Canedo
52,5220504,Serranópolis
52,5220603,Silvânia
52,5220686,Simolândia
52,5220702,Sítio D'abadia
52,5221007,Taquaral de Goiás
52,5221080,Teresina de Goiás
52,5221197,Terezópolis de Goiás
52,5221304,Três Ranchos
52,5221403,Trindade
52,5221452,Trombas
52,5221502,Turvânia
52,5221551,Turvelândia
52,5221577,Uirapuru
52,5221601,Uruaçu
52,5221700,Uruana
52,5221809,Urutaí
52,5221858,Valparaíso de Goiás
52,5221908,Varjão
52,5222005,Vianópolis
52,5222054,Vicentinópolis
52,5222203,Vila Boa
52,5222302,Vila Propício
53,5300108,Brasília

COD,NOME,SIGLA
35,São Paulo, SP
41,Paraná, PR
42,Santa Catarina, SC
43,Rio Grande do Sul, RS
50,Mato Grosso do Sul, MS
11,Rondônia, RO
12,Acre, AC
13,Amazonas, AM
14,Roraima, RR
15,Pará, PA
16,Amapá, AP
17,Tocantins, TO
21,Maranhão, MA
24,Rio Grande do Norte, RN
25,Paraíba, PB
26,Pernambuco, PE
27,Alagoas, AL
28,Sergipe, SE
29,Bahia, BA
31,Minas Gerais, MG
33,Rio de Janeiro, RJ
51,Mato Grosso, MT
52,Goiás, GO
53,Distrito Federal, DF
22,Piauí, PI
23,Ceará, CE
32,Espírito Santo, ES
