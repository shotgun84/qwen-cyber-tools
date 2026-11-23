# qwen-cyber-tools

Defensive cybersecurity tool-call fine-tuning set for Qwen (OpenAI-style messages).

- 3346 examples in `train.jsonl`
- Shards in `batch_*.jsonl`, `shard_*.jsonl`, `wave*.jsonl`
- Lab-only TEST-NET (192.168.x, 10.x, 203.0.113.x, example.com, testapp.example.local)
- Covers network, vuln/CVE, intel, file triage, forensics, webapp defensive, incident with ticket approval, crypto/TLS, logs, multi-tool chains, safety/errors
- No exploits, no real credentials. Authorization checks included.
