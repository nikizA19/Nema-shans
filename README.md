# Nema-shans
Nema shans da mina


If statement ako tva e po malko ot tva dai tva ako ne dai drugoto - type shit 
(define(nz x)
(if (< x 0)(x)-x))

Chrez cons konstruirame tochkova dvoika primer:

(cons Y Z) koeto stava tochkova dvoika ot (Y . Z)

(Append Imeto na spisuka(Kakvoto iskame da dobavim)))


Chrez
(Null? list)
proverqvame dali nqkoi spisuk e prazen ili ne

(define (fact n)
   (if (= n 1)
     1
   (* n (fact (- n 1)))))

namirane na nai golqm obsht delitel  chrez gcd


Първи начин - чрез рекурсивна процедура, която реализира рекурсивен процес

(define (fib n)
  (cond ((= n 0) 0)
        ((= n 1) 1)
  (else (+ (fib (- n 1)) 
           (fib (- n 2))))))



(define (fib n)
(cond ((= n 0)0)
      ((= n 1)1)
(else(+(fib (- n 1))
        (fib(- n 2))))))


  (define (denom kinds)
    (cond ((= kinds 1) 1)
          ((= kinds 2) 2)
          ((= kinds 3) 5)
          ((= kinds 4) 10)
          ((= kinds 5) 20)
          ((= kinds 6) 50)))
  (cc amount 6))


  Дефинирайте функция, която по зададено n пресмята n-тия член на рекурсивната редица:

(define (red n)
  (cond ((= n 1) 6)
        ((= n 2) -4)
        ((> n 2) (- (* 3 (red (- n 1))) 
             (* 2 (red (- n 2)) n (- n 1))))))









             

