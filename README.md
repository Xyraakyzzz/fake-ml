# fake-ml

![npm version](https://img.shields.io/npm/v/x-fake-ml)
![npm downloads](https://img.shields.io/npm/dm/x-fake-ml)
![license](https://img.shields.io/npm/l/x-fake-ml)

Fake Mobile Legends lobby card generator — support bot WA, Telegram, website, dan lainnya.

## Installation

```bash
npm install x-fake-ml
```

## Usage

```javascript
const generateCard = require('x-fake-ml')

const result = await generateCard({
  avatar: 'https://example.com/avatar.jpg',
  username: 'Kyxzz',
  rank: 'imo',
  border: 1
})

console.log(result)
// {
//   status: 'success',
//   code: 200,
//   avatar: 'https://example.com/avatar.jpg',
//   username: 'Kyxzz',
//   rank: 'imo',
//   border: 1,
//   result: '/path/to/123456.png'
// }
```

## Parameters

| Parameter  | Type   | Required | Default | Description |
|------------|--------|----------|---------|-------------|
| `avatar`   | string | No       | default | URL foto avatar |
| `username` | string | No       | Player  | Nama player (max 15 karakter) |
| `rank`     | string | No       | imo     | Nama rank |
| `border`   | number | No       | 0       | Nomor border (0 = outline default) |

## Available Ranks

| Rank | Key |
|------|-----|
| Epic | `epic` |
| Glory | `glory` |
| Grandmaster | `gm` |
| Honor | `honor` |
| Immortal | `imo` |
| Legend | `legend` |
| Mawi | `mawi` |

## Available Borders

| Border | Preview |
|--------|---------|
| 1 | ![Border 1](https://raw.githubusercontent.com/Xyraakyzzz/fake-ml/master/assets/border/1.webp) |
| 2 | ![Border 2](https://raw.githubusercontent.com/Xyraakyzzz/fake-ml/master/assets/border/2.webp) |
| 3 | ![Border 3](https://raw.githubusercontent.com/Xyraakyzzz/fake-ml/master/assets/border/3.webp) |
| 4 | ![Border 4](https://raw.githubusercontent.com/Xyraakyzzz/fake-ml/master/assets/border/4.webp) |
| 5 | ![Border 5](https://raw.githubusercontent.com/Xyraakyzzz/fake-ml/master/assets/border/5.webp) |
| 6 | ![Border 6](https://raw.githubusercontent.com/Xyraakyzzz/fake-ml/master/assets/border/6.webp) |
| 7 | ![Border 7](https://raw.githubusercontent.com/Xyraakyzzz/fake-ml/master/assets/border/7.webp) |
| 8 | ![Border 8](https://raw.githubusercontent.com/Xyraakyzzz/fake-ml/master/assets/border/8.webp) |
| 9 | ![Border 9](https://raw.githubusercontent.com/Xyraakyzzz/fake-ml/master/assets/border/9.webp) |
| 10 | ![Border 10](https://raw.githubusercontent.com/Xyraakyzzz/fake-ml/master/assets/border/10.webp) |
| 11 | ![Border 11](https://raw.githubusercontent.com/Xyraakyzzz/fake-ml/master/assets/border/11.webp) |
| 12 | ![Border 12](https://raw.githubusercontent.com/Xyraakyzzz/fake-ml/master/assets/border/12.webp) |
| 13 | ![Border 13](https://raw.githubusercontent.com/Xyraakyzzz/fake-ml/master/assets/border/13.webp) |
| 14 | ![Border 14](https://raw.githubusercontent.com/Xyraakyzzz/fake-ml/master/assets/border/14.webp) |
| 15 | ![Border 15](https://raw.githubusercontent.com/Xyraakyzzz/fake-ml/master/assets/border/15.webp) |
| 16 | ![Border 16](https://raw.githubusercontent.com/Xyraakyzzz/fake-ml/master/assets/border/16.webp) |

> Border 0 = outline default warna gold `#b8956f`

## License

MIT © [Kyxzz](https://github.com/Xyraakyzzz) 
