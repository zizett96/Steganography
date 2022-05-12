# Steganography
     텍스트를 암호화하여 이미지에 저장 및 이미지에 저장된 값을 복호화
- 구현된 기능
<!---->
1. 암호화
2. 복호화
---
## Form Design
### Preview
<!---->
 - Form1.cs(Steganograthy)
<!---->
![image](https://user-images.githubusercontent.com/55373791/167827300-300e737a-b05a-4dc8-81d5-4685201b8b25.png)
<!---->
---
## Programing
<!---->
### List
1. Form1.cs
2. Crypto.cs
3. SteganographyConvert.cs
<!---->
#### Form1.cs
1. 이미지 열기 및 저장
2. UI 구현
<!---->
#### Crypto.cs
1. 암호화 및 복호화
 - Rijndeal Algorithm(레인달 알고리즘) : 대칭키 알고리즘으로 AES에 활용되는 알고리즘
<!---->
#### SteganographyConvert.cs
1. 암호화 된 값을 이미지의 RGB값을 조정해 숨기는 작업
2. 이미지의 RGB 값을 이용해 복호화된 값을 추출하는 작업
<!---->
