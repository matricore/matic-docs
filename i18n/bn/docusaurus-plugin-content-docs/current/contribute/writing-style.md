---
id: writing-style
title: লেখা বিষয়ক সাধারণ নির্দেশিকা
sidebar_label: General writing guidelines
description: লেখার সময় নিচের নির্দেশিকাগুলো মেনে চলুন।
keywords:
  - docs
  - matic
  - polygon
  - documentation
  - writing
  - contribute
  - style
image: https://wiki.polygon.technology/img/polygon-wiki.png
slug: writing-style
---

Polygon Wiki-এর জন্য ডকুমেন্টেশন তৈরি করার সময় স্টাইল কনভেনশনের ব্যবহারের ব্যাপারে এবং
টেকনিক্যাল ডকুমেন্টেশন লেখার সময় সুপরিচিত পদ্ধতি ব্যবহারের উপরে জোর দিয়েছে।
এই নির্দেশিকার লক্ষ্য হচ্ছে লেখকদের স্পষ্ট, সংক্ষিপ্ত এবং সঙ্গতিপূর্ণ কন্টেন্ট তৈরি করতে
সহায়তা করা। Polygon টিম Polygon Wiki-কে একটি অফিসিয়াল ডকুমেন্ট প্রোডাক্ট হিসাবে বিবেচনা করে।

## প্রাথমিক নির্দেশিকা {#primary-guidelines}

আমরা মনে করি সামঞ্জস্যপূর্ণ ডিজাইন হলো Polygon-এর বিশেষ হয়ে ওঠার অন্যতম একটি কারণ এবং আমরা এই উল্লেখযোগ্য বৈশিষ্ট্য়টি বজায় রাখতে চাই। Polygon টিম Polygon Wiki-কে একটি অফিসিয়াল
ডকুমেন্ট প্রোডাক্ট হিসাবে বিবেচনা করে। প্রথম থেকেই আমরা কিছু নির্দেশিকা চালু করেছি, যাতে নতুন অবদানগুলো সামগ্রিক প্রকল্পের উন্নতিতে সাহায্য করে:

- **গুণমান**: Polygon প্রজেক্টে কোডকে নিশ্চিত করতে হবে যে এটা যেন পর্যাপ্ত টেস্ট-কেস, বিবরণমূলক কমিট মেসেজ,
প্রমাণ সহ স্টাইল গাইড মেনে চলে, যার ফলে অবদান থেকে সামঞ্জস্যতা সংক্রান্ত কোনো প্রতিশ্রুতি ভঙ্গ করে না বা
উচ্চমানের পিয়ার-রিভিউর প্রমাণ এবং ফিচার ইন্টারঅ্যাকশনে
কোনো বিরূপ প্রভাব না ফেলে।
- **সাইজ**: Polygon প্রকল্পের সংস্কৃতি হলো নিয়মিতভাবে ছোট ছোট পুল-রিকোয়েস্ট আকারে
জমা করা। পুল-রিকোয়েস্ট যত বড় হবে, আপনাকে তত বেশি সেল্ফ-কন্টেইনড এবং পৃথক পৃথকভাবে পর্যালোচনাযোগ্য PR-এর সিরিজ পুনরায় জমা দেওয়ার কথা বলা হতে পারে।
- **রক্ষণাবেক্ষণযোগ্যতা**: ফিচারটির জন্য যদি চলমান রক্ষণাবেক্ষণের প্রয়োজন হয় (যেমন
নির্দিষ্ট ডেটাবেসের ব্র্যান্ডের জন্য সাপোর্ট), তাহলে আপনাকে আমরা এই ফিচারটি রক্ষণাবেক্ষণ করার
দায়িত্ব গ্রহণের অনুরোধ করতে পারি।

স্টাইল গাইড নিচের স্টাইল ম্যানুয়ালগুলোকে অনুসরণ করে থাকে:

> আপনি যদি এই নির্দেশিকায় স্টাইল, ভয়েস বা টার্মিনোলজি সংক্রান্ত কোনো প্রশ্নের উত্তর খুঁজে না পান,
> তাহলে অনুগ্রহ করে এই রিসোর্সগুলো দেখুন।

- [Google-এর স্টাইল গাইড](https://github.com/google/styleguide/blob/gh-pages/docguide/style.md)
- [অক্সফোর্ড স্টাইল ম্যানুয়াল](https://global.oup.com/academic/product/new-oxford-style-manual-9780198767251?cc=nl&lang=en&)
- [Microsoft ম্যানুয়াল অব স্টাইল](https://docs.microsoft.com/en-us/style-guide/welcome/)

### স্ট্যাটিক-সাইট জেনারেটর {#static-site-generator}

[Docusaurus](https://docusaurus.io/), মার্কডাউনে ডকুমেন্টেশন তৈরি করার একটি স্ট্যাটিক সাইট জেনারেটর,
ব্যবহার করে Wiki তৈরি করা হয়েছে। Wiki মার্কডাউন ফাইলের জন্য নিম্নলিখিত মেটাডেটা টেমপ্লেট অনুসরণ করে এবং
প্রতিটি নতুন ডকুমেন্টে এটি ব্যবহার করতে হবে:

```
---
id: wiki-maintainers
title: Wiki Maintainers
sidebar_label: Maintainers
description: A list of Polygon Wiki maintainers
keywords:
  - docs
  - matic
  - polygon
  - wiki
  - docs
  - maintainers
  - contributors
image: https://matic.network/banners/matic-network-16x9.png
slug: community-maintainers
---
```

একটি মার্কডাউন ফাইলের জন্য মেটাডেটা লেখার সময় নিম্নলিখিত গুরুত্বপূর্ণ বিষয়গুলো বিবেচনায় রাখবেন:
- আমরা অবদানকারীদের একটি **অনন্য আইডি** ব্যবহার করতে বলি; **শুধুমাত্র** "পরিচিতি" বা "ওভারভিউ"-এর মত প্রচলিত শব্দ বা বাক্য ব্যবহার করা এড়িয়ে যেতে বলি।
- **টাইটেল বা শিরোনাম** দ্বারা আচর্টিকেলের শুরুতে যে বাক্য ব্যবহার করা হয় তাকে বুঝানো হয়েছে, যেমন "সাধারণ লেখা সম্পর্কিত নির্দেশিকা" হচ্ছে এই আর্টিকেলের শিরোনাম। তাই প্রতিটি আর্টিকেলের শুরুতে একটি H1/H2 হেডার যোগ করার প্রয়োজন নেই। পরিবর্তে, মেটাডেটা থেকে এই **টাইটেল** ব্যবহার করুন।
- **বর্ণনা** খুব দীর্ঘ করা যাবে না, কারণ এটি সূচিপত্রে ব্যবহার করা হয়, যেখানে অক্ষরের সীমাবদ্ধতা রয়েছে। উদাহরণস্বরূপ, *basics-blockchain.md*-এর বর্ণনা "ব্লকচেইন হচ্ছে লেনদেন রেকর্ড করার একটি অপরিবর্তনীয় লেজার" সূচিপত্রে নিম্নলিখিতভাবে প্রদর্শিত হয়: ![img](/img/contribute/index-tile.png)

  **বর্ণনায়** **সর্বোচ্চ 60টি অক্ষর** রাখা যাবে, যাতে অক্ষরগুলোর মাঝে থাকা স্পেসও গণনা করা হয়ে থাকে।
- SEO বৃদ্ধি এবং আর্টিকেলটি বর্ণনা করার ক্ষেত্রে কীওয়ার্ড খুবই গুরুত্বপূর্ণ ভূমিকা পালন করে। অন্তত পাঁচটি কীওয়ার্ড ব্যবহার করে দেখার চেষ্টা করুন।

:::note

আরো বিস্তারিত জানতে,
অনুগ্রহ করে [অফিসিয়াল মেটাডেটা ডকুমেন্টেশন](https://docusaurus.io/docs/next/api/plugins/@docusaurus/plugin-content-docs#markdown-front-matter) দেখুন।

:::

### পাঠকের সাথে অভিজ্ঞতা শেয়ার করুন {#share-the-experience-with-the-reader}

- উত্তম পুরুষ: "আমি" অথবা "আমাকে" ব্যবহার করবেন না। উত্তম পুরুষ খুব কম ব্যবহারের চেষ্টা করবেন, তবে ব্যবহার করতে হলে
ইন্টেন্ট সহ ব্যবহার করবেন। উত্তম পুরুষ অত্যধিক ব্যবহার করা হলে শেয়ার করা অভিজ্ঞতার গুরুত্ব অনেকাংশে কমে যায়
এবং পাঠক পড়তে গিয়ে উৎসাহ হারিয়ে ফেলতে পারে।
- মধ্যম পুরুষ: বেশিরভাগ ক্ষেত্রে, পাঠককে সরাসরি সম্বোধন করুন। টিউটোরিয়ালের জন্য, উত্তম পুরুষের
বহুবচন—আমরা, আমাদেরকে, আমাদের—বা মধ্যম পুরুষ বাচক শব্দ ব্যবহার করুন। কারণ টিউটোরিয়াল একটি বিষয়কে আরো সহজবোধ্য করে তোলার চেষ্টা করে, তাই অন্যান্য ডকুমেন্টের তুলনায় টিউটোরিয়ালে
উত্তম পুরুষের বহুবচনের ব্যবহার অনেক বেশি স্বাভাবিক ও প্রচলিত একটি প্রথা।
- নাম পুরুষ: Polygon বা Polygon টেকনোলজিকে উল্লেখ করার জন্য "আমরা" ব্যবহার করবেন না।
- কর্তৃবাচ্য: যেখানে সম্ভব, বর্তমান কাল ব্যবহার করুন। তবে কিছু কিছু ক্ষেত্রে কর্মবাচ্য
ব্যবহারের প্রয়োজন হয়; যখন এজেন্ট ফোকাসে থাকবে তখন ভাববাচ্য ব্যবহার করুন।
- মানুষের উপস্থিতির কথা মাথায় রাখুন: টেকনিক্যাল বিষয় বর্ণনা করার সময় শুধু সফটওয়্যার (বা কোড) কী করে তা বলার পরিবর্তে ডায়নামিক টোন ব্যবহার করলে বিষয়বস্তুটি পাঠককে
আরো সহজে বুঝতে সাহায্য করতে পারে।
- সর্বনাম: সম্ভব হলে লিঙ্গ-নিরপেক্ষ সর্বনাম, যেমন "তারা" ব্যবহার করুন। সাধারণত, আপনি
যে কোনো বিশেষ্যকে একবচন থেকে বহুবচনে পরিবর্তন করতে পারেন, যাতে কর্তা-ক্রিয়া-সর্বনামের মধ্যে সামঞ্জস্য থাকে এবং
"পুরুষ", "মহিলার" মতো লিঙ্গ নির্দিষ্ট সর্বনামের ব্যবহার এড়ানো যায়।
  - অব্যক্তিগত এবং সম্ভাব্য অস্পষ্ট সর্বনামের ব্যাপারে সতর্ক থাকবেন। আপনি যদি এগুলোর মধ্যে
  কোনো অব্যক্তিগত সর্বনাম ব্যবহার করেন, তাহলে আপনাকে নিশ্চিত হতে হবে যে বাক্যে "কীসের?", "কোনটির?", বা "কী হিসাবে?" মতো করে আপনি উত্তর দিচ্ছেন।
    - সব, অন্য, যে কোনো
    - প্রতিটি, হয় এটা
    - কিছু, অনেক, দুটোই নয়, কোনোটাই নয়,
    - এক, অন্যান্য
    - একই, একাধিক, কিছু, এরকম
    - সেটা, সেগুলো, এগুলো, ওইগুলো

### দ্রুত এবং সংক্ষিপ্ত হওয়া {#being-swift-and-concise}

- ডকুমেন্টেশন তখনই শক্তিশালী এবং অর্থপূর্ণ হয়ে ওঠে, যখন প্রয়োজনীয় শব্দ এবং সঠিক বাগধারা ব্যবহার করা হয়।
  - সম্ভব হলে, সাধারণ ও সুপরিচিত শব্দ ব্যবহারের চেষ্টা করুন।
  - কঠিক বা জাঁকজমকপূর্ণ ভাষা এবং সাহিত্যিক বাগধারা ব্যবহার এড়িয়ে চলুন।
  - অর্থহীন ভাষা, অতি চলতি ভাষা এবং হেঁয়ালি এড়িয়ে চলুন।
  - ক্রিয়া-বিশেষণ এবং কোনো বিষয়ে নিজস্ব মতামত প্রদান করা এড়িয়ে চলুন। উদাহরণস্বরূপ, এমন শব্দ এবং বাক্যাংশ ব্যবহার করবেন না, যার মধ্যে "সহজে", "দ্রুত", "সহজ", "তাড়াতাড়ি" অন্তর্ভুক্ত থাকে। যদি প্রয়োজন হয়, তাহলে অতিরঞ্জিত করার বদলে, যতটুকু প্রয়োজন, ততটুকু বলুন।
  - এমন বাক্যাংশ ব্যবহার করবেন না, যা থেকে অস্পষ্টতা তৈরি হয়। যেমন, "যখন এই রিলিজটি হবে..." বলার পরিবর্তে
  "এই রিলিজটি লাইভ হওয়ার পরে..." ব্যবহার করুন।
  - শব্দ বেছে নেওয়ার ব্যাপারে অতিরিক্ত মনোযোগ দিন। "কারণ" (কারণ ও ফলাফল ইঙ্গিত করে) ব্যবহারের পরিবর্তে "থেকে"
  (একটি নির্দিষ্ট সময়কে ইঙ্গিত করে) বা "পরে" (প্রতিবার) ব্যবহারের পরিবর্তে "একবার" (শুধু একবার) ব্যবহার করা
  বেছে নিন।
  - বিস্ময়বোধক চিহ্ন এড়িয়ে চলুন।
- অপ্রয়োজনীয় শব্দ বা বাক্যাংশ যোগ করা এড়িয়ে চলুন। উদাহরণস্বরূপ:
  - "এবং তারপর" বলার বদলে শুধুমাত্র "তারপর" ব্যবহার করুন।
  - "এটা করার জন্য" বলার বদলে শুধুমাত্র "এটার জন্য" ব্যবহার করুন।
  - "পাশাপাশি হিসাবে" বলার বদলে শুধুমাত্র "এবং" ব্যবহার করুন।
  - "এর মাধ্যমে" বলার বদলে একটি উপযুক্ত বাংলা বিকল্প যেমন "ব্যবহার", "মাধ্যমে" বা "দ্বারা" ব্যবহার করুন।
- একটি কথোপকথনমূলক টোন ব্যবহার করুন যা খুব আনুষ্ঠানিক নয়, তবুও পেশাদার।
- স্পষ্টতা: যেখানে সম্ভব শব্দ বা বাক্যাংশকে প্রাণবন্ত করে তুলুন। উদাহরণস্বরূপ:
  - "যেমন" বলার বদলে "উদাহরণস্বরূপ" ব্যবহার করুন।
  - "অর্থাৎ" বলার বদলে "এটার মানে" ব্যবহার করুন বা অতিরিক্ত কিছুর প্রয়োজন ছাড়াই বাক্যটির অর্থকে স্পষ্ট করে তুলতে
  সেটি আবার নতুন করে অন্যভাবে লিখুন।
  - "ইত্যাদি" বলার বদলে "এবং তাই" ব্যবহার করুন বা কন্টেন্টকে এমনভাবে সংশোধন করুন যেন এই জাতীয় শব্দ ব্যবহার করতে না হয়। উদাহরণের তালিকা শেষ করতে
  "ইত্যাদি"-এর পরিবর্তে একটি বা দুটি উদাহরণের উপরে জোর দিন এবং "যেমন" বা "এটার মতো" ব্যবহার করুন।
  - "সতর্কতা"-এর পরিবর্তে “নোটিশ”, "সাবধানতা", বা "সতর্কীকরণ"-এর মতো উপযুক্ত বাংলা বিকল্প শব্দ ব্যবহার করুন।
  - সংকোচন করলে ডকুমেন্টেশনটি আরও কথোপকথনমূলক বলে মনে হয়-অন্তত যারা ইংরেজী বলেন, তাদের ক্ষেত্রে। সংকোচন ব্যবহারের সময় এবং কারণ সম্পর্কে সচেতন থাকবেন।

## কাঠামো {#structure}

ডকুমেন্টগুলো একটা বিভাগে সংগঠিত হতে হবে। প্রতিটি বিভাগ থেকে একটি থিম বা বিষয় পেশ করতে হবে। প্রতিটি বিভাগের মধ্যে, একটি বা একাধিক অনুচ্ছেদ থাকবে।
প্রতিটি অনুচ্ছেদে শুধুমাত্র একটি বিষয়ই থাকতে পারবে। একাধিক বিভাগে, একই বিষয়ের পুনরাবৃত্তি এড়িয়ে চলুন
এবং একাধিক বিষয়বস্তু থাকা অনুচ্ছেদগুলো বিভক্ত করে দিন।
অনুচ্ছেদটি যে কী বিষয়ে, পাঠক যেন প্রথম বাক্য থেকেই তা বুঝতে পারেন।

## প্রোডাক্ট ডকুমেন্টেশন {#product-documentation}

আপনি যদি কোনো নির্দিষ্ট প্রোডাক্টের ব্যাপারে লেখেন, তাহলে নিশ্চিত করুন যে ডকুমেন্টটি থেকে যেন সেই প্রোডাক্টটি বোঝা যায়। আগের Polygon ডকুমেন্টেশন সর্বজনীন এবং Polygon PoS ভিত্তিক ছিল।
তবে এখন যেহেতু Polygon-ভিত্তিক একাধিক প্রোডাক্ট আছে, তাই অবদানকারীদের নিজেদের সংযোজন সম্পর্কে সতর্ক থাকতে হবে

উদাহরণস্বরূপ, "## ব্যবহার করে Polygon-এ একটি স্মার্ট চুক্তি ডিপ্লয় করা" একটি অস্পষ্ট বাক্য। যদি এই টিউটোরিয়ালে
Polygon PoS-এর কথা উল্লেখ করা হয়, তাহলে সেটা স্পষ্ট হতে হবে, যেমন "### ব্যবহার করে Polygon PoS-এ একটি স্মার্ট চুক্তি ডিপ্লয় করা।" Polygon Hermez এর মতো Polygon Rollup এর ক্ষেত্রে
একই উদাহরণ ব্যবহার করুন, "### ব্যবহার করে Polygon Hermez-এ একটি স্মার্ট চুক্তি ডিপ্লয় করা"।

সাধারণ গাইড হোক বা টিউটোরিয়াল, নিশ্চিত করুন যে প্রোডাক্ট ডকুমেন্টেশন যেন সঠিক প্রোডাক্ট ডকুমেন্টেশন হাবে যোগ করা থাকে। বেশিরভাগ ডকুমেন্টের ক্ষেত্রে একটি সাধারণ হাবের নিচে সেগুলোর রেফারেন্স থাকে (যেমন "ডেভেলপ" বা "যাচাইকরণ"), তবে প্রকৃত ডকুমেন্টটি এটির প্রোডাক্ট ডকুমেন্টেশনের নিচে থাকবে। হাবে ডকুমেন্ট রেফারেন্সের জন্য আপনাকে `sidebars.js` যোগ করতে হবে।
তবে প্রকৃত ডকুমেন্টটি এটির সংশ্লিষ্ট প্রোডাক্ট ডকুমেন্টেশন হাবে থাকবে,
এবং ইউজার এটায় ক্লিক করলে এটি তাকে রিডিরেক্ট করবে। অধিকাংশ ডকুমেন্টের ক্ষেত্রে একই গাইডলাইন
প্রযোজ্য হবে। একটি সাধারণ হাবের নিচে তাদের রেফারেন্স থাকতে হবে, তবে প্রকৃত ডকুমেন্ট এটির প্রোডাক্ট ডকুমেন্টেশনের নিচে থাকবে।

টিউটোরিয়ালে উল্লিখিত API ব্যতিরেকে, Polygon Wiki-তে থাকা প্রায় সব API-ভিত্তিক ডকমেন্টেশন রেফারেন্স ডকুমেন্টেশন হিসেবে রয়েছে।
যেমন, Matic.js এর API ডকুমেন্টেশন API-এর প্রতিটি ফাংশন বা পদ্ধতির
কাঠামো, প্যারামিটার বা রিটার্ন ভ্যালু বিষয়ক তথ্যাবলী প্রদান করে।

## API ডকুমেন্টেশন {#api-documentation}

একটি API ডকুমেন্টেশন করার সময় নিচের বিষয়গুলো বিবেচনায় রাখুন:

* একটি জোরালো ভূমিকা যা একটি প্রারম্ভিক পয়েন্ট প্রদান করে।
* কল বা অনুরোধের একটি স্পষ্ট বর্ণনা। বর্ণনা করুন যে এন্ডপয়েন্ট কী করে।
* একটি সম্পূর্ণ প্যারামিটারের তালিকা:
  * প্যারামিটারের ধরন
  * উপলভ্য প্যারামিটার দেখানো প্লেসহোল্ডার সহ সিনট্যাক্স এক্সপ্রেশন
  * বিশেষ ফরম্যাটিং
* একাধিক ভাষার জন্য কোডের উদাহরণ।
* প্রত্যাশিত আউটপুট সহ একটি নমুনা কল।
* ত্রুটির কোড। এজের ক্ষেত্রে।
* যদি প্রয়োজন হয় তবে API কী কীভাবে নেবেন সে বিষয়ে নির্দেশাবলী।
* প্রায়শই জিজ্ঞাসিত প্রশ্নাবলী বা সাধারণ ব্যবহারিক ক্ষেত্রের উল্লেখ বেশিরভাগ ক্ষেত্রেই সাহায্যকারী হয়ে থাকে।
* সোশ্যাল মিডিয়া পোস্ট, ব্লগ বা ভিডিও কন্টেন্টের মতো অতিরিক্ত রিসোর্সের লিঙ্ক।
