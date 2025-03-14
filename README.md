### Frontend

- React
- HTML
- CSS
- JavaScript

### Backend

- Python Django
- MariaDB

[Historia Projektu](https://www.notion.so/Historia-Projektu-1aeb9ae9dd1380fba9eaf9b8dae7bb66?pvs=21)

Kupiliśmy komputer, który posłuży nam jako serwer. Zainstalowaliśmy Proxmoxa - platformę do wirtualizacji. Na tym serwerze utworzyliśmy maszynę wirtualną (VM) z systemem Ubuntu Server. Nasz plan obejmuje wykorzystanie następujących technologii:

1. Docker - do konteneryzacji naszych aplikacji
2. Python Django - jako nasz backend
3. React - jako nasz frontend
4. MariaDB - jako nasza baza danych

Taka konfiguracja umożliwi nam stworzenie nowoczesnej, skalowalnej aplikacji webowej. Docker zapewni nam izolację i łatwość zarządzania poszczególnymi komponentami. Django posłuży nam do szybkiego tworzenia API i logiki biznesowej, React umożliwi nam budowę interaktywnego interfejsu użytkownika, a MariaDB zapewni nam niezawodne przechowywanie danych.

Aby zrealizować ten projekt, będziemy musieli skonfigurować środowisko Dockera na naszej maszynie wirtualnej, stworzyć odpowiednie kontenery dla Django, Reacta i MariaDB, a następnie połączyć je ze sobą za pomocą Docker Compose. Taka architektura zapewni nam elastyczność w rozwoju i wdrażaniu naszej aplikacji.