Multiwii_Nav_V2.3 NAV V7
=================

Mutliwii 2.3 + GPS NAV + Drotek V3 support

----------------------------------------------------------------
Modification apportées par Olivier FERNANDEZ wareck@cegetel.net:
----------------------------------------------------------------
Code bas� sur Multiwii 2.3 Nav b7 (eosbandi)
-int�gration des cartes DroflyV2 et DroflyV3
-Int�gration du support SDCARD et correction de quelques bugs li�s au datalogger
-Correction d'un bug du variometre
-Correction d'un bug lié au failsafe
-Ajout du code de restriction de vol "Wadudu"
-Ajout du support des cartes PCF8591 I2C ADC
-Ajout d'une boucle de controle sur la validité des options SDCARD dans config.h
-Patch correctif pour le SBUS (permet l'utilisation de recepteur orangeRX/futaba SBUS, inverseur necessaire http://www.fernitronix.fr/fr/multi-copters/les-gadgets-multiwii/les-recepteurs-sbus-et-multiwii-2-3 )
-Correction des calculs pour le baromètre
-Ajout d'option permettant au code de fonctionner sans GPS
-Utilisation possible d'inter 6 poisitions pour les voies AUX
-Traduction en français des messages d'aletre lors de la compilation

Code based on Multiwii 2.3 Nav b7 (eosbandi)
-DroflyV2 and DroflyV3 boards integration
-code integration for SDCARD and corrective patch for datalogger
-corrective patch for variometer error
-corrective patch for failsafe bug
-integrate code volume fly restriction "Wadudu"
-Add PCF8591 I2C ADC card support
-add build error if SDCARD options aren't well tuned in config.h
-Sbus Corrective patch (can use orangeRX or futaba sbus, need an inverter http://www.fernitronix.fr/fr/multi-copters/les-gadgets-multiwii/les-recepteurs-sbus-et-multiwii-2-3 )
-Corrective patch for Barometer
-Allow code works without GPS
-Allow 6 position switch for AUX
-French conversion for some compilation error code
