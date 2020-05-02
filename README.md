STORE "jumlah_penumpang" INPUT 
STORE "kecepatan_awal = 20"
STORE "kecepatan"

IF (penumpang) = 0 
 DO "kecepatan = kecepatan_awal"
ELSE IF (penumpang) < 1
 DO "kecepatan = kecepatan_awal - 2"
ELSE IF (penumpang) > 2
 DO "kecepatan = kecepatan_awal - 5 "
ELSE IF (penumpang) = 4
DO "kecepatan = "kecepatan_awal - 7"
ELSE
 Display "Kecepatan"