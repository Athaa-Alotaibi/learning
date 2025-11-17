# learning
This repository is for training 

REAL FUNCTION FindMax(n)
       INTEGER, INTENT(IN) :: n
       INTEGER :: i
       REAL :: maxval
       maxval = NUM(1)
       DO i = 2, n
         IF (NUM(i) > maxval) THEN
           maxval = NUM(i)
         END IF
       END DO
       FindMax = maxval
     END FUNCTION FindMax

     
