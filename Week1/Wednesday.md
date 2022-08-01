<h1 align="center">:pushpin: Introduction to programming & Javascript - Week 1: Wednesday, July 20th, 2022</h1>

<h2>1. Your date of birth in the matrix? exercise</h2>

`Binary`
| 2<sup>12</sup> | 2<sup>11</sup> | 2<sup>10</sup> | 2<sup>9</sup> | 2<sup>8</sup> | 2<sup>7</sup> | 2<sup>6</sup> | 2<sup>5</sup> | 2<sup>4</sup> | 2<sup>3</sup> | 2<sup>2</sup> | 2<sup>1</sup> | 2<sup>0</sup> |
| ---- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |--- |--- |
4096 |2048| 1024 | 512 | 256 | 128 | 64  |  32 |  16 |  8  |  4  |  2  |  1  |

  <h4><b><li>My date of birth: </b> August 17th, 1999 :date: </h4></li>
  
  `Decimal number: 08 (August)`
  | 2<sup>12</sup> | 2<sup>11</sup> | 2<sup>10</sup> | 2<sup>9</sup> | 2<sup>8</sup> | 2<sup>7</sup> | 2<sup>6</sup> | 2<sup>5</sup> | 2<sup>4</sup> | 2<sup>3</sup> | 2<sup>2</sup> | 2<sup>1</sup> | 2<sup>0</sup> |
| ---- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |--- |--- |
|0|0| 0 | 0 | 0 | 0 | 0  |  0 |  0 |  1  |  0 |  0  |  0  |

  `Decimal number: 17 (Day)`
| 2<sup>12</sup> | 2<sup>11</sup> | 2<sup>10</sup> | 2<sup>9</sup> | 2<sup>8</sup> | 2<sup>7</sup> | 2<sup>6</sup> | 2<sup>5</sup> | 2<sup>4</sup> | 2<sup>3</sup> | 2<sup>2</sup> | 2<sup>1</sup> | 2<sup>0</sup> |
| ---- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |--- |--- |
|0|0| 0 | 0 | 0 | 0 | 0  |  0 |  1 |  0  |  0 |  0  |  1  |

  `Decimal number: 1999 (August)`
  2<sup>12</sup> | 2<sup>11</sup> | 2<sup>10</sup> | 2<sup>9</sup> | 2<sup>8</sup> | 2<sup>7</sup> | 2<sup>6</sup> | 2<sup>5</sup> | 2<sup>4</sup> | 2<sup>3</sup> | 2<sup>2</sup> | 2<sup>1</sup> | 2<sup>0</sup> |
| ---- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |--- |--- |
| 0 | 0 | 1 | 1 | 1  |  1 |  1 |  0  |  0 |  1  |  1  | 1 | 1|

<h2>2. MIPS exercise</h2>

1. Create a program that adds any two given numbers provided by the user

```assembly  
.data
	      number1: .asciiz "\nInput first number: "
	      number2: .asciiz "\nInput second number: "
	      result_message: .asciiz "\nThe result is: "
  .text
  	main:
              li $v0, 4
              la $a0, number1
              syscall

              li $v0, 5
              syscall

              move $t0, $v0

              li $v0, 4
              la $a0, number2 
              syscall

              li $v0, 5
              syscall

              move $t1, $v0

              add $t2, $t0, $t1

              li $v0, 4
              la $a0 result_message
              syscall

              li $v0, 1
              move $a0, $t2
              syscall

              li $v0, 4
              la $a0, message
              syscall
  ```
  2. Create a program that displays your name
  
  ```assembly
  .data
        message: .asciiz "\nJessica Montserrat Morales Enrique\n"
  .text
        main:
              li $v0, 4
              la $a0, message
              syscall
  ```
