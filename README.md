# nq-libs

**English** | **Русский**

Libraries for [Nq](https://github.com/qopix/nq) ≥ 0.4 (Linux x86-64).

---

## English

| Library | Status | Description |
|---------|--------|-------------|
| `net` | Ready | TCP sockets |
| `http` | Ready | HTTP/1.0 GET client |
| `https` | Stub | TLS not implemented yet |
| `fs` | Ready | File open/read/write/remove/mkdir |
| `time` | Ready | unix_now, sleep_ms |
| `hash` | Ready | djb2, fnv1a |
| `encoding` | Ready | hex_encode |
 | `crypto` | Ready | xor_bytes |
| `json` | Partial | parse_int, skip_ws |
| `vec` | Ready | Dynamic array |
| `str` | Ready | starts_with, contains |
| `log` | Ready | info/warn/error |
| `math` | Ready | gcd, lcm |
| `test` | Ready | assert, test_summary |
| `os` | Ready | pid, exit_code |

```nq
import "github.com/qopix/nq-libs/net"
import "github.com/qopix/nq-libs/http"
```

---

## Русский

| Библиотека | Статус | Описание |
|------------|--------|----------|
| `net` | Готово | TCP-сокеты |
| `http` | Готово | HTTP/1.0 GET |
| `https` | Заглушка | TLS пока нет |
| `fs` | Готово | Файлы |
| `time` | Готово | unix_now, sleep_ms |
| `hash` | Готово | djb2, fnv1a |
| `encoding` | Готово | hex_encode |
| `crypto` | Готово | xor_bytes |
| `json` | Частично | parse_int |
| `vec` | Готово | Динамический массив |
| `str` | Готово | starts_with, contains |
| `log` | Готово | Логгер |
| `math` | Готово | gcd, lcm |
| `test` | Готово | assert |
| `os` | Готово | pid |

```nq
import "github.com/qopix/nq-libs/net"
import "github.com/qopix/nq-libs/http"
```
