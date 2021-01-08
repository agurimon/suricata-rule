# 설치

```bash
$ sudo add-apt-repository ppa:oisf/suricata-stable
$ sudo apt update
$ sudo apt install suricata
```

# 실행

```bash
$ sudo suricata -s test.rules -i eth0 
```