# 🚗 Keréknyom – Autós Élménybeszámoló Platform

A **Keréknyom** egy full-stack webalkalmazás, amely lehetővé teszi, hogy autótulajdonosok megosszák tapasztalataikat járművükről, értékeléseket adjanak különböző szempontok alapján (pl. megbízhatóság, teljesítmény), képeket töltsenek fel, és mások hozzászólásokat írhassanak.

---

## 📸 Funkciók

- Autós posztok létrehozása képpel és leírással
- Értékelés több szempont szerint:
  - Teljesítmény, megbízhatóság, kényelem, fenntartási költség, stb.
- Kommentelés a bejegyzések alatt
- Posztok listázása és részletes megtekintése
- Szűrés vagy rendezés teljesítmény / megbízhatóság alapján

---

## 🛠️ Tech Stack

| Technológia       | Leírás                        |
|-------------------|-------------------------------|
| Frontend          | Angular 17                    |
| Backend           | Spring Boot 3.x (Java 17)     |
| Adatbázis         | H2 (fejlesztéshez), PostgreSQL (később) |
| API               | REST + Swagger UI             |

---

## 📦 Projektstruktúra


---

## 🚀 Telepítés és futtatás fejlesztői környezetben

### 1. Backend (Spring Boot)

#### Előkészületek:

- Java 17+
- Maven 3.8+

#### Parancsok:

```bash
cd backend
./mvnw spring-boot:run
