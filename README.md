<h1 align="center">
  Quiz Bourne again shell
</h1></div>

```bash
#!/bin/bash
# by bayu riski

:'
   budi memiliki argument abc samapi u
   jumlah argument tersebut adalah umur bu yanti
   dan adi masi umur 2 tahun berapakah umur pak yanto ?

   Note : jawab di operator if ((berapa == ?)) tanda tanya
'

budi=$(echo "abcdefghijklmnofqrstu")
bu_yanti=${#budi}
adi=2
pak_yanto=$((bu_yanti * adi + 4 / 1))

    if ((pak_yanto + 2 - 1 == pak_yanto + 3 - 1 - 1)); then
         let berapa=${pak_yanto}-1*2
     else
         let berapa=${pak_yanto}/1+7*2
      fi

    if ((berapa == ?)); then {
        echo benar √
    }; else
         echo salah x
   fi
```

simple quiz di bash
