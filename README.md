# 🚗 Keréknyom – Autós Élménybeszámoló Platform

A **Keréknyom** egy full-stack webalkalmazás, amely lehetővé teszi, hogy autótulajdonosok megosszák tapasztalataikat járművükről, értékeléseket adjanak különböző szempontok alapján (pl. megbízhatóság, teljesítmény), képeket töltsenek fel, és mások hozzászólásokat írhassanak.

---

## 📸 Funkciók

- Autós posztok létrehozása képpel és leírással
- Értékelés több szempont szerint:
  - Teljesítmény, megbízhatóság, kényelem, szervizélmény, stb.
- Kommentelés a bejegyzések alatt
- Posztok listázása, részletes nézet
- Rendezés teljesítmény / megbízhatóság alapján

---

## 🛠️ Tech Stack
* [![Angular][Angular.io]][Angular-url]

| Technológia       | Leírás                        |
|-------------------|-------------------------------|
| Frontend          | Angular 17                    |
| Backend           | Spring Boot 3.x (Java 17)     |
| Adatbázis         | PostgreSQL 15 / H2            |
| API               | REST + Swagger UI             |



---

## 🚀 Telepítés fejlesztői környezetben

### 1. Backend (Spring Boot)

```bash
cd backend
./mvnw spring-boot:run
Elérés: http://localhost:8080
Swagger UI: http://localhost:8080/swagger-ui/index.html

🌱 További tervek
Felhasználói bejelentkezés (JWT)

Admin panel

Képfeltöltés fájlrendszerbe vagy felhőbe (pl. Cloudinary)

Mobiloptimalizálás



📄 License
Ez a projekt gyakorlati célra készült, nem kereskedelmi felhasználásra.
