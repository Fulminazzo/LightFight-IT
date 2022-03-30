# LightFight

LightFight e' un plugin combat log creato con l'obiettivo primario della crosscompatibilita'. Infatti, puo' essere utilizzato dalla 1.8 fino alla 1.18 e versioni successive! Qui troverete una semplice lista delle feature piu' importanti, ma vi consiglio di leggere attentamente la [Wiki](https://github.com/Fulminazzo/LightFight-IT/wiki) per capire meglio come funziona il plugin.

## Funzionamento

LightFight e' molto semplice: quando un plugin viene colpito da un'altra entita' e/o un player, lei/lui e' messo in Combat Mode, facendo si' che alcune azioni (eseguire comandi, volare, cambiare la gamemode...) sono bloccate. Tutto cio' puo' essere facilmente modificato nel file [config.yml](https://github.com/Fulminazzo/LightFight-IT/wiki/Configuration) per adattare queste azioni alle vostre preferenze.

<div align="center">
    <img src="https://github.com/Fulminazzo/LightFight-IT/blob/main/images/timer.png" alt="Timer Preview">
    <p style="line-height: 100px"><small>Un uso molto poco pratico della chiave <b>timer</b>.</small></p>
</div>

## Config

Il [File di Configurazione](https://github.com/Fulminazzo/LightFight-IT/tree/main/config.yml) e' cruciale per modificare il comportamento del plugin. Qui troverai molte feature che possono essere applicate:
- **aggiornamento automatico** del file config.yml;
- **combattimento PvE**: abilita la Combat Mode per le entita';
- **respawn automatico** alla morte;
- una lista di **mondi ignorati**;
- una lista di **eventi** da **disabilitare**;
- **barriere**;

e [altro](https://github.com/Fulminazzo/LightFight-IT/wiki/Configuration)!
<p align="center">
    <img src="https://github.com/Fulminazzo/LightFight-IT/blob/main/images/enable.png" alt="Enable Preview">
</p>

## Comandi

Il plugin supporta tre comandi principali:
- [CTag](https://github.com/Fulminazzo/LightFight-IT/wiki/Commands#ctag)
- [CUntag](https://github.com/Fulminazzo/LightFight-IT/wiki/Commands#cuntag)
- [LightFight](https://github.com/Fulminazzo/LightFight-IT/wiki/Commands#lightfight)

I primi due comandi ti permettono di controllare e rimuovere la Comnbat Mode per un utente. Il terzo comando e' il piu' importante per gli admin: permette di controllare e cambiare il funzionamento del plugin o come i giocatori interagiscono con il mondo che li circonda. Il comando ```LightFight``` ammette alcuni sottocomandi che sono spiegati [qui](https://github.com/Fulminazzo/LightFight-IT/wiki/Commands#lightfight).

<p align="center">
    <img src="https://github.com/Fulminazzo/LightFight-IT/blob/main/images/ctag.png" alt="CTag Preview">
</p>

## Messaggi

LightFight ha inoltre una lista di messaggi che possono essere modificati nel [file dei messaggi](https://github.com/Fulminazzo/LightFight-IT/tree/main/messages.yml).

## Integrazioni

Sia [PlaceholderAPI](https://github.com/PlaceholderAPI/PlaceholderAPI) che [WorldGuard](https://enginehub.org/worldguard) sono supportati. Non solo il plugin offre molte [placeholder](https://github.com/Fulminazzo/LightFight/wiki/Placeholders), ma WorldGuard puo' essere usato per **impostare barriere** dove l'utente in combattimento non puo' entrare (questo succedera' solo se la region ha la flag **pvp** impostata su **deny**).
