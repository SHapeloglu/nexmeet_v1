# CLAUDE.md — NexMeet v1 (arşiv sürümü)

> 🗄️ **ARŞİV (2026-10-07):** Bu sürüm artık geliştirilmiyor. Güncel sürüm: **[SHapeloglu/nexmeet_v3](https://github.com/SHapeloglu/nexmeet_v3)** (canlı: nexmeet.powerbi.com.tr).

İlk sürüm (2026-05-14): Google Meet benzeri WebRTC video konferans — çoklu katılımcı, mikrofon/kamera, ekran paylaşımı, WebM kayıt, sohbet, davet linki, dosya paylaşımı, uzak kontrol ajanı. **Join token ve TTS/çeviri yok.**

- GitHub: https://github.com/SHapeloglu/nexmeet_v1 — **PUBLIC repo**
- **Güncel/canlı sürüm: `/root/nexmeet` (repo `nexmeet_v3`)** — yeni geliştirme orada yapılır. Bu repo tarihsel referans.
- Mimari: `architect.md` · Görevler: `task.md` · Fikirler: `backlog.md` · Günlük: `session.md`

## Çalıştırma (yerel deneme)

```bash
./scripts/start.sh          # Windows: scripts\start.bat — venv + pip + uvicorn
# veya: cd backend && pip install -r requirements.txt && uvicorn main:app --reload --port 8000
```

## Kurallar

- Bu repoda değişiklik yapmadan önce kullanıcıya sor; düzeltmeler normalde v3'e gider.
- `uploads/` içinde 1 kullanıcı görseli ve `backend/__pycache__` izleniyor; `.gitignore` ve `.env.example` yok.
- Public repo: kullanıcı dosyası, IP, anahtar commit etme.
