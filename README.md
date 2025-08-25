# Projekt: Kopiowanie dyskietek C64 na systemie Linux OPenCBM + XUM1541

## Opis projektu

Projekt ma na celu umożliwienie uruchomienia stacji dysków 1541 II (kompatybilnej z komputerami Commodore 64) na systemie Linux. 
Dzięki temu użytkownicy będą mogli odczytywać, zapisywać oraz kopiować dane z dyskietek C64 na nowoczesne systemy, przy użyciu narzędzi takich jak OpenCBM oraz dedykowanego programu, który współpracuje z OpenCBM.

## Wymagania

- **Linux** (preferowana dystrybucja: Debian, Gentoo, Slackware)
- **OpenCBM** - program do komunikacji z komputerami Commodore 64
- **Mój program** - dodatkowy program współpracujący z OpenCBM, który umożliwia łatwą obsługę stacji dysków 1541 II na systemie Linux

### Wymagane zależności:

- `openCBM` (w wersji kompatybilnej z Twoim systemem)
- `libusb` (jeśli używasz urządzenia podłączonego przez USB)
- `gcc` i inne narzędzia do kompilacji (w przypadku potrzeby kompilowania OpenCBM)
- `Mój program` (dodatkowy program współpracujący z OpenCBM)

## Instalacja

### 1. Instalacja OpenCBM

Aby zainstalować OpenCBM na systemie Linux, postępuj zgodnie z poniższymi krokami:

#### a. Instalacja z repozytoriów systemowych (jeśli dostępne)

Na systemach opartych na Debianie/Ubuntu:

```bash
sudo apt update
sudo apt install opencbm

Na systemach opartych na RedHat/Fedora:

sudo dnf install opencbm

b. Instalacja z kodu źródłowego

Jeśli OpenCBM nie jest dostępny w repozytoriach, możesz pobrać kod źródłowy i zbudować go ręcznie:

git clone https://github.com/Dirk-Matthies/OpenCBM.git
cd OpenCBM
make
sudo make install


Niedługo cała reszta pozdrawiam bofh@retro cdn ...
