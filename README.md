# すえなみチャンス

```mermaid
sequenceDiagram
  participant エンジニア
  participant スタッフ
  participant すえなみさん
  participant 焼肉店
  loop 食事
    エンジニア ->> スタッフ: 注文
    スタッフ ->> エンジニア: 肉/伝票
  end
  エンジニア ->> すえなみさん: 伝票おねがいします
  すえなみさん ->> 焼肉店: 支払い
```

