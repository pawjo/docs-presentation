---
marp: true
style: |
  section {
    color: black;
  }

  section h1 {
    color: black;
  }

  section.title {
    font-size: 32px;
  }

  section.title h1 {
    background-color: white;
    width: fit-content;
    margin: 20px;
  }

  section.title p {
    background-color: white;
    width: fit-content;
    margin: 20px;
  }


  section.lead {
    justify-content: start;
    text-align: left;
    font-weight: bold;
  }

  section.lead h1 {
    font-size: 60px;
    padding: 60px;
  }

  section.lead h3 {
    position: absolute;
    right: 80px;
    bottom: 90px;
  }

  section.content {
    justify-content: start;
    text-align: left;
    padding: 70px;
    padding-right: 700px
  }

  section.content td, th {
    border: none!important;
  }

  section.content-right ul, ol {
    position: fixed;
    right: 60px;
    top: 120px;
    width: 500px;
    padding-right: 50px;
  }

  section.image-right img {
    position: fixed;
    right: 42px;
    top: 120px;
    padding-right: 50px;
    background: none;
  }

  section.image-right-bottom img {
    position: fixed;
    right: 42px;
    bottom: 100px;
    padding-right: 50px;
    background: none;
  }

  section.content-wide {
    padding-right: 90px
  }

---

<!-- _class: lead -->
<!-- footer: 15.09.2022 -->

![bg](template/Slide2.PNG)

# Jak żyć z dokumentacją?

### Paweł Wiszniewski

---

<!-- _class: content image-right-bottom -->
<!-- paginate: true -->

![w:500](obrazy/baby_yoda.webp)

# O mnie

- Junior .NET Developer w Billennium
- Student Informatyki na Politechnice Białostockiej
- Email: pawel.wiszniewski20@gmail.com
- Czasem fotograf

---

<!-- _class: content content-right -->

![bg](template/Slide3.PNG)

# Agenda

1. Jest jak jest
2. Nie musi być tak źle
3. Jak to dokumentacja bez Worda? - Docs as code

---

<!-- _class: title -->

# Jest jak jest

Czyli codzienne problemy
![bg](Obrazy/tlo4.jpg)

---

<!-- _class: content content-right image-right -->

![bg](template/Slide7.PNG)

## Kiedy ostatnio dokumentacja zawiodła?

Oczywiście w kryzysowej sytuacji, gdy nikt nie wie jak coś powinno działać...

![w:500](Obrazy/no_results.png)

---
<!--- _class: content content-right -->

![bg](template/Slide3.PNG)

# Jak wytłumaczyć brak dokumentacji?

- brak czasu
- niechęć do pisania dokumentacji
- kod / sposób działania wydaje się oczywisty
- brak techwriterów w projekcie

![w:380](Obrazy/scrum.jpg)

---

![bg right:30%](Obrazy/plemiona2.jpg)

## Co to jest wiedza plemienna?

- tzw. zdrutowane rozwiązania
- niekompletna wśród członków zespołu
- odejście guru pewnego tematu z projektu = utrata

---

<!-- _class: image-right -->

# Nie musi być tak źle

![w:500](Obrazy/solution.jpg)

---

<!-- _class: content content-right -->

![bg](template/Slide3.PNG)

## A może jednak dokumentacja tworzy się sama? - dokumentacja niejawna

- powstaje podczas analizy, komunikacji z klientem
- skupia się na fragmencie projektu a nie na całym jego zakresie
- nie koniecznie jest rozbudowanym opisem

---

![bg right:30%](Obrazy/memes-sad.gif)

## Wady dokumentacji niejawnej

- nie jest zebrana w jednym miejscu
- możliwość przeoczenia wad rozwiązania
- informacje mogą być nieaktualne

---

<!-- _class: content image-right -->

## Co jeszcze okazuje się pomocne?

W projektach znajdują się przyjaciele dokumentacji - **testy**.

*A testy nie powinny być pisane na podstawie dokumentacji?*

![w:500](Obrazy/qa.jpg)

---

<!-- ![bg](template/Slide3.PNG) -->


## Testy bez dokumentacji

- bez scenariuszy
- testy są również dokumentacją niejawną dla programistów
- aktualne

---
<!-- _class: content content-right -->

![bg](template/Slide3.PNG)

## Jak żyć z dokumentacją

![w:400](obrazy/light.webp)

- wszystkie ustalenia i zmiany w jednym miejscu
- wydzielony czas w każdym sprincie
- proste opisy zadań

---

## Co jeszcze?

- ustalenie potrzeb
- dokumentacja służy do komunikacji ze sobą z przyszłości/przeszłości
- wiedza plemienna, bugi, itp

---

<!-- _class: content content-wide -->

![bg right:40%](obrazy/swiat_gdyby.jpg)

## Co by było, gdyby stworzyć dokumentację przed realizowaniem projektu?

- łatwiejsze wyodrębnienie zadań
- obraz całego rozwiązania
- zmniejszenie ryzyka wystąpienia problemów
- ułatwienie w ocenieniu zmian w stosunku do pierwotnej wersji

---

<!-- _class: content -->

## Niestety niemożliwe

---

<!-- _class: title -->

# Jak to dokumentacja bez Worda? - Docs as code

![bg opacity:70%](Obrazy/docs_as_code_example.jpg)

---
<!-- _class: content content-wide -->

![bg](template/Slide3.PNG)
## Jaka jest idea "Docs as code"?

*upodobnienie procesu tworzenia dokumentacji do procesu tworzenia kodu aplikacji*

 |||
|-|-|
|![w:220](Obrazy/markdown.png)|![w:300](Obrazy/vsc.webp)|

---

<!-- _class: content image-right -->

## Co nam to faktycznie daje?

edycja wraz z kodem
+
sprawdzanie w trakcie code review
+
automatyzacja

= dokumentacja żyje razem z kodem i jest poważniej traktowana

![w:500](Obrazy/super_happy.jpg)

---

![bg right:25%](Obrazy/ruby_error2.png)

## Takie wspaniałe rozwiązanie posiada wady?

- techwriterzy mogą miec trudności
- początkowa konfiguracja i błędy podczas kompilacji

---

<!-- _class: content content-wide -->

## Czy ktoś tego używa?

![bg](template/Slide3.PNG)

|||
|-|-|
|![w:450](Obrazy/spotify.png)|![w:450](Obrazy/netflix.png)|
|Spotify for developers      |Netflix Devices|

---
<!-- _class: content image-right -->

## Jekyll

- zaprojektowany do tworzenia blogów
- domyślnie wspierany przez Github Pages

![w:500](Obrazy/jekyll_logo.png)

---
![bg right:60% w:700](Obrazy/demo.png)

## Jekyll demo

---

<!-- _class: content content-wide -->

![bg](template/Slide3.PNG)

## Demo 2 - prezentacja

|||
|-|-|
|![w:700](Obrazy/demo2.png)|Prezentacja została wykonana przy pomocy frameworka Marpit.|

---

## Materiały
- https://testerzy.pl/baza-wiedzy/artykuly/jak-poprawnie-tworzyc-dokumentacje
- https://wedlugplanu.pl/001/
- https://www.writethedocs.org/
- https://bulldogjob.pl/articles/779-pisz-dokumentacje-tak-jak-kod
- https://docs-as-co.de/
- https://jekyllrb.com
- https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll

---

<!-- _class: image-right -->


# Koniec
![w:800](obrazy/dziekuje_za_uwage.jpg)