# Parking_management_system

**[๐์ฃผ์ฐจ์ฅ ๊ด๋ฆฌ ์์คํ๐]**  

> ์ด์ ์์๊ฒ ํธ๋ฆฌํ ์ฃผ์ฐจ ์์คํ์ ์ ๊ณตํ๊ธฐ ์ํ ํ๋ก๊ทธ๋จ์ผ๋ก ์์ฐจ,์ถ์ฐจ,์ ์ฐ ๋ฑ์ ๊ธฐ๋ฅ์ ์ํํ  ์ ์์ผ๋ฉฐ ๊ด๋ฆฌ์๋ ์ ์ฐ๋ด์ญ์ ๊ด๋ฆฌํ  ์ ์๋ ํ๋ก๊ทธ๋จ
>

### Environment / ํ๊ฒฝ

```
์คํ ํ๊ฒฝ : ๊ฐ์๋จธ์  ๊ธฐ๋ฐ์ Raspbian
๊ฐ๋ฐ ํ๊ฒฝ : C/C++, Raspbian(Linux), Mobaxterm, Visual studio code
```

### Prerequisites / ์ ํ ์กฐ๊ฑด

```
์ปดํ์ผ: MOBIS_06 ํด๋์์ make์๋ ฅ -> ์๋ ์ปดํ์ผ
       
        MOBIS_06->make
        libcpp->make
        maincpp->make
    
```


## ์คํ๋ฐฉ๋ฒ
```
1. ์์ถํ์ผ์ ํ๋๋ ํ ๋ฆฌ์ ๋ค์ด
2. ํ๋๋ ํ ๋ฆฌ์์ tar -xvf MOBIS_06.tar ๋ช๋ น์ด๋ฅผ ์ฌ์ฉํ์ฌ ์์ถ ํด์ 
3. .bashsrc ํ์ผ์ ๊ณต์ ๋ผ์ด๋ธ๋ฌ๋ฆฌ ์์น ์ค์  
    (ex : vi .bashsrc๋ฅผ ์๋ ฅํ์ฌ ๋ง์ง๋ง์ค์ export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/home/pi/lib ์ถ๊ฐ)
4. MOBIS_06ํด๋์์ make๋ช๋ น์ด๋ฅผ ์ฌ์ฉํ์ฌ ์ปดํ์ผ
5. MOBIS_06ํด๋์์ ./maincpp/main์ ์๋ ฅํ์ฌ ์คํ

```

### Installing / ์ค์น



```
Clone the repo : git clone https://github.com/M-Parking-Project/Parking_management_system.git
MOBIS_06.tar -> tar -xvf MOBIS_06.tar
vi .bashrc=>export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/home/pi/lib ๊ณต์ ๋ผ์ด๋ธ๋ฌ๋ฆฌ ์์น ์ค์ 
```



## Running the tests / ํ์คํธ์ ์คํ
```
์คํ: ./maincpp/main
```

## ์คํํ๋ฉด ์์

๋ฉ์ธํ๋ฉด

![๋ฉ์ธํ๋ฉด](https://user-images.githubusercontent.com/45057466/156688293-9cc96e5e-df8e-42fc-93c5-f3a50b50003b.PNG)

์ ํ๋ฒํธ์กฐํ

![์ ํ๋ฒํธ์กฐํ](https://user-images.githubusercontent.com/45057466/156688286-c3fe3b37-0d55-4f4e-906a-0639abd1d895.PNG)

์ถ์ฐจ

![์ถ์ฐจ](https://user-images.githubusercontent.com/45057466/156688289-3248895b-195a-4d9c-a956-35dbf200b6e1.PNG)

ํ์๋ฑ๋ก

![ํ์๋ฑ๋ก](https://user-images.githubusercontent.com/45057466/156688294-89e6518a-9c78-408a-9ffa-f9a5c189850c.PNG)

์์ฐจ

![์์ฐจ](https://user-images.githubusercontent.com/45057466/156688292-89f85fae-d75d-4dbc-be9a-c0d8678e70fa.PNG)

ํํฉ๋ณด๊ธฐ

![ํํฉ๋ณด๊ธฐ](https://user-images.githubusercontent.com/45057466/156688288-ae5500d9-fe61-4a15-9843-c42e65373b06.PNG)


๊ด๋ฆฌ์๋ชจ๋ - ์๋ณ ์ถ์ด

![image](https://user-images.githubusercontent.com/45057466/156697580-c0454995-26d7-4839-aa4c-c6e3910bb3d9.png)


## Built With / ํ์


์ด๋ฆ|๊ฐ๋ฐ
---|---|
๊ถํ์ง|file ๋ฐ ์ ์ฐ๊ณผ ๊ด๋ จ ๊ธฐ๋ฅ ๊ฐ๋ฐ|
์ํ๋น|๊ด๋ฆฌ์ ๊ธฐ๋ฅ ๊ฐ๋ฐ|
์ ํด๊ฒฝ|์ฃผ์ฐจ์ฅ๊ณผ ํ์ ๊ด๋ จ ๊ธฐ๋ฅ ๊ฐ๋ฐ|



