# Mein erstes API

## Allgemeine Infrastruktur
![](./images/Infrastructure.png)

## API Dokumentation
`GET /allitems`: Gibt Alle Elemente der Shopping Liste zurück

`GET /itembyid/{itemdId}`: Gibt ein einzelnes Elemnt zurück.
**Parameter**: `itemId` - Einzigartige Id des Elements

`POST /newelement/{elementId}`: Erstellen von einem neuen Element.
**Parameter**: `elementId` - Einzigartige Id des Elements

`DELETE /itembyid/{itemdId}`: Löschen von einem Element.
**Parameter**: `itemId` - Einzigartige Id des Elements

`PATCH /itembyid/{itemdId}`: Aktualisieren von einem Element.
**Parameter**: `itemId` - Einzigartige Id des Elements

 
