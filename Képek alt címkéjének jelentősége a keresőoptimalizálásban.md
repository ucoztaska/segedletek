# Képek alt címkéjének jelentősége a keresőoptimalizálásban

A SEO (keresőoptimalizálás) nagyon fontos minden egyes weboldal esetében, mivel ez határozza meg a weboldal pozícióját a keresőmotorokban, ezáltal több látogatót hozva a weboldalra.

A SEO jelentős része a tagokban található meg, mivel minden egyes tag olyan információt tartalmaz, amelyeket a Googlebot értékesnek minősít. Ezek a tartalmi tagok (mint például a fejlécek - H1, H2, stb) szöveget tartalmaznak, viszont mi a helyzet a képekkel?

Sokan állítják, hogy egy kép többet mond ezer szónál, viszont amennyiben nem optimalizáljuk rendesen a keresőmotorok számára, csupán a látogatóknak mond valamit; a Googlebotnak pedig semmit. 

A képek lényegét úgy emelhetjük ki, hogy kitöltjük az "alt" címkéit. Ezt minden egyes kép esetében meg kell tenni. Egyes képeknél lehetetlen kitölteni ezt a címkét, viszont az nem nagy gond, főleg ha a kép nem bír nagy jelentőséggel. Az "alt" címke még akkor is hasznos, ha egy kép betöltése sikertelen, a látogató tudja, mit tartalmaz a kép, miről szól az, mivel ilyenkor egy szöveg jelenik meg a kép helyett.

A kép alap HTML kódját mindenki ismeri. Vegyünk példának egy Mona Lisa festményt.

```html
<img src="/images/Mona_Lisa_festmeny.png" />
```

Most nézzük meg alt taggal:

```html
<img src="/images/Mona_Lisa_festmeny.png" alt="Leonardo da Vinci: Mona Lisa" />
```

Így a Googlebot értelmezni tudja, hogy az a kép Mona Lisa festményét ábrázolja.

Sokan indexképeket használnak bejegyzéseknél. Ezek olyan képek, amelyek a bejegyzés lényegét mutatják be a bejegyzések listázásánál, valamint maga a bejegyzések oldalán. Úgy mint a uCoz Táska esetében. Én az $IMG_URL1$ kódot használom a bejegyzések listázásánál, tehát így:

```html
<img src="$IMG_URL1$" />
```

Ilyen esetekben ajánlott a bejegyzés címét elhelyezni alt címkeként:

```html
<img src="$IMG_URL1$" alt="$ENTRY_TITLE$" />
```

Így a Googlebot is tudni fogja, hogy az adott kép a bejegyzést ábrázolja, valamint, hogy az egy adott bejegyzéshez kapcsolódik. Ezáltal jobban rangsorolhatja a weboldal bejegyzését a keresési találatokban.
