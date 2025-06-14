# Avaliação

```bash
# ==================================================================
# ===================  CODESPACE SETUP  ============================
# ==================================================================
# tko
sudo apt-get update && pipx install tko
# se for utilizar go
go install golang.org/x/tools/gopls@latest
# se for utilizar typescript
npm install typescript typescript-language-server esbuild readline-sync ts-node
# ==================================================================
# =====================  LOCAL SETUP  ==============================
# ==================================================================
# Se estiver no seu computador e já tiver o setup para fazer o clone
# local com as ferramentas de desenvolvimento e compiladores, lembre
# de atualizar o tko antes de começar a avaliação. 
pipx upgrade tko
# ==================================================================
# ==================  FAZENDO A AVALIAÇÃO  =========================
# ==================================================================
# abra o tko na raiz do repositório que você acabou de clonar
tko open .

# Baixe as atividades e rode os testes.
# Se quiser marcar a autoavalição para acompanhar a sua nota
# marque que fez sozinho, mas isso não é obrigatório ou muda a nota.

# ==================================================================
# =================  ENVIANDO A AVALIAÇÃO  =========================
# ==================================================================
git add .
git commit -m "Avaliação"
git push
```

## Acompanhamento

### Exercícios

- [ ] `@apagando     *03 :leet`[Apagando elementos de forma eficiente](https://github.com/qxcodeed/arcade/blob/master/base/apagando/Readme.md)
- [ ] `@triangulo    *03 :leet`[Imprimindo ao contrário](https://github.com/qxcodeed/arcade/blob/master/base/triangulo/Readme.md)
- [ ] `@queimada     *03 :leet`[Tocando fogo na floresta](https://github.com/qxcodeed/arcade/blob/master/base/queimada/Readme.md)
- [ ] `@setbuild     *10 :make`[Conjunto usando Lista Sequencial Ordenada](https://github.com/qxcodeed/arcade/blob/master/base/setbuild/Readme.md)
- [ ] `@lista_d1     *03 :make`[Lista Dupla com Nó Sentinela](https://github.com/qxcodeed/arcade/blob/master/base/lista_d1/Readme.md)
