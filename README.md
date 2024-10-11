# Herói XP Nível

Este é um programa simples em Python que determina o nível de um herói com base na quantidade de experiência (XP) adquirida. O usuário insere o nome do herói e a quantidade de XP, e o programa classifica o herói em um nível apropriado.

## Como Funciona

O programa solicita dois inputs ao usuário:
1. **Nome do Herói**: O nome do herói que você deseja verificar.
2. **Quantidade de XP**: O valor numérico que representa a experiência ganha pelo herói.

Com base no valor de XP fornecido, o programa determina o nível do herói de acordo com a seguinte classificação:

| Nível       | Faixa de XP          |
|-------------|----------------------|
| Ferro       | XP < 1000            |
| Bronze      | 1001 ≤ XP ≤ 2000     |
| Prata       | 2001 ≤ XP ≤ 5000     |
| Ouro        | 5001 ≤ XP ≤ 7000     |
| Platina     | 7001 ≤ XP ≤ 8000     |
| Ascendente  | 8001 ≤ XP ≤ 9000     |
| Imortal     | 9001 ≤ XP ≤ 10000    |
| Radiante    | XP > 10000           |

## Exemplo de Uso

Aqui está um exemplo de interação com o programa:

```bash
Digite o nome do Herói: Thor
Digite a quantidade de XP ganho: 7500
O herói **Thor** está no nível **Platina**
```
Requisitos

    Python 3.x instalado em seu sistema.

Como Executar

    Clone o repositório ou baixe o código.

    Abra um terminal e navegue até o diretório onde o código está salvo.

    Execute o programa com o comando:

```bash

python nome_do_arquivo.py
```

Insira o nome do herói e a quantidade de XP conforme solicitado.