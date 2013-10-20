Notatka JP nygga 20.10.2013 :D


find ~/ -mtime -n <== szukanie plikow uzywanych n dni temu

find ~/ -atime n <== szukanie polikow nieuzywanych przez ostatnie 2n dni

find /etc\( -type f -and -name a* \) -or \( -type d -and ! -empty\ 2>/dev/null

rm x?? <== usun pliki z 3 znakami zaczynajace sie na x


mkdir $(date +%F) ==> tworzenie kat. o nazwie z data dzisiejsza




