# 购物助手

技能包位于 [`shopping-helper/`](shopping-helper/)。

运行环境需要同时提供 `web-access` skill，用于核验在售商品、价格、卖家和交易条件。若单独分发本技能包，应同时安装该依赖；若计划面向其他用户安装，建议将两者打包为同一插件。

行为评估用例位于 [`shopping-helper/evals/cases.yaml`](shopping-helper/evals/cases.yaml)，覆盖隐式触发、购买必要性、购买时机、证据门槛和失败恢复。
