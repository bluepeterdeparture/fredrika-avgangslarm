# BluePeterDeparture v2.7

Driftkandidat byggd vidare på v2.6.1 med fyra avgränsade korrigeringar:

- 5-minuterslarmet ljuder när displayen växlar från **6 till 5 minuter** (vid 5:59 kvar), så ljud och visning följs åt.
- **Auto** är borttaget. Endast **Dag** och **Natt** finns och senaste manuella val sparas.
- **Skärm vaken** har robustare Wake Lock-logik, visar ✓ endast när låset faktiskt är aktivt och försöker återaktivera låset när appen kommer tillbaka i förgrunden.
- Vid smalare fönster ligger status, testknappar, Skärm vaken och Inställningar kvar i layouten och ska inte försvinna.

Ljuden är oförändrade från v2.6.1:
- `short.wav` = 5-minuterssignal
- `sound.wav` = avgångssignal

Synlig version: `⚓ BluePeterDeparture v2.7`.
