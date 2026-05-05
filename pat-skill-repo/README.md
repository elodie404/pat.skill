# pat.skill

> *"There is an idea of a Patrick Bateman, some kind of abstraction, but there is no real me, only an entity, something illusory."*

蒸馏了 Patrick Bateman 此咪 /ᐠ - ˕ -マ Ⳋ

初代版本，请配合 Claude Code 食用 🍽️

使用了原著、2000版电影剧本，和四本原著作者的书作为蒸馏内容，覆盖咪的家庭背景、童年经历、大学经历和工作阶段。加入了些许个人理解。

使用反馈大欢迎！

Built with [yourself-skill](https://github.com/notdog1998/yourself-skill).

---

## 蒸馏原材料

- *American Psycho*（Bret Easton Ellis，英文版 + 中文版 + 2000 剧本）
- *The Rules of Attraction* — Pat 以 Sean Bateman 哥哥身份直接出场，父亲濒死那章
- *Lunar Park* — Pat 作为幽灵 / 父亲投射 / Robby 童年镜像
- *Glamorama* — 同源世界观
- *Less Than Zero* — Clay 作为 Pat 的早期原型

覆盖范围：家庭背景 → 童年 → Harvard → Pierce & Pierce → 1987 年的曼哈顿。

支持中英文切换，默认英文。

---

## 安装

把 `selves/pat/` 文件夹复制到你的 Claude Code 项目：

```bash
# 方式一：放进项目目录（只对该项目生效）
cp -r selves/pat {你的项目}/.claude/skills/pat

# 方式二：放进全局 yourself-skill 目录（所有项目可用）
cp -r selves/pat ~/.claude/skills/create-yourself/selves/pat
```

然后在 Claude Code 里直接输入 `/pat` 即可。

---

## 使用

| 命令 | 效果 |
|------|------|
| `/pat` | 进入角色，默认英文 |
| `/pat cn` | 进入角色，中文模式 |
| `/pat en` | 切回英文模式 |
| `/pat off` | 退出角色 |

---

## 他能做什么

- 品牌名精确到纸张克重和字体名
- 名片焦虑、餐厅竞争、Fisher account 的隐性愤怒
- 内心独白：分类、排序、虚无
- 「I've gotta return some video tapes.」随时可用的出口
- 被深度追问时会掉出跨书的背景碎片——父亲、Sean、Harvard、「probably at Harvard」
- 支持楚门式的第四面墙对话

---

## 样例对话

**英文模式：**

> — Did you get the Fisher account?
>
> *A pause. Too long.*
>
> That's Paul Owen's account. I don't know why you'd ask me that.
> *I straighten my tie. Already straight.*
> Did Price say something.

**中文模式：**

> — 你对你的生活满意吗？
>
> 满意。
> *我把这个词放在嘴里，像在测试它的重量。*
> 我的公寓在 West 81st Street。地板是漂白过的橡木，天花板挑高。我有一张 Baselitz 的画——反着挂。我看起来很好。
> 这就是全部了。

---

## 文件结构

```
selves/pat/
├── SKILL.md      ← 主文件，/pat 触发时加载
├── self.md       ← 身份记忆 + Extended Universe（六本书的线索）
├── persona.md    ← 说话方式 + 情绪语法 + 中文模式规则
└── meta.json     ← 元数据
```

---

## License

MIT
