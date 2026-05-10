

# Platforma mobilnej rehabilitacji domowej

## Opis projektu

Projekt został wykonany w ramach przedmiotu „System kontroli wersji”. Celem projektu było praktyczne wykorzystanie systemu kontroli wersji GIT oraz platformy GitHub do zarządzania dokumentacją nowej usługi medycznej.

Projekt przedstawia dokumentację platformy mobilnej wspierającej rehabilitację pacjentów w warunkach domowych. System ma umożliwiać pacjentom wykonywanie ćwiczeń rehabilitacyjnych przy użyciu aplikacji mobilnej oraz poprzez kontakt z fizjoterapeutą.

## Dokumenty utworzone w projekcie

W repozytorium znajdują się następujące pliki:

- `opis_usługi.txt` – opis usługi medycznej,

- `plan_wdrożenia.txt` – harmonogram wdrożenia projektu,

- `ryzyka.txt` – analiza potencjalnego ryzyka,

- `kampania_marketingowa.txt` – plan kampanii promocyjnej,

- `ankieta_pacjentów.txt` – przykładowa ankieta dla pacjentów,

- `images/logo.png` – logo projektu,

- `.gitignore` – konfiguracja ignorowanych plików,

- `.gitattributes` – konfiguracja plików binarnych.


## Instrukcja pracy z repozytorium

### Klonowanie repozytorium

```bash
git clone <adres_repozytorium>
```

### Przełączanie gałęzi

```bash
git checkout main
git checkout marketing
```

### Wyświetlanie historii commitów

```bash
git log --oneline
```

### Przywracanie wcześniejszych wersji plików

```bash
git checkout <ID_commita>
```

## Wykorzystane polecenia GIT

W projekcie wykorzystano następujące polecenia:

- `git init` – utworzenie repozytorium,

- `git add` – dodawanie plików do repozytorium,

- `git commit` – zapisywanie zmian,

- `git branch` – tworzenie nowych gałęzi,

- `git checkout` – przełączanie między gałęziami,

- `git merge` – scalanie gałęzi,

- `git tag` – oznaczanie wersji projektu,

- `git push` – wysyłanie zmian do GitHub.

## Napotkane problemy

Podczas realizacji projektu wystąpił problem z uwierzytelnianiem podczas wysyłania repozytorium na GitHub przy użyciu HTTPS. Problem został rozwiązany poprzez konfigurację klucza SSH i połączenie repozytorium z GitHub za pomocą SSH.

