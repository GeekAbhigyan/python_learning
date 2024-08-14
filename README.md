# Python Learning

## Mutable and Immutable data types 
  
  ## Mutable (jo change ho sakta hai )
  * list 
  * set 
  * dictionary
  * bytearray
  * array

  ## Immutable (jo change nahi hota balki dusri object ban jati hai )

  * integers 
  * floating - point numbers 
  * boolean 
  * strings 
  * frozen set 
  * bytes 
 
 ## Image reference to show the difference between mutable and immutable 

 strinf and number ke case me wo purana wala wahi reh jata hai aur naya wala value me reference update ho jata hai <br>
 baad me garbage collector aake ussko clean kar deta hai  



 <img src = "./01_basics/items/image.png"></img>


 - keyError -> matlab dictionary iss naam ki koi key nahi hai


 # Internal working of python

 <img src = "./01_basics/items/"></img>

 ##

 m= [1,2,3]
 n = [1,2,3]
  m==n  checks the value
  m==n checks the reference

  #

  diference between repr , string and print in python ?


  #


  x<y<z    is same as ( x<y and y<z )


  #

  math.floor(0.1) -> round to the samllest 

  math.ceil(0.1) -> round to the highest

  #

  0o -> octal number

  0b -> binary number

  0x -> hexadecimal number

  oct(10) -> 0o12

  bin(10) -> 0b1010   

  hex(10) -> 0xa

  int ("64" ,8) = 52

  #

  random.random() -> 0.0 to 1.0

  random.randomint(1,100) -> 1 to 100

  random.choice([1,2,3,4,5]) -> 1,2,3,4,5

  random.shuffle([1,2,3,4,5]) -> [5,4,3,2,1]
  #
  decimal specific

  from decimal import Decimal

  Decimal('0.1') +Decimal('0.1')

#

"|" is for union 

#
empty set gives data type as dict

#
