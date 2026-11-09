## EN

# Linux Network Diagnostics Lab

## Objective
Practice basic Linux network diagnostics and learn how to troubleshoot network connectivity, inspect network interfaces, identify DNS configuration and analyze network traffic.

## Environment
- Operating System: Fedora Linux 43
- Network Interface: `wlo1` (Wi-Fi)
- Local IPv4 Address: `192.168.100.31`
- Default Gateway: `192.168.100.1`
- DNS Server: `192.168.100.1`

## Tasks Performed

1. Inspected network interfaces and IP configuration.
2. Identified the default gateway and routing table.
3. Checked DNS server configuration.
4. Inspected network device status.
5. Tested local network and internet connectivity.
6. Verified DNS resolution.
7. Traced the network path to an external host.
8. Inspected listening network sockets and ports.
9. Examined the ARP/NDP neighbor table and MAC addresses.

## Commands Used

| Command | Purpose |
|---|---|
| `ip addr` | Displays network interfaces and IP addresses |
| `ip route` | Displays the routing table |
| `resolvectl dns` | Displays configured DNS servers |
| `resolvectl status` | Displays DNS configuration |
| `nmcli device status` | Shows network device status |
| `ping` | Tests network connectivity |
| `tracepath` | Traces the network path to a destination |
| `ss -tulpen` | Displays listening sockets and network ports |
| `ip neigh` | Displays the neighbor table with IP and MAC addresses |

## Connectivity Tests

Tested connectivity to three destinations:

- Default gateway: `192.168.100.1`
- External IP address: `1.1.1.1`
- Domain name: `google.com`

All three tests were successful.

## Key Findings

- Identified the local IPv4 address and Wi-Fi interface.
- Identified the default gateway and DNS server.
- Confirmed local and external network connectivity.
- Verified successful DNS resolution.
- Observed network hops and Path MTU information using `tracepath`.
- Learned the difference between listening on `0.0.0.0` and `127.0.0.1`.
- Identified the relationship between IP addresses and MAC addresses.
- Learned how to interpret `REACHABLE` and `STALE` neighbor states.

## Skills Practiced

- Linux network administration
- TCP/IP fundamentals
- DNS troubleshooting
- Network connectivity diagnostics
- Routing and default gateways
- Network ports and listening services
- IP and MAC address identification

## PL

# Laboratorium diagnostyki sieci w systemie Linux

## Cel
Ćwiczenie podstawowej diagnostyki sieci w systemie Linux, rozwiązywanie problemów z łącznością sieciową, sprawdzanie interfejsów sieciowych, weryfikacja konfiguracji DNS oraz analiza ruchu sieciowego.

## Środowisko
- System operacyjny: Fedora Linux 43
- Interfejs sieciowy: `wlo1` (Wi-Fi)
- Lokalny adres IPv4: `192.168.100.31`
- Domyślna brama sieciowa: `192.168.100.1`
- Serwer DNS: `192.168.100.1`

## Wykonane zadania

1. Sprawdzenie interfejsów sieciowych i konfiguracji adresów IP.
2. Identyfikacja domyślnej bramy sieciowej oraz tablicy routingu.
3. Weryfikacja konfiguracji serwera DNS.
4. Sprawdzenie stanu urządzeń sieciowych.
5. Testowanie łączności w sieci lokalnej oraz z Internetem.
6. Weryfikacja rozpoznawania nazw DNS.
7. Śledzenie ścieżki sieciowej do hosta zewnętrznego.
8. Sprawdzenie aktywnych gniazd (socketów) sieciowych i portów.
9. Analiza tablicy sąsiedztwa (ARP/NDP) oraz adresów MAC.

## Użyte polecenia

| Polecenie | Cel |
|---|---|
| `ip addr` | Wyświetla interfejsy sieciowe i adresy IP |
| `ip route` | Wyświetla tablicę routingu |
| `resolvectl dns` | Wyświetla skonfigurowane serwery DNS |
| `resolvectl status` | Wyświetla konfigurację DNS |
| `nmcli device status` | Pokazuje stan urządzeń sieciowych |
| `ping` | Testuje łączność sieciową |
| `tracepath` | Śledzi ścieżkę sieciową do miejsca docelowego |
| `ss -tulpen` | Wyświetla aktywne gniazda i porty sieciowe |
| `ip neigh` | Wyświetla tablicę sąsiedztwa z adresami IP i MAC |

## Testy łączności

Przeprowadzono testy łączności z trzema punktami docelowymi:

- Domyślna brama sieciowa: `192.168.100.1`
- Zewnętrzny adres IP: `1.1.1.1`
- Nazwa domenowa: `google.com`

Wszystkie trzy testy zakończyły się powodzeniem. 

## Kluczowe ustalenia

- Zidentyfikowano lokalny adres IPv4 oraz interfejs sieci Wi-Fi.
- Zidentyfikowano domyślną bramę sieciową oraz serwer DNS.
- Potwierdzono łączność z siecią lokalną i zewnętrzną.
- Zweryfikowano poprawność rozpoznawania nazw DNS.
- Przeanalizowano kolejne etapy połączenia sieciowego (tzw. „hopy”) oraz wartość Path MTU przy użyciu narzędzia `tracepath`.
- Poznano różnicę między nasłuchiwaniem na adresach `0.0.0.0` oraz `127.0.0.1`.
- Określono relację między adresami IP a adresami MAC.
- Nauczono się interpretować stany sąsiadów (neighbor states), takie jak `REACHABLE` oraz `STALE`.

## Nabyte umiejętności

- Administracja siecią w systemie Linux
- Podstawy protokołów TCP/IP
- Rozwiązywanie problemów z DNS
- Diagnostyka łączności sieciowej
- Routing i domyślne bramy sieciowe
- Porty sieciowe i usługi nasłuchujące
- Identyfikacja adresów IP oraz MAC
