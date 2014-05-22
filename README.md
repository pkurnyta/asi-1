> *Uważaj na człowieka, którego nie interesują szczegóły.*
>
> — William Feather


## Architektura Serwisów Internetowych 2013/14

Legenda: `#1` – MyGists, `#2` – MyPages, `#3` – MyBooks, `#4` – inna aplikacja.

Oceny: A1, B2, C3, D4, E5.


### RSpec

Do aplikacji przygotowywanych na egzamin należy dopisać testy.<br>
(Wystarczy ok. 50 testów – po równo dla *controllers* i *views*.)<br>
Testy powinny korzystać z narzędzia [RSpec](http://rspec.info/):

- [rspec-core](https://github.com/rspec/rspec-core)
- [rspec-expectations](https://github.com/rspec/rspec-expectations)
- [rspec-mocks](https://github.com/rspec/rspec-mocks)
- [rspec-rails](https://github.com/rspec/rspec-rails)

Aplikacja powinna składać się z co najmniej dwóch modeli (nie wliczając
modeli generowanych/wymaganych przez użyte gemy, np. *device*).
Aplikacja powinna być napisana w Rails w wersji nie mniejszej niż 4.1.0.

Aplikację należy wdrożyć na **ShellyCloud**.<br>
(Chyba, że ustaliłem to z szefem zespołu inaczej.)<br>
Jak to zrobić jest opisane [tutaj](https://github.com/rails4/my_gists).


### Niezaliczone laboratorium

1. Chraniuk, Mateusz
1. Mańkowska, Monika
1. Sielachowicz, Paweł
1. Stasiak, Sebastian
1. Sulich, Bartłomiej
1. Żelazek, Mateusz


### Egzamin poprawkowy (wrzesień)

Na termin poprawkowy należy **samodzielnie** napisać i uruchomić
na Shelly Cloud aplikację korzystającą z jednego z API z tej listy
[List of data APIs that require no server-side auth or private credentials](https://gist.github.com/wbzyl/9989677)
(mój fork [gist:4952991](https://gist.github.com/afeld/4952991)).
Do aplikacji należy napisać ok. 40 testów,
a kod należy podłączyć do systemu [Travis](https://travis-ci.org/).

Szkielet aplikacji korzystającej z *Movie Database API* umieściłem
na GitHubie – [My Movies](https://github.com/rails4/my_movies).
Aplikacje na egzamin powinny korzystać z innych API.

Ostateczny termin rozliczenia się z projektu – **31.08.2014**.

1. Acewicz, Patryk
1. Bigda, Piotr
1. Komorowski, Szymon
1. Korszuń, Kacper
1. Kurnyta, Przemysław
1. Nowicki, Jakub
1. Szynkaruk, Kamil
1. Zbierowski, Maciej

----

1. Smykowski, Adrian


<!--

1. [Smykowski, Adrian](https://github.com/FiskSMK/ASI). [A#4](http://vanfisk.herokuapp.com) **brak na liście z dziekanatu**
1. [Szynkaruk, Kamil](https://github.com/ferocis/my_gists), [C+#1](http://zaliczenie.herokuapp.com/)
1. [Zbierowski, Maciej](https://github.com/Macio1992/myBooks). [B#3](http://my-books-macio1992.herokuapp.com/)

1. [Hawks 2](https://github.com/szykom/AsiYT). [Hello, Stranger](http://asiyt.shellyapp.com/): Sz. Komorowski, P. Acewicz
   - brak testów!
   - nie wiadomo o co chodzi w aplikacji
   - po zalogowaniu brak przykładowych danych (playlist…)

1. [Bigda, Piotr](https://github.com/CoJaTutajRobie/egzamin). [brak repo]
1. [Kurnyta, Przemysław](https://github.com/pkurnyta/exam). [My Movies](http://mymovies-pk.herokuapp.com/) [Travis: failed]

1. [Nowicki, Jakub](https://github.com/jnowicki/rails-myGists). [myGists](http://mygists.kubavic.vdl.pl) [1 model, Gemfile: rspec2, Travis: DEPRECATION WARNINGS]
1. [Korszuń, Kacper](https://github.com/gathaspar/RailsApp2). [PiGist](http://pigist.shellyapp.com/) [1 model: +lang?, Gemfile: rspec2, Travis: 7 testów]

-->

### Teams 4.1.1 (*deadline* – 18.05.2014)

Kod aplikacji należy podłączyć do systemu [Travis](https://travis-ci.org/) –
free hosted continuous integration platform for the open source community.

**Proszę o dodanie mnie jako *collaborator* do repozytorium z projektem.**

#### Zespoły

1. [CŁOP](https://github.com/kipperek/RailsExam). [Posts](http://railsexamfinal.shellyapp.com/) [2 osobne modele, Gemfile: rspec2]
1. [MiDaS](https://github.com/henio180/EduWords). [EduWords](http://eduwords.project-midas.com/) [Gemfile: minitest+rspec2, Travis: deprecated]
1. [Z3](https://github.com/zajacmp3/RailsExam). [My Static Pages Private](http://www.railsexam.zajacmp3.pl) [1 model]
1. [PMT](https://github.com/Macio1992/rubyOnRailsProject). [Kontakty](http://contestcreator.cloudapp.net/) [Gemfile: rspec2, Travis: pending]
1. [Deoxyribonucleotide](https://github.com/MacMisDev/karczma). [Karczma](http://karczma.shellyapp.com/) [1 model, Gemfile: minitest+rspec2, Travis: WARNING: deprecated]
1. [Dzikie Bociany](https://github.com/Zhukovo/RoR-Egzamin). [My Gists](http://ror-bociany.shellyapp.com/) [1 model]
1. [Noramino](https://github.com/Bllade/ASI_exam.git). [My Notes](http://notes-exam.shellyapp.com) [1 model, Travis: deprecated]
1. [RubyOnUnicorns](https://github.com/KLamkiewicz/RubyOnUnicorns). [My Gists](http://rubyonunicorns.shellyapp.com) [1 model, Gemfile: activerecord-deprecated_finders, rspec2]
1. [The Procrastinators](https://github.com/mbuda/RailsGroupProject). [Games](http://game-reviews.shellyapp.com/) [Gemfile: rspec2]
1. [PANDA5](https://github.com/lipek92/PANDA5). [MyGists Pro](http://panda5.shellyapp.com) [1 model, Gemfile: rspec2]
1. [GITpower](https://github.com/mbednarczyk/asiegzamin). [My Gists](http://asiegzamin.shellyapp.com) [1 model, Gemfile: rspec2]
1. [1337](https://github.com/YoungCoder/1337/). [Pro Tips](http://skorzenno.pl/)
1. [MirJan](https://github.com/Pelen/mirjan). [My Books](http://mirjan.shellyapp.com) [1 model]
1. [Splendor, Styl, Przepych](https://github.com/lukasz978/splendor). [Splendor](http://vps66305.ovh.net) [Travis: WARNINGS]
1. [None](https://github.com/kaka2991/my_gists). [My Gists](http://my-gists.shellyapp.com/) [1 model, Gemfile: rspec2]

----

Dane wpisujemy tak:

1. `[Nazwa zespołu](link do repozytorium). [Nazwa Aplikacji](link do aplikacji na Shelly Cloud)`

TODO:

1. [P&S – dziewczyny Rubiego](https://github.com/MPaulina/AplikacjaASI). [MyGist](http://dziewczynyrubiego.shellyapp.com/)
1. [JSON](https://github.com/gruchanet/snippeter_on_steroids).
1. [Disco w rytmie polo](https://github.com/kpawel-29/Disco-w-rytmie-polo).


#### Indywidualiści

1. [Cywiński, Tymoteusz](https://github.com/tcywinski/my_movies_123). [My Movies](http://my-movies-123.herokuapp.com/) [Shelly Cloud?]
1. [Kołek, Maciej](https://bitbucket.org/ferus/csgotraders). [CSGO Traders](http://beta.csgotraders.net) [Gemfile: rspec2, Travis: brak]
1. [Kwiatkowski, Dominik](https://github.com/Kalumniatoris/railsy). [Agisty](http://agisty.shellyapp.com)
1. [Lek, Szymon](https://github.com/leyas/rails-app). [Gisty](http://szymon.shellyapp.com) [1 model, Gemfile: rspec2, Travis: 30 testów]
1. [Szklarska, Milena](https://github.com/madebytechnology/RailsAppExam). [#music #power #fun](http://musicalbums.shellyapp.com) [Gemfile: rspec2]

<!--

### Ścieżka raz, dwa, trzy (*deadline* – 12.05.2014)

Przykładowa aplikacja, którą należy uruchomić, dopisać brakujący kod
i **testy** – [MyMovies](https://github.com/rails4/my_movies)
(testy controllers + views; wystarczy ok. 50 testów).
Aplikacja ta korzysta z *Movie Database API*.

Kod aplikacji należy podłączyć do systemu [Travis](https://travis-ci.org/) –
free hosted continuous integration platform for the open source community.

Zamiast aplikacji *MyMovies* można napisać *samodzielnie* inną aplikację
korzystajacą z innego API, na przykład, któregoś z tej listy –
[List of data APIs that require no server-side auth or private credentials](https://gist.github.com/wbzyl/9989677)
(forked from [gist:4952991](https://gist.github.com/afeld/4952991)).

-->


### Wasze aplikacje (zaliczenie)

1. [Acewicz-Hepfner, Patryk](https://github.com/pacewicz/my_gists). [C#1](http://mygists-pa.herokuapp.com).
1. Banecki, Daniel. [B#1](http://filmotekaczlowieka.herokuapp.com/).
1. [Bednarczyk, Marek](https://github.com/mbednarczyk/my_gists_reedit). [E#1](http://mygistsmbednarczyk.herokuapp.com).
1. [Bigda, Piotr](https://github.com/CoJaTutajRobie/ruby). [C#1](http://nowyprojekt123.herokuapp.com).
1. [Borkowski, Maciej](https://github.com/borek199/my_gists). [D#1](http://mygistsmborkowski.herokuapp.com).
1. [Buda, Marta](https://github.com/mbuda/reviewIt). [E#3](http://books-review.herokuapp.com).
1. [Cimoch, Jarosław](https://github.com/jcimoch/mygists). [D#1](http://jcimoch-my-gists.herokuapp.com/).
1. [Cywiński, Tymoteusz](https://github.com/tcywinski/my_movies_123). C#1.
1. [Czechowicz, Kacper](https://github.com/kipperek/Rails-FirstApp). [E#1](http://kczechowicz-gists.herokuapp.com).
1. [Czerwińska, Agnieszka](https://github.com/aczerwinska/my_gists). [D#1](http://gistmys.herokuapp.com/).
1. [Dargacz, Mateusz](https://github.com/mateuszdargacz/md_gists). [C#1](http://asi-mdargacz.herokuapp.com/).
1. [Dąbrowski, Arkadiusz](https://github.com/ArkadiuszD/Wpisy). [D#1](http://kolejnedziadostwo.herokuapp.com/).
1. [Gafka, Dariusz](https://github.com/dgafka/my_gists). [D+#1](http://evening-everglades-2118.herokuapp.com).
1. [Gąsior, Łukasz](https://github.com/lukgas6/projekt-asi). [D+#1](http://lgasior-gists.herokuapp.com/).
1. [Janowski, Arkadiusz](https://github.com/janusy/my_gists). [D#1](http://janusygists.herokuapp.com).
1. [Jaworowski, Michał](https://github.com/kropeq/my-gist). [C+#1](http://jaworgists.herokuapp.com).
1. [Józwiak, Roman](https://github.com/gruchanet/snippeter). [E#1](http://snippeter-app.herokuapp.com).
1. [Kadłubowski, Paweł](https://github.com/kpawel-29/my_gists_with_bootstrap). [E#1](http://gistmaster.herokuapp.com).
1. [Karolczak, Jakub](https://github.com/Taureli/MyGists). [C+#1](http://mygists-jkarolczak.herokuapp.com).
1. [Kąkol, Jan](https://github.com/jankkol/ruby_gist). [D#1](http://jankkolgists.herokuapp.com).
1. [Kołek, Maciej](https://bitbucket.org/ferus/csgotraders). [E#4](http://beta.csgotraders.net)
1. [Komorowski, Szymon](https://github.com/szykom/asi-my-gists). [C+#1](http://szykom-my-gists.herokuapp.com).
1. [Korszuń, Kacper](https://github.com/gathaspar/RailsGistProject). [C#1](http://stark-beyond-9781.herokuapp.com).
1. [Kucharski, Maciej](https://github.com/Maciekek/my-gists2). [D#1](http://my-gists.herokuapp.com).
1. [Kurnyta, Przemysław](https://github.com/pkurnyta/my_gists). [C#1](http://pk-gists.herokuapp.com/).
1. [Kwiatkowski, Dominik](https://github.com/Kalumniatoris/asip1). [C+#1](http://agisty123.herokuapp.com).
1. [Labuda, Damian](https://github.com/kaka2991/my_gists). [E#1](http://damlab.herokuapp.com).
1. [Lamkiewicz, Krzysztof](https://github.com/KLamkiewicz/RubyGist). [C#1](http://mojegisty.herokuapp.com).
1. [Leśniak, Michał](https://github.com/mlesniak91/my_notes). [E#3](http://mlesniak.herokuapp.com/notes).
1. [Leyk, Szymon](https://github.com/leyas/rails-app). [D#2](http://sl-gists.herokuapp.com/).
1. [Lipowski, Michał](https://github.com/lipek92/my_gists). [D#1](http://mygistsmlipowski.herokuapp.com).
1. [Litke, Sabina](https://github.com/SabinaL/my_gists). [C#1](http://gists.herokuapp.com/).
1. [Ławicki, Patryk](https://github.com/true-or-false/myBinaries). [C+#1](http://mybeanaries.herokuapp.com).
1. [Maciejewski, Michał](https://github.com/mmaciejewski/my_gists_rework). [C#1](http://mygistsrework.herokuapp.com).
1. [Marciniak, Paulina](https://github.com/MPaulina/my_gist). [C#1](http://asi-my-gist.herokuapp.com/).
1. [Masztarowski, Sebastian](https://github.com/Bllade/Gisty). [D#1](http://smasztarowskigists.herokuapp.com).
1. [Miś, Maciej](https://github.com/MacMisDev/gists). [E#1](http://mmgists.heroku.com) [chartkick].
1. [Napiórkowski, Sebastian](https://github.com/sebnapi/my_yachts/). [E#4](http://my-yachts.herokuapp.com).
1. [Nowak, Wojciech](https://github.com/YoungCoder/railsgists). [D#1](http://djangoisbetterthanrails.herokuapp.com).
1. [Nowicki, Jakub](https://github.com/jnowicki/rails-myGists). [C#1](http://just-some-gists.herokuapp.com).
1. [Ochędzan, Krzysztof](https://github.com/Krzychuuu/Ruby). [D#1](http://kochedzan.herokuapp.com).
1. [Ossowski, Marcin](https://github.com/mossowski/my_gists). [D#1](http://mossowski-gists.herokuapp.com).
1. [Paluch, Przemysław](https://github.com/Zhukovo/My_gists-Ruby-on-Rails/tree/production). [C#1](http://notateczki.herokuapp.com).
1. [Pieniążczak, Jan](https://github.com/Pelen/books2). [E#3](http://pelen.herokuapp.com). [dropbox]
1. [Piotrkowski, Łukasz](https://github.com/pietrakkk/gists). [C#1](http://lpiotrkowski-gists.herokuapp.com/) [`"C"*20 == "C"`]
1. [Plenis, Jakub](https://github.com/novalien/Aplikacje-zadanie-1). [C#1](http://mojezadania.herokuapp.com).
1. [Podgórski, Mirosław](https://github.com/ziomski/my_books). [E#3](http://ziomski.herokuapp.com) [cloudinary].
1. [Rękawek, Szymon](https://github.com/waveq/MyGists). [C+#1](http://mygistsszymonrekawek.herokuapp.com).
1. [Rzeszuto, Agnieszka](https://github.com/arzsz/my_gists). [C+#1](http://fast-beach-4233.herokuapp.com/gists).
1. [Sienkiewicz, Daniel](https://github.com/henio180/asisecond). [E#3](http://asisecond.herokuapp.com).
1. [Sikora, Jacek](https://github.com/jaresh/my_videos). [E#3](http://jsvideos.herokuapp.com) [google strorage+fog].
1. [Skałkowski, Michał](https://github.com/Michaldwadwa/projekt1-rails). [C#1](http://projekcik1.herokuapp.com).
1. [Skarżyński, Łukasz](https://github.com/LukSkarDev/railsapp). [C#1](http://lsgists.herokuapp.com/gists).
1. [Stenka, Dominik](https://github.com/ddstenka/my_gists). [C#1](http://rubyongist.herokuapp.com/)
1. [Synowczyk, Piotr](https://github.com/psynowczyk/MyGists), [C#1](http://psgists.herokuapp.com/).
1. [Szklarska, Milena](https://github.com/madebytechnology/Gists), [D#1](http://mygistsapp.herokuapp.com/)
1. [Wittbrodt, Łukasz](https://github.com/lukasz978/my_gists). [C+#1](http://lrails.herokuapp.com/).
1. [Zając, Mateusz](https://github.com/zajacmp3/RubyOnRails-Informatyka-). [E#2](http://www.rails.zajacmp3.pl).
1. [Zawadzki, Dawid](https://github.com/ghost717/my_gists). [C+#1](http://dzawadzki-app.herokuapp.com).
1. [Żynis, Przemysław](https://github.com/Zynio/MyBooks.git). [C#3](http://managerstore.herokuapp.com).
1. [Żuchowski, Sebastian](https://github.com/modziek/project_ruby). [C#1](http://maniana.herokuapp.com//).


## Użyteczne linki

* TJ VanToll.
  [List of Pseudo-Elements to Style Form Controls](http://tjvantoll.com/2013/04/15/list-of-pseudo-elements-to-style-form-controls/)
* [Rails Testing for Zombies](https://www.codeschool.com/courses/rails-testing-for-zombies) –
  Unit Testing
* [A Guide to Testing Rails Applications](http://edgeguides.rubyonrails.org/testing.html)
* Every Dog has one Blog.
  [Must Have Gems for Development Machine in Ruby on Rails](http://www.codebeerstartups.com/2013/04/must-have-gems-for-development-machine-in-ruby-on-rails)


## Kilka uwag

Podstawowe funkcjonalności, które należy zaimplementować:

1. Strony aplikacji powinny być responsywne.
Co to oznacza, w wypadku Bootstrapa jest opisane w sekcji
[Mobile first](http://getbootstrap.com/css/#overview-mobile).
W szczególności należy dopracować stronę główna aplikacji.
2. Każda z przykładowych aplikacji musi mieć zaimplementowane:
wyszukiwanie i paginację (z infinite scrolling).
3. Do aplikacji wdrożonej na Heroku należy dodać sporo
sensownych przykładowych rekordów. W tym celu należy użyć
pliku *db/seeds.rb*.
4. Plus dla aplikacji korzystających z:
  - Rails 4.1 [Variants, Enums lub Mailer previews](http://weblog.rubyonrails.org/2014/4/8/Rails-4-1/).
  - [Sizer Soze](http://sizersoze.org/) – What is the cost of your non-responsive images?

*Uwaga:* W repozytoriach nie powinno być *śmieci*, np.
plików *backup* edytora.
