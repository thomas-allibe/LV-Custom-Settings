# LV-Custom-Settings

Sets up my NI LabVIEW Developpement Environnement for best workflow!

## Settings modified

### 1. LabVIEW.ini

This section describes keys modified by the script.

* Show scripting VI server properties & methods </br>
```server.viscripting.showScriptingOperationsInEditor=True```
* Don't show diagram terminals as icons </br>
```FancyFPTerms=False```
* Don't automatically insert feedback node when cycling a wire </br>
```autoInsertFeedbackNode=False```
* Default label position: controls & constants to Left-Middle </br>
```DefaultLabelPositionBD=11```
* Default label position: indicators to Left-Middle </br>
```DefaultLabelPositionIndBD=5```
* Use paper like grid for Front Panel </br>
```SnapGridDrawAsLines=2```
* Enqble TCP VI Server </br>
```server.tcp.enabled=True```

### 2. vi.lib

* Error cluster, remove "(no error)" mention, it's useless...

### 3. VIPM

* OpenG Toolkit
* PaneRelief
* JKI JSON
* JKI HTTP REST
* JKI Flat UI Controls 2.0
* AntiDoc
* AntiDoc Add-on - LabVIEW project documentation
* Asciidoc for LabVIEW