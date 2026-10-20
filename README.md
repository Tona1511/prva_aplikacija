# Prva aplikacija

## Vjezba 1

Projekt je izrađen u Flutteru i programskom jeziku Dart.

## Sadrzaj projekta

- Flutter aplikacija
- Dart program bin/provjera.dart
- Android emulator Pixel 6

## Pokretanje Dart programa

dart run bin/provjera.dart

## Pokretanje Flutter aplikacije

flutter run

## Verzije alata

- Flutter: 3.47.7 (stable)
- Dart: 3.13.5 (stable)
- DevTools: 2.60.0
- Operacijski sustav: Windows 11
- Android emulator: Pixel 6


## Provjera razumijevanja 2

Kada se parametar funkcije promijeni iz String? u String, Dart više ne dopušta prosljeđivanje vrijednosti null.

Flutter analyze prijavljuje grešku jer null nije dopušten za tip String.

Operator ?? postaje nepotreban jer String ne može imati vrijednost null.

Vraćanjem tipa na String? problemi nestaju.
