# fnursonmezbinarysearchtreeproject1
[Patika.dev](https://www.patika.dev/tr)


# 1-) Binary Search Tree [7,5,1,8,3,6,0,9,4,2] 
- Root => 7 
- 5<7 olduğu için root'un soluna yerleşir.
- 1<7 ve aynı zamanda 1<5 olduğu için 5'in de soluna yerleşir.
- 8>7 olduğu için root'un sağına yerleşir.
- 3<7 , 3<5 olduğu için 7 ve 5'in soluna, 3>1 olduğundan 1'in sağına yerleşir.
- 6<7 olduğu için root'un soluna, 6>5 olduğu için 5'in sağına yerleşir.
- 0<7 olduğu için root'un soluna, 0<5 ve 0<1 olduğu için 1'in soluna yerleşir.
- 9>7 ve 9>8 olduğu için 8'in sağına yerleşir.
- 4<7 ve 4<5 olduğu için 5'in soluna, 4>1 ve 4>3 olduğu için 3'ün sağına yerleşir.
- 2<7 olduğu için root'un soluna, 2<5 olduğu için 5'in soluna, 2>1 olduğu için 1'in sağına, 2<3 olduğu için 3'ün soluna yerleşir.
-------
                   7
                5     8
              1   6     9
            0   3
              2   4
                 
