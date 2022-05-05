# gold-digger-release
Po rozbaleni si treba nakonfigurovat nasledovne:
1. account_defaults.properties
- tu sa nastavuje predmetna nakupna mena a percentualne poziadavky na trh, ktore spustia nakup
- automat automaticky spusta nakup ked trhova cena podlezie najlepsi kurz tohtorocneho nakupu
2. messaging.properties
- tu sa nastavuje emailove alebo sms (twillio) konto, z ktoreho chces dostavat notifikacie (login + heslo)
3. startup.sh
- do tohto skriptu si musis uviest svoje api kluce s trade opravnenim, ktore sa nastavia ako premenne prostredia
- je treba aj polygon api kluc na ziskavanie dat z trhu, ten sa da ziskat cez ich stranku s bezplatnou reg.
- posledna vec je nepovinna a to je ciel notifikacie. Automat sam zisti ci ide o mailovu alebo sms notifikaciu
