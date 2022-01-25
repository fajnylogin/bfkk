# Android 25.01.2022 (Zabłudów)

## Zasady tworzenia aplikacji
Musimy odpowiedzieć na pytanie „dlaczego użytkownik miałby z niej korzystać?”.
Odpowiedź powinna być równoznaczna z korzyściami jej posiadania. 

I to właśnie korzyści powinny dawać wytyczne, jakie funkcjonalności powinna mieć Twoja aplikacja. Nie odwrotnie.

Wygrywają proste w użyciu aplikacje, które mają przyjazny wygląd i realizują konkretne potrzeby użytkowników. Jednakże ich twórcy wciąż starają się pozornie wzbogacić aplikacje o mało przydatne funkcje. 

Poniżej następstwa jednego z najczęstszych błędów podczas projektowania aplikacji:
- Użytkownik usuwa aplikacje, będąc przytłoczonym nadmiarem funkcji.
- Korzystający z aplikacji nie realizuje głównego jej celu, bo nie wie, który cel jest nadrzędny (lub dotarcie do niego zajmuje zbyt wiele kroków).
- Są funkcje, które rozpraszają uwagę użytkownika i nie realizują konkretnej potrzeb. Przez to szuka on innego, prostszego rozwiązania.

## Aplikacja mobilna
Oprogramowanie działające na urządzeniach przenośnych (telefony, tablety, smartwatch'e).

Składa się z trzech warstw:
- interfejs użytkownika - wygląd aplikacji
- logika aplikacji (kod źródłowy, w którym zapisano, co ma się zadziać w jakiejś sytuacji) - dzięki niej wchodzimy w interakcję z aplikacją
- system danych - gdzie zapisywane są treści

## Aplikacja natywna
Aplikacje mobilna napisane w językach odpowiednich i zalecanych dla Androida (Kotlin, Java) lub iOS (Swift).

## Aplikacja hybrydowa
Aplikacje generowane lub konwertowane z technologii internetowych jak np. HTML, JavaScript lub innych języków pośrednich.

## Notyfikacje Push
Powiadomienia push w aplikacji umożliwiają użytkownikom otrzymywanie istotnych dla nich informacji, a twórcom aplikacji – skuteczne przykucie ich uwagi dostosowanymi i trafnymi treściami.

## Brief
Podstawowy dokument zawierający zestaw informacji użytecznych do rozpoznania potrzeb, wstępnych funkcjonalności i założeń projektu tworzenia aplikacji mobilnej

## Minimum Viable Product (MVP)
Aplikacja, która ma wystarczającą ilość funkcji, żeby zaspokoić główną potrzebę jej użytkownika. Pojęcie odnosi się również do techniki tworzenia aplikacji, gdzie głównym celem jest oddanie do użytku możliwie najbardziej wartościowy produkt, w jak najkrótszym czasie. Aplikacja przybiera swój ostateczny kształt dopiero po zebraniu opinii przez wczesnych jej użytkowników oraz dodaniu istotnych dla
nich funkcjonalności.

## Monetyzacja
Strategia pozyskiwania środków od użytkowników w przypadku korzystaniu z aplikacji komercyjnych

## NDA
Umowa o poufności zawarta pomiędzy co najmniej dwiema stronami, które zobowiązują się do wymiany poufnych materiałów lub wiedzy z zastrzeżeniem ich dalszego nierozpowszechniania.

## Onboarding 
Ekrany powitalne w aplikacji, często spełniają funkcję instrukcji dla użytkownika, odpowiadają w skrócie, jak można z niej korzystać

## Retencja
Używane w kontekście częstotliwości korzystania z aplikacji, im większa retencja, tym większy czas spędzany w aplikacji przez użytkownika.

## Software house
Firma tworząca oprogramowanie w tym aplikacje mobilne oraz rozwiązania internetowe w zależności od specjalizacji.

## View
Są trzy typy elementów View:
- TextView
- ImageView
- Button
Mają określone granice i kolor tła (także przezroczysty).

## Czym jest platforma Android?
- https://www.android.com/intl/pl_pl/everyone/

## W jakim języku piszemy?
- Java
- Kotlin
- C#
- HTML/CSS/JS + framework'i

## W czym tworzymy aplikacje?
- Android Studio
- IntelliJ IDEA
- Xamarin

## Wygląd aplikacji
- material.io

## Gdzie szukać informacji?
- Google
- Developer Android
- Stack Overflow

## Android Visualizer
- https://labs.udacity.com/android-visualizer/

## Android Inventor
- http://appinventor.mit.edu/explore/

## Rozmiar ekranu
Rzeczywisty rozmiar fizyczny, mierzony jako przekątna ekranu. Dla uproszczenia system Android grupuje wszystkie rzeczywiste rozmiary ekranu na cztery ogólne rozmiary: mały, normalny, duży i bardzo duży.
https://developer.android.com/training/multiscreen/screendensities

## Gęstość ekranu
Ilość pikseli w fizycznym obszarze ekranu; zwykle określane jako dpi (kropki na cal). Na przykład ekran o „niskiej” gęstości ma mniej pikseli w danym obszarze fizycznym, w porównaniu do ekranu o „normalnej” lub „wysokiej” gęstości. Dla uproszczenia system Android grupuje wszystkie rzeczywiste gęstości ekranu na sześć ogólnych gęstości: niska, średnia, wysoka, bardzo wysoka, bardzo wysoka i bardzo wysoka.

## Orientacja
Orientacja ekranu z punktu widzenia użytkownika. Jest to krajobraz lub portret, co oznacza, że proporcje ekranu są odpowiednio szerokie lub wysokie. Należy pamiętać, że nie tylko różne urządzenia domyślnie działają w różnych orientacjach, ale orientacja może się zmienić w czasie wykonywania, gdy użytkownik obraca urządzenie. 

## Rozdzielczość 
Całkowita liczba fizycznych pikseli na ekranie. Podczas dodawania obsługi wielu ekranów aplikacje nie działają bezpośrednio z rozdzielczością; aplikacje powinny dotyczyć wyłącznie rozmiaru i gęstości ekranu, określonych przez ogólne grupy wielkości i gęstości. 

## Piksel niezależny od gęstości (dp) 
Wirtualna jednostka pikseli, której należy użyć podczas definiowania układu interfejsu użytkownika, aby wyrazić wymiary lub pozycję układu w sposób niezależny od gęstości. 
Piksel niezależny od gęstości odpowiada jednemu pikselowi fizycznemu na ekranie o rozdzielczości 160 dpi, który jest podstawową gęstością przyjętą przez system dla ekranu o „średniej” gęstości. 
W czasie wykonywania system w przejrzysty sposób obsługuje dowolne skalowanie jednostek dp, zależnie od rzeczywistej gęstości używanego ekranu. 
Konwersja jednostek dp na piksele ekranowe jest prosta: `px = dp * (dpi / 160)`. 
Na przykład na ekranie o rozdzielczości 240 dpi 1 dp to 1,5 piksela fizycznego. 
Podczas definiowania interfejsu użytkownika aplikacji należy zawsze używać jednostek dp, aby zapewnić prawidłowe wyświetlanie interfejsu użytkownika na ekranach o różnych gęstościach.

## Jednostki
- px (piksele) - odpowiada rzeczywistym pikselom na ekranie.
- w (cale) - w oparciu o fizyczny rozmiar ekranu. 1 cal = 2,54 centymetra
- mm (milimetry) - w oparciu o fizyczny rozmiar ekranu.
- pt (punkty) - 1/72 cala w oparciu o fizyczny rozmiar ekranu.
- dp lub dip (piksele niezależne od gęstości) - abstrakcyjna jednostka oparta na fizycznej gęstości ekranu. Jednostki te odnoszą się do ekranu o rozdzielczości 160 dpi, więc jeden dp to jeden piksel na ekranie o rozdzielczości 160 dpi. Stosunek dp-do piksela zmienia się wraz z gęstością ekranu, ale niekoniecznie w proporcji bezpośredniej. Uwaga: Kompilator akceptuje zarówno „dip”, jak i „dp”, chociaż „dp” jest bardziej spójny z „sp”.
- sp (piksele niezależne od skali) - jest to jak jednostka dp, ale jest również skalowane według preferencji użytkownika dotyczących rozmiaru czcionki. Zaleca się korzystanie z tego urządzenia podczas określania rozmiarów czcionek, aby dopasować je zarówno do gęstości ekranu, jak i preferencji użytkownika. Od zrozumienia niezależności gęstości w Androidzie: 
~~~
Jednostka   Opis                        Jednostki na cal fizyczny   Niezależność od gęstości    Ten sam rozmiar fizyczny na każdym ekranie
px 	        Piksele 	                  Różni się 	                nie 	                      nie
w 	        Cale 	                      1 	                        tak 	                      tak
mm 	        Milimetry 	                25,4 	                      tak 	                      tak
pt 	        Zwrotnica 	                72 	                        tak 	                      tak
dp 	        Niezależne piksele 	        ~ 160 	                    tak 	                      nie
sp          Skaluj niezależne piksele 	~ 160 	                    tak 	                      nie 
~~~

## Android icons dla różnych rozdzielczości ekranu urządzenia.
~~~
                            ldpi     mdpi    hdpi     xhdpi    xxhdpi     xxxhdpi
Launcher And Home           36*36    48*48   72*72    96*96    144*144    192*192
Action Bar And Tab          24*24    32*32   48*48    64*64    96*96      128*128
Notification                18*18    24*24   36*36    48*48    72*72      96*96
Background                  320*426  320*470 480*640  720*1280 1080*1920  1440*2560
~~~
