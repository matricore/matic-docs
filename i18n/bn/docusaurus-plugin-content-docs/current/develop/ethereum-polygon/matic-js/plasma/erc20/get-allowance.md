---
id: get-allowance
title: getAllowance
keywords:
- 'plasma client, erc20, getAllowance, polygon, sdk'
description: 'ব্যবহারকারীর জন্য অনুমোদিত পরিমাণ জেনে নিন।'
---

ব্যবহারকারীর জন্য অনুমোদিত পরিমাণ পেতে `getAllowance`পদ্ধতি ব্যবহার করা যেতে পারে।

```
const erc20Token = plasmaClient.erc20(<token address>, true);

const balance = await erc20Token.getAllowance(<userAddress>);
```
