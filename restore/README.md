# Geri alma araçları

Bu klasör `tickwarden-archived/archive-meta` deposundaki araçların kopyasıdır; arşiv tek başına da çalışır.

```bash
export GITHUB_TOKEN=...          # repo + admin:org kapsamlı
python3 restore/restore.py --list            # durum
python3 restore/restore.py --unarchive --apply
python3 restore/restore.py --visibility public --apply
python3 restore/restore.py --meta --apply
python3 restore/restore.py --transfer-back --apply
```

Tam kayıt (envanter, transfer planı, JSON export): https://github.com/tickwarden-archived/archive-meta
