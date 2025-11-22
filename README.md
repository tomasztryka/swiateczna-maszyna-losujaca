# 🎄 Świąteczna Maszyna Losująca

Prosta aplikacja do losowania Secret Santa dla rodziny i znajomych w świątecznym stylu!

## 🎄 Co to robi?

Aplikacja pozwala na sprawiedliwe losowanie kto komu kupuje prezent, z gwarancją że:
- ✅ Nikt nie wylosuje samego siebie
- ✅ Każda osoba wylosuje dokładnie jedną inną osobę
- ✅ Proces jest prosty i zabawny!

## ✨ Wygląd

- 🎨 Świąteczne kolory: czerwień, zieleń, złoto
- ❄️ Spadający śnieg w tle
- ⭐ Migające gwiazdki i ozdoby
- 🎁 Świąteczne emoji (choinka, Mikołaj, renifer, prezenty)
- 🌟 Animacje i confetti na zakończenie
- 📱 Responsywny design (działa na telefonie i komputerze)

## 🚀 Jak używać?

### 1. Dodaj uczestników
- Wpisz imiona wszystkich osób które będą uczestniczyć
- Potrzeba minimum 2 osób
- Możesz dodawać i usuwać osoby przed rozpoczęciem

### 2. Rozpocznij losowanie
- Kliknij "ROZPOCZNIJ LOSOWANIE!"
- Przekazuj urządzenie każdej osobie po kolei
- Każda osoba:
  1. Widzi swoje imię
  2. Klika "LOSUJ!"
  3. Zapamiętuje kogo wylosowała
  4. Klika "Zrozumiałem/am, przekaż dalej!"
  5. Przekazuje urządzenie następnej osobie

### 3. Gotowe!
- Gdy wszyscy wylosują, pojawi się ekran końcowy
- Możesz kliknąć "Pokaż podsumowanie" aby zobaczyć pełną listę kto komu wylosował (tylko dla organizatora!)
- Możesz zacząć od nowa klikając "Zacznij od nowa"

## 🎨 Technologia

- **HTML5** - struktura
- **Tailwind CSS (CDN)** - style
- **Vanilla JavaScript** - logika
- **localStorage** - zapisywanie stanu

## 🔒 Prywatność

- Wszystkie dane są zapisywane tylko lokalnie w przeglądarce (localStorage)
- Nic nie jest wysyłane do internetu
- Możesz w każdej chwili zresetować aplikację

## 🎯 Algorytm

Aplikacja używa algorytmu **derangement** - czyli permutacji gdzie żaden element nie jest na swoim miejscu. Gwarantuje to że:
- Każda osoba dostaje inną osobę (nie siebie)
- Algorytm próbuje różne kombinacje aż znajdzie poprawną
- W najgorszym przypadku (bardzo rzadkim) używa prostej rotacji listy

## 💡 Wskazówki

- **Auto-save**: Stan jest automatycznie zapisywany, więc nawet jak przypadkowo odświeżysz stronę, postęp się zachowa
- **Powrót**: Możesz wrócić do edycji listy przed zakończeniem losowania (ale stracisz postęp)
- **Reset**: W każdej chwili możesz zacząć od nowa

## 🎁 Miłego losowania!
