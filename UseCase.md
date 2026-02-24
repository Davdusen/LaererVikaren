## Primære aktører

Bestillingsansvarlig (Gunbritt)  
Administrationen    
Vikarerne
 
## Aktør Handlinger

**Bestillingsansvarlig (Gunbritt):**

Administrerer vikarerne    
Finder kvalificerede vikarer   
Booking bekræftelse til skole/vikarer

**Administrationen:**
Kunne danne et hurtigt overblik

**Vikarerne:**
Oplyser tilgængelighed

## Aktør mål

**Bestillingsansvarlig (Gunbritt):**

Booke vikarer      
Find tilgængelige vikarer    
Fjerner vikarer fra listen

**Administrationen**  
Danne overblik   
Tilføjer nye vikarer     

**Vikarer**    
Oplyser tilgængelighed


## Use cases

| Use Case | Use Case Navn|
| ---- | ---- |
|UC1 | Registrér Vikar |
|UC2 | Book Vikar|
|UC3 | Oplys Tilgængelighed|
|UC4 | Se Vikarer | 
|UC5 | Redigér Vikar|

### Use case 1 
Navn: Registrér Vikar   
Aktør: Administrationen  

1. Påbegynd registrering af vikar
2. System returnerer input form
3.  Input form udfyldes med vikar information
4. System gemmer og bekræfter  
* step 1-4 gentages indtil der ikke flere vikarer skal tilføjes 

### Use case 2
Navn: Book Vikar   
Aktør: Bestillingsansvarlig (Gunbritt)  
Succes:
1. Find kvalificeret vikar   
2. Ring til tilgængelig vikar
3.  Book vikar i systemet
4. System gemmer og bekræfter  booking
5. Skolens informationer sendes til vikar
* step 1-5 gentages indtil der ikke flere vikarer skal bookes

### Use case 3
Navn: Oplys Tilgængelighed  
Aktør: Vikarer 

1. Dan overblik over tilgængelige arbejdsdage
2. Registrer datoer i system
3.  System gemmer og bekræfter  
* step 1-3 gentages indtil der ikke flere tilgængelige arbejdsdage 

## Kvalitetssikring af Use Cases

- Fremgår relevant aktør, samt aktørmål.  
- Fremgår Use Case med step by step.
- Beskriver den et forretningsmål ?
- Ingen UI-specifikke betegnelser ( design: knap osv.)
- Indgår der 3-10 steps
- Tydeligt sprog ( virksomhedesn sprog)
- Er de relevante for casen?


