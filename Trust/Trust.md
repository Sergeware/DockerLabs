# Trust

**Distro atacante:** Parrot Security

**IP objetivo:** 172.17.0.2

**Dificultad:** Muy fácil

---

## Reconocimiento

### Escaneo de puertos

```bash
nmap -sV 172.17.0.2
```
<!-- cap1 -->

| Puerto | Servicio |
| ------ | -------- |
| 22     | SSH      |
| 80     | HTTP     |

El servidor web muestra una vista default, nada relevante.

<!-- cap2 -->
