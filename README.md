# 📄 publisher-to-pdf

![License: MIT](https://shields.io)
![PowerShell](https://shields.io)

Uno script PowerShell leggero ed efficace per la **conversione massiva e automatizzata** di file Microsoft Publisher (`.pub`) in formato PDF. 

> ⚠️ **Nota:** Utile per mettere al sicuro e archiviare i tuoi documenti in vista della dismissione definitiva di Microsoft Publisher da parte di Microsoft.

---

## 📋 Requisiti

* **Microsoft Publisher** installato sulla stessa macchina in cui viene eseguito lo script.
* **Privilegi di Amministratore** (necessari per eseguire script PowerShell non firmati).

---

## 🚀 Come usarlo

### Metodo Rapido (Esecuzione diretta dal Web)
Se non vuoi scaricare manualmente lo script, apri PowerShell come **Amministratore** ed esegui questo comando (sostituisci l'URL con il link RAW del tuo script):

```powershell
Invoke-RestMethod -Uri "https://githubusercontent.com" | Invoke-Expression
```

### Metodo Manuale
1. **Scarica** il file `publisher-to-pdf.ps1` sul tuo computer.
2. Apri lo script e **modifica i percorsi delle cartelle** (sorgente e destinazione) all'interno del codice.
3. Apri PowerShell come **Amministratore**.
4. Abilita l'esecuzione degli script (se non lo hai già fatto):
   ```powershell
   Set-ExecutionPolicy RemoteSigned -Scope Process -Force
   ```
5. **Lancia lo script**.

---

## ⚖️ Licenza

Questo progetto è distribuito sotto la **Licenza MIT**. Consulta il file [LICENSE](LICENSE) per maggiori dettagli.

---

## ☕ Supporta il progetto

Se questo script ti ha fatto risparmiare ore di lavoro e vuoi supportare lo sviluppo di altri strumenti gratuiti, puoi offrirmi un caffè!

[![Sostenimi su Buy Me A Coffee](https://shields.io)](https://buymeacoffee.com/johnsoul)
