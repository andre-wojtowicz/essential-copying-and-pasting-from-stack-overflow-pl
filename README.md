# Niezbędnik Kopiuj Wklej ze Stack Overflow

Autor: [Tariq Ali](https://tra38.github.io/)

Książka została pierwotnie opublikowana na [GitBook](https://tra38.gitbooks.io/essential-copying-and-pasting-from-stack-overflow/).

![Ikona Creative Commons Uznanie Autorstwa](cc-by-icon.png)

Ta książka jest na licencji [Creative Commons Uznanie autorstwa 4.0 Międzynarodowe](https://creativecommons.org/licenses/by/4.0/).

Tłumaczenie zostało sfinansowane przez [Wydział Matematyki i Informatyki Uniwersytetu im. Adama Mickiewicza w Poznaniu](https://wmi.amu.edu.pl/).

## Wstęp

Zainspirowana tą okładką. Ta książka została napisana śmiertelnie poważnie.

![Niezbędnik Kopiuj Wklej ze Stack Overflow](cover.jpg)

Źródło: [ThePracticalDev @ Twitter](https://twitter.com/ThePracticalDev/status/705825638851149824).

## Kwestie licencjonowania kodu

Zanim skopiujesz i wkleisz kod, upewnij się, że *masz prawo* skopiować i wkleić ten kod. Jeśli nie masz takiego prawa, dopuścisz się kradzieży czyjejś własności intelektualnej. A to byłoby *lenistwo*.

Większość kodu na Stack Overflow to "wycinki" (ang. *snippets*). Nie spełniają standardów oryginalności i przez to nie są chronione prawem autorskim. Możesz je kopiować i wklejać, nie przejmując się, że przegrasz sprawę w sądzie.

Część kodu na Stack Overflow to o wiele dłuższe fragmenty niż "wycinki". I dlatego kwalifikują się do ochrony prawem autorskim. Domyślnie wszystkie treści na Stack Overflow (włącznie z kodem) są na licencji CC-BY-SA 3.0.

Nie jest to w ogóle licencja rekomendowana w przypadku oprogramowania i SO stara się wybrać inną licencję, która zastąpi ją w przyszłości w odniesieniu do kodu. Ale na razie obowiązuje CC-BY-SA 3.0. Nawet jeśli SO w przyszłości zmieni zasady licencjonowania, to cały wcześniejszy kod nadal pozostanie objęty CC-BY-SA 3.0.

CC-BY-SA 3.0 jest licencją copyleft tak samo jak GPL 3.0. Ogólnie rzecz biorąc, wolno ci korzystać z całego kodu objętego CC-BY-SA 3.0 o ile:

* Uznasz autorstwo strony, z której weźmiesz kod.
* Licencjonujesz swój kod na tych samych warunkach co CC-BY-SA 3.0. Powtórzmy: CC-BY-SA 3.0 nie jest rekomendowana dla oprogramowania, więc licencjonowanie własnego kodu na CC-BY-SA 3.0 nie ma sensu.

Ale jeśli zrobisz prawne czary-mary, to możesz zmienić licencję swojego kodu ze Stack Overflow, z okropnej CC-BY-SA 3.0 na prawilną licencję Open Source odpowiednią dla oprogramowania. Działa to tak:

1. Każdy utwór na licencji CC-BY-SA 3.0 może być automatycznie przeniesiony na wyższą wersję CC-BY-SA 4.0.
2. Zgodnie ze stroną [Creative Commons](https://creativecommons.org/compatiblelicenses/), licencja CC-BY-SA 4.0 jest kompatybilna z [GPL 3.0](https://www.gnu.org/copyleft/gpl.html) oraz z [Free Art License](http://artlibre.org/licence/lal/en/). Zarówno GPL 3.0, jak i Free Art License to licencje typu copyleft.

Nie ma żadnego realnego sposobu rozróżnienia pomiędzy "wycinkiem kodu" nieobjętym ochroną praw autorskich a znacznie większym blokiem kodu, który ze względu na zawarte w nim treści *jest* objęty ochroną (i dlatego jest licencjonowany CC-BY-SA 3.0). Możesz zdać się na zdrowy rozsądek, aby zdecydować, czy jakiś kod kwalifikuje się jako "wycinek", czy nie, ale jeśli sąd przyjmie inną od twojej definicję "wycinka", to masz pecha.

Jeśli pracujesz z kodem objętym licencją permisywną lub zastrzeżoną, to masz cztery możliwości:

* Zmień licencję kodu na GPL 3.0 lub Free Art License, potem kopiuj i wklejaj do woli.
* Zatrudnij drogiego prawnika, żeby bronił twojego prawa do korzystania z wycinków kodu ze Stack Overflow...
* Licz na to, że osoba, której kod kopiujesz i wklejasz, nie dba o to, że naruszasz licencję CC-BY-SA 3.0 aż tak bardzo, żeby cię pozwać.
  * Osobiście polecam to podejście, bo szanse, że ktoś natknie się na twój kod i będzie skarżył się, że nie przestrzegasz warunków CC-BY-SA 3.0, są niższe niż to, że tę książkę naprawdę wyda O'Reilly. Jeśli będziesz mieć pecha (a to się zdarza), możesz po prostu przeprosić i napisać zakwestionowany kod od nowa.
* ...albo napisz swoją własną pseudo[Cleanroom](https://en.wikipedia.org/wiki/Clean_room_design)ową implementację kodu ze Stack Overflow.

Oto instrukcja krok po kroku:

1. Zrób notatki na temat kodu ze Stack Overflow. Szczególnie na temat działania, implementacji itd.
2. Zamknij przeglądarkę.
3. Zaczekaj kilka minut, aż zapomnisz kod.
4. Użyj informacji z notatek do ponownego zaimplementowania kodu ze Stack Overflow.
5. Teraz jesteś właścicielem praw autorskich napisanego przez siebie kodu... nawet jeśli jest on **dokładnie taki sam** jak pierwotny kod na Stack Overflow. A skoro masz już prawa do tego kodu, to możesz włączyć go do swojego projektu z licencją permisywną lub zastrzeżoną.

Jest to metoda wolniejsza niż tradycyjne "Ctrl + C i Ctrl + V". Ma jednak tę zaletę, że pozwala na głębsze zrozumienie kodu ze Stack Overflow. A to może być przydatne, bo zapewne będziesz później opiekować się tym kodem.

Przed końcem rozdziału trzeba jeszcze wspomnieć o jednym. Niektórzy użytkownicy mogą swój kod na Stack Overflow objąć licencją permisywną. W takich przypadkach możesz zastosować się do tej licencji zamiast martwić się o copyleft w CC-BY-SA 3.0. Zajrzyj na profil użytkownika, który dodał "kod", i sprawdź, czy nie jest on dostępny na innej licencji.

## Uznanie autorstwa kodu

*Najlepszą praktyką* przy kopiowaniu kodu ze Stack Overflow jest podanie linku do odpowiedzi, z której pochodzi. Są ku temu dwa powody:

1. Ktoś bardzo ci pomógł, udostępniając niezwykle wartościowy kod. Wypada go nagrodzić, umieszczając we własnym kodzie komentarz, którego i tak nikt nigdy nie przeczyta.
2. Czasem trzeba spojrzeć jeszcze raz na tę odpowiedź przy późniejszym debugowaniu kodu. Jeśli autor kodu opisał go szczegółowo, może to być szczególnie przydatne.

Może się zdarzyć, że wraz z rozwojem projektu znacznie zmodyfikujesz pierwotny kod z SO. W takim wypadku nie ma sensu zachowywać danych autora, bo jego praca i tak już poszła na przemiał. Nie ma co go nadal wychwalać, a za sprawą twoich modyfikacji nawet szczegółowy opis kodu może być już kompletnie bezużyteczny. Usuń ten komentarz ze swojego kodu. ASAP!

Decyzję, czy uznać czyjeś autorstwo, czy usunąć informację o nim, podejmuj, kierując się własnym, profesjonalnym osądem.

Zwróć uwagę, że o ile uznanie autorstwa nie jest zazwyczaj wymagane w przypadku "wycinków kodu", to jeśli stosujesz się do warunków licencji (zarówno ogólnej CC-BY-SA 3.0, jak i licencji permisywnych), taki wymóg zazwyczaj występuje.

## Jaki kod kopiować?

Zazwyczaj na Stack Overflow znajdziesz odpowiedzi na nurtujące cię pytanie. To nie zawsze jest dla ciebie dobre.

* Niektóre odpowiedzi na Stack Overflow mogą być po prostu błędne. *Każdy* może odpowiadać na pytania na SO. A to, że coś jest w Internecie, wcale nie znaczy, że to prawda. O ile odpowiedzi wyraźnie błędne dostają często negatywne oceny użytkowników, to te mniej oczywiste mogą mieć dużo głosów na plus. Na domiar złego zazwyczaj nie masz pewności, czy kod w ogóle się skompiluje albo czy będzie działał, dopóki go nie wypróbujesz.
* Niektóre odpowiedzi nie mają żadnych wyjaśnień tylko sam kod. Szybkie kopiuj-wklej może się wydawać wygodne, ale to nie tak. Najpierw musisz wiedzieć, *co* ten kod w ogóle robi. W końcu to ty będziesz zajmować się nim w przyszłości.
* Niektóre odpowiedzi mają wartość głównie historyczną. Kiedyś rzeczywiście działały, ale już od dawna te rozwiązania nie są najlepsze. Stack Overflow cierpi na syndrom "kto pierwszy, ten lepszy". Zazwyczaj pierwsza odpowiedź zgarnia najwięcej głosów i z tego powodu jest najbardziej widoczna. Bardziej "współczesne" odpowiedzi zwykle mają mniej głosów i ledwo je widać gdzieś na dole strony. 

Właśnie dlatego bezrefleksyjne kopiuj-wklej z pierwszej odpowiedzi to beznadziejny pomysł. Dobrze o tym wiem. Sam tak robiłem.

Zamiast tego przeskroluj stronę i przeczytaj wszystkie odpowiedzi, a nawet wszystkie komentarze do nich. Mogą dać ci więcej informacji albo coś wyjaśnić, dzięki czemu decyzję o tym, co skopiować, podejmiesz bardziej świadomie. Może zerknij też na boczny pasek strony i przejrzyj inne powiązane pytania.

Pomocne jest też sprawdzenie daty pytania i odpowiedzi. Stack Overflow to strona o długiej historii i świadomość, kiedy coś zostało opublikowane, naprawdę pomaga ocenić, czy jest to aktualna treść, czy raczej coś, co już dawno się zdezaktualizowało. To nie znaczy, że musisz z miejsca odrzucać odpowiedzi sprzed roku czy dwóch lat. Po prostu twój profesjonalny osąd zyskuje dodatkowy aspekt do uwzględnienia, zanim zrobisz Ctrl + C.

Jeśli nie zadowalają cię odpowiedzi na jakieś pytanie, nie przejmuj się. Szukaj dalej. Stack Overflow krzywo patrzy na ludzi zadających ciągle te same pytania. A mimo to wciąż się tak dzieje. Zazwyczaj takie pytania są zamykane jako "duplikaty", ale nikt ich nie usuwa i masz do nich normalny dostęp. Poszukaj takich "zduplikowanych" pytań, a może znajdziesz o wiele lepsze odpowiedzi niż w tak zwanej wersji "kanonicznej".

I na koniec pamiętaj, że wcale *nie* musisz robić kopiuj-wklej tylko raz. Możesz z kilku wycinków kodu wybrać to, co ci najbardziej odpowiada. Oczywiście jeśli zamierzasz dodać uznanie autorstwa dla kilku różnych skopiowanych wycinków, z których coś wklejasz u siebie, to masz drobny problem. Nie martw się na zapas - jak już znajdziesz się w takie sytuacji, na pewno jakoś wybrniesz.

## Dodatek: Kod gotowy do wykorzystania

Stack Overflow to strona zbudowana na schemacie Q&A - pytanie-odpowiedź. Użytkownicy zadają pytania, a inni na nie odpowiadają. Oficjalnie strona zniechęca do "dyskusji" - omawiania w nieskończoność najwłaściwszego sposobu rozwiązania problemu. Zamiast tego powinna szybko dawać odpowiedzi na realne problemy.

Z tego powodu na Stack Overflow ciężko natrafić na programy gotowe do wykorzystania, które wystarczy po prostu skopiować i wkleić. Stack Overflow działa tak, że daje kod rozwiązujący konkretne, specjalistyczne problemy, a nie wypluwa cały, działający program.

*Różni* się tym od innych stron Q&A z szerszej platformy Stack Exchange (która hostuje Stack Overflow). Strony Q&A takie jak Code Review albo Code Golf serwują repozytoria "gotowego kodu".

* [Code Review](http://codereview.stackexchange.com/) to strona, gdzie koderzy omawiają działające programy innych osób i sugerują, jak można je poprawić. (Przykład: [Działająca gra w kółko i krzyżyk w Pythonie, JavaScript, PHP i HTML](http://codereview.stackexchange.com/questions/123337/python-javascript-php-html-unbeatable-tic-tac-toe))
* [Code Golf](http://codegolf.stackexchange.com/) to strona, na której użytkownicy przyjmują wyzwania i tworzą działające programy spełniające pewne kryteria (np. wielkość). (Przykład: [Generowanie słów naiwnym łańcuchem Markowa](http://codegolf.stackexchange.com/questions/75673/na%C3%AFve-markov-chain-word-generation))

Cały kod z Code Review oraz Code Golf jest objęty licencją CC-BY-SA 3.0 (tak samo jak kod na Stack Overflow). Większość tego kodu to nie są "wycinki". To przecież pełne, działające programy, a nie dwie linijki kodu.

Nawet przepisanie ich w innym języku byłoby utworem pochodnym (ponieważ do napisania własnego kodu inspirował cię kod kogoś innego), więc nadal należy stosować się do warunków licencji CC-BY-SA 3.0.

Jeśli dla własnego kodu posługujesz się copyleft, to nie ma prawnych przeciwwskazań do używania kodu z Code Review albo Code Golf. Jeśli jednak pracujesz na kodzie objętym licencją permisywną albo zastrzeżoną, zastanów się nad wykonaniem implementacji pseudo"Cleanroom", którą przedstawiłem wcześniej w rozdziale o licencjonowaniu kodu.

Korzystanie z Code Review i Code Golf do wyszukiwania "kodu gotowego do wykorzystania" to nie jest dobry pomysł. "Kod gotowy do wykorzystania" tylko czeka na stronach hostujących kod, takich jak SourceForge, BitBucket i GitHub w formie otwartego oprogramowania objętego odpowiednimi licencjami. Na takich stronach znajdziesz "kod gotowy do wykorzystania", który trafi w twoje wyjątkowe potrzeby.

Wykorzystywanie kodu z Code Review i Code Gold można też uznać za nie do końca etyczne, ponieważ korzystasz wtedy z faktu, że na Stack Exchange wszystko bez wyjątku jest objęte licencją CC-BY-SA 3.0. Ludzie wrzucający na Code Review swoją implementację FizzBuzz liczą na to, że ktoś ją omówi, a nie że ty ją sobie wykorzystasz.

Ale oczywiście *wolno* ci zgodnie z prawem kopiować i wklejać kod z Code Review i Code Golf. Odpowiedzi i komentarze do tego kodu również mogą okazać się niezwykle pomocne i przynajmniej w teorii mogą rozwinąć twoje programistyczne umiejętności.
