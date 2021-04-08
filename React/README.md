# React

自動化管理效能

[Spigot](https://www.spigotmc.org/resources/react-smart-server-performance.21057/) | [Source Code](https://github.com/VolmitSoftware/React)

## Triton設定

**Prefix:** `React.`  
**Variable Regex:** `$\w`  
**Ignored keys:**

```
map.+
command.help.(?:symbol)-.+
sampler.chunks-loaded.flag
sampler.chunks-per-second.symbol
sampler.entities-\w+.(?:symbol)
sampler.tick-time.symbol
sampler.tps.symbol-\w+
```
