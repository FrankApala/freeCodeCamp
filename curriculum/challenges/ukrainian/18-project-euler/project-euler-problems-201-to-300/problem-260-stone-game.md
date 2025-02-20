---
id: 5900f4701000cf542c50ff83
title: 'Завдання 260: гра в камені'
challengeType: 1
forumTopicId: 301909
dashedName: problem-260-stone-game
---

# --description--

В гру грають двоє гравців, використовуючи три купи каменів.

На кожному ході гравець забирає один або кілька каменів з купи. Проте, якщо гравець бере камені з більше, ніж однієї купи, то з кожної вибраної купи необхідно забрати однакову кількість каменів.

Інакше кажучи, гравець обирає $N > 0$ каменів і забирає:

- $N$ камені з будь-якої купи; або
- $N$ камені з кожної з двох куп ($2N$ загалом); або
- $N$ камені з кожної з трьох куп ($3N$ загалом).

The player taking the last stone(s) wins the game.

A winning configuration is one where the first player can force a win.

For example, (0,0,13), (0,11,11) and (5,5,5) are winning configurations because the first player can immediately remove all stones.

A losing configuration is one where the second player can force a win, no matter what the first player does.

For example, (0,1,2) and (1,3,3) are losing configurations: any legal move leaves a winning configuration for the second player.

Consider all losing configurations ($x_i$,$y_i$,$z_i$) where $x_i ≤ y_i ≤ z_i ≤ 100$. We can verify that $\sum (x_i + y_i + z_i) = 173\\,895$ for these.

Find $\sum (x_i + y_i + z_i)$ where ($x_i$,$y_i$,$z_i$) ranges over the losing configurations with $x_i ≤ y_i ≤ z_i ≤ 1000$.

# --hints--

`stoneGame()` має повернути `167542057`.

```js
assert.strictEqual(stoneGame(), 167542057);
```

# --seed--

## --seed-contents--

```js
function stoneGame() {

  return true;
}

stoneGame();
```

# --solutions--

```js
// solution required
```
