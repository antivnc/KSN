# KSN
KSN - Abschlussaufgabe


KSN 1:

Der Advanced File Source mit (radio.dat) wird mit dem Signal Source multipliziert. Daraufhin folgt der Tiefpassfilter welche im Anschluss in den WBFM Recieve und dann im Rational Resampler landet. Das Ausgangssignal des Resamplers wird dann in den Waterfall Sink, den Frequency Sink und in den Audio sind geführt. 


KSN 2:

Der Advanced File Source mit (radio.dat) wird mit einem Audio Source, welcher vorerst multipliziert wird, addiert. Dieses Signal läuft dann in den WBFM Transmit, welcher in weiterer Folge in einen Rational Resampler und in einen Channel Model läuft. Dies wird in einen weiteren Rational Resampler weitergeführt welcher dann im WBFM Recieve landet. Dieses Ausgangssignal wird nochmals multipliziert und wird dann im Audio Sink ausgegeben. Radio.dat wird im Waterfall Sink und im Frequency Sink ausgegeben.

Ergebnis: In beiden Fällen hört man ein gewisses Rauschen.
