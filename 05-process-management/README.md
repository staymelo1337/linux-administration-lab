## EN

# Linux Process and Service Management Lab

## Objective
Practice managing Linux processes, systemd services, monitoring system resources and analyzing system logs.

## Environment
- Operating System: Fedora Linux 43
- Shell: Bash
- Service Manager: systemd

## Tasks Performed

### 1. Process Management
- Listed running processes using `ps aux`.
- Searched for specific processes using `pgrep`.
- Created a background process using `sleep`.
- Identified process IDs (PIDs).
- Terminated processes using `kill`.
- Verified that processes were successfully terminated.

### 2. Service Management
- Inspected service status using `systemctl`.
- Checked whether services were enabled at system startup.
- Listed currently running system services.
- Learned the difference between starting and enabling a service.
- Practiced understanding `start`, `stop`, `restart`, `enable` and `disable`.

### 3. Log Analysis
- Displayed recent system logs using `journalctl`.
- Filtered logs by priority using `journalctl -p err`.
- Displayed logs from the current day.
- Practiced identifying system errors and warnings.

### 4. Resource Monitoring
- Monitored running processes using `top`.
- Inspected CPU and memory usage.

## Commands Used

| Command | Purpose |
|---|---|
| `ps aux` | Lists running processes |
| `pgrep -a` | Searches for processes by name |
| `sleep` | Creates a process for testing |
| `kill` | Sends a signal to a process |
| `top` | Monitors system resources |
| `systemctl status` | Checks service status |
| `systemctl start` | Starts a service |
| `systemctl stop` | Stops a service |
| `systemctl restart` | Restarts a service |
| `systemctl enable` | Enables automatic startup |
| `systemctl disable` | Disables automatic startup |
| `systemctl list-units` | Lists systemd units |
| `journalctl` | Displays system logs |

## Skills Practiced

- Linux process management
- Process identification and termination
- systemd service management
- System log analysis
- CPU and RAM monitoring
- Basic Linux troubleshooting

## PL

# Laboratorium: Zarządzanie procesami i usługami w systemie Linux

## Cel
Ćwiczenie zarządzania procesami w systemie Linux, usługami `systemd`, monitorowania zasobów systemowych oraz analizy logów systemowych.

## Środowisko
- System operacyjny: Fedora Linux 43
- Shell: Bash
- Menedżer usług: `systemd`

## Wykonane zadania

### 1. Zarządzanie procesami
- Wyświetlenie listy uruchomionych procesów za pomocą polecenia `ps aux`.
- Wyszukiwanie konkretnych procesów przy użyciu `pgrep`.
- Tworzenie procesu działającego w tle za pomocą `sleep`.
- Identyfikacja identyfikatorów procesów (PID).
- Zatrzymywanie procesów za pomocą polecenia `kill`.
- Weryfikacja, czy procesy zostały poprawnie zakończone.

### 2. Zarządzanie usługami
- Sprawdzanie stanu usług za pomocą `systemctl`.
- Weryfikacja, czy usługi są włączone do automatycznego uruchamiania wraz z systemem.
- Wyświetlanie listy aktualnie działających usług systemowych.
- Zrozumienie różnicy między uruchomieniem usługi a włączeniem jej automatycznego startu.
- Ćwiczenie użycia poleceń: `start`, `stop`, `restart`, `enable` oraz `disable`.

### 3. Analiza logów
- Wyświetlanie ostatnich logów systemowych za pomocą `journalctl`.
- Filtrowanie logów według priorytetu (np. `journalctl -p err`).
- Wyświetlanie logów z bieżącego dnia.
- Identyfikacja błędów i ostrzeżeń systemowych.

### 4. Monitorowanie zasobów
- Monitorowanie uruchomionych procesów za pomocą narzędzia `top`.
- Sprawdzanie zużycia procesora (CPU) oraz pamięci RAM.

## Użyte polecenia

| Polecenie | Zastosowanie |
|---|---|
| `ps aux` | Wyświetla listę uruchomionych procesów |
| `pgrep -a` | Wyszukuje procesy według nazwy |
| `sleep` | Tworzy proces (przydatne do testów) |
| `kill` | Wysyła sygnał do procesu |
| `top` | Monitoruje zasoby systemowe |
| `systemctl status` | Sprawdza stan usługi |
| `systemctl start` | Uruchamia usługę |
| `systemctl stop` | Zatrzymuje usługę |
| `systemctl restart` | Restartuje usługę |
| `systemctl enable` | Włącza automatyczne uruchamianie usługi |
| `systemctl disable` | Wyłącza automatyczne uruchamianie usługi |
| `systemctl list-units` | Wyświetla jednostki (units) systemu systemd |
| `journalctl` | Wyświetla logi systemowe |

## Ćwiczone umiejętności

- Zarządzanie procesami w systemie Linux
- Identyfikacja i kończenie procesów
- Zarządzanie usługami w systemie systemd
- Analiza logów systemowych
- Monitorowanie użycia procesora (CPU) i pamięci RAM
- Podstawowe rozwiązywanie problemów w systemie Linux
