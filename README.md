# magnetismo
promemoria, cose che si tendono a dimenticare quando non le usi


Come si misura un campo magnetico?
La forza di una elettrocalamita?

Si misura in TESLA e si indica con la lettera T e quindi si usano i sottomultipli, ad esempio mT (milliTesla).

Si misurano anche in gauss e sono proporzionali all'intensità magnetica [A/m].
Abbiamo dunque una corrispondenza diretta di seguito riportata:
#
0,0035 T = 3,5 mT = 35 gauss = circa 2800 A/m
#
0,0010 T = 1,0 mT = 10 gauss = circa 800 A/m
#
0,0005 T = 0,5 mT =  5 gauss = circa 400 A/m

# T
Ricordare che l'unità di misura Tesla è una misura di densità.


# Forza tra due fili percorsi da corrente
Forza = k * i<sub>1</sub> * i<sub>2</sub> * L / d
#
dove k = 2 * 10<sup>-7</sup> [Newton / Ampere<sup>2</sup>], L = lunghezza comune ai due fili, d = distanza tra i due fili

perché k = permeabilità magnetica del vuoto / (2 pigreco)



# Flusso magnetico (fi)
Con flusso magnetico invece si indica quanto campo magnetico attraversa una superficie.
#
fi = B * Area * cos(alfa)

dove
 - B è la densità del campo magnetico
 - alfa è l'angolo tra campo magnetico e superficie

#
# Definizioni delle unità di misura nel Sistema Internazionale (SI).


(f) forza espressa in Newton<br>
[N] unità di misura della forza 
necessaria per accelerare una massa da un chilogrammo (Kg)
di un metro al secondo quadrato (m/s²)
<br>1 N = 1 Kg⋅m/s²
<br>
In altre parole, un newton è la forza che, applicata a un oggetto con una
massa di un chilogrammo, produce un'accelerazione di un metro al secondo quadrato.
Poi l'accelerazione gravitazionale sulla terra vale g = 9,8[m/s²]
<br>quindi 0,98[N] = 0,1[Kg]
<br>mentre 1,00[N] = 0,10204816...[Kg]

(Q) carica elettrica espressa in Coulomb<br>
[C] unità di misura della carica elettrica
<br> 1[C] = 1[A⋅s]

(B) espresso in Tesla<br>
[T] unità di misura del campo magnetico (o induzione magnetica) ossia
la densità del flusso magnetico (B).
<br> 1[T] = Campo magnetico che genera 1[N] di forza su una carica di 1[C] che si muove in
modo perpendicolare al campo con velocità di 1[m/s] per un percorso di 1 m della corrente.
Immaginando un filo disteso su un piano, la lunghezza del filo di 1m può anche essere
curvo, a zig zag o in linea retta, conta la distanza percorsa dalla corrente.
<br> 1 T = 1 N / (C⋅m/s)
<br> 1 T = 1 N / (A⋅m)
<br> 1 T = 1 Kg / (A⋅s²)

Si misura anche in Gauss [G] con i seguenti rapporti
<br> 1[T] = 10000[G]
<br> 1m[T] = 10[G]

(L) induttanza espressa in Henry<br>
[H] unità di misura dell'induttanza che induce la caduta di 1[Volt] se percorsa
da una variazione di corrente di 1[Ampere] per 1[secondo].
<br> 1[H] = 1[V⋅s/A]   (relazione elettrica)
<br> 1[H] = 1[N⋅m/A²]  (relazione magnetica)


(u) permeabilità magnetica espressa in Henry / metro<br>
[H/m] per similitudine con la conduttanza elettrica.
<br> costante nel vuoto u = 4 pigreco / 10000000 [H/m]
<br> cambia per ogni materiale, nell'aria è quasi uguale al vuoto.


(fi) flusso magnetico espresso in Weber<br>
[Wb] unità di misura del flusso magnetico che attraversa una superficie perpendicolarmente
<br> fi = B[T] ⋅ Area[m²]
<br>     [N⋅m²/(A⋅m)] = [N⋅m/A]

(H) intensità del campo magnetico espressa in Ampere al metro<br>
[A/m] unità di misura dell'intensità magnetica
<br> H =    B      /   u
<br>   = [N/(A⋅m)] / [H/m] = [N/(A⋅m)] [A⋅A⋅m/(N⋅m)] = [A/m]

H[A/m] = i[A] ⋅ n[1/m]
<br>dove "n" rappresenta il numero di spire al metro (lunghezza del filo)
#
# Ragionando sulle spire
Dunque, ora immaginando di fare una sola spira con un filo lungo un metro,
si ottiene un certo valore di H che dipende dalla corrente.
<br>Facendo invece due spire con lo stesso metro di filo, si raddoppia il
valore di H e si dimezza l'area circoscritta dalle spire.
<br>In tal modo aumenta la densità magnetica B = u ⋅ H ma, attenzione,
non il flusso complessivo che invece rimane costante.

fi[Wb] = Area [m²] ⋅ B[T] <br>
fi[Wb] = Area [m²] ⋅ u[H/m] ⋅ H[A/m] <br> 
fi[Wb] = Area [m²] ⋅ u[H/m] ⋅ i[A] ⋅ n[1/m] <br> 

Quando si fa un solenoide con varie spire quindi, si mantiene la stessa area
ma si aumenta la lunghezza del filo che aumenta B[T], H[A/m] e fi[Wb].


