# 🕵️ Roteiro da Investigação

Vamos investigar **juntos**, por rodadas. Em cada rodada, abra o arquivo indicado, procure a resposta e anote. Não precisa ter pressa — a graça é achar a pista.

> Dica de analista: use **Ctrl+F** para buscar dentro de cada arquivo.

---

## Rodada 1 — O gatilho
Abra **`alerta.txt`**.

1. Qual conta disparou o alerta?
2. Que horas foi o acesso e de qual país?
3. Por que isso é estranho?

## Rodada 2 — A porta de entrada
Abra a pasta **`emails/`** e leia as três mensagens.

4. Qual dos e-mails parece um golpe? Como você percebeu?
5. Qual o endereço do site?
6. Que "truques" o e-mail usou para te apressar?

## Rodada 3 — Quem caiu
Abra **`logs/web.log`**.

7. Alguém da padaria clicou no link do golpe? Quem e a que horas?

## Rodada 4 — O invasor entra
Abra **`logs/auth.log`**.

9. Ache a linha do login das 03:12. O que tem de diferente nela?
10. Aconteceu alguma coisa **antes** das 03:12 com essa mesma conta?

## Rodada 5 — O estrago
Volte ao **`logs/web.log`**.

11. Depois de entrar às 03:1x, o que o invasor acessou?
12. Qual linha é a **prova** de que dados foram roubados? 
13. Que dado foi levado?

## Rodada 6 — A linha do tempo
Junte tudo. Coloque os eventos em ordem:

```
1. ____/____ ____:____  →  e-mail de golpe chega
2. ____/____ ____:____  →  funcionário clica no link
3. ____/____ ____:____  →  invasor entra na conta
4. ____/____ ____:____  →  invasor exporta os dados
```

## Rodada 7 — E agora, analista?
14. Cite **3 coisas** que o SOC deve fazer para conter e evitar que aconteça de novo.
