# vue-prov-2020-12-08
Vue prov för 190s

## Att tänka på

1. Använd back-ticks **` ` (shift + `)** om du vill ha html över flera rader i en komponent.
```        var testcomponent = {
            template: `
                <div>
                    <p></p>
                </div>
            `
        }
```
2.	Använd små bokstäver på komponent-namn och events/metoder.

## Fråga 1 - Interpolation

Skapa två data variabler som heter **pi** och **e**, tilldela pi värdet 3.14 och e värdet 2.71.
Skriv sedan ut texten **"Pi har värdet 3.14"** och **"E har värdet 2.71"** med hjälp av data variablerna och valfria taggar.

### Resultat
**Pi har värdet 3.14**<br><br>
**E har värdet 2.71**<br>

## Fråga 2 - Loopa
1. Skapa en data variabel med namnet **students** som är en **array [ ]** och innehåller tre objekt med studenter:

```
{id: 1, name: 'Kalle'},
{id: 2, name: 'Pelle'},
{id: 3, name: 'Nalle'}
```

2. Loopa sedan igenom arrayen med studenterna i en html lista där du skriver ut namnet,
du väljer själv om du vill använda <**ul**> unorderd-list eller <**ol**> ordered-list.
