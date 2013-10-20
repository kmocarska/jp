Notatka 20.10.2013 :D


find ~/ -mtime -10 <== szukanie plikow uzywanych 10 dni temu

``find ~/ -atime 20 <== szukanie polikow nieuzywanych przez ostatnie 20 dni

``find /etc\( -type f -and -name a* \) -or \( -type d -and ! -empty\ 2>/dev/null
