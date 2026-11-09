## EN

# Linux File and Directory Permissions

## Objective
Practice managing Linux file permissions, ownership and access control.

## Tasks Performed
1. Created files and directories for permission testing.
2. Inspected file permissions using `ls -l`.
3. Modified permissions using `chmod`.
4. Practiced numeric permission notation.
5. Changed file groups using `chgrp`.
6. Tested file access using different user accounts.

## Commands Used

| Command | Purpose |
|---|---|
| `chmod` | Changes file permissions |
| `chown` | Changes file owner and group |
| `chgrp` | Changes file group |
| `ls -l` | Displays file permissions and ownership |
| `touch` | Creates empty files |
| `sudo -u` | Executes commands as another user |

## Permission Examples

| Permission | Meaning |
|---|---|
| `600` | Owner: read and write |
| `640` | Owner: read/write, group: read |
| `644` | Owner: read/write, others: read |
| `700` | Owner: full permissions |
| `770` | Owner and group: full permissions |
| `777` | Everyone: full permissions |

## Skills Practiced
- Linux file permissions
- User and group access control
- File ownership management
- Numeric permissions
- Basic Linux troubleshooting

## PL

# Uprawnienia do plików i katalogów w systemie Linux

## Cel
Ćwiczenie zarządzania uprawnieniami do plików, ich uprawnieniami oraz kontrolą dostępu w systemie Linux.

## Wykonane zadania
1. Utworzono pliki i katalogi na potrzeby testowania uprawnień.
2. Sprawdzono uprawnienia plików za pomocą polecenia `ls -l`.
3. Zmodyfikowano uprawnienia przy użyciu polecenia `chmod`.
4. Przećwiczono zapis uprawnień w formie liczbowej.
5. Zmieniono grupy przypisane do plików za pomocą polecenia `chgrp`.
6. Przetestowano dostęp do plików z poziomu różnych kont użytkowników.

## Użyte polecenia

| Polecenie | Zastosowanie |
|---|---|
| `chmod` | Zmiana uprawnień do plików |
| `chown` | Zmiana właściciela i grupy pliku |
| `chgrp` | Zmiana grupy pliku |
| `ls -l` | Wyświetlanie uprawnień i informacji o własności plików |
| `touch` | Tworzenie pustych plików |
| `sudo -u` | Wykonywanie poleceń w imieniu innego użytkownika |

## Przykłady uprawnień

| Uprawnienia | Znaczenie |
|---|---|
| `600` | Właściciel: odczyt i zapis |
| `640` | Właściciel: odczyt/zapis, grupa: odczyt |
| `644` | Właściciel: odczyt/zapis, pozostali: odczyt |
| `700` | Właściciel: pełne uprawnienia |
| `770` | Właściciel i grupa: pełne uprawnienia |
| `777` | Wszyscy: pełne uprawnienia |

## Nabyte umiejętności
- Zarządzanie uprawnieniami do plików w systemie Linux
- Kontrola dostępu dla użytkowników i grup
- Zarządzanie własnością plików
- Stosowanie uprawnień w zapisie liczbowym
- Podstawowe rozwiązywanie problemów w systemie Linux
