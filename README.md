# TAPI

## Punkty

__PUNKTY ZNAJDUJĄ SIĘ [TUTAJ](./punkty.md)__

---

## Egzamin

Egzamin odbędzie się:
**03.02.2025 r. godz. 13:00 w sali 405**

---

## Projekt

Minimum 3 resourcy i minimum 3 poziomy zagniedżenia

Do oceny projektu:

### 1. Rest (10 pkt.)

1. Stworzenie routów dla resourców swojego tematu
   - 5 podstawowych metod HTTP dla każdego resourcu (GET dwa razy)
   - routy powinny być zgodne z RESTowymi założeniami
2. Poprawne użycie w.w. metod HTTP
   - powinny wykonywać to do czego służą
3. Poprawnie użycie kodów HTTP
   - **minimum** po 3 na każdy endpoint
   - odpowiednie zwrotki dla odpowiednich sytuacji
4. Poprawne użycie nagłówków HTTP
   - **minimum** po 3 na każdy endpoint
   - mogą być jako middleware'y
5. HATEOS
   - podstawowa struktura linków do poruszania się po applikacji
6. Konfiguracja serwera
   - odpowiednia obsługa corsów (przyjmujemy tylko sensowne originy)
7. Poprawność RESTa
   - zachowane zasady nazewnictwa resourców

### 2. GraphQL (10 pkt.)

1. Stworzenie definicji typów gQL
   - typy te same (lub sensownie podobne) co w REST API
   - Query i Mutacje te same (lub sensownie podobne) co w REST API
   - minimum 1 własny scalar
   - minimum 1 typ filtrujący
   - minimum 1 typ inputowy (a najlepiej wszystkie)
2. Implementacja resolverów gQL
   - zwracające odpowiednie dane
   - powinna się znaleźć w nich logika filtrowania, sortowania, paginacji
   - filtrowanie powinno pozwalać na wybór sposobu filtrowania:
     - dla stringów: równy, zawiera, nie równy, nie zawiera
     - dla liczb: równy, większy, mniejszy, większy lub równy, mniejszy lub równy
     - dla innych typów: `¯\_(ツ)_/¯`
3. Konfiguracja serwera GraphQL korzystajacego z w/w typów oraz resolverów
4. Dodanie do projektu playgroundu (np. ApolloPlayground lub GraphQLi)

### 3. gRPC (10 pkt.)

1. Przygotowanie plików .proto z definicjami
   - typy te same (lub sensownie podobne) co w REST API i GraphQL
   - serwisy i metody te same (lub sensownie podobne) co w REST API i GraphQL
2. Implementacja resolverów serwisów opisanych w pliku .proto
   - powinna się znaleźć w nich logika filtrowania, sortowania, paginacji
3. Konfiguracja serwera
   - funkcje resolverów wyniesione do osobnych plików
4. Konfiguracja klienta który będzie korzystał z serwera
   - klient powinien być gotowy do odpalenia i przetestowania

### 4. Dokumentacja (10 pkt.)

1. Wygenerowanie pliku zgodnego ze specyfikacją OpenAPI na podstawie wcześniej zrobionego REST API
   - musi zawierać schemy obiektów
2. Komentarze dokumentacji
3. SwaggerUI
4. Docusaurus z krótkim opisem o czym jest API, jakie technologie użyte itp.
   - odnośniki do podstron

### 5. Typescript (10 pkt.)

1. Otypowanie projektu w jakimś stopniu
   - w zależności od zaawansowania projektu i użytych bibliotek; im prostszy projekt tym więcej powinno być otypowane
2. Zadania z typescripta na zajęciach
   - **wstępnie(!)** wychodzi na zajęcia 29.11

### 6. Aktywność (10 pkt.)

1. Obecności
2. Aktywność

---

### Ujemne punkty :)

1. Pushnięcie node_modulesów
