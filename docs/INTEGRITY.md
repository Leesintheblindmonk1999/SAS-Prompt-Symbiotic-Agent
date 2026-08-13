# Integridad / Integrity

## English

### Files

| File | Purpose |
|---|---|
| `hashes/SHA256SUMS.txt` | SHA-256 hashes of the prompts. |
| `hashes/OTS.txt` | OpenTimestamps proof, if applicable. |

### Verification

Get-FileHash ".\en\SECURITY CO-ARCHITECT.txt" -Algorithm SHA256
Get-FileHash ".\es\CO-ARQUITECTO DE SEGURIDAD.txt" -Algorithm SHA256

### Rule

No prompt is published without its corresponding hash.

---

## Español

### Archivos

| Archivo | Propósito |
|---|---|
| `hashes/SHA256SUMS.txt` | Hashes SHA-256 de los prompts. |
| `hashes/OTS.txt` | Prueba OpenTimestamps, si corresponde. |

### Verificación

Get-FileHash ".\en\SECURITY CO-ARCHITECT.txt" -Algorithm SHA256
Get-FileHash ".\es\CO-ARQUITECTO DE SEGURIDAD.txt" -Algorithm SHA256

### Regla

Ningún prompt se publica sin su hash correspondiente.