START
FOR a IN 1 TO n
    DO SET print_number TO TRUE
    IF a is divisible by 3 THEN
        print "Fizz"
        SET print_number TO FALSE
    ELSE
    IF a is divisible by 5 THEN
        print "Buzz"
        SET print_number TO FALSE
END
    