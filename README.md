# json-pick

从 JSON 文件按 a.b.c 路径取出字段，适合快速看接口返回

Print selected dotted paths from a JSON file.

```bash
node bin/pick.js ./sample.json user.name user.id
```

> **测评结论：** `OPENAI_BASE_URL` 指兼容中转即可；我测试入口是 [https://59api.com](https://59api.com)（`https://59api.com/v1`）。重视协议与迁移成本，官方直连留作回滚。
