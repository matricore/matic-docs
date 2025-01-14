---
id: faq
title: คำถามที่พบบ่อย
description: FAQที่เกี่ยวกับ Polygon
keywords:
  - docs
  - matic
  - polygon
  - faq
image: https://wiki.polygon.technology/img/polygon-wiki.png
---

# คำถามถามบ่อย {#frequently-asked-questions}

## Polygon คืออะไร {#what-is-polygon}

Polygon คือโซลูชั่นการเลื่อนสำหรับบล็อกแบบสาธารณะ โดยเฉพาะอีthereumPolygon ให้ตัวชั่ง ในขณะที่มั่นใจว่าประสบการณ์ผู้ใช้ที่เหนือกว่าในลักษณะที่ปลอดภัยและถอดรหัสได้มีการดำเนินการการทำงานสำหรับ Ethereum บน Kovan TesnetPolygon ตั้งใจจะรองรับโซ่นายอื่นในอนาคต ซึ่งจะช่วยให้เราสามารถจัดเตรียมคุณสมบัติการทำงานร่วมกันพร้อมกับการปรับระดับให้กับเครือข่ายบล็อกติดต่อกันที่มีอยู่

## Polygon แตกต่างจากการนำ Plasma มาใช้รูปแบบอื่นๆ อย่างไร {#how-is-polygon-different-from-other-implementations-of-plasma}

การดำเนินการของโพลีกอนถูกสร้างขึ้นบนอีเคอินแบบอิงจากสถานะที่ทำงานบน อีเวนต์ ในขณะที่การใช้งานอื่นๆ ของ Plasma ใช้ UTXO โดยหลักซึ่งจำกัดการเหล่านี้ให้เจาะจงการชำระเงินด้วยการมีอิเลคเชน แบบอิงแบบStateช่วยให้Polygon สามารถจัดเตรียมตัวปรับขนาดสำหรับสัญญาแบบอัจฉริยะทั่วไปเช่นกัน

ประการที่สอง Polygon ใช้ชั้นเช็คโดยสาธารณะซึ่งเผยแพร่ เช็คพอยต์หลังจากช่วงเวลาที่ใช้ระยะเวลา (ไม่เหมือนเช็คพอยต์หลังจากทุกบล็อกใน Plasma Cash) ช่วยให้ระบบภายในทำงานด้วยความเร็วสูงในขณะที่พิมพ์เช็คพอยต์ในแบตเช็คพอยต์เหล่านี้พร้อมกับตัวพิสูจน์ความสำเร็จการฉ้อโกง ทำให้มั่นใจว่า Eechin sidechains ของ Polygon ทำงานในลักษณะที่ปลอดภัย

## โปรเจกต์ของคุณมอบความสามารถในการปรับขนาดให้กับ Ethereum โดยใช้เชน Plasma ซึ่งเป็นโปรโตคอลหรือบล็อกเชนดั้งเดิมของตัวเองหรือไม่ {#your-project-provides-scalability-for-ethereum-using-plasma-chains-is-it-a-protocol-or-a-native-blockchain-in-itself}

เครือข่าย Polygon คือโซลูชั่น **"sidechain "** ซึ่งสินทรัพย์เชน Ethereum คือ อุปกรณ์ dApps / Tokens / Protocol ของเชนหลักสามารถย้าย/ย้ายไปยัง Polygon sidechain และเมื่อจำเป็น ก็จะสามารถถอนสินทรัพย์กลับคืนสู่เชนหลัก

## ข้อดีการแข่งขันของ Polygon เหนือคู่แข่งคืออะไร? {#what-are-the-competitive-advantages-of-polygon-over-its-competitors}

### โซลูชันการปรับขนาด L2 {#l2-scaling-solutions}

Polygon มุ่งมั่นที่จะทำให้การปรับขนาดด้วยการทำงานแบบไม่มีตัวกลางบรรลุผลสำเร็จPolygon ใช้เช็คพอยต์และหลักฐานพิสูจน์การฉ้อโกงเป็นระยะๆเมื่อผู้ใช้ต้องการถอนสินทรัพย์ของตน จะใช้เช็คพอยต์เพื่อพิสูจน์สินของตนบน sidechain ในขณะที่จำเป็นต้องมีการพิสูจน์ความถูกต้องในการฉ้อโกงเพื่อท้าทายการฉ้อโกงหรือพฤติกรรมที่ไม่ดีและสแต็คเกอร์สแลช

โครงการอื่น ๆ ยังนำเสนอโซลูชั่นการเลื่อนขยาย L2 แต่มีองค์ประกอบหลักสององค์ที่เราแตกต่างกัน:

1. ประการแรก Polygon จะมุ่งเน้นไปที่ธุรกรรมทางการเงิน นอกจากเกมและ dApps อื่นๆ ด้วยนอกจากนี้ เรายังมีแผนสำหรับบริการทางการเงินที่พังเต็มรูปแบบ เช่น dApps ที่ให้กู้ยืม/การเทรดแบบ Token Swaps, Margin และอื่น ๆ อีกมากมาย)

2. ประการที่สอง ในขณะที่ Polygon ใช้เช็คพอยต์สำหรับเวลาบล็อก 1 วินาที (พร้อมเลเยอร์ PoS ) โซลูชั่นอื่น ๆ อีกมากมายอาจมีช่วงบล็อกมากกว่าเวลาบล็อก Ethereum เนื่องจากคุณต้องผลักดันบล็อกทุกบล็อกของsidechain ไปยังเชนหลัก

### โซลูชันการปรับขนาด L1 {#l1-scaling-solutions}

นอกจากนี้ ท่ามกลางโครงการการเลื่อนอื่น ๆ Polygon จะโดดเด่นเนื่องจากความสามารถในการบรรลุระดับได้ ในขณะที่ยังคงระดับที่ดีของการเข้ารหัส

ที่สำคัญกว่า โครงการที่สามารถปรับขนาดเหล่านี้มีปัญหา "การสร้างล้อใหม่"โดยกำลังสร้างโซ่นุกรใหม่ที่ชุมชนผู้พัฒนา ระบบนิเวศ เอกสารทางเทคนิค และธุรกิจต้องสร้างจาก **"รอยขีดข่วน"**Polygon อีกข้างหนึ่งคือเชนที่รองรับ EVM และมีสินบน dApps / สินบน Ethereum ทั้งหมดที่มาพร้อมกับชั่วนิรันดร์ พร้อมใช้งานเมื่อคลิกปุ่ม

### การชำระเงิน {#payments}

เราเชื่อว่าโพล่งมีขอบในแง่ของการใช้งานเพราะในโซลูชั่นอื่น ทั้งผู้ส่งและผู้รับต้องสร้างช่องทางการชำระเงินของตนซึ่งเป็นเรื่องยุ่งยากมากๆ สำหรับผู้ใช้ในขณะที่เทคโนโลยีพื้นฐานของ Polygon นั้นไม่มีข้อกำหนดของช่องทางการชำระเงินสำหรับผู้ใช้ และพวกเขาต้องการเพียงที่อยู่ Ethereum ที่ถูกต้องเพื่อรับโทเค็นเท่านั้นสิ่งนี้สอดคล้องกับวิสัยทัศน์ระยะยาวของเราในการปรับปรุงประสบการณ์ผู้ใช้สำหรับแอปพลิเคชันแบบไม่มีตัวกลาง

### การซื้อขายและการเงิน {#trading-and-finance}

Polygon ตั้งใจที่จะเปิดใช้งานไลบรารีของ DEX (เช่น 0x) สภาพคล่อง, เลียบแบบเหลว (เช่น เครือข่าย Kyber ) และโปรโตโตคอลทางการเงินประเภทอื่นๆ เช่น โพรโทโทคอล Dhala บนแพลตฟอร์มซึ่งจะทำให้ผู้ใช้ Polygon สามารถเข้าถึงแอปพลิเคชัน Serverage แบบหลากหลายเช่น DEXs, dp LPs และอื่นๆ อีกมากมาย

## Polygon จะเปรียบเทียบกับโซลูชันการเชื่อมต่อแบบอื่นได้อย่างไร {#how-does-polygon-compare-with-other-sidechain-solutions}

บน Polygon ธุรกรรมทั้งสองจะปลอดภัยด้วยกลไกหลายประการบน sidechain และเชนหลักบนsidechain ธุรกรรมใด ๆ ที่ทำโดยชั้นผู้สร้างของ Block จะได้รับการตรวจสอบและเช็คพอยต์ไปยังเชนหลักโดยชั้นเช็คพอยต์แบบย่อยสูง

หากธุรกรรมการฉ้อโกงใด ๆ เกิดขึ้นบน sidechain จึงสามารถตรวจพบและจัดการได้โดยชั้นเช็คพอยต์แม้ในสถานการณ์ที่รุนแรงและไม่น่าเป็นไปได้สูงซึ่งชั้นผู้สร้างบล็อกรวมถึงชั้นเช็คพอยต์ทั้งสองแบบรวม แม้กระนั้นเชนหลักก็ยังมีตัวพิสูจน์การฉ้อโกงซึ่งใครจากสาธารณะสามารถมาและท้าทายธุรกรรมใด ๆ ที่พวกเขาลบหลู่ ๆ ในการฉ้อโกง บน sidechain

หากความท้าทายสำเร็จจะมีการปล่อยทางเศรษฐกิจ / การลงโทษทางการเงินไปยังพรรคการรวมตัวกันเนื่องจากเดิมพันของพวกเขาจะถูกล่วงลงนอกจากนี้ ผู้ท้าทายสาธารณะจะได้รับการตอบแทนด้วยเดิมพันที่บดขยี้ของตัวแสดงอีเคเฮนที่ฉ้อโกง

ซึ่งทำให้ Polygon เป็นเครือข่าย sidechain แบบประหยัดซึ่งมีระดับสูง ของการถอดรหัสและระบบความปลอดภัยของธุรกรรม sidechain

นอกจากนี้ ความจุและ TPS ของ Polygon ยังสูงกว่าโซลูชั่นอื่นโดยเฉพาะเมื่อ Polygon สามารถมี ธุรกรรมนับพันๆ ในขณะที่ตัวอื่นๆ เป็น Eechin sidechin เดียว ซึ่งมีขีดจำกัดสูงกว่าการโอนหลายพันรายการ

## เพิ่มเซเดเควินใหม่ด้วยหลักการอะไร?จะมีข้อกำหนดพิเศษสำหรับเซอรินภายในของบริษัทส่วนตัวหรือไม่ {#via-what-principles-will-new-sidechains-be-added-will-there-be-any-special-requirements-for-private-companies-local-sidechains}

เมื่อเทียบกับ State Channel แล้ว Plasma เป็นทางเลือกที่ดีกว่าสำหรับเฟรมเวิร์กด้านการปรับขนาด ส่วนใหญ่เกิดจากการรับประกันความปลอดภัยของเฟรมเวิร์ก ซึ่งโดยทั่วไปแล้วอาจกล่าวได้ว่าผู้ใช้จะไม่มีวันสูญเสียเงินทุนไม่ว่าในเหตุการณ์ใดๆ ก็ตามแน่นอนว่าอาจมีความล่าช้าในการรับเงินคืนบ้าง แต่ตัวดำเนินการ Byzantine Plasma ไม่สามารถสร้างเงินหรือทำธุรกรรมสองครั้งได้

Polygon จะพยายามเป็นโครงสร้างพื้นฐานด้านบล็อกเชนสาธารณะที่เปิดกว้างอย่างสมบูรณ์ในอนาคต โดยอาศัยมาตรการที่ก่อให้เกิดแรงจูงใจทางเศรษฐศาสตร์/มาตรการที่ลดแรงจูงใจทางเศรษฐศาสตร์เป็นตัวขับเคลื่อนการรักษาความปลอดภัยและความเสถียรของระบบเป็นหลักดังนั้นทุกคนควรที่จะสามารถเข้าร่วมระบบและมีส่วนร่วมในฉันทามติอย่างไรก็ตาม ในขั้นตอนการเลื่อนของเครือข่าย โดยเริ่มต้น Polygon จะต้องใช้บทบาทขนาดใหญ่เพื่อเปิดใช้งานsidechin

นอกจากนี้ sidechains ของ Polygon จะถือว่าเป็นระบบย่อยสำหรับสาธารณะโดยหลักคือ มีแผงข้างสำหรับทุกคนที่จะใช้เช่นเดียวกับบล็อกติดต่อกันแบบอื่น ๆอย่างไรก็ตาม เชน Polygon Enterprise จะตั้งใจที่จะให้ระบบเชื่อมต่อแบบเฉพาะตัว (เปิดใช้งานระบบป้องกันความเป็นส่วนตัว) สำหรับองค์กรเฉพาะการรักษาความปลอดภัยและการถอดรหัสของเชนดังกล่าวจะยังคงถูกเก็บรักษาไม่เหมือนเดิมโดยใช้เลเยอร์เช็คพอยต์และหลักฐานการฉ้อโกงบนเชนหลัก

## จะรวมผลิดอีเคอิน ด้วยโซ่หลัก (Ethereum) {#will-sidechains-also-be-synced-with-the-main-chain-ethereum}

แน่นอนชั้นเช็คอีเวนต์สาธารณะจะตรวจสอบการดำเนินการทั้งหมดที่เกิดขึ้นบนระบบ sidechain และเผยแพร่ตัวพิสูจน์อักษรไปยังเชนหลักเพื่อให้มั่นใจว่า การรักษาความปลอดภัยแบบโง่ของธุรกรรม sidechain สัญญาของเชนหลัก Plasma ประกอบด้วยพรูฟ Fraud ประเภทต่าง ๆ ที่สามารถท้าทายธุรกรรมของธุรกรรม Echain ใด ๆ สำหรับกิจกรรมการฉ้อโกงหากผู้ท้าชิงประสบความสำเร็จ เดิมพันของนักแสดงsidechain ที่เกี่ยวข้องกับการฉ้อโกงจะถูกเลื่อนและถูกส่งไปยังผู้ท้าทายซึ่งเทียบเท่ากับค่าบุคงของบั๊ก ที่ดำเนินการต่อไปแผนการที่ดีสำหรับการทำความเข้าใจคือด้านล่าง:

![ภาพหน้าจอ](/img/matic/Architecture.png)

## จะมีการนำเอารายการ "รูปแบบการใช้งานที่เป็นไปได้" ที่อยู่ตอนท้ายของเอกสารนำเสนอข้อมูล (White Paper) ไปใช้หรือไม่จะนำไปใช้ในลักษณะใด {#at-the-end-of-the-white-paper-there-is-a-list-of-potential-use-cases-will-all-of-that-be-implemented-in-what-order}

ตรกะพื้นฐาน คือ - หากมี dApp / Protocol ที่ทำงานบน Ethereum แต่ถูกจำกัดด้วยค่าผ่านธุรกรรมต่ำและค่าธรรมเนียมการทำธุรกรรมสูง จากนั้นเราจะสามารถเพิ่มการสนับสนุนสำหรับโพรโทคอล dApps / Protocol เหล่านี้บนเครือข่าย Polygon

## เหตุใดการทำสำเนาการนำ Plasma ของ Polygon ไปปรับใช้จึงเป็นเรื่องยาก {#why-will-it-be-difficult-to-replicate-polygon-s-plasma-implementation}

แม้ว่ามันจะเกี่ยวกับเอฟเฟกต์เครือข่ายในแง่ที่เครือข่ายสามารถปรับขนาด/ ขยายระบบนิเวศได้ดีกว่าระบบอื่นๆ การแก้ปัญหาบล็อกเชนต้องเป็นแหล่งเปิดเพราะเกี่ยวกับสินทรัพย์จริงที่ใช้โดยระบบนี้

เป็นกรณีที่มีโครงการโอเพนซอร์สทั้งหมดที่สามารถปรับใช้กับเราได้อย่างเท่าเทียมกัน เช่นเดียวกับการใช้งานของคู่แข่งรายอื่นๆ เนื่องจากเราจะได้รับใบอนุญาต GPL ซึ่งให้อำนาจแก่ใครก็ตามที่ได้นำเอาโอเพ่นซอร์สแบบบังคับไปใช้กับโค้ดของพวกเขาแต่อีกครั้ง จุดคือการคัดลอกโค้ดจะใช้ได้แม้กับ Bitcoin, Ethereum และโครงการอื่น ๆ ก็เพิ่มเติมเกี่ยวกับเอฟเฟกต์เครือข่ายที่โครงการหนึ่งสามารถบรรลุได้

## สิ่งที่พิเศษเกี่ยวกับการนำ Plasma ของเครือข่าย Polygon ไปปรับใช้คืออะไร {#what-s-special-about-polygon-network-s-plasma-implementation}

Plasma ใช้ระบบแบบแบบอิงจากบัญชีมากกว่าระบบ UTXOซึ่งช่วยให้เราพร้อมประโยชน์อย่างมากในการใช้ EVM บนเชน Polygon ซึ่งช่วยให้เราสามารถใช้ระบบนิเวศ Ethereum ทั้งหมดเครื่องมือนักพัฒนาไลบรารีการรวม, ฯลฯ สำหรับเครือข่าย Polygon

ใช้เครือข่าย Polygon โดย dApps ได้โดยไม่ต้องมีการเปลี่ยนแปลงใด ๆ กับโทเค็น ERC20นอกจากนี้ ชั้นชี้ของเราก็บอกให้เราได้รับคำสั่งของ Magitites เร็วกว่าการใช้งานอื่นๆ ของ Plasma เพราะเราจะจัดเตรียมตัวป้องกันบล็อกแต่ละตัวในเช็คพอยต์ ในขณะที่การใช้งานอื่นๆ ของ Plasma จะต้องส่งหลักฐานแต่ละบล็อกไปยังเชนหลัก

## คุณจะแก้ปัญหาเรื่องการทำงานแบบมีตัวกลางอย่างไร {#how-are-you-going-to-solve-the-issues-with-centralization}

นี่คือไดอะแกรมที่จะให้บริบทบางส่วนแก่คุณ:

![ภาพหน้าจอ](/img/matic/Merkle.png)

ดังนั้นโหนด PoA จะกลายเป็น Delegates (ด้วย Proof of Solvency i.e จึงต้องฝากจำนวนการเดิมพัน) และ KYC ที่เลือกโดยชั้นของ PoS เหมือนกับ EOS Deled Proof of Stake (DPoS) หรือโหนด Besentine Fault Tolerance (DBFT)

ประการที่สอง, ให้สมมติทั้งหมดของ Delegates (หรือ 2/3) เปลี่ยนนักแสดงที่ไม่ดีและสร้างบล็อกที่ผิดพลาด, จากนั้นคุณมีตัวทำความสะอาดชั้นของ PoS ที่จะตรวจสอบบล็อกทั้งหมดและหากมีการทุจริตใด ๆ มีการเลื่อนลง และเช็คจะหยุดสำหรับการกระทำการแก้ไขปัญหา

ประการที่สามให้บอกว่าแม้เลเยอร์ Stainker PoS (ซึ่งจะเป็นโหนดจำนวนมาก) ก็จะเปลี่ยนการทรยศและชนเพื่อสร้างเช็คพอยต์ที่ผิดพลาด คือ PoA ทั้งหมดจะเสียหายถึงกระนั้นก็ตาม ตามปรัชญาพลาสมาเรากำลังเขียนหนึ่งในสิ่งที่โลภของการปรับขนาดไซต์ **ตัวพิสูจน์ความถูกต้อง**ที่ถูกดูโดยโครงการขนาดใหญ่มากมาย (สามารถดูตัวเฝ้าระวังได้โดยตัวเฝ้าระวังยามสามารถเห็นได้ว่าตัวเฝ้าระวังการจัดเก็บของเราบน GitHub)กลไกการพิสูจน์การฉ้อโกงนี้ช่วยให้ใครในที่สาธารณะเพื่อท้าทายธุรกรรมใด ๆ บนเชนหลัก Ethereum

## ทำไมถึงต้องใช้โทเค็น MATIC {#why-is-matic-token-required}

เหตุผลต่อไปนี้เสริมความจำเป็นในการมีโทเค็น MATIC :

### Polygon ตั้งใจจะเน้นว่าเป็นโซลูชั่นการเลื่อนแบบวัตถุประสงค์ทั่วไปสำหรับบล็อกสาธารณะ {#polygon-intends-to-be-a-general-purpose-scaling-solution-for-public-blockchains}

เรากำลังเริ่มต้นบน Ethereum เนื่องจากบาเซชีนตัวแรกของเรา แต่ใน Polygon สามารถนำไปใช้งานบนบาเซคาอินได้หลายแบบโดยจะมีการเพิ่มเชนพื้นฐานอื่นๆ ในไม่ช้า ดังนั้นจึงไม่สมเหตุสมผลที่จะมีการใช้สกุลเงินเพียงสกุลเดียว (Ether) สำหรับการจ่ายค่าธรรมเนียมในไซด์เชนหากมีความกังวลที่มีอยู่เกี่ยวกับอนาคตของ Basechains โดยมี Basechain ซึ่งเป็นสินทรัพย์แบบดั้งเดิมสำหรับ Polygon จะทำให้เครือข่ายการเลื่อนหลุดดังนั้นจึงเป็นสิ่งสำคัญที่จะต้องสร้างระบบนิเวศสำหรับผู้วาง Stake บนโทเค็นเครือข่ายของ Polygon

### รุ่นการรักษาความปลอดภัย Appcoin {#appcoin-security-model}

Polygon ตั้งใจที่จะให้ DApp จ่ายค่าธรรมเนียมของ Polygon ได้ใน DApp-coin โดยการสรุปกลไกการแลกเปลี่ยนโทเค็นโดยใช้ Liquidity Pool อย่าง Kyberผู้ใช้ใช้ดีพีเหรียญเพื่อจ่ายค่าธรรมเนียมโดยทั่วไปแล้ว โดยจะแลกเปลี่ยนสำหรับโทเค็นของ MATICดังนั้นนักพัฒนา DApp ที่ต้องการมอบประสบการณ์การใช้งานที่ราบรื่นจะช่วยคง Liquidity Pool ของ Polygon เอาไว้ได้

### การตั้งค่าเครือข่ายในขั้นตอนถัดไป {#seeding-the-network-in-nascent-stages}

แทบจะเป็นไปไม่ได้เลยที่จะสร้างระบบเมื่อมีธุรกรรมในเครือข่ายตอนเริ่มต้นเพียงเล็กน้อยหรือไม่มีเลย เนื่องจากเราไม่สามารถแจกจ่าย Eth ไปยังเลเยอร์ตัวตรวจสอบความถูกต้องที่มีการทำงานแบบไม่มีตัวกลางสูงและผู้สร้างบล็อกได้ในขณะที่ใช้โทเค็น MATIC เราได้จัดเตรียมโทเค็นจำนวนมากเพื่อแจกจ่ายออกไปเพื่อเพิ่มผู้สร้างบล็อก, Stake ตัวสร้างเช็คพอยต์ และเสนอรางวัลในการสร้างบล็อกในภายหลังการจัดเตรียมสิ่งนี้ก็เพื่อให้มั่นใจว่า ผู้วาง Stake จะได้รับรางวัลแม้ว่าเครือข่ายจะใช้เวลาพอสมควรกว่าจะได้รับผลจากเครือข่ายซึ่งคล้ายกับเหตุผลที่ว่าทำไมจึงมีการเก็บรางวัลการสร้างบล็อกไว้สำหรับ Bitcoin ผู้วาง Stake และผู้สร้างบล็อกจะได้รับผลตอบแทนในลักษณะเดียวกันนี้ที่จะทำให้เครือข่ายปลอดภัย

หากความกังวลของคุณเกี่ยวกับผู้พัฒนา หนึ่งในเสาหลักของกลยุทธ์ของเราคือการทำให้อุปสรรคในการเริ่มต้นสำหรับผู้พัฒนาต่ำมากๆเราได้ทำให้แน่ใจว่าเครื่องมือสำหรับผู้พัฒนา Ethereum ทั้งหมดใช้งานได้ทันทีบน Polygonในแง่ของโทเค็นที่จำเป็นสำหรับค่าธรรมเนียมการจ่ายบน temnet จึงไม่แตกต่างกันสำหรับการสร้างผู้พัฒนาบน Ethereumdev ได้รับโทเค็นฟรีสำหรับเช็คเน็ตจากก๊อกน้ำ Polygon เช่นเดียวกับที่อยู่ในอีthereumคุณต้องใช้โทเค็นสำหรับ MATIC เฉพาะเมื่อคุณต้องการปรับใช้บน Polygon Manet โดยอัตโนมัติ ค่าแก๊สจะต่ำกว่า Ethereum ประมาณ 1/100 ของค่าธรรมเนียมธุรกรรมคุณจะจ่ายบน Ethereum

## ตัวขับเคลื่อนการใช้งานและความต้องการโทเค็น MATIC คืออะไร {#what-drives-the-use-and-demand-for-matic-tokens}

โทเค็นมีการใช้งานหลักๆ 2 ประการ:

1. ใช้โทเค็นเพื่อจ่ายค่าธรรมเนียมการทำธุรกรรมในเครือข่าย
2. โทเค็นใช้สำหรับการเดิมพันเพื่อเข้าร่วมกลไถนาวของ Sake สำหรับชั้นเช็คและชั้นการผลิตบล็อก.

### เหตุผลที่สองสำหรับความต้องการโทเค็น {#some-of-the-secondary-reasons-for-token-demand}

* เครือข่าย Polygon ตั้งใจที่จะให้ DApp จ่ายค่าธรรมเนียมของ Polygon ได้ใน DApp-coin โดยการสรุปกลไกการแลกเปลี่ยนโทเค็นโดยใช้ Liquidity Pool อย่าง Kyberผู้ใช้ใช้ดีพีเหรียญเพื่อจ่ายค่าธรรมเนียมโดยทั่วไปแล้ว โดยจะแลกเปลี่ยนสำหรับโทเค็นของ MATICดังนั้นนักพัฒนา DApp ที่ต้องการมอบประสบการณ์การใช้งานที่ราบรื่นจะช่วยคง Liquidity Pool ของ Polygon เอาไว้ได้

* เพื่อเปิดใช้งานทางออกที่เร็วกว่า เรากำลังใช้กลไกการกู้ยืมโดยใช้โพรโทคอล Dhala โดยตัวส่งสามารถรับโทเค็นแบบออกและสามารถจ่ายจำนวนออกจากระบบด้วยค่าธรรมเนียมขนาดเล็กเพื่อเป็นค่าใช้จ่ายผู้ให้กู้จะอ้างสิทธิ์ในโทเค็นหลังจากผ่านไปหนึ่งสัปดาห์โดยใช้ Exit-Tokenผู้ใช้จึงแทบจะถอนได้ทันทีในขณะที่ผู้ให้กู้สามารถรับดอกเบี้ยสำหรับบริการที่พวกเขาให้

### การเบิร์นโทเค็นระดับโปรโตคอล {#protocol-level-burning-of-tokens}

เราตั้งใจจะเผาเปอร์เซ็นต์ของค่าธรรมเนียมการทำธุรกรรมในทุกบล็อกซึ่งทำให้โทเค็นส์ภาวะเงินฝืดในธรรมชาติ และให้การสนับสนุนอย่างสม่ำเสมอในแง่ของค่าที่เลเวลของโพรโทคอล

### อุปสรรคในการเริ่มต้นต่ำ (จึงมีโอกาสในการนำไปใช้อย่างรวดเร็วที่สูงกว่า) {#low-entry-barrier-and-hence-higher-chances-of-quick-adoption}

เราจะพึ่งพา DApp อย่างมากในการสร้างการยอมรับของผู้ใช้หนึ่งในคุณสมบัติที่สำคัญคือ เรารักษาสถาปัตยกรรมซึ่งเข้ากันได้กับ ระบบนิเวศ พัฒนา Ethereum ทั้งหมด คือสัญญาสมาร์ท, กระเป๋าสตางค์ , IDEs, เครื่องมือ DevOps อื่นๆ เข้ากันได้โดยตรงกับ Polygon

ย้าย DApp ใดๆ ของ Ethereum ไปยัง Polygon ได้โดยแทบไม่มีการเปลี่ยนแปลงที่สำคัญดังนั้นอุปสรรคในการเข้าสำหรับนักพัฒนา Ethereum ที่มีอยู่เพื่อเปลี่ยนเป็น Polygon จึงเป็นการลบซึ่งสามารถเริ่มตัวจัดการแบบ dApp ได้ซึ่งจะมีศักยภาพในการนำอุปสงค์อินทรีย์จำนวนมากเนื่องจากเอฟเฟกต์เครือข่ายที่สร้างรอบเครือข่าย Polygon

## เป็นโทเค็นประเภท ERC20 ใช่ไหม {#is-token-type-erc20}

รองรับและโทเค็นเดียวกันจะใช้กับเชน Polygon ด้วย เช่น ไม่จำเป็นต้องย้ายไปยังโทเค็นดั้งเดิมในอนาคต

## TPS ที่คาดหวังไว้ที่คุณสามารถนำไปใช้กับเครือข่าย Ethereum ได้คืออะไรตอนนี้คุณกำลังใช้งานอะไรบน Testnet {#what-is-the-expected-tps-you-ll-be-able-to-bring-to-the-ethereum-network-what-are-you-running-at-now-on-testnet}

sidechain เดี่ยวมีความสามารถของ 7,000+ ต่อวินาทีPolygon มีขีดความสามารถในการเพิ่มระบบย่อยอัตโนมัติ แต่ปัจจุบัน โฟกัสของเราจะอยู่ในการรักษาความมั่นคงของเครือข่ายด้วยอีโคอิน หนึ่งด้าน
