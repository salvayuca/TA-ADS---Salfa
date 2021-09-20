START
INPUT "besar-suhu"
      "tipe-suhu"
IF "tipe-suhu" IS "farenheit"
    DO ("besar-suhu"-32)*(5/9)
ELSE
    IF "tipe-suhu" IS "kelvin"
        DO ("besar-suhu"-273.15)
ELSE
    IF "tipe-suhu" IS "celcius"
        DO "besar-suhu"
ENDIF
SHOW DO
END