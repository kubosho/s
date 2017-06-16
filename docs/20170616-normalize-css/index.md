# 5分で分かるnormalize.cssの周辺

[kubosho_](https://github.com/kubosho_)

-----

## 自己紹介代わりに最近書いた本

![Reset CSSフレンズ](img/reset-css-friends.jpg)

[https://o2p.booth.pm/items/504599](https://o2p.booth.pm/items/504599)

-----

## そもそもの前提

- normalize.cssの方向性は6年間安定している
- normalize.cssは大変革を望んでいない
- [https://github.com/necolas/normalize.css/issues/664#issuecomment-298708485](https://github.com/necolas/normalize.css/issues/664#issuecomment-298708485)

-----

## normalize.css v6.0.0

- [https://github.com/necolas/normalize.css/pull/649](https://github.com/necolas/normalize.css/pull/649)
- 全ての私見的なスタイルが削除された
- [Bootstrapがnormalize.cssからRebootへ移行する一因になった](https://github.com/twbs/bootstrap/issues/21740)

-----

## ownerのNicolasはv6.0.0の変更は間違いと認める

> I think the move to prioritize philosophical purity over practically in v6 has been a mistake. Removing `body { margin: 0 }` is baffling and inconvenient
[https://github.com/necolas/normalize.css/issues/664#issuecomment-291207159](https://github.com/necolas/normalize.css/issues/664#issuecomment-291207159)

-----

## Nicolasの立ち位置

- 実用性のほうが純粋性に比べて勝る（なのでbodyに既定で宣言されている8pxは実用的ではない）
- [https://github.com/necolas/normalize.css/issues/664#issuecomment-291220318](https://github.com/necolas/normalize.css/issues/664#issuecomment-291220318)

-----

## issue上で喧嘩

- [https://github.com/necolas/normalize.css/issues/664](https://github.com/necolas/normalize.css/issues/664)

-----

## Nicolas怒りのrevert

- [https://github.com/necolas/normalize.css/commit/b4a8fdaf8321093b1e3cad612fb76cf2b7d3275d](https://github.com/necolas/normalize.css/commit/b4a8fdaf8321093b1e3cad612fb76cf2b7d3275d)

-----

## Jonathanの不穏な行動

- [jonathantneal/postcss\-normalize: Use the parts of normalize\.css you need from your browserlist](https://github.com/jonathantneal/postcss-normalize)
- [Transfer repository · Issue \#10 · jonathantneal/postcss\-normalize](https://github.com/jonathantneal/postcss-normalize/issues/10)

-----

## そして2つのv7.0.0が生まれた

- [https://github.com/jonathantneal/postcss-normalize/blob/master/lib/normalize.css](https://github.com/jonathantneal/postcss-normalize/blob/master/lib/normalize.css)
- [https://github.com/necolas/normalize.css/blob/master/normalize.css](https://github.com/necolas/normalize.css/blob/master/normalize.css)

-----

## Andreyの運命や如何に

> And @jonathantneal did this project postcss-normalize! @necolas what do you think if we add link to this project to Normalize.css README? I think your users will be happy to find more way to use Normalize.css.
[https://github.com/necolas/normalize.css/issues/679](https://github.com/necolas/normalize.css/issues/679)

-----

## Node.jsとio.jsとは違い喧嘩別れ

- 分かれたことによって何か前進するわけでもない
- 使う側としては2つのバージョンの差異を見ないといけないので混乱するだけ

-----

## まとめ

- Nicolas GallagherとJonathant Nealの方向性の違いから軋轢が生まれた
- Jonathant Nealはpostcss-normalizeのコミット履歴をなくしたり、v6ともnicolas版のv7と違うものをv7と言い張っている
- 自分はJonathant Nealを信用したくない