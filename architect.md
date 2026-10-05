# architect.md — 🎥 NexMeet — Video Konferans Uygulaması Mimari Referansı

Bu dosya projenin yapısının hızlı-referans özetidir. Kod değiştikçe güncel tutun.

## Genel Bakış

Google Meet benzeri, tam özellikli web tabanlı video konferans uygulaması.

## Teknoloji Yığını

- FastAPI
- Uvicorn
- Docker / docker compose
- Bash betikleri

## Dizin Yapısı

```
README.md
agent/
  agent.py
  requirements.txt
  run_agent.bat
  run_agent.sh
backend/
  __init__.py
  main.py
  requirements.txt
docker/
  Dockerfile
  docker-compose.yml
frontend/
  index.html
scripts/
  start.bat
  start.sh
uploads/
  6ba37304-ffec-423f-a724-1e85c99dfe54_image.jpg
```

## Modüller / Kaynak Dosyalar

- `agent/agent.py` — NexMeet Uzak Kontrol Ajanı
- `agent/run_agent.sh`
- `backend/main.py`
- `scripts/start.sh` — NexMeet Başlatma Scripti (Linux/macOS)

## Giriş Noktaları ve Yapılandırma

- `agent/requirements.txt`
- `backend/main.py`
- `backend/requirements.txt`
- `docker/Dockerfile`
- `docker/docker-compose.yml`
- `frontend/index.html`

## Dağıtım / Çalışma Ortamı

- GitHub: https://github.com/SHapeloglu/nexmeet_v1

## Diğer Dokümanlar

- `README.md`

## Mimari Kararlar

_Önemli tasarım kararlarını ve gerekçelerini buraya ekleyin (ör. "X yerine Y seçildi çünkü ...")._
