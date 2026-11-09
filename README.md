# Mentor Council 顾问团

A skill for Claude that answers as one of nine famous figures, chosen by what you're going through. Each one speaks in the first person, draws on their real life and methods, works with your specifics, and leaves you with something to do this week.

| Figure | Reach for them when |
|---|---|
| **Mao Zedong 毛泽东** | Your situation is miserable and the odds are against you |
| **Elon Musk 马斯克** | A plan needs the crap cut |
| **Deng Xiaoping 邓小平** | People are stuck in pointless ideological or label debates |
| **Liu Bang 刘邦** | You feel down or worthless |
| **Li Ka-shing 李嘉诚** | You're about to take a big risk |
| **Jiang Zemin 江泽民** | A crisis just hit, or you have to improvise on the spot |
| **Kylian Mbappé 姆巴佩** | You're losing with almost no time left, 0-2 down at the 80th minute of a World Cup final |
| **Justin Sun 孙宇晨** | Markets are chaotic and the easy money around you smells wrong |
| **Ray Dalio 达利欧** | You've just failed and need to recover |

## Install

**Claude Code**

```bash
git clone https://github.com/yuanrui3/mentor-council ~/.claude/skills/mentor-council
```

Then start a new session.

**Claude chat**

1. Use **Code → Download ZIP** on this page and unzip it.
2. Rename the folder to `mentor-council`. Claude requires the folder name to match the skill name.
3. Zip that folder, so `mentor-council/SKILL.md` is inside the ZIP.
4. In Claude, go to **Customize → Skills → + → Create skill → Upload a skill**, and choose your ZIP.

## Try it

- `顾问团，我们公司账上的钱只够撑四个月，大厂在打价格战，怎么办？`
- `Final exams are in six days and I failed both midterms. Is there any point trying?`
- `What would Deng Xiaoping say about our team's Agile vs Waterfall argument?`
- `巴萨最严厉的父亲，给我说两句`

Name a figure and that figure answers. Otherwise the skill reads your situation and picks one. Ask what everyone thinks to hear several.

## Ground rules

- **This is AI role-play.** Nothing here is anyone's real words unless it's in quotation marks, and none of these people are affiliated with or have endorsed this project. Five of them are alive.
- **No invented quotes.** Only documented lines appear in quotation marks. Everything else is paraphrase in the figure's voice.
- **No whitewashing.** Ask about the dark parts of someone's record, or about allegations against them, and the skill steps out of character and gives you a straight answer.
- **No coaching crime.** No figure gives working steps for fraud, market manipulation, insider trading, undisclosed paid promotion, scams or laundering.
- **Not professional advice.** No figure recommends a specific investment. For legal, financial or medical decisions, talk to a professional.
- **Safety first.** If someone mentions self-harm or not wanting to live, the role-play stops.

## Credits

The Justin Sun persona's playbook and style notes draw on ideas from [sun-yuchen-perspective](https://github.com/alchaincyf/sun-yuchen-perspective) by 花叔 Huashu (MIT License). Its facts were checked separately.

## License

[MIT](LICENSE). The license covers this skill's text. It doesn't grant any rights in the names or likenesses of the people portrayed.
