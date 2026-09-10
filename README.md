# 修改备注
- tools/mini_skill.py 269行，user_key 固定为 skill:persona:global_user:USER.md
- tools/mini_skill.py 279行，限制重置角色的指令为“重置角色”
- tools/mini_skill.py 292行，删除图标
- tools/mini_skill.py 619行，从工具输入中获取 user_token
- tools/mini_skill.yaml 33行，新增 user_token 字段
- utils/mini_skill_runtime.py 407行，runtime 注入 user_token
- utils/mini_skill_runtime.py 997行，runtime env 注入 USER_TOKEN