## Moving average

*Note: You may think of it as "how well the given person has been doing recently".
      This computes exponentially moving average (EMA) of competitor averages.
      EMA is a weighted average, with weights decreasing exponentially,
      meaning that more recent values contribute more to the computed average.
      Here we use α = 0.8, meaning that the average emphasizes last ~5 results
      (weight of results older than 5 is around 1/3 in total and decreases quickly for particular results).
      People with less than 5 averages are ignored (as there's not much data to base on).*
*Updated on  6 August 2023*


### Rubik's Cube

| Moving average | Person |
| ---: | :--- |
| 7.68 | [Ciarán Beahan](https://www.worldcubeassociation.org/persons/2012BEAH01) |
| 8.00 | [Nathaniel Timothy Sunil](https://www.worldcubeassociation.org/persons/2022SUNI01) |
| 8.25 | [Tao Yu (喻韬)](https://www.worldcubeassociation.org/persons/2012YUTA01) |
| 8.38 | [CJ Furey](https://www.worldcubeassociation.org/persons/2022FURE01) |
| 8.64 | [Richard Madden](https://www.worldcubeassociation.org/persons/2017MADD04) |
| 8.89 | [Cillian Hainbach](https://www.worldcubeassociation.org/persons/2022HAIN04) |
| 9.44 | [Enda Loftus](https://www.worldcubeassociation.org/persons/2021LOFT01) |
| 9.44 | [Iollan Walsh](https://www.worldcubeassociation.org/persons/2021WALS03) |
| 10.08 | [Kalin Doherty](https://www.worldcubeassociation.org/persons/2021DOHE02) |
| 10.25 | [Scott Froggatt](https://www.worldcubeassociation.org/persons/2019FROG01) |
| 10.57 | [Rhys Maher](https://www.worldcubeassociation.org/persons/2022MAHE05) |
| 10.69 | [Gerard McAteer](https://www.worldcubeassociation.org/persons/2016MCAT01) |
| 11.31 | [Adam Furlong](https://www.worldcubeassociation.org/persons/2019FURL04) |
| 11.36 | [Eric Quinn](https://www.worldcubeassociation.org/persons/2019QUIN11) |
| 11.71 | [Rían Burke](https://www.worldcubeassociation.org/persons/2019BURK05) |
| 11.72 | [John O'Connell](https://www.worldcubeassociation.org/persons/2015OCON03) |
| 11.83 | [Nicolàs Keane Conesa](https://www.worldcubeassociation.org/persons/2021CONE01) |
| 11.87 | [Aisling Chan](https://www.worldcubeassociation.org/persons/2014CHAN05) |
| 12.03 | [Maeve Hickey](https://www.worldcubeassociation.org/persons/2017HICK06) |
| 12.03 | [Laurence He](https://www.worldcubeassociation.org/persons/2019HELA03) |
| 12.12 | [Conor O'Loughlin](https://www.worldcubeassociation.org/persons/2018OLOU01) |
| 12.20 | [Odhran D’Arcy](https://www.worldcubeassociation.org/persons/2023DARC01) |
| 12.30 | [Keith Jackman](https://www.worldcubeassociation.org/persons/2019JACK03) |
| 12.48 | [Cathal Burke](https://www.worldcubeassociation.org/persons/2021BURK03) |
| 12.54 | [James Tyrrell](https://www.worldcubeassociation.org/persons/2019TYRR01) |
| 12.61 | [Natan Regiec](https://www.worldcubeassociation.org/persons/2022REGI03) |
| 12.64 | [Scott Doyle](https://www.worldcubeassociation.org/persons/2015DOYL04) |
| 12.80 | [Ronan Finke](https://www.worldcubeassociation.org/persons/2021FINK02) |
| 12.92 | [Alex Kelly](https://www.worldcubeassociation.org/persons/2022KELL03) |
| 12.99 | [Kazim Haider](https://www.worldcubeassociation.org/persons/2019HAID03) |
| 13.05 | [Liam Craven](https://www.worldcubeassociation.org/persons/2017CRAV01) |
| 13.15 | [Anthony Tighe](https://www.worldcubeassociation.org/persons/2021TIGH01) |
| 13.20 | [Peter Illes](https://www.worldcubeassociation.org/persons/2022ILLE02) |
| 13.28 | [Tymon Szalinski](https://www.worldcubeassociation.org/persons/2021SZAL01) |
| 13.39 | [Aleksander Bober](https://www.worldcubeassociation.org/persons/2022BOBE02) |
| 13.44 | [Cormac Coffey](https://www.worldcubeassociation.org/persons/2022COFF01) |
| 13.49 | [Oscar Green](https://www.worldcubeassociation.org/persons/2022GREE14) |
| 13.50 | [Ben Timmons](https://www.worldcubeassociation.org/persons/2017TIMM01) |
| 13.56 | [Mikey Whelan](https://www.worldcubeassociation.org/persons/2015WHEL02) |
| 13.59 | [Kim Hackett](https://www.worldcubeassociation.org/persons/2022HACK05) |
| 13.67 | [Andrei Orprecio](https://www.worldcubeassociation.org/persons/2022ORPR01) |
| 13.87 | [Daniel Grealy](https://www.worldcubeassociation.org/persons/2017GREA01) |
| 13.97 | [Andy Lee Mitchell](https://www.worldcubeassociation.org/persons/2017MITC05) |
| 14.02 | [Thomas Visaya-Neville](https://www.worldcubeassociation.org/persons/2014VISA01) |
| 14.04 | [Kelsey McKenna](https://www.worldcubeassociation.org/persons/2012MCKE01) |
| 14.06 | [Adam Bermingham](https://www.worldcubeassociation.org/persons/2020BERM02) |
| 14.06 | [Noah Kirrane](https://www.worldcubeassociation.org/persons/2022KIRR02) |
| 14.10 | [Simon Kelly](https://www.worldcubeassociation.org/persons/2017KELL08) |
| 14.19 | [Tykhon Pererva](https://www.worldcubeassociation.org/persons/2022PERE32) |
| 14.21 | [Oisín Mulkerrin](https://www.worldcubeassociation.org/persons/2023MULK01) |

### 2x2x2 Cube

| Moving average | Person |
| ---: | :--- |
| 2.04 | [Kalin Doherty](https://www.worldcubeassociation.org/persons/2021DOHE02) |
| 2.69 | [Enda Loftus](https://www.worldcubeassociation.org/persons/2021LOFT01) |
| 3.08 | [CJ Furey](https://www.worldcubeassociation.org/persons/2022FURE01) |
| 3.19 | [Richard Madden](https://www.worldcubeassociation.org/persons/2017MADD04) |
| 3.34 | [William Carey](https://www.worldcubeassociation.org/persons/2019CARE02) |
| 3.43 | [Lucas Dowling](https://www.worldcubeassociation.org/persons/2023DOWL01) |
| 3.48 | [Scott Froggatt](https://www.worldcubeassociation.org/persons/2019FROG01) |
| 3.56 | [Thomas Visaya-Neville](https://www.worldcubeassociation.org/persons/2014VISA01) |
| 3.56 | [Keith Jackman](https://www.worldcubeassociation.org/persons/2019JACK03) |
| 3.60 | [Cillian Hainbach](https://www.worldcubeassociation.org/persons/2022HAIN04) |
| 3.67 | [Rían Burke](https://www.worldcubeassociation.org/persons/2019BURK05) |
| 3.69 | [Ciarán Beahan](https://www.worldcubeassociation.org/persons/2012BEAH01) |
| 3.69 | [Tao Yu (喻韬)](https://www.worldcubeassociation.org/persons/2012YUTA01) |
| 3.88 | [Peter Illes](https://www.worldcubeassociation.org/persons/2022ILLE02) |
| 3.99 | [Cathal Murdock](https://www.worldcubeassociation.org/persons/2022MURD01) |
| 4.12 | [John O'Connell](https://www.worldcubeassociation.org/persons/2015OCON03) |
| 4.18 | [Conor McMorrow](https://www.worldcubeassociation.org/persons/2019MCMO01) |
| 4.21 | [Iollan Walsh](https://www.worldcubeassociation.org/persons/2021WALS03) |
| 4.24 | [Rhys Maher](https://www.worldcubeassociation.org/persons/2022MAHE05) |
| 4.47 | [Eric Quinn](https://www.worldcubeassociation.org/persons/2019QUIN11) |
| 4.51 | [Natan Regiec](https://www.worldcubeassociation.org/persons/2022REGI03) |
| 4.52 | [Conor Sheridan](https://www.worldcubeassociation.org/persons/2012SHER01) |
| 4.58 | [Seán O'Toole](https://www.worldcubeassociation.org/persons/2017OTOO03) |
| 4.60 | [Gerard McAteer](https://www.worldcubeassociation.org/persons/2016MCAT01) |
| 4.62 | [Maeve Hickey](https://www.worldcubeassociation.org/persons/2017HICK06) |
| 4.67 | [Jake Donnelly](https://www.worldcubeassociation.org/persons/2015DONN01) |
| 4.67 | [Cathal Burke](https://www.worldcubeassociation.org/persons/2021BURK03) |
| 4.69 | [James Tyrrell](https://www.worldcubeassociation.org/persons/2019TYRR01) |
| 4.79 | [Alex Kelly](https://www.worldcubeassociation.org/persons/2022KELL03) |
| 4.81 | [Oscar Green](https://www.worldcubeassociation.org/persons/2022GREE14) |
| 4.83 | [Kazim Haider](https://www.worldcubeassociation.org/persons/2019HAID03) |
| 4.87 | [Andy Lee Mitchell](https://www.worldcubeassociation.org/persons/2017MITC05) |
| 4.89 | [Julia Hurley](https://www.worldcubeassociation.org/persons/2022HURL02) |
| 4.90 | [Hugo McGrath](https://www.worldcubeassociation.org/persons/2022MCGR02) |
| 4.91 | [Simon Kelly](https://www.worldcubeassociation.org/persons/2017KELL08) |
| 4.91 | [Ben Timmons](https://www.worldcubeassociation.org/persons/2017TIMM01) |
| 4.95 | [Nimai Osio](https://www.worldcubeassociation.org/persons/2019OSIO01) |
| 4.98 | [Ethan Moloney-Illien](https://www.worldcubeassociation.org/persons/2019MOLO02) |
| 4.98 | [Tiernan Garvey](https://www.worldcubeassociation.org/persons/2022GARV01) |
| 5.01 | [Ben Keogh](https://www.worldcubeassociation.org/persons/2016KEOG01) |
| 5.05 | [Conor Smith](https://www.worldcubeassociation.org/persons/2018SMIT37) |
| 5.05 | [Kevin Tspon](https://www.worldcubeassociation.org/persons/2021TSPO01) |
| 5.07 | [Laurence He](https://www.worldcubeassociation.org/persons/2019HELA03) |
| 5.07 | [Ronan Finke](https://www.worldcubeassociation.org/persons/2021FINK02) |
| 5.08 | [Anthony Tighe](https://www.worldcubeassociation.org/persons/2021TIGH01) |
| 5.09 | [Adam Bermingham](https://www.worldcubeassociation.org/persons/2020BERM02) |
| 5.11 | [Brúin Fahy](https://www.worldcubeassociation.org/persons/2022FAHY01) |
| 5.16 | [Nicolàs Keane Conesa](https://www.worldcubeassociation.org/persons/2021CONE01) |
| 5.20 | [Conor Reilly](https://www.worldcubeassociation.org/persons/2022REIL01) |
| 5.22 | [Pal Illes](https://www.worldcubeassociation.org/persons/2022ILLE01) |

### 4x4x4 Cube

| Moving average | Person |
| ---: | :--- |
| 26.61 | [Ciarán Beahan](https://www.worldcubeassociation.org/persons/2012BEAH01) |
| 35.27 | [Cillian Hainbach](https://www.worldcubeassociation.org/persons/2022HAIN04) |
| 37.79 | [Adam Furlong](https://www.worldcubeassociation.org/persons/2019FURL04) |
| 38.40 | [Richard Madden](https://www.worldcubeassociation.org/persons/2017MADD04) |
| 40.19 | [Tao Yu (喻韬)](https://www.worldcubeassociation.org/persons/2012YUTA01) |
| 41.37 | [Laurence He](https://www.worldcubeassociation.org/persons/2019HELA03) |
| 42.55 | [John O'Connell](https://www.worldcubeassociation.org/persons/2015OCON03) |
| 45.25 | [CJ Furey](https://www.worldcubeassociation.org/persons/2022FURE01) |
| 46.24 | [James Tyrrell](https://www.worldcubeassociation.org/persons/2019TYRR01) |
| 46.41 | [Maeve Hickey](https://www.worldcubeassociation.org/persons/2017HICK06) |
| 46.50 | [Eric Quinn](https://www.worldcubeassociation.org/persons/2019QUIN11) |
| 48.29 | [Natan Regiec](https://www.worldcubeassociation.org/persons/2022REGI03) |
| 48.92 | [Gerard McAteer](https://www.worldcubeassociation.org/persons/2016MCAT01) |
| 50.41 | [Ben Timmons](https://www.worldcubeassociation.org/persons/2017TIMM01) |
| 50.61 | [Kalin Doherty](https://www.worldcubeassociation.org/persons/2021DOHE02) |
| 51.75 | [Andy Lee Mitchell](https://www.worldcubeassociation.org/persons/2017MITC05) |
| 52.57 | [Adam Bermingham](https://www.worldcubeassociation.org/persons/2020BERM02) |
| 53.16 | [Liam Craven](https://www.worldcubeassociation.org/persons/2017CRAV01) |
| 53.53 | [Cathal Burke](https://www.worldcubeassociation.org/persons/2021BURK03) |
| 54.16 | [Rían Burke](https://www.worldcubeassociation.org/persons/2019BURK05) |
| 54.92 | [Colm Fitz](https://www.worldcubeassociation.org/persons/2017FITZ01) |
| 55.16 | [Enda Loftus](https://www.worldcubeassociation.org/persons/2021LOFT01) |
| 56.04 | [Ronan Finke](https://www.worldcubeassociation.org/persons/2021FINK02) |
| 56.17 | [Aisling Chan](https://www.worldcubeassociation.org/persons/2014CHAN05) |
| 57.35 | [Rhys Maher](https://www.worldcubeassociation.org/persons/2022MAHE05) |
| 57.39 | [Colm McCarthy](https://www.worldcubeassociation.org/persons/2018MCCA02) |
| 57.53 | [Sinéad Cleary](https://www.worldcubeassociation.org/persons/2019CLEA04) |
| 57.71 | [Simon Kelly](https://www.worldcubeassociation.org/persons/2017KELL08) |
| 58.20 | [Eoin Summerville](https://www.worldcubeassociation.org/persons/2016SUMM02) |
| 58.21 | [Scott Froggatt](https://www.worldcubeassociation.org/persons/2019FROG01) |
| 58.87 | [Conor O'Loughlin](https://www.worldcubeassociation.org/persons/2018OLOU01) |
| 59.19 | [Conor Sheridan](https://www.worldcubeassociation.org/persons/2012SHER01) |
| 1:00.30 | [Tadhg Kelly](https://www.worldcubeassociation.org/persons/2022KELL21) |
| 1:00.53 | [Conor Smith](https://www.worldcubeassociation.org/persons/2018SMIT37) |
| 1:00.56 | [Keith Jackman](https://www.worldcubeassociation.org/persons/2019JACK03) |
| 1:00.81 | [Thomas Visaya-Neville](https://www.worldcubeassociation.org/persons/2014VISA01) |
| 1:01.02 | [Alex Kelly](https://www.worldcubeassociation.org/persons/2022KELL03) |
| 1:02.12 | [Conor Reilly](https://www.worldcubeassociation.org/persons/2022REIL01) |
| 1:02.91 | [Logan Tully](https://www.worldcubeassociation.org/persons/2022TULL02) |
| 1:03.60 | [Mikey Whelan](https://www.worldcubeassociation.org/persons/2015WHEL02) |
| 1:04.23 | [James McCambridge](https://www.worldcubeassociation.org/persons/2019MCCA09) |
| 1:04.48 | [Eoin Brereton Hurley](https://www.worldcubeassociation.org/persons/2014HURL01) |
| 1:04.98 | [Rory Furlong](https://www.worldcubeassociation.org/persons/2022FURL01) |
| 1:05.23 | [Mary Hennessy](https://www.worldcubeassociation.org/persons/2015HENN02) |
| 1:05.32 | [Kevin Tspon](https://www.worldcubeassociation.org/persons/2021TSPO01) |
| 1:06.33 | [Tymon Szalinski](https://www.worldcubeassociation.org/persons/2021SZAL01) |
| 1:06.41 | [Jake Donnelly](https://www.worldcubeassociation.org/persons/2015DONN01) |
| 1:06.51 | [Anthony Tighe](https://www.worldcubeassociation.org/persons/2021TIGH01) |
| 1:07.06 | [Oliver Schuch](https://www.worldcubeassociation.org/persons/2021SCHU02) |
| 1:07.08 | [Eoin Dowling](https://www.worldcubeassociation.org/persons/2017DOWL01) |

### 5x5x5 Cube

| Moving average | Person |
| ---: | :--- |
| 45.63 | [Ciarán Beahan](https://www.worldcubeassociation.org/persons/2012BEAH01) |
| 55.76 | [Nathaniel Timothy Sunil](https://www.worldcubeassociation.org/persons/2022SUNI01) |
| 1:12.17 | [Cillian Hainbach](https://www.worldcubeassociation.org/persons/2022HAIN04) |
| 1:13.48 | [James Tyrrell](https://www.worldcubeassociation.org/persons/2019TYRR01) |
| 1:13.66 | [Adam Furlong](https://www.worldcubeassociation.org/persons/2019FURL04) |
| 1:17.32 | [Laurence He](https://www.worldcubeassociation.org/persons/2019HELA03) |
| 1:18.66 | [Richard Madden](https://www.worldcubeassociation.org/persons/2017MADD04) |
| 1:25.16 | [John O'Connell](https://www.worldcubeassociation.org/persons/2015OCON03) |
| 1:31.11 | [Eric Quinn](https://www.worldcubeassociation.org/persons/2019QUIN11) |
| 1:32.44 | [Gerard McAteer](https://www.worldcubeassociation.org/persons/2016MCAT01) |
| 1:34.23 | [Maeve Hickey](https://www.worldcubeassociation.org/persons/2017HICK06) |
| 1:34.48 | [Colm Fitz](https://www.worldcubeassociation.org/persons/2017FITZ01) |
| 1:35.77 | [Tao Yu (喻韬)](https://www.worldcubeassociation.org/persons/2012YUTA01) |
| 1:37.13 | [CJ Furey](https://www.worldcubeassociation.org/persons/2022FURE01) |
| 1:37.67 | [Liam Craven](https://www.worldcubeassociation.org/persons/2017CRAV01) |
| 1:38.78 | [Conor Reilly](https://www.worldcubeassociation.org/persons/2022REIL01) |
| 1:39.64 | [Adam Bermingham](https://www.worldcubeassociation.org/persons/2020BERM02) |
| 1:39.82 | [Ben Timmons](https://www.worldcubeassociation.org/persons/2017TIMM01) |
| 1:41.69 | [Andy Lee Mitchell](https://www.worldcubeassociation.org/persons/2017MITC05) |
| 1:42.02 | [Colm McCarthy](https://www.worldcubeassociation.org/persons/2018MCCA02) |
| 1:44.33 | [Natan Regiec](https://www.worldcubeassociation.org/persons/2022REGI03) |
| 1:46.64 | [Conor O'Loughlin](https://www.worldcubeassociation.org/persons/2018OLOU01) |
| 1:47.13 | [Scott Doyle](https://www.worldcubeassociation.org/persons/2015DOYL04) |
| 1:49.72 | [Conor Smith](https://www.worldcubeassociation.org/persons/2018SMIT37) |
| 1:50.38 | [Enda Loftus](https://www.worldcubeassociation.org/persons/2021LOFT01) |
| 1:50.58 | [Scott Froggatt](https://www.worldcubeassociation.org/persons/2019FROG01) |
| 1:51.42 | [Mary Hennessy](https://www.worldcubeassociation.org/persons/2015HENN02) |
| 1:51.58 | [Elliott Laurent](https://www.worldcubeassociation.org/persons/2022LAUR09) |
| 1:54.71 | [Oliver Schuch](https://www.worldcubeassociation.org/persons/2021SCHU02) |
| 1:55.40 | [Ronan Finke](https://www.worldcubeassociation.org/persons/2021FINK02) |
| 1:57.52 | [Rían Burke](https://www.worldcubeassociation.org/persons/2019BURK05) |
| 1:58.33 | [Conor Sheridan](https://www.worldcubeassociation.org/persons/2012SHER01) |
| 2:00.98 | [Ben Keogh](https://www.worldcubeassociation.org/persons/2016KEOG01) |
| 2:01.93 | [Kevin Tspon](https://www.worldcubeassociation.org/persons/2021TSPO01) |
| 2:01.98 | [Sinéad Cleary](https://www.worldcubeassociation.org/persons/2019CLEA04) |
| 2:02.01 | [James McCambridge](https://www.worldcubeassociation.org/persons/2019MCCA09) |
| 2:02.66 | [Seán O'Toole](https://www.worldcubeassociation.org/persons/2017OTOO03) |
| 2:04.54 | [Thomas Visaya-Neville](https://www.worldcubeassociation.org/persons/2014VISA01) |
| 2:07.53 | [Simon Kelly](https://www.worldcubeassociation.org/persons/2017KELL08) |
| 2:08.79 | [Eoin Summerville](https://www.worldcubeassociation.org/persons/2016SUMM02) |
| 2:10.05 | [Eoin Dowling](https://www.worldcubeassociation.org/persons/2017DOWL01) |
| 2:16.79 | [Rory Furlong](https://www.worldcubeassociation.org/persons/2022FURL01) |
| 2:32.10 | [Alex Kelly](https://www.worldcubeassociation.org/persons/2022KELL03) |

### 6x6x6 Cube

| Moving average | Person |
| ---: | :--- |
| 1:20.73 | [Ciarán Beahan](https://www.worldcubeassociation.org/persons/2012BEAH01) |
| 2:39.97 | [Richard Madden](https://www.worldcubeassociation.org/persons/2017MADD04) |
| 2:42.31 | [Adam Furlong](https://www.worldcubeassociation.org/persons/2019FURL04) |
| 2:45.56 | [John O'Connell](https://www.worldcubeassociation.org/persons/2015OCON03) |
| 2:53.91 | [Colm Fitz](https://www.worldcubeassociation.org/persons/2017FITZ01) |
| 2:59.39 | [Ben Timmons](https://www.worldcubeassociation.org/persons/2017TIMM01) |
| 3:10.07 | [Conor Reilly](https://www.worldcubeassociation.org/persons/2022REIL01) |
| 3:11.06 | [Eric Quinn](https://www.worldcubeassociation.org/persons/2019QUIN11) |
| 3:14.37 | [Gerard McAteer](https://www.worldcubeassociation.org/persons/2016MCAT01) |
| 3:20.57 | [Conor Smith](https://www.worldcubeassociation.org/persons/2018SMIT37) |
| 3:35.01 | [Maeve Hickey](https://www.worldcubeassociation.org/persons/2017HICK06) |
| 3:45.98 | [Mary Hennessy](https://www.worldcubeassociation.org/persons/2015HENN02) |
| 4:12.18 | [Eoin Dowling](https://www.worldcubeassociation.org/persons/2017DOWL01) |

### 7x7x7 Cube

| Moving average | Person |
| ---: | :--- |
| 2:04.77 | [Ciarán Beahan](https://www.worldcubeassociation.org/persons/2012BEAH01) |
| 4:11.29 | [Adam Furlong](https://www.worldcubeassociation.org/persons/2019FURL04) |
| 4:14.53 | [Richard Madden](https://www.worldcubeassociation.org/persons/2017MADD04) |
| 4:23.82 | [John O'Connell](https://www.worldcubeassociation.org/persons/2015OCON03) |
| 4:29.76 | [Colm Fitz](https://www.worldcubeassociation.org/persons/2017FITZ01) |
| 4:52.41 | [Conor Smith](https://www.worldcubeassociation.org/persons/2018SMIT37) |
| 5:04.19 | [Ben Keogh](https://www.worldcubeassociation.org/persons/2016KEOG01) |
| 5:26.45 | [Gerard McAteer](https://www.worldcubeassociation.org/persons/2016MCAT01) |

### 3x3x3 One-Handed

| Moving average | Person |
| ---: | :--- |
| 12.88 | [Tao Yu (喻韬)](https://www.worldcubeassociation.org/persons/2012YUTA01) |
| 13.57 | [Ciarán Beahan](https://www.worldcubeassociation.org/persons/2012BEAH01) |
| 14.75 | [Richard Madden](https://www.worldcubeassociation.org/persons/2017MADD04) |
| 16.81 | [CJ Furey](https://www.worldcubeassociation.org/persons/2022FURE01) |
| 21.72 | [Scott Froggatt](https://www.worldcubeassociation.org/persons/2019FROG01) |
| 22.21 | [Cillian Hainbach](https://www.worldcubeassociation.org/persons/2022HAIN04) |
| 22.78 | [Eoin Summerville](https://www.worldcubeassociation.org/persons/2016SUMM02) |
| 23.38 | [Maeve Hickey](https://www.worldcubeassociation.org/persons/2017HICK06) |
| 23.87 | [James Tyrrell](https://www.worldcubeassociation.org/persons/2019TYRR01) |
| 23.89 | [Gerard McAteer](https://www.worldcubeassociation.org/persons/2016MCAT01) |
| 24.00 | [Natan Regiec](https://www.worldcubeassociation.org/persons/2022REGI03) |
| 24.82 | [Cathal Burke](https://www.worldcubeassociation.org/persons/2021BURK03) |
| 25.05 | [John O'Connell](https://www.worldcubeassociation.org/persons/2015OCON03) |
| 25.22 | [Miłosz Andzel](https://www.worldcubeassociation.org/persons/2022ANDZ01) |
| 25.52 | [Nicolàs Keane Conesa](https://www.worldcubeassociation.org/persons/2021CONE01) |
| 25.84 | [Blake Bowers](https://www.worldcubeassociation.org/persons/2010BOWE01) |
| 25.93 | [Ronan Finke](https://www.worldcubeassociation.org/persons/2021FINK02) |
| 26.63 | [Iollan Walsh](https://www.worldcubeassociation.org/persons/2021WALS03) |
| 27.40 | [Conor Sheridan](https://www.worldcubeassociation.org/persons/2012SHER01) |
| 28.21 | [Rían Burke](https://www.worldcubeassociation.org/persons/2019BURK05) |
| 29.23 | [Ben Timmons](https://www.worldcubeassociation.org/persons/2017TIMM01) |
| 29.77 | [Adam Furlong](https://www.worldcubeassociation.org/persons/2019FURL04) |
| 29.84 | [Clara O'Brien](https://www.worldcubeassociation.org/persons/2021OBRI04) |
| 30.82 | [Thomas Visaya-Neville](https://www.worldcubeassociation.org/persons/2014VISA01) |
| 30.98 | [Eric Quinn](https://www.worldcubeassociation.org/persons/2019QUIN11) |
| 31.61 | [Kevin Tspon](https://www.worldcubeassociation.org/persons/2021TSPO01) |
| 31.67 | [Kalin Doherty](https://www.worldcubeassociation.org/persons/2021DOHE02) |
| 31.76 | [James McCambridge](https://www.worldcubeassociation.org/persons/2019MCCA09) |
| 32.06 | [Adam Bermingham](https://www.worldcubeassociation.org/persons/2020BERM02) |
| 32.39 | [Enda Loftus](https://www.worldcubeassociation.org/persons/2021LOFT01) |
| 32.62 | [Laurence He](https://www.worldcubeassociation.org/persons/2019HELA03) |
| 32.75 | [Ben Keogh](https://www.worldcubeassociation.org/persons/2016KEOG01) |
| 33.38 | [Eoin Dowling](https://www.worldcubeassociation.org/persons/2017DOWL01) |
| 34.35 | [Cian Ó'Flannagáin](https://www.worldcubeassociation.org/persons/2021OFLA01) |
| 34.79 | [Rory Power Breen](https://www.worldcubeassociation.org/persons/2022BREE02) |
| 34.93 | [Edward Connell](https://www.worldcubeassociation.org/persons/2018CONN04) |
| 36.14 | [Conor Reilly](https://www.worldcubeassociation.org/persons/2022REIL01) |
| 36.58 | [Anthony Tighe](https://www.worldcubeassociation.org/persons/2021TIGH01) |
| 36.61 | [William Carey](https://www.worldcubeassociation.org/persons/2019CARE02) |
| 37.97 | [Tymon Szalinski](https://www.worldcubeassociation.org/persons/2021SZAL01) |
| 38.03 | [Colm Fitz](https://www.worldcubeassociation.org/persons/2017FITZ01) |
| 38.82 | [Zayd Vawda](https://www.worldcubeassociation.org/persons/2022VAWD01) |
| 39.24 | [Daithi O'Connor](https://www.worldcubeassociation.org/persons/2021OCON01) |
| 42.06 | [Simon Kelly](https://www.worldcubeassociation.org/persons/2017KELL08) |
| 44.32 | [Cormac Coffey](https://www.worldcubeassociation.org/persons/2022COFF01) |
| 46.25 | [Mary Hennessy](https://www.worldcubeassociation.org/persons/2015HENN02) |
| 48.21 | [Seán O'Toole](https://www.worldcubeassociation.org/persons/2017OTOO03) |
| 1:00.87 | [Conor Baumann](https://www.worldcubeassociation.org/persons/2009BAUM01) |

### Megaminx

| Moving average | Person |
| ---: | :--- |
| 52.70 | [Enda Loftus](https://www.worldcubeassociation.org/persons/2021LOFT01) |
| 1:02.84 | [Ciarán Beahan](https://www.worldcubeassociation.org/persons/2012BEAH01) |
| 1:05.51 | [Richard Madden](https://www.worldcubeassociation.org/persons/2017MADD04) |
| 1:07.18 | [Scott Froggatt](https://www.worldcubeassociation.org/persons/2019FROG01) |
| 1:10.55 | [Maeve Hickey](https://www.worldcubeassociation.org/persons/2017HICK06) |
| 1:24.76 | [Rían Burke](https://www.worldcubeassociation.org/persons/2019BURK05) |
| 1:25.12 | [Rhys Maher](https://www.worldcubeassociation.org/persons/2022MAHE05) |
| 1:37.20 | [James Tyrrell](https://www.worldcubeassociation.org/persons/2019TYRR01) |
| 1:39.15 | [Rory Furlong](https://www.worldcubeassociation.org/persons/2022FURL01) |
| 1:40.83 | [Adam Furlong](https://www.worldcubeassociation.org/persons/2019FURL04) |
| 1:41.24 | [Cillian Hainbach](https://www.worldcubeassociation.org/persons/2022HAIN04) |
| 1:41.78 | [Tymon Szalinski](https://www.worldcubeassociation.org/persons/2021SZAL01) |
| 1:46.23 | [Seán O'Toole](https://www.worldcubeassociation.org/persons/2017OTOO03) |
| 1:47.66 | [Kevin Tspon](https://www.worldcubeassociation.org/persons/2021TSPO01) |
| 1:49.31 | [John O'Connell](https://www.worldcubeassociation.org/persons/2015OCON03) |
| 1:49.69 | [Ben Timmons](https://www.worldcubeassociation.org/persons/2017TIMM01) |
| 1:49.90 | [Hannah Grossmith](https://www.worldcubeassociation.org/persons/2022GROS04) |
| 1:51.74 | [Colm Fitz](https://www.worldcubeassociation.org/persons/2017FITZ01) |
| 2:00.07 | [Mary Hennessy](https://www.worldcubeassociation.org/persons/2015HENN02) |

### Pyraminx

| Moving average | Person |
| ---: | :--- |
| 2.39 | [Enda Loftus](https://www.worldcubeassociation.org/persons/2021LOFT01) |
| 3.77 | [Richard Madden](https://www.worldcubeassociation.org/persons/2017MADD04) |
| 4.43 | [Kevin Tspon](https://www.worldcubeassociation.org/persons/2021TSPO01) |
| 4.45 | [Ciarán Beahan](https://www.worldcubeassociation.org/persons/2012BEAH01) |
| 4.66 | [Cillian Hainbach](https://www.worldcubeassociation.org/persons/2022HAIN04) |
| 5.14 | [CJ Furey](https://www.worldcubeassociation.org/persons/2022FURE01) |
| 5.26 | [William Carey](https://www.worldcubeassociation.org/persons/2019CARE02) |
| 5.35 | [Jake Donnelly](https://www.worldcubeassociation.org/persons/2015DONN01) |
| 5.47 | [Rían Burke](https://www.worldcubeassociation.org/persons/2019BURK05) |
| 5.48 | [Ronan Finke](https://www.worldcubeassociation.org/persons/2021FINK02) |
| 5.58 | [Miłosz Andzel](https://www.worldcubeassociation.org/persons/2022ANDZ01) |
| 5.90 | [Scott Froggatt](https://www.worldcubeassociation.org/persons/2019FROG01) |
| 6.03 | [Maeve Hickey](https://www.worldcubeassociation.org/persons/2017HICK06) |
| 6.07 | [Diarmuid Leo Clarke](https://www.worldcubeassociation.org/persons/2022CLAR14) |
| 6.48 | [Keith Jackman](https://www.worldcubeassociation.org/persons/2019JACK03) |
| 6.49 | [Rhys Maher](https://www.worldcubeassociation.org/persons/2022MAHE05) |
| 6.50 | [Charlie Maxwell](https://www.worldcubeassociation.org/persons/2022MAXW02) |
| 6.53 | [Oscar Green](https://www.worldcubeassociation.org/persons/2022GREE14) |
| 6.56 | [Brúin Fahy](https://www.worldcubeassociation.org/persons/2022FAHY01) |
| 6.70 | [Ben Keogh](https://www.worldcubeassociation.org/persons/2016KEOG01) |
| 6.79 | [Finian Hogan](https://www.worldcubeassociation.org/persons/2022HOGA01) |
| 6.83 | [Aisling Chan](https://www.worldcubeassociation.org/persons/2014CHAN05) |
| 6.83 | [Tiernan McCorry](https://www.worldcubeassociation.org/persons/2022MCCO09) |
| 6.91 | [Conor Smith](https://www.worldcubeassociation.org/persons/2018SMIT37) |
| 6.91 | [Tymon Szalinski](https://www.worldcubeassociation.org/persons/2021SZAL01) |
| 7.09 | [Brandon McCann](https://www.worldcubeassociation.org/persons/2022MCCA04) |
| 7.27 | [Conor McMorrow](https://www.worldcubeassociation.org/persons/2019MCMO01) |
| 7.32 | [Julia Hurley](https://www.worldcubeassociation.org/persons/2022HURL02) |
| 7.36 | [Ben Timmons](https://www.worldcubeassociation.org/persons/2017TIMM01) |
| 7.49 | [Nuadha Walsh](https://www.worldcubeassociation.org/persons/2021WALS04) |
| 7.57 | [Cathal Burke](https://www.worldcubeassociation.org/persons/2021BURK03) |
| 7.58 | [Finn Molloy](https://www.worldcubeassociation.org/persons/2022MOLL03) |
| 7.67 | [Alex Kelly](https://www.worldcubeassociation.org/persons/2022KELL03) |
| 7.69 | [Adam Bermingham](https://www.worldcubeassociation.org/persons/2020BERM02) |
| 7.69 | [Hugo McGrath](https://www.worldcubeassociation.org/persons/2022MCGR02) |
| 7.81 | [Caelan Tan](https://www.worldcubeassociation.org/persons/2023TANC02) |
| 7.88 | [Conor Gleeson](https://www.worldcubeassociation.org/persons/2022GLEE01) |
| 7.95 | [Daniel O'Donoghue](https://www.worldcubeassociation.org/persons/2022ODON01) |
| 8.06 | [Anthony Tighe](https://www.worldcubeassociation.org/persons/2021TIGH01) |
| 8.10 | [Liam Craven](https://www.worldcubeassociation.org/persons/2017CRAV01) |
| 8.12 | [Iollan Walsh](https://www.worldcubeassociation.org/persons/2021WALS03) |
| 8.12 | [Natan Regiec](https://www.worldcubeassociation.org/persons/2022REGI03) |
| 8.15 | [Lucas Dowling](https://www.worldcubeassociation.org/persons/2023DOWL01) |
| 8.24 | [Eoin Ryan-Preston](https://www.worldcubeassociation.org/persons/2019RYAN03) |
| 8.64 | [Jamie Barton](https://www.worldcubeassociation.org/persons/2021BART03) |
| 8.71 | [Thomas Michael Seán Cunningham](https://www.worldcubeassociation.org/persons/2022CUNN04) |
| 8.82 | [Xavier Skorulski](https://www.worldcubeassociation.org/persons/2019SKOR02) |
| 8.82 | [Clara O'Brien](https://www.worldcubeassociation.org/persons/2021OBRI04) |
| 8.86 | [Paul Watson](https://www.worldcubeassociation.org/persons/2019WATS03) |
| 8.93 | [Conor Sheridan](https://www.worldcubeassociation.org/persons/2012SHER01) |

### Rubik's Clock

| Moving average | Person |
| ---: | :--- |
| 6.44 | [Seán O'Toole](https://www.worldcubeassociation.org/persons/2017OTOO03) |
| 7.61 | [Rían Burke](https://www.worldcubeassociation.org/persons/2019BURK05) |
| 8.21 | [Richard Madden](https://www.worldcubeassociation.org/persons/2017MADD04) |
| 9.82 | [Ben Timmons](https://www.worldcubeassociation.org/persons/2017TIMM01) |
| 10.07 | [William Carey](https://www.worldcubeassociation.org/persons/2019CARE02) |
| 10.08 | [Finian Hogan](https://www.worldcubeassociation.org/persons/2022HOGA01) |
| 10.30 | [Ronan Finke](https://www.worldcubeassociation.org/persons/2021FINK02) |
| 11.16 | [Enda Loftus](https://www.worldcubeassociation.org/persons/2021LOFT01) |
| 11.26 | [Kevin Tspon](https://www.worldcubeassociation.org/persons/2021TSPO01) |
| 11.46 | [Julia Hurley](https://www.worldcubeassociation.org/persons/2022HURL02) |
| 11.53 | [Simon Kelly](https://www.worldcubeassociation.org/persons/2017KELL08) |
| 11.66 | [Nicolàs Keane Conesa](https://www.worldcubeassociation.org/persons/2021CONE01) |
| 12.70 | [Kalin Doherty](https://www.worldcubeassociation.org/persons/2021DOHE02) |
| 13.00 | [Jack Corr](https://www.worldcubeassociation.org/persons/2022CORR06) |
| 13.12 | [Adam Bermingham](https://www.worldcubeassociation.org/persons/2020BERM02) |
| 13.21 | [Mary Hennessy](https://www.worldcubeassociation.org/persons/2015HENN02) |
| 13.53 | [Cillian Hainbach](https://www.worldcubeassociation.org/persons/2022HAIN04) |
| 14.26 | [Nuadha Walsh](https://www.worldcubeassociation.org/persons/2021WALS04) |
| 15.00 | [Brúin Fahy](https://www.worldcubeassociation.org/persons/2022FAHY01) |
| 15.24 | [Conor Reilly](https://www.worldcubeassociation.org/persons/2022REIL01) |
| 15.25 | [Sinéad Cleary](https://www.worldcubeassociation.org/persons/2019CLEA04) |
| 16.41 | [Edward Connell](https://www.worldcubeassociation.org/persons/2018CONN04) |
| 16.47 | [Tymon Szalinski](https://www.worldcubeassociation.org/persons/2021SZAL01) |
| 19.31 | [Jamie Barton](https://www.worldcubeassociation.org/persons/2021BART03) |
| 20.91 | [Ciarán Beahan](https://www.worldcubeassociation.org/persons/2012BEAH01) |
| 21.31 | [Eric Quinn](https://www.worldcubeassociation.org/persons/2019QUIN11) |
| 24.22 | [Clara O'Brien](https://www.worldcubeassociation.org/persons/2021OBRI04) |
| 28.62 | [Iollan Walsh](https://www.worldcubeassociation.org/persons/2021WALS03) |

### Skewb

| Moving average | Person |
| ---: | :--- |
| 3.93 | [Cathal Burke](https://www.worldcubeassociation.org/persons/2021BURK03) |
| 4.03 | [William Carey](https://www.worldcubeassociation.org/persons/2019CARE02) |
| 4.45 | [Rían Burke](https://www.worldcubeassociation.org/persons/2019BURK05) |
| 4.90 | [Enda Loftus](https://www.worldcubeassociation.org/persons/2021LOFT01) |
| 5.08 | [Ronan Finke](https://www.worldcubeassociation.org/persons/2021FINK02) |
| 5.42 | [Richard Madden](https://www.worldcubeassociation.org/persons/2017MADD04) |
| 5.52 | [Ben Timmons](https://www.worldcubeassociation.org/persons/2017TIMM01) |
| 5.66 | [Cillian Hainbach](https://www.worldcubeassociation.org/persons/2022HAIN04) |
| 6.22 | [CJ Furey](https://www.worldcubeassociation.org/persons/2022FURE01) |
| 6.49 | [Hugo McGrath](https://www.worldcubeassociation.org/persons/2022MCGR02) |
| 6.56 | [Timothy Jefferson Ryan](https://www.worldcubeassociation.org/persons/2018RYAN04) |
| 6.94 | [Conor Sheridan](https://www.worldcubeassociation.org/persons/2012SHER01) |
| 7.02 | [Peter Illes](https://www.worldcubeassociation.org/persons/2022ILLE02) |
| 7.10 | [John O'Connell](https://www.worldcubeassociation.org/persons/2015OCON03) |
| 7.17 | [Ciarán Beahan](https://www.worldcubeassociation.org/persons/2012BEAH01) |
| 7.20 | [Alex Kelly](https://www.worldcubeassociation.org/persons/2022KELL03) |
| 7.33 | [Charlie Osborne](https://www.worldcubeassociation.org/persons/2022OSBO02) |
| 7.61 | [Nuadha Walsh](https://www.worldcubeassociation.org/persons/2021WALS04) |
| 7.92 | [Ben Keogh](https://www.worldcubeassociation.org/persons/2016KEOG01) |
| 7.93 | [Maeve Hickey](https://www.worldcubeassociation.org/persons/2017HICK06) |
| 7.96 | [Lucas Dowling](https://www.worldcubeassociation.org/persons/2023DOWL01) |
| 8.01 | [Keith Jackman](https://www.worldcubeassociation.org/persons/2019JACK03) |
| 8.02 | [Aidan Browne](https://www.worldcubeassociation.org/persons/2019BROW10) |
| 8.20 | [Jake Donnelly](https://www.worldcubeassociation.org/persons/2015DONN01) |
| 8.24 | [Kevin Tspon](https://www.worldcubeassociation.org/persons/2021TSPO01) |
| 8.40 | [Julia Hurley](https://www.worldcubeassociation.org/persons/2022HURL02) |
| 8.42 | [Elliott Laurent](https://www.worldcubeassociation.org/persons/2022LAUR09) |
| 8.55 | [Charlie Maxwell](https://www.worldcubeassociation.org/persons/2022MAXW02) |
| 8.56 | [Andy Lee Mitchell](https://www.worldcubeassociation.org/persons/2017MITC05) |
| 8.56 | [Kalin Doherty](https://www.worldcubeassociation.org/persons/2021DOHE02) |
| 8.60 | [Liam Craven](https://www.worldcubeassociation.org/persons/2017CRAV01) |
| 8.63 | [Natan Regiec](https://www.worldcubeassociation.org/persons/2022REGI03) |
| 8.89 | [Scott Froggatt](https://www.worldcubeassociation.org/persons/2019FROG01) |
| 8.90 | [Oscar Green](https://www.worldcubeassociation.org/persons/2022GREE14) |
| 9.07 | [Adam Bermingham](https://www.worldcubeassociation.org/persons/2020BERM02) |
| 9.24 | [Simon Kelly](https://www.worldcubeassociation.org/persons/2017KELL08) |
| 9.27 | [Brúin Fahy](https://www.worldcubeassociation.org/persons/2022FAHY01) |
| 9.42 | [Finn Molloy](https://www.worldcubeassociation.org/persons/2022MOLL03) |
| 9.43 | [Rhys Maher](https://www.worldcubeassociation.org/persons/2022MAHE05) |
| 9.55 | [Sebastian Bunting](https://www.worldcubeassociation.org/persons/2022BUNT04) |
| 9.76 | [Conor Smith](https://www.worldcubeassociation.org/persons/2018SMIT37) |
| 9.99 | [Iollan Walsh](https://www.worldcubeassociation.org/persons/2021WALS03) |
| 10.37 | [Isaac Kenneally](https://www.worldcubeassociation.org/persons/2022KENN13) |
| 10.44 | [Alex Cullen](https://www.worldcubeassociation.org/persons/2016CULL02) |
| 10.49 | [Ethan Moloney-Illien](https://www.worldcubeassociation.org/persons/2019MOLO02) |
| 10.56 | [Rory Furlong](https://www.worldcubeassociation.org/persons/2022FURL01) |
| 10.60 | [Rose O'Neill](https://www.worldcubeassociation.org/persons/2022ONEI04) |
| 10.85 | [Anthony Tighe](https://www.worldcubeassociation.org/persons/2021TIGH01) |
| 10.91 | [Liam Daniel Rocha Oliveira](https://www.worldcubeassociation.org/persons/2022OLIV10) |
| 10.92 | [Daithi O'Connor](https://www.worldcubeassociation.org/persons/2021OCON01) |

### Square-1

| Moving average | Person |
| ---: | :--- |
| 12.28 | [Richard Madden](https://www.worldcubeassociation.org/persons/2017MADD04) |
| 16.31 | [Rían Burke](https://www.worldcubeassociation.org/persons/2019BURK05) |
| 19.73 | [John O'Connell](https://www.worldcubeassociation.org/persons/2015OCON03) |
| 20.10 | [Adam Bermingham](https://www.worldcubeassociation.org/persons/2020BERM02) |
| 23.02 | [Ciarán Beahan](https://www.worldcubeassociation.org/persons/2012BEAH01) |
| 24.49 | [Rory Furlong](https://www.worldcubeassociation.org/persons/2022FURL01) |
| 24.96 | [Mikey Whelan](https://www.worldcubeassociation.org/persons/2015WHEL02) |
| 28.25 | [Conor Sheridan](https://www.worldcubeassociation.org/persons/2012SHER01) |
| 28.85 | [Daithi O'Connor](https://www.worldcubeassociation.org/persons/2021OCON01) |
| 30.62 | [Ben Timmons](https://www.worldcubeassociation.org/persons/2017TIMM01) |
| 32.38 | [Seán O'Toole](https://www.worldcubeassociation.org/persons/2017OTOO03) |
| 33.79 | [Ronan Finke](https://www.worldcubeassociation.org/persons/2021FINK02) |
| 35.94 | [Conor Smith](https://www.worldcubeassociation.org/persons/2018SMIT37) |
| 37.52 | [Eric Quinn](https://www.worldcubeassociation.org/persons/2019QUIN11) |
| 40.43 | [Gerard McAteer](https://www.worldcubeassociation.org/persons/2016MCAT01) |
| 41.51 | [Colm Fitz](https://www.worldcubeassociation.org/persons/2017FITZ01) |
| 42.28 | [Cormac Finke](https://www.worldcubeassociation.org/persons/2021FINK01) |
| 54.00 | [Simon Kelly](https://www.worldcubeassociation.org/persons/2017KELL08) |
| 1:41.82 | [Conor Baumann](https://www.worldcubeassociation.org/persons/2009BAUM01) |

### 3x3x3 With Feet

| Moving average | Person |
| ---: | :--- |
| 1:20.08 | [Ciarán Beahan](https://www.worldcubeassociation.org/persons/2012BEAH01) |

### Rubik's Magic

| Moving average | Person |
| ---: | :--- |
| 1.78 | [Conor Baumann](https://www.worldcubeassociation.org/persons/2009BAUM01) |
