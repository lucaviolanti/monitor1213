## Disclaimer ##
Il progetto è stato sviluppato e testato **solo** su piattaforma Windows 7 x64, pertanto non è garantito che funzioni su altre piattaforme.
### Versione di Netbeans consigliata ###
[Netbeans + JDK](http://www.oracle.com/technetwork/java/javase/downloads/jdk-7-netbeans-download-432126.html)

# Istruzioni #

Recuperare il file corrispondente alla versione del sistema operativo utilizzato:
  * _caso x64_:[CLIPSJNI.dll x64](http://www.di.unito.it/~piovesan/CLIPSJNI%2064-bit.zip)
  * _caso x86_: visitare la pagina [CLIPSJNI.dll x86](https://code.google.com/p/xclipsjni/source/browse/#svn%2Ftrunk%2FXCLIPSJNI%2FCLIPSJNI), cercare il file "CLIPSJNI.dll", Salva come...

e copiarlo nella cartella nel java.library.path (di default è C:\Windows\System32).

Se è stato modificato il java.library.path, si può recuperarlo con il metodo:
`System.getProperty("java.library.path");`

A questo punto è possibile effettuare checkout della versione corrente del progetto da Netbeans.