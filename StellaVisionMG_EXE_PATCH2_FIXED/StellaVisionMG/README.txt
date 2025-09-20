Atualizações principais
-----------------------
- O bloco final `if __name__ == "__main__":` em `app.py` foi substituído pelo snippet solicitado, garantindo execução padrão na porta 5001.
- Os helpers de SKU (`_slug`, `_build_prefix`, `_next_seq`), o `get_db` e a rota `/dev/sku` foram adicionados em `app.py`, próximos ao topo do arquivo, logo após as migrações e antes das rotas.
- Os templates existentes permaneceram inalterados; o back-end apenas passou `rows`, `chart_labels` e `chart_values` para `dashboard.html`.
- Para iniciar na porta 5001 utilize `export PORT=5001 && python app.py` (Linux/macOS) ou `set PORT=5001 && python app.py` (Windows).
