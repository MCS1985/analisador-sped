# Analisador SPED PISCOFINS

Analisador de arquivos SPED Contribuições e Fiscal via DuckDB-WASM (tudo no navegador, sem servidor).

## Acessar online

https://mcs1985.github.io/analisador-sped

## Como usar

1. Abra o link acima
2. Arraste os arquivos .txt do SPED (ou a pasta inteira) para o dropzone
3. Use os filtros para navegar pelos dados
4. Exporte XLSX via botão "Baixar XLSX"

## Editar e publicar alterações

### No mesmo PC

```powershell
cd D:\FERRAMENTAS_MCS_IA
git add analisador_sped.html
git commit -m "descrição da alteração"
git push
```

### Em outro PC

```powershell
git clone https://github.com/MCS1985/analisador-sped.git
cd analisador-sped
```

Edite o arquivo `analisador_sped.html` e depois:

```powershell
git add analisador_sped.html
git commit -m "descrição da alteração"
git push
```

O site atualiza automaticamente em ~1 minuto.

### Primeira configuração (só uma vez)

```powershell
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"
```

### Resumo de comandos

| Comando | O que faz |
|---|---|
| `git status` | Mostra arquivos modificados |
| `git add analisador_sped.html` | Prepara o arquivo para commit |
| `git commit -m "mensagem"` | Cria um commit |
| `git push` | Envia as alterações para o GitHub |
| `git pull` | Baixa alterações do GitHub (no outro PC) |
