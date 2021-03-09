# WebHookTools

> Just For GitHub!!!!!!!!!!!!

## 创建WebHook

```
/webhook-create
```

会返回 WebHookID 和 需要在 GitHub 绑定的URL

## 绑定WebHooK

```
/webhook-bind <WebHookID> <SECRET> <REPO>
```

REPO格式：`<User>/<REPO>`

## 删除WebHook

```
/webhook-del <WebHookID>
```

