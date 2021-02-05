# Blitzer AI
Dieses Projekt verwendet object detection, um Geräte zur Geschwindigkeitsüberwachung zu identifizieren. Verwendet wurde dabei das Yolov5s Model von Ultralytics, welches mithilfe von Fotos aus sozialen Netzwerken und Suchmaschinen trainiert wurde. Ziel dieses Projektes ist es, eine Smartphone-App zur Kamera-basierenden Warnung vor Radargeräten zu schaffen. 
## Datengrundlage
| Geschwindigkeitsmessanlage | Anzahl der Bilder | Datei |
|--|--|--|
| Traffipax Traffistar S330 | 1 | - |
| Traffipax Traffiphot S | 1 | - |
| PoliScan Speed | 207 | speed.pt |
| PoliScan FM1| 1056 | fm1.pt |
| Leivtec XV3 | 1| - |
| Jenoptik Traffistar S350 | 253 | - |
| Nicht analysierte Bilder | 5880 | - |

## Roadmap
 - [ ] Ausreichend große Datengrundlage zusammenstellen
 - [ ] Modell trainieren, welches von Smartphones verwendet werden kann, um in Echtzeit Blitzer zu erkennen
 - [ ] Restliche App-Funktionalität und Community-Funktionen integrieren

## Beispielbilder
<img src="https://raw.githubusercontent.com/habibhaidari1/blitzer-ai/master/bilder/1.jpg" />
<img src="https://raw.githubusercontent.com/habibhaidari1/blitzer-ai/master/bilder/2.jpg" />
<img src="https://raw.githubusercontent.com/habibhaidari1/blitzer-ai/master/bilder/3.jpg" />
<img src="https://raw.githubusercontent.com/habibhaidari1/blitzer-ai/master/bilder/4.jpg" />
<img src="https://raw.githubusercontent.com/habibhaidari1/blitzer-ai/master/bilder/5.jpg" />
<img src="https://raw.githubusercontent.com/habibhaidari1/blitzer-ai/master/bilder/6.jpg" />

## Limitationen
 - Weder mein Smartphone, noch mein Computer sind stark genug, um die
   Analyse in Echtzeit zu ermöglichen  
 - Ich konnte die Ergebnisse leider nicht mit realen Daten Testen, da ich keine Gelegenheit hatte
 - Der PoliScan FM1 (Blitzer-Trailer) ist besonders oft in der Datengrundlage vertreten. Das liegt möglicherweise an der charakteristischen Form, welche ein beliebtes Foto-Motiv auf sozialen Netzwerken darstellt