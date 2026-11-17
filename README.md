# Mouse Tab Switcher Plus

Switch OSRS interface tabs with your mouse buttons.

## Credit

This is an extended version of **[Mouse Tab Switcher](https://github.com/JD-Michelena/MouseTabSwitcher)
by JD_Michelena**. The idea and the tab-switching approach are theirs, and this plugin started as a fork of
it. All credit for the original goes to them. If you only need Button 4/5 opening fixed tabs, use the
original.

## Vibe coded

To be upfront: this plugin is **vibe coded**. I described what I wanted, and an AI assistant
([Claude](https://claude.com/claude-code)) wrote the code. I tried it out and steered the changes, but I
didn't write the code by hand. Bug reports are welcome in the issues.

## Features

- **Any number of mouse buttons.** Button 4, Button 5, the middle button and buttons 6–8 each get their own action.
- **Next / previous tab.** Instead of a fixed tab, a button can step to the next or previous tab. The order follows
  what your layout shows: left to right, top row then bottom row. It works the same in Fixed, Resizable – Classic,
  Resizable – Modern and the modern bottom-line layout, and tabs that are hidden in your layout (like Logout in
  modern) are left out.
- **Double-click actions.** Each button can do something else when pressed twice quickly (speed adjustable,
  250 ms by default). A button with a double-click action waits that long before doing its single action;
  buttons without one react instantly.
- **Direct tab bindings.** Any button can open one specific tab, like the original plugin.
- **Wrap around** from the last tab to the first, or stop at the ends.
- **Skip tabs** you never want to land on when stepping (Logout by default). Direct bindings still open them.
- **Shift reverses** a Next/Previous button (optional).
- **Keyboard hotkeys** for Next/Previous, for mice whose software maps extra side buttons to keys.
- **Close tab if already open** (optional): a direct binding for the open tab closes the side panel, like clicking it.

Defaults: Button 4 = Previous tab, Button 5 = Next tab.

## Notes

- Works whether RuneLite's **Block extra mouse buttons** option is on or off. Leaving it on is fine, and keeps
  the game itself from seeing the side buttons.
- On Windows, Java only reports mouse buttons 1–5. Extra buttons on gaming mice usually need the mouse's software
  to map them to a key; bind that key with the Next/Previous hotkeys.
- Binding the middle button stops middle-click camera dragging.

## License

BSD 2-Clause, see [LICENSE](LICENSE).
