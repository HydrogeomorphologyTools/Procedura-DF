#Procedura Runout 1.0.0

#Complete MCR e Web Installer

Procedura semplificata per il calcolo della distanza arresto di potenziali colate detritiche, su base morfometrica.

Utilizza come input uno shapefile di punti su reticolo idrografico creato col toolbox per ArcGIS "Procedura2PointProfile", reperibile in questo stesso account GitHub sotto il percorso "Procedura-DF". Il reticolo viene estratto con approccio slope-area e lo stesso viene classificato in zone di potenziale innesco, propagazione, rallentamento ed arresto di colata in base a formule empiriche di dissipazioine energetica, queste operazioni vengono svolte mediante un ulteriore toolbox per ArcGIS denominato "Procedura" reperibile sempre in questa directory GitHub.
Il presente applicativo, utilizzando i prodotti eaborati dai toolbox per ArcGIS, calcola la distanza d'arresto di una potenziale colata detritica, su base morfometrica.
Applicativo sviluppato nell'ambito di una convenzione con la Regione Veneto sulla pericolosità in zone di conoide.

L'algoritmo non è garantito su porzioni di DTM pianeggianti (stessa quota) e può dare origine ad errori.
Testato su DTM regionale (Veneto) 5 metri.

Versioni del software fornite: Completa con MCR Matlab e Web Installer.

#Eseguibili scaricabili al seguente link:
#https://github.com/HydrogeomorphologyTools/Procedura-DF/releases
