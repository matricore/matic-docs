---
id: withdraw-start
title: withdrawStart
keywords:
- 'pos client, erc721, withdrawStart, polygon, sdk'
description: 'Инициируйте процесс вывода.'
---

Метод `withdrawStart` можно использовать для инициации процесса вывода, который сжигает указанный токен в polygon chain.

```
const erc721Token = posClient.erc721(<child token address>);

const result = await erc721Token.withdrawStart(<token id>);

const txHash = await result.getTransactionHash();

const txReceipt = await result.getReceipt();

```
