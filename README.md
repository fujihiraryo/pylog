# pylog
Pythonのログ出力モジュール

実行例

```bash
python main.py
```

```python
import pylog
logger = pylog.setup_logger()
# ログを出力
logger.debug("debug")
logger.info("info")
logger.warning("warning")
logger.error("error")
logger.critical("critical")
```

```text
2020-10-07 16:08:38,052 main.py:4 [DEBUG] debug
2020-10-07 16:08:38,052 main.py:5 [INFO] info
2020-10-07 16:08:38,052 main.py:6 [WARNING] warning
2020-10-07 16:08:38,053 main.py:7 [ERROR] error
2020-10-07 16:08:38,053 main.py:8 [CRITICAL] critical
```
