# Projekt: Uczelniana Chmura Obliczeniowa oparta na OpenStack

## Opis projektu
Projekt ma na celu zaprojektowanie, wdrożenie i udokumentowanie kompletnej chmury obliczeniowej opartej na platformie **OpenStack**, działającej na serwerach uczelnianych. System będzie wykorzystywany jako środowisko obliczeniowe i wdrożeniowe dla projektów studenckich oraz dydaktycznych.

## Zakres projektu
### 1. Architektura i wdrożenie OpenStack
- Konfiguracja kontrolerów i węzłów obliczeniowych
- Uruchomienie usług Nova, Neutron, Glance, Keystone, Cinder, Horizon
- Opcjonalnie: wysoka dostępność usług

### 2. Bezpieczeństwo chmury
- Polityki bezpieczeństwa, izolacja sieciowa, firewall
- Zabezpieczenie API oraz Horizon
- Monitorowanie i audyt

### 3. Zarządzanie zasobami
- Tworzenie i zarządzanie maszynami wirtualnymi
- Przygotowanie obrazów systemowych i szablonów VM

### 4. Repozytorium Docker i konteneryzacja
- Wdrożenie repozytorium obrazów kontenerów (np. Harbor)
- Przygotowanie obrazów do projektów studenckich

### 5. Klaster Kubernetes
- Integracja Kubernetes z infrastrukturą OpenStack
- Uruchamianie aplikacji kontenerowych w klastrze

### 6. Domeny i środowiska wdrożeniowe
- Konfiguracja domen i poddomen
- Przygotowanie wielośrodowiskowego pipeline'u (dev/test/prod)
- Integracja z CI/CD (GitLab, GitHub Actions, Jenkins)

### 7. Dokumentacja
- Dokumentacja architektury
- Instrukcja użytkownika dla studentów i dydaktyków
- Zbiór dobrych praktyk DevOps

## Efekty projektu
- Środowisko chmurowe wspierające zajęcia i projekty
- Możliwość realizacji procesów CI/CD
- Skalowalne środowisko do wdrażania aplikacji studenckich

