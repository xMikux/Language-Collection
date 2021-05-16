# InteractiveChat

互動式聊天室, 可以顯示物品 提及別人, 或者自己寫新的變數!

[Spigot](https://www.spigotmc.org/resources/interactivechat-show-items-inventory-in-chat-custom-chat-keywords-bungee-velocity-support.75870/) | [Source Code](https://github.com/LOOHP/InteractiveChat)

## Triton設定

**Prefix:** `InteractiveChat.`  
**Variable Regex:** `{%\w.-%+}`  
**Ignored keys:**

```
Settings\.(?!BungeecordUnknownItem).+
Settings\.PlayerNotFound\.Hover\.(?!Text).+
Commands\.(?!HoverMessage).+
Chat\.(?!MentionedTitle|UnknownPlayerMentionSubtitle|KnownPlayerMentionSubtitle|MentionHoverText).+
ItemDisplay\.(?!Item|Inventory|EnderChest)\.(?!InventoryTitle|Description|HoverMessage).+
Player\.(?!Hover).+
PlayerNotFound.+
```
