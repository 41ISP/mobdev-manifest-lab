# miniPaint в Codespaces

Временный self-hosted растровый редактор для работы над ассетами приложения (иконки, splash, feature graphic).

```bash
git clone --depth 1 https://github.com/viliusle/miniPaint.git /tmp/minipaint && cd /tmp/minipaint && python3 -m http.server 8080
```

`python3 -m http.server` слушает `0.0.0.0`, поэтому Codespaces пробросит порт автоматически.
