
<https://zh.wikipedia.org/zh-hans/阿房宫赋>

> 呜呼！灭六国者，六国也，非秦也。族秦者，秦也，非天下也。嗟夫！
>
> **使六国各爱其人，则足以拒秦。使秦复爱六国之人，则递三世可至万世而为君，谁得而族灭也**。
>
> **秦人不暇自哀，而后人哀之。后人哀之，而不鉴之，亦使后人而复哀后人也**。

<https://zh.wikipedia.org/wiki/竹書紀年>


``` shell
curl -f#L https://github.com/DivineEngine/Profiles/archive/refs/heads/master.tar.gz -o DivineEngine.tgz
tar xf DivineEngine.tgz --one-top-level=DivineEngine --strip-components 1

curl -f#L https://github.com/GeQ1an/Rules/archive/refs/heads/master.tar.gz -o StickRules.tgz
tar xf StickRules.tgz --one-top-level=StickRules --strip-components 1 --exclude=Images

curl -f#L https://github.com/dler-io/Rules/archive/refs/heads/main.tar.gz -o dler-io.tgz
tar xf dler-io.tgz --one-top-level=dler-io --strip-components 1

curl -f#L https://github.com/Loyalsoldier/clash-rules/archive/refs/heads/release.tar.gz  -o Loyalsoldier.tgz
tar xf Loyalsoldier.tgz  --one-top-level=Loyalsoldier --strip-components 1
```

# reference

## docs

<https://wiki.metacubex.one/config/rules/ipcidr/>

> 当请求为域名匹配到 `GEOIP` 或 `IP-CIDR` 规则时，Clash 将请求 DNS 查询来检查域名的 IP 是否匹配此条规则，可以选择 `no-resolve` 选项以跳过域名去进行 dns 解析
>
> 如在更早的匹配中触发了解析，则依旧会匹配到添加了 `no-resolve` 选项的 IP 规则

<https://wiki.metacubex.one/config/rules/rule-provider/>

<https://dreamacro.github.io/clash/zh_CN/configuration/rules.html>

<https://clash.wiki/configuration/rules.html>

> `no-resolve` 选项是可选的, 它用于跳过规则的 DNS 解析. 当您想要使用 `GEOIP`、`IP-CIDR`、`IP-CIDR6`、`SCRIPT` 规则, 但又不想立即将域名解析为 IP 地址时, 这个选项就很有用了.

<https://dreamacro.github.io/clash/zh_CN/premium/rule-providers.html>

<https://stash.wiki/rules/rule-set>

## rules

<https://github.com/Loyalsoldier/clash-rules/>

<https://github.com/dler-io/Rules>

<https://github.com/GeQ1an/Rules/>

~~<https://github.com/DivineEngine/Profiles/>~~ **2023-01-26 停更**

<https://github.com/RuCu6/QuanX/tree/main/Rules>