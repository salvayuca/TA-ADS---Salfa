START
STORE "Nilai" AS Number
IF ("Nilai" < 68)
    DISPLAY "Nilai"
ELSE IF "Nilai" IS divisible by 5
    DISPLAY "Nilai"
ELSE IF ("Nilai" MODULUS BY 5 = 4)
    DO "Nilai" + 1
ELSE IF ("Nilai" MODULUS BY 5 = 3)
    DO "Nilai" + 2
END IF