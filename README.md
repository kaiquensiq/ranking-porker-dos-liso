# Poker dos Liso — Ranking

Ranking oficial do grupo de poker **Poker dos Liso**, atualizado após cada torneio.

## Como visualizar

Acesse: `https://<seu-usuario>.github.io/<nome-do-repositorio>/`

## Como atualizar o ranking

1. Abra o arquivo `poker_dos_liso.html`
2. No final do arquivo, dentro da tag `<script>`, localize o array `all_tournaments`
3. Adicione o novo torneio seguindo o padrão:
```js
{n:16, p:5, isNew:true, r:[["Jogador",1,2],["Jogador2",2,0], ...]}
```
- `n` = número do torneio
- `p` = quantidade de jogadores
- `r` = resultado: `["Nome", lugar, eliminações]`
4. Atualize também o array `ranking` com os pontos recalculados
5. Salve e envie para o GitHub

## Sistema de pontuação

| Colocação | Pontos |
|-----------|--------|
| 1º lugar  | 15 pts + 5 bônus |
| 2º lugar  | 12 pts |
| 3º lugar  | 10 pts |
| 4º lugar  | 8 pts  |
| 5º lugar  | 6 pts  |
| 6º lugar  | 4 pts  |
| 7º lugar  | 3 pts  |
| 8º lugar  | 2 pts  |
| 9º lugar  | 1 pt   |
| Eliminação | +2 pts cada |
