# List haqida mashqlar.

# Uyga vazifani qanday topshirish kerak
bitta faylga hamma mashqlarni, har birini alohida funksiya korinishida yozing.

Masalan:

#### A. 1 dan 10 gacha bo'lgan sonlardan iborat list yarating va uni bir o'zgaruvchiga saqlab qoying. shu o'zgaruvchini *print* qiling 

#### B. 5 ta so'zdan iborat list yarating va uni *print* qiling. Funksiyani 3marta chaqiring
```python
"""
list_haqida.py 
hamma mashqlar bitta faylda boladi, lnhar bir mashq alohida Funksiya boladi
"""
# A savolning javobi
# yangi funksiya yaratamiz uni ichida mashqnig javobini yozamiz
def mashq_A():
    print('-'*15,'Mashq A','-'*15)
    sample_numbers = [1,2,3,4,5,6,7,8,9,10]
    print(sample_numbers)

# o'sha funksiyani chaqirganimizda endi javobi chiqadi
mashq_A()


# A savolning javobi
# yangi funksiya yaratamiz uni ichida mashqnig javobini yozamiz
def mashq_B():
    print('-'*15,'Mashq B','-'*15)
    sample_words = ['hello','world','python','time','school']
    print(sample_words)

# Funksiyani 3marta chaqiring
mashq_B()
mashq_B()
mashq_B()
```

Natija quyidagicha chiqadi

```bash
--------------- Mashq A ---------------
[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
--------------- Mashq B ---------------
['hello', 'world', 'python', 'time', 'school']
--------------- Mashq B ---------------
['hello', 'world', 'python', 'time', 'school']
--------------- Mashq B ---------------
['hello', 'world', 'python', 'time', 'school']
```



# Endi Mashqlarni boshlaymiz. 

### 1. Sonlardan iborat List yarating. shu listdagi sonlar yigindisini print qiling


### 2. Sonlardan iborat List yarating. shu listdagi sonlar ko'paytmasini print qiling

### 3. Sonlardan iborat List yarating. shu listdagi eng katta sonni print qiling

### 4. Sonlardan iborat List yarating. shu listdagi eng kichkina sonni print qiling

### 5. stringdan iborat list yarating. shu listdagi uzunlig 4 dan ortiq stringlarni sonini print qiling

