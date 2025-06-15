---
title: Vim to nie meta, vim to lokalne minimum
date: 2025-06-15 21:08:00 +0000
categories: [PROGRAMMING_STACK, KEYBOARDS]
tags: [qmk, keyboards, vim, vscode, editors]     # TAG names should always be lowercase
---


# Table of Contents

- [Table of Contents](#table-of-contents)
- ["I did it my way"](#i-did-it-my-way)
  - [Jest nieźle …](#jest-nieźle-)
  - [… aż do czasu](#-aż-do-czasu)
  - [TempleOS wannabe](#templeos-wannabe)
  - [Friendship with QWERTY ended, now colemak is my best friend](#friendship-with-qwerty-ended-now-colemak-is-my-best-friend)
- [argumenty przeciw](#argumenty-przeciw)
  - ["Wow, but vim movement is so great"](#wow-but-vim-movement-is-so-great)
  - ["Może i movement da się zastąpić, ale mamy wiele przydatnych mark i skrotów!"](#może-i-movement-da-się-zastąpić-ale-mamy-wiele-przydatnych-mark-i-skrotów)
  - ["Może i masz rację, jednak nie odpalisz VS Code w terminalu!"](#może-i-masz-rację-jednak-nie-odpalisz-vs-code-w-terminalu)
    - ["Ale ja lubię używać narzędzi w terminalu, które mogę obsługiwać bez myszki!"](#ale-ja-lubię-używać-narzędzi-w-terminalu-które-mogę-obsługiwać-bez-myszki)
  - ["Ale vim jest minimalistyczny!!!!11!one!"](#ale-vim-jest-minimalistyczny11one)
  - ["(zrezygnowany) masz rację, co mogę w takim razie zmienić?"](#zrezygnowany-masz-rację-co-mogę-w-takim-razie-zmienić)
- [Czy jest gdzieś jeszcze miejsce dla vima?](#czy-jest-gdzieś-jeszcze-miejsce-dla-vima)
- [Podsumowanie](#podsumowanie)
- [słowniczek skrótów](#słowniczek-skrótów)
- [przydatne linki](#przydatne-linki)

Ostatnimi czasy zacząłem uczyć się Emacs'a, jak otwarto-źrodłowej
alternatywy dla Obsidian'a i podobnych narzędzi do robienia
zaawansowanych notatek. Po długiej przerwie ponownie zetknąłem się ze
szeroką i nieco hermetyczną **społecznością fanatyków edytorów** i tymi
samymi "pozytywami" jakie słyszałem w kontekście Vima. W poniższym
artykule, skierowanym zarówno do doświadczonych programistów jak i
początkującyh, dopiero co stojących przed wyborem edytora, chciałbym
wyjaśnić dlaczego lwia część tych argumentów nie ma większego sensu
i **nie warto używać Vima w celu efektywnej edycji kodu**.


<a id="org39bf35f"></a>

# "I did it my way"

Rozpoczynając studia na kierunku informatyka, miałem już to szczęście
że byłem zaawansowanym linuksiarzem i zwolennikiem filozofii
open-source, co sprawiło, że gdy musiałem wybrać edytor nie
zastanawiałem się długo i sięgnałem po pierwsze narzędzie polecane
przez społeczność - NeoVim.

Zachwalano mi, jak przyjemny i ergonomiczny jest sposób poruszania się
w vimie, bardzo spodobał mi się minimalizm tego edytora - jedno okno
na tym etapie było wystarczające i wprowadzało dużo mniej szumu
informacyjnego niż **IDE, które początkowo przytłoczyło mnie** z kilkoma
bocznymi i górnymi paskami, oknami wyboru plików, terminal'em,
debuggerem, etc.


<a id="org01c1199"></a>

## Jest nieźle &#x2026;

Nie znając zbytnio alternatyw pierwszy rok mojej przygody z
programowaniem w trakcie studiów ukończyłem, używając tylko i
wyłącznie vima jako edytora kodu. Mogłem patrzyć z wyższością na
rowieśników na roku, którzy korzystali z różnych, często gorszych
alternatyw.

![img](./images/me_irl.jpg "Taki wygląd mój, vimiarza na pierwszym roku studiów.")


<a id="orged26655"></a>

## &#x2026; aż do czasu

Jednak wraz z rozpoczęciem drugiego roku, na moim uczelnianym
horyzoncie jawił się przedmiot Systemy Operacyjne 2 i jedną z
możliwych form zaliczenia było napisanie własnego, prostego
systemu operacyjnego. Będąc kimś kto niezwykle lubi wyzwania
i poznawanie technologii od podeszwki, od razu wybrałem tę
opcję - i zrozumiałem skąd potrzeba tylu informacji w nowoczesnych
IDE.


<a id="org0db19f2"></a>

## TempleOS wannabe

Praca nad systemem operacyjnym wymagała zręcznego przemieszczania się
pomiędzy wieloma otwartymi plikami, i VSC z swoim podglądem całego
repozytorium sprawdzał się w tym celu lepiej, niż przęłaczenie się
między oknami Vima, i szukanie plików w shellu.

System opercyjny oprócz kodu w C, zawiera fragmenty assemblera, co
tylko nawarstwia problemy w tak prostym środowisku jak Vim. Każda
instalacja kolejnej wtyczki do syntax highlighting'u wiązała się z
googlowaniem, szukaniem sposobu ich instalacji, i mnóstwem podobnych
gówień. Długo byłoby streszczać, ale myśle że wystaraczy podsumować
faktem, że do pięt nie dorastało to swobodzie i łatwości instalacji
rozszerzeń (i ich jakości) jaki oferuje domyślny, wbudowany w VSC
marketplace.

Mógłbym wymieniać jeszcze długo, jednak pozwolę sobie przejść
już do konkretnego wniosku jaki staram się przybliżyć powyższymi
przykładami - projekt w większej skali, korzystający z większej liczby
technologii wskazał mi, skąd takie a nie inne decyzje projektowe przy
współczesnych IDE oraz uduwodnił, że vim ma
**wyraźne braki w środowisku dewelopera**, których nie można
zaobserwować, jeśli nie wychyli się nosa dalej niż plik
konfiguracyjny edytora, albo proste bash'owe skrypty.


<a id="orga541b75"></a>

## Friendship with QWERTY ended, now colemak is my best friend

W tym samym okresie wskoczyłem wesoło w rabbit hole klawiatur
mechanicznych a przede wszystkim układów klawiatury. Przestałem
korzystać z **QWERTY**, w pełni przerzucając się na **colemaka**, układ
klawiatury dużo bardziej ergonomiczny, zbudowany na zasadzie
umieszczenia najcześciej występujących znaków w środkowym rzędzie
klawiatury, dzięki czemu znacząco zniwelowana jest
ilość ruchów palców przy pisaniu kodu. Keybindingi Vima powstały z
myślą o QWERTY, wymagałoby ode mnie zmiany każdego z nich w celu
zachowania kompatybilności z pamięcią mieśniową, jaką wyrobiłem
pracując na z parą vim + QWERTY. Najwyraźniej nie bez powodu
**autor colemaka zmienił vima na sublime text**.


<a id="org8dc2bfc"></a>

# argumenty przeciw

Pozwolę sobie przeprowadzić teraz **dialog platoński**, z archetypowym
**zwolennikiem vima**, w celu udowodnienia, że każda z cech uznawanych za
pozytyw vima wcale nie jest **najbardziej optymalnym rozwiązaniem**.

![img](./images/a_vs_b.jpg)


<a id="org30094ca"></a>

## "Wow, but vim movement is so great"

Tak, **różne tryby vima ułatwiają poruszanie się**, w przypadku
**standardowej klawiatury**. Jednak w momencie, kiedy zniknie to
ograniczenie a klawiatura może mieć dowolne, wbudowane przez nas
tryby, skróty, i podobne już na poziomie sterownika, vim movement nie
ma najmniejszego sensu. Przeprogramowanie klawiatury w stosunku do
vima ma nastepujące plusy:

-   **działa niezależnie od programu, systemu czy nawet komputera.** Są
    skrótami na wyższym poziomie abstrakcji niż skróty w config'u vima,
-   **nie wymaga od nas synchronizacji pomiędzy urządzeniami**, w
    przeciwieństwie do plików konfiguracyjnych vima,
-   jest **niezależne od wybranego układu klawiatury**.

Wystarczy jakakolwiek klawiatura z otwarto-źródłowym sterownikiem
**QMK** aby móc realnie skorzystać z każdego z plusów wymienionych
powyżej. Konfiguracji możemy często dokonać nawet z poziomu
przeglądarki, **bez potrzeby instalacji dodatkowego oprogramowania**.

Pozwolę sobie podać krótki przykład z konfiguracji mojego projektu
klawiatury, którą zbudowałem jeszcze w trakcie błogich, studenckich
lat.

![img](./images/keyboard-layout.png "Mój layout klawiatury SCSBAF40")

Pod moim prawym kciukiem, znajduje się klawisz opisany jako "mod". W
momencie kiedy go trzymam, pod palcami mojej prawej ręki mam klawisze
strzałek, jak i inne klawisze ułatwiające nawigację. Dosłownie
wbudowałem w moją klawiaturę movement vima i działa on niezależnie czy
korzystam z VSC, przeglądarki, macOS'a czy GNU/linux'a. To tylko jeden
z przykładów, aby rozbudzić Twoją ciekawość dodam, że w podobny sposób
mogę poruszać kursorem, kontrolować spotify, etc.

Aby oddać nieco sprawiedliwości, dzięki temu, że miałem styczność z
vimem wpadłem na taki pomysł. Nie zmienia to faktu, że moje końcowe
rozwiązanie jest wygodniejsze a vim był przy tym tylko dobrą
inspiracją. 


<a id="org0120aef"></a>

## "Może i movement da się zastąpić, ale mamy wiele przydatnych mark i skrotów!"

Podobnie jak każdy inny program dostępny na rynku, z tą subtelną
rożnicą, że wklejanie to ctrl+V, nie żaden "Yank" lub
ctrl+shift+V. Kompatybilność skrótów między takimi narzędziami jak
przeglądarka, edytor, czy nawet arkusz kalkulacyjny sprawia, że nie
musimy swoich zdolności kognitywnych poświęcać na matematykę skrótową
ilokroć zmieniamy okno. W celu zapamiętywania nie warto używać mózgu,
wystarczy do tego dysk twardy, bądź kartka.

Jak bardzo bym chciał, tak jednak nie mogę powiedzieć, że skróty
klawiszowe w vimie są złe same w sobie - jednak z całą pewnością są
niekompatyblne jeśli zestawimy je praktycznie z każdym innym
software'm jaki istnieje na rynku.


<a id="org9bac9fd"></a>

## "Może i masz rację, jednak nie odpalisz VS Code w terminalu!"

W 99% wyzwań, jakie stoją przed współczesnym programistą nie ma on
kontaktu z sprzętem, który realnie wymaga od niego aby łączył się
przy pomocy emulatora terminala, a jeśli już takie zjawisko występuje
to i tak istniejące już IDE są kombajnami, które pozwalają w łatwy
sposób połączyć się przez np. SSH, zachowując przy tym większość
konfiguracji i rozszerzeń z hosta, jako przykład niech posłuży SSH w
VSC.

Wystarczy przypomnieć sobie, kiedy realnie ostatni raz wystąpiła
potrzeb, aby korzystać z urządzenia, które nie pozwala ci podpiąć się
przy pomocy VSC z wtyczką dla SSH - dla mnie było to prawie rok
temu kiedy musiałem pracować z *AI on the edge*. Jeśli komuś zdarza się to
faktycznie przynajmniej raz w tygodniu w takim przypadku vim
może być realną alternatywą.


<a id="org56c4b66"></a>

### "Ale ja lubię używać narzędzi w terminalu, które mogę obsługiwać bez myszki!"

Nie lubisz, a po prostu dobrze je znasz i spędziłeś z nimi dużo czasu.
W przypadku narzędzi GUI nikt nie zabrania ci dalej korzystać z
skrótów, masz jednak zawsze pod reką możliwość skorzystania z
okienkowych ikonek. Do tego GUI oferuje dużo lepsze renderowanie
czcionek niż terminal. Jeśli pracujesz z kodem długo i gęsto się w
niego wpatrując, chcesz aby wyglądał dobrze. No chyba że poświęcimy
dodatkowy czas na konfigurację terminala, systemu i miliona innych
rzeczy tylko po to, założenie, że korzystasz z minimalistycznego
edytora (o czym za chwilę powiem więcej) a zarazem z nowoczesnego, w
pełni skonfigurowanego i wyposażonego w szereg dodatkowych funkcji
terminala jest absurdalne i niespójne.


<a id="orga45b7bb"></a>

## "Ale vim jest minimalistyczny!!!!11!one!"

Zdefiniuj minimalizm i czy jest nim instalowanie kolejnego runtime
języka, którego realnie nie użyjesz, na ile też minimalizmem jest
instalacja miliona wtyczek, by doprowadzić swój edytor prawie że do
stanu w jakim domyślnie dostajemy VS code. Początkowa wersja edytora
jest faktycznie minimalistyczna, żeby nie powiedzieć pusta i
prymitywna. Do tego społeczność i maintainerzy projektów pokroju vima
nie słyszeli nigdy o czymś takim jak dobre domyślne ustawienia, co
także dokłada nam pracy w konfiguracji.

**Minimalizm w kontekście vima jest co najwyżej buzzwordem** i nie ma
znaczenia w świecie, gdzie współczesnym komputerom nie brakuje:

-   mocy obliczeniowej,
-   wyświetlacza z możliwościami większymi niż czarno-białe ASCI,
-   miejsca na dysku.

W tej chwili piszę ten tekst z komputera, który ma tylko 256 GiB
przestrzeni dyskowej i te 250 MiB, które zajmuje VSC wcale nie boli.


<a id="org8fd92ce"></a>

## "(zrezygnowany) masz rację, co mogę w takim razie zmienić?"

Jeśli miałbym podać ci tylko i wyłącznie jedną rzecz, którą warto
zmienić by odczuć różnicę w korzystaniu praktycznie z każdego typu
softu będzie to **klawiatura**. Na rynku jest wiele firm, które oferują
klawiatury korzystające z QMK (np. Keychron albo NuPhy). Dzięki temu
będziesz w stanie przeprogamować ją w podoby sposób jak ja.

Jeśli nie chcesz rezygnować z vimowego sposobu poruszania się a
zarazem chcesz mieć możliwość korzystania z nowoczesnego IDE, dostępne
są przeróżne **wtyczki, które umożliwiają dodanie trybu vima**, z całym
wachlarzem vimowych modyfikatorów, trybów, etc.


<a id="org4ed333d"></a>

# Czy jest gdzieś jeszcze miejsce dla vima?

Oczywiście! Mimo wszystko znajdzie się czasem potrzeba, na użycie
prostego terminalowego edytora tekstu, gdy chcesz na szybko przerobić
jakiś config na zdalnej maszynie czy też pracujesz z ARMem, którego
moc obliczeniowa niewiele wyprzedza mikrofalę.

Vim mimo wszystko zawiera w sobie **dużo mniej szumu informacyjnego** i
faktycznie ma prosty interfejs, być może może dobrze służyć jako
**distraction-free edytor tekstu**, choć na to też mainstream'owe IDE
znalazły sposób (np. Zen mode w VSC).

Kwestionuję jedynie używanie vima do pisania softu, na współczesnych
maszynach z ich obecnymi możliwościami, w tym celu istnieją po prostu
lepsze opcje.


<a id="org58ef63f"></a>

# Podsumowanie

Mogłem w całym powyższym artykule reprezentować postawę wielkiego
antyfana vima, jednak prawda jest zgoła inna - uważam, że vim to też
narzędzie i **na pewno ma swoją niszę**. Nie odradzam nikomu aby
zmieniał teraz soft z jakiego korzysta, jedynie proszę serdecznie
każdego vimiarza, którzy to przeczytał o trochę skruchy i zmianę
argumentacji - **nie należysz do elity**, a Twój ulubiony program to co
najwyżej **suboptymalne rozwiązanie**.

Skupiając się na kilku mniejszych zaletach nie zauważasz wielu miejsc
gdzie możesz odnaleźć **prawdziwy endgame**, który realnie przyspieszy i
ułatwi waszą pracę. Nie bój się nowoczesnych narzędzi i ich pełnego
pakietu funkcjonalności - ma on za zadanie **ułatwić Twoją pracę**, a nie
zapchać dysk niepotrzebną treścią.


<a id="orgf276218"></a>

# słowniczek skrótów

*IDE* - *Integrated Developer Environment* edytor kodu zintegrowany z
innymi, niezbędny dla programisty narzędziami, takimi jak debugger,
okno terminala, etc.

*VSC*, *VS code* - Visual Studio Code, otwarto-źrdłowe IDE.

*vim*, *neovim* - odnoszę się do edytora vim i wszystkich pokrewnych,
np. forków takich jak neovim, przodków jak vi, i ogólnie szeroko
pojętej rodziny edytorów.

*edge AI* - AI na urządzeniach końcowych, często z pogranicza
embedded, np. kamera + mikroprocesor obsługujący przetwarzanie obrazu.


<a id="org0481531"></a>

# przydatne linki

-   [SCSBAF40](https://github.com/AIn0n/scsbaf40), projekt mojej prywatnej klawiatury
-   [Colemak](https://colemak.com/), ergonomiczny układ klawiatury
-   [vim mode dla VS Code](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)

