![example](https://user-images.githubusercontent.com/55129119/112847014-4d91a800-90af-11eb-88a3-04fa7880afdc.jpg)
# Xamarin_AR
Xamarin AR rakendus koos Nuget ja ARCore liidesega Androidile.
 
Kasutasime Github repositooriumi: https://github.com/xamarin/XamarinComponents/tree/master/Android/ARCore/samples
 
Raskused:
Näite tööle saamine vajas veidi tööd, kuna alguses tekkis mitu viga. Pidi paigaldama uue Android apk versiooni. Pidi muutma Android manifestis target Sdk versiooni ja eemaldama
armeabi-v7a toetatud arhitektuuride seast. Kui emulaatori versioon oli vale ei olnud võimalik ka rakendust mobiilis emuleerida, seda muutes/eemaldades hakkas ta tööle.

Kerge:
Peale tööle saamist oli rakenduse ülesehitus üsna loogiline. Kuigi materjale lugedes ei soovita paljud Xamarini AR rakenduste loomiseks, pigem soovitatakse kasutada Unityt.
