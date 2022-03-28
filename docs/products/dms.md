# Dokumendihaldus Sharepointis
*Versioon: 1.3.5.110*

Sharepoint on suurepärane platvorm tööks dokumentidega ja nende haldamiseks.
Vaikimisi on toetatud sellised olulised funktsionaalsused nagu:

* **versiooniajalugu** - iga muudatus dokumendiga talletub versiooniajalukku ning saab hiljem kontrollida ning vajadusel taastada varasemat versiooni
* **sorteerimine ja filtreermine** - mistahes dokumendi andmeväljade järgi sorteerimise ja filtreerimise võimalus
* **otsing** - Sharepointi võimekas otsing leiab märksõnad ka levinud dokumentide sisust (Office dokumendid, PDF, jms)

Oleme omalt poolt lisanud dokumentidega töö lihtsustamiseks eraldi toimingute paneeli, mis muudab dokumentide haldamise veelgi lihtsamaks.
[![](images/dms/manageDocumentPanel.png)](images/dms/manageDocumentPanel.png)


## Registreerimine
Registreerimine annab dokumendile unikaalse numbrikombinatsiooni, mille järgi on seda hiljem lihtsam leida ja identifitseerida.
Dokumendi numbris saab kajastada:

* käesolevat aastat
* viidet kaustale, kus dokument asub
* viidet dokumendiliigile
* unikaalset numbriosa, mis iga registreerimisega suureneb

[![](images/dms/registerDocument.gif)](images/dms/registerDocument.gif)

## Dokumendi numbri broneerimine
Broneerimine võimaldab küsida süsteemilt uue registreerimisnumbri ilma, et seda dokumendile veel rakendatakse. Sageli kasutatakse seda võimalust kui dokumenti pole veel süsteemi üles laetud, kuid dokumendi sisusse on vaja number määrata.
Broneeritud numbri saab lihtsasti kopeerida ning kleepida dokumendile:

[![](images/dms/reserveDocNumber.gif)](images/dms/reserveDocNumber.gif)

Juba broneeritud numbreid kuvatakse rippmenüüs, kust saab kohe numbri rakendada dokumendile:

[![](images/dms/applyReservedDocNumber.gif)](images/dms/applyReservedDocNumber.gif)

## Salvesta dokument PDF-iks
PDF on laialt levinud ja kasutatud dokumendi formaat ning väga sageli on vaja just selles failivormingus dokumente edastada kliendile või koostööpartnerile.
Nüüd saab valitud dokumendi PDF-iks konverteerida vaid paari klõpsuga. Toetatud on järgmiste failide konverteerimine: doc, docx, ppt,  pptx, xls, xlsx, html, rtf, csv, odp, ods, odt, pot, potm, potx, pps, ppsx, ppsxm, pptm

Loodud PDF-i saab salvestada Sharepointi samasse kausta (PDF-ile rakendatakse algse dokumendi metaandmed) või kohe alla laadida:

[![](images/dms/convertToPDF.gif)](images/dms/convertToPDF.gif)

## Seosta partneri andmed
Paljud dokumendid on seotud koostööpartnerite ja teiste ettevõtetega. Selleks, et kindla partneriga seotud dokumente lihtsamini üles leida, on mõistlik dokumendile partneri andmed külge märkida.

Lahendus võimaldab valida partnerite registrist sobiva partneri ning rakendada andmed dokumendile. Kui õige partneri andmeid pole veel registris, saab lihtsasti teostada otsingu äriregistrist ning tõmmata sealt andmed enda partnerite registrisse. 

Vajadusel saab partneri andmeid täiendada ja siis rakendada dokumendile:

[![](images/dms/applyPartnerInfo.gif)](images/dms/applyPartnerInfo.gif)

## Dokumendi loomine mallist
Ettevõtte dokumendimallide kasutamine annab olulist ajavõitu uute dokumentide loomisel ning tagab alati ühtse stiili ning käekirja dokumentide vormistamisel. 

Selleks võimaldab lahendus koondada kõik ettevõtte mallid ühte dokumenditeeki ning kasutada neid mistahes Dokumendihalduse kaustas. Mallist dokumendi loomisel saab valida kausta ja õige malli, anda loodavale dokumendile nimi ning uus dokument ongi loodud

[![](images/dms/new-doc-from-template.gif)](images/dms/new-doc-from-template.gif)
## Dokumentide seostamine
Võimaldab linkida dokumendid omavahel. Mõlemale dokumendile tekib link seotud failile. Valida saab seotud dokumenti Sharepointis olemasolevate dokumentide hulgast. Või laadida üles uue seotud dokumendi - sel juhul saab üles laetud dokument ka seotud dokumendi kõik metaandmed.
[![](images/dms/related-documents.gif)](images/dms/related-documents.gif)

***
Uuendame ja arendame dokumendihalduse lahendust pidevalt edasi ning kõiki lahenduses olemasolevaid võimalusi ei pruugi siin kirjelduses veel üleval olla.
Kui Sul on mõte või idee, mis peaks kindlasti veel ühes head dokumendihalduses olema - anna meile julgelt märku: <mihkel@sharecloud.ee>

*Versioon: 1.5.6.112*