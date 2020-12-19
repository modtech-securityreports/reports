# DDoS attempt results (avg ping for before aswell as during test)

| Test               | Ping before test | Ping during test | Difference                 |
| ------------------ | ---------------- | ---------------- | -------------------------- |
| Low-Power DDoS     | 120ms            | 121ms            | 1ms                        |
| High-Power DDoS #1 | 120ms            | 122ms            | 2ms                        |
| High-Power DDoS #2 | 171ms            | 122ms            | -49ms > likely discord API |

# Machine Takeover

| Test no. | Success                    | Method                                           |
| -------- | -------------------------- | ------------------------------------------------ |
| 01       | `false` > Not same network | Other-MVPS-server-based Network Attack           |
| 02       | `false` > Not same network | Other-MVPS-server-based Network Attack           |
| 03       | `false`                    | MVPS Network attack from outside of MVPS Network |
| 04       | `false` > Firewall Block   | Direct DNS-based IP attack\*                     |

\* test performed although this scenario is extremely unlikely. Finding the Modtech IP is not very likely.
