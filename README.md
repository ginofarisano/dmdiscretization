# dmdiscretization

discretization.py permette di trasformare valori discreti in valori compresi in un intervallo.
È possibile selezionare qualsiasi csv file, specificare i campi e gli intervalli di interesse ed attendere che parta il download con il file modificato.

Per lanciarlo in locale è necessario scaricare l’sdk per python di Google App Engine: https://cloud.google.com/appengine/downloads#Google_App_Engine_SDK_for_Python

É inoltre possibile caricarlo sul web; a tal proposito creare un’applicazione chiamata dmdiscretization e tramite GoogleAppEngineLauncher o tramite terminale caricarlo sul web. A tal proposito fare riferimento al tutorial: https://cloud.google.com/appengine/docs/python/gettingstartedpython27/introduction

esempio: http://dmdiscretization.appspot.com/

In locale non si sono riscontrati problemi per file csv anche di grandi dimensioni. Sul web, invece, con file csv di grandi dimensioni e considerato che GAE per un’applicazione web gratuita mette a disposizione solo 128 MB di Ram, potrebbero esserci dei problemi. 

