# Hemtenta-Spring-Security

---

## Hot 1: SQL Injection (20 poäng totalt)

### G-frågor (12 poäng)

**1.1 Hotet och er implementation (8p)**
- Förklara hur SQL injection fungerar mot REST APIs (3p)
- Visa kodexempel från era JPA Repository-operationer som skyddar mot SQL injection (5p)

**1.2 Skyddsmekanismen (4p)**
- Förklara hur JPA/Hibernate förhindrar SQL injection med prepared statements

---

## Hot 2: Trasig autentisering (30 poäng totalt)

### G-frågor (18 poäng)

**2.1 Hotet och lösenordssäkerhet (10p)**
- Beskriv autentiseringsproblem som kan drabba REST APIs (4p)
- Visa kodexempel på BCrypt-hashing och lösenordsvalidering (6p)

**2.2 Session-baserad autentisering (8p)**
- Förklara hur sessions fungerar för ert API och vad som händer vid inloggning

### VG-frågor (12 poäng)

**2.3 JWT implementation (12p)**
- Visa kod för JWT-generering och validering (8p)
- Förklara fördelarna med stateless authentication för REST APIs (4p)

---

## Hot 3: Trasig auktorisering (30 poäng totalt)

### G-frågor (18 poäng)

**3.1 Hotet och rollbaserad säkerhet (12p)**
- Beskriv privilege escalation i APIs med exempel (4p)
- Visa er Spring Security konfiguration för endpoint-skydd baserat på roller (8p)

**3.2 HTTP-statuskoder (6p)**
- Förklara skillnaden mellan 401 och 403, ge exempel från ert API

### VG-frågor (12 poäng)

**3.3 Metodsäkerhet (8p)**
- Visa @PreAuthorize-annotationer från era service-klasser

**3.4 Objektbaserad säkerhet (4p)**
- Hur implementerar ni att User A inte kan komma åt User B:s data?

---

## Hot 4: Exponering av känslig data (12 poäng totalt)

### G-frågor (8 poäng)

**4.1 Dataskydd (8p)**
- Förklara vilka typer av känslig data som kan läcka via APIs (2p)
- Visa hur ni använder DTOs för att filtrera känslig data från API-responses (6p)

### VG-frågor (4 poäng)

**4.2 Avancerad datakryptering (4p)**
- Visa implementation av kryptering av känslig data utöver lösenord

---

## Hot 5: Säkerhetskonfigurationsfel (8 poäng totalt)

### G-frågor (4 poäng)

**5.1 Spring Security konfiguration (4p)**
- Visa er SecurityConfiguration-klass och förklara vilka endpoints som är öppna vs skyddade

### VG-frågor (4 poäng)

**5.2 Avancerad konfiguration (4p)**
- Visa implementation av antingen säkra HTTP-headers ELLER rate limiting (välj ett)

---
