# Osobista Strona-Wizytówka

To jest kod źródłowy mojej osobistej strony internetowej, dostępnej pod adresem [maciejskulski.omg.lol](https://maciejskulski.omg.lol).

## Filozofia Projektu

Stronę zaprojektowałem zgodnie z kilkoma kluczowymi dla mnie zasadami z obszaru technologii i cyberbezpieczeństwa, a jej kod źródłowy jest w pełni otwarty do wglądu.

* **🛡️ Bezpieczeństwo Przede Wszystkim (Security-First)**
    * Wdrożono restrykcyjną politykę **Content Security Policy (CSP)** z użyciem `nonce`, aby zapobiegać atakom XSS.
    * Zastosowano dodatkowe nagłówki bezpieczeństwa, takie jak `Permissions-Policy` i `Referrer-Policy`.
    * Wszystkie linki otwierane w nowej karcie posiadają atrybut `rel="noopener noreferrer"`, chroniąc przed atakami typu tabnabbing.

* **⚡ Architektura Zero-Zależności (Zero-Dependency)**
    * Cała strona zawarta jest w jednym pliku `index.html` i nie polega na żadnych zewnętrznych skryptach, stylach czy fontach.
    * Eliminuje to ryzyko ataków typu *supply-chain* i gwarantuje maksymalną wydajność oraz niezawodność.

* **♿ Pełna Dostępność (Accessibility)**
    * Struktura strony oparta jest na semantycznym HTML5.
    * Zaimplementowano atrybuty ARIA oraz style dla stanu `:focus-visible`, aby ułatwić nawigację osobom korzystającym z klawiatury i czytników ekranu.

* **🕵️ Prywatność Użytkownika (Privacy-Focused)**
    * Strona nie używa plików cookie, skryptów śledzących ani żadnych narzędzi analitycznych. Twoja wizyta jest w 100% anonimowa.
