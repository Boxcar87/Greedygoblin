![Look again](https://imgur.com/WnJGjbR.jpg)
![Look thrice](https://i.imgur.com/wbLP9ME.jpg)

**GreedyGoblin is a generic filter, I don't go line by line editing every possible item.**

I have constructed the script in a very readable manner, if you want to edit it some please feel free and just rename it so it saves. If you don't want a certain item to show, you can delete that block or comment it out, either will work. If you want something else to show, please add it in accordingly to prevent issues. POD scripts read in order of tier, so you need to label Superior items > Non-magic items > Inferior items, from top to bottom.

Here's how it works:

`
Ethereal items have a purple ETH pas a prefix
`

`
Enhanced Damage or Enhanced Defense items will show their respective %ED as a prefix
`

`
Spears and polearms over 4OS are shown
`

`
0/5/6 OS Berserker axe are shown
`

`
CTA/Hoto bases are shown.
`

`
0/3/5 2H Elite Swords are shown 
`

`
0 and 4OS shields show after 60, before 60 2/3 OS show as well. Ethereal paladin shields show after 60.
`

`
White rune word bases, Assassin +3 claws, Sorceress +3 staves, and Amazon +3 skill bases are shown.
`

`
OOC, any rune Lem+, and high value items have alerts and a sexy female voice
`

`
Any crap item that is 1 box wide first gets checked for gold value, if worth enough it will show up as its value
`

!*After 60 Scepter bases don't show, I haven't built the filter around those yet. So if you're wanting to make a runeword in a scepter, temporarily disable GreedyGoblin.*

### 23 Mar 2024
```
•Depreciated CLVL filter scaling and replaced the mechanic with Filter level.
```

## VSCode Extension

*This is for editing the filter manually yourself, it is not required and only makes reading/writing a bit easier inside of VSCode*

![sample](https://i.imgur.com/MxSZBcy.png)
First download the POE filter extension in VSCode

![image](https://imgur.com/5CCTZnE.jpg)

Then navigate to `Users/%USER%/.vscode/extensions/robby.poe-filter.../syntaxes` and replace the Filter.tmLanguage with the file here.
