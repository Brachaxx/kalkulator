<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# Jak stworzyć własny kalkulator

_Dowiesz się jak stworzyć własny kalkulator w CS!_

</header>

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

## Step 1: Przygotowanie środowiska
Zainstaluj Visual Studio lub inny edytor, który obsługuje C# (np. Visual Studio Code z odpowiednimi rozszerzeniami).
Utwórz nowy projekt konsolowy w C#.

Krok 2: Struktura programu
Utwórz nową aplikację konsolową w C#.
W głównym pliku (np. Program.cs) zacznij pisać kod.

Krok 3: Wprowadzenie danych od użytkownika
Będziesz musiał poprosić użytkownika o podanie dwóch liczb oraz wybranie operacji matematycznej.

Krok 4: Komentarze i wyjaśnienie
Wczytanie liczb: Program wczytuje dwie liczby od użytkownika za pomocą Console.ReadLine() i konwertuje je na typ double za pomocą Convert.ToDouble().
Wybór operacji: Użytkownik wybiera operację matematyczną, która będzie wykonana na tych liczbach. Używamy switch do obsługi różnych operacji.
Operacje matematyczne: Program obsługuje podstawowe operacje: dodawanie, odejmowanie, mnożenie i dzielenie. Jeśli użytkownik wybierze dzielenie przez zero, program wyświetli odpowiedni komunikat o błędzie.
Wynik: Na końcu program wyświetli wynik obliczeń.

Krok 5: Testowanie programu
Po zapisaniu programu, uruchom go, aby sprawdzić, czy wszystko działa poprawnie. Sprawdź różne kombinacje liczb oraz operacji.

Krok 6: Dodatkowe funkcjonalności (opcjonalnie)
Możesz rozbudować kalkulator o więcej funkcji, np. obliczenia z pierwiastkami, potęgowanie, obliczenia procentowe.
Możesz dodać obsługę wyjątków, aby program nie zawiesił się w przypadku nieprawidłowych danych wejściowych.
Gotowy program będzie prostym kalkulatorem, który wykonuje podstawowe operacje matematyczne na dwóch liczbach.

