# 強制停止する

## 有効化
```bash
curl -X POST -H "Content-Type: application/json" -d '{"killApplicationActive": true}' http://localhost:8080/actuator/chaosmonkey/assaults
```

## 無効化
```bash
curl -X POST -d '{"killApplicationActive": false}' http://localhost:8080/actuator/chaosmonkey/assaults
```

# 例外を発生させる
## 有効化

```bash
curl -X POST -H "Content-Type: application/json" -d '{"exceptionsActive": true}' http://localhost:8080/actuator/chaosmonkey/assaults
```

## 無効化

```bash
curl -X POST -H "Content-Type: application/json" -d '{"exceptionsActive": false}' http://localhost:8080/actuator/chaosmonkey/assaults
```

# レスポンスを遅延させる
## 有効化

```bash
curl -X POST -H "Content-Type: application/json" -d '{"latencyActive": true}' http://localhost:8080/actuator/chaosmonkey/assaults
```

## 無効化

```bash
curl -X POST -H "Content-Type: application/json" -d '{"latencyActive": false}' http://localhost:8080/actuator/chaosmonkey/assaults
```
