# Document Database

## NoSQL Document Database in eigenen Worten
In der Document Database werden die Daten in einzelnen Dokumenten gespeichert nicht wie bei SQL Datenbanken in Tabellen.

## Use Cases
Am besten geeignet ist diese Art von Datenbank, wenn man eine skalierbare Lösung benötigt. Besonders gut sind die geeignet für Benutzerprofile, bei denen man Informationen über einzelne Benutzer speichern muss.

## Beispiel
{
     "id": 1,
     "vorname": "Justin",
     "nachname": "Rasi",
     "email": "justin@gmail.com",
     "hobbies": [
        "soccer",
        "gym",
        "shopping"
     ],
     "arbeit": [
        {
           "name": "ZKB",
           "status": "Lernender",
           "date_founded": {
              "$date": "2012-05-19T04:00:00Z"
           }
        }
     ]
  }

## Unterschiede zu Relationalen Datenbanken
Bei Dokument Datenbanken werden die Informationen in einem einzelnen File gespeichert. Es ist deshalb ein eigenes Objekt.

## Bekannteste Dokument Datenbanken
Zu den bekanntesten Dokument Datenbanken gehören z.B. folgende:
Amazon DynamoDB.
MongoDB.
MongoDB Atlas.
Couchbase.
Google Cloud Firestore.
InterSystems IRIS.
Percona Server for MongoDB.
ArangoDB.