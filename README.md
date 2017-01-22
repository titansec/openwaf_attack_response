Name
====

openwaf_attack_response是[openwaf](https://github.com/titansec/openwaf)的子模块，用于返回自定义攻击响应页面，有效防止信息泄露

TODO
====

* 支持自定义响应模版

Configuration Directives
========================

```
    "twaf_attack_response": {
        "state": true,           -- 模块开关
        "detail_state": true     -- 是否显示详细信息
    }
```

###state
**syntax:** *"state": true|false*

**default:** *true*

**context:** *twaf_attack_response*

模块开关，支持true和false，默认开启

###detail_state
**syntax:** *"detail_state": true|false*

**default:** *true*

**context:** *twaf_attack_response*

若开启，则显示详细信息