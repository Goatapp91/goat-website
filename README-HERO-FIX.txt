PRZYCZYNA ZNALEZIONA:
W przesłanym ZIP-ie hero-goat.png JUŻ jest nową kozą z martwym ciągiem.
Problemem jest to, że index.html nadal odwoływał się do tej samej starej nazwy
hero-goat.png, więc GitHub Pages/przeglądarka mogły podawać starą wersję z cache.

NAPRAWA:
- utworzono nową nazwę: hero-goat-deadlift-v2.png
- index.html preloaduje i wyświetla właśnie hero-goat-deadlift-v2.png
- dzięki nowemu URL przeglądarka nie może użyć starego hero-goat.png z cache.

Wgraj CAŁĄ zawartość tego ZIP-a zamiast obecnej wersji repo.
