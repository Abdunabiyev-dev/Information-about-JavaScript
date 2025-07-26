# Information-about-JavaScript

JavaScript faylini boshqa fayllarga ulash uchun quyidagi teg ishladiladi " <script> "

Agar bizda juda ko'p JavaScript kodi bo'lsa , uni alohida faylga qo'yishimiz mumkin. Misol uchun " <script src="/path/to/script.js"></script> "

Bir nechta skriptlarni biriktirish uchun bir nechta teglardan foydalaning . Misol uchun " <script src="/js/script1.js"></script> , <script src="/js/script2.js"></script> "

Bitta <script>tegda atribut ham, kod ham bo‘lishi mumkin emas.

JavaScript faylni html faylga ulash uchun quyidagi tegni ishlatishingiz kerak bo'ladi " <script src="main.js"></script> "

Odatda, kodni yanada o'qilishi uchun bayonotlar alohida satrlarda yoziladi. Masalan " alert('Hello'); alert('Suhrob'); "

JavaScriptda bizga kerak bo'lmagan kodni vaqtincha quyidagidek comment ga olib tursak bo'ladi " /* Hello */ "

Biz brauzer sahifasiga biron-bir so'z or yoki gap chiqarmoqchi bo'lsak quyidagi tegni ishlatishimiz mumkin " alert('World'); "

JavaScriptda kodimizni zamonaviy kod ga aylantirsak bo'ladi . " 'use strict'; "

JavaScriptda biz o'zgaruvchi elon qilishimiz mumkin " let user = 'John', age = 25, message = 'Hello'; "

JavaScript faylga html fayldagi kodimizni olib kelishimiz mumkin . " const body = document.getElementById("body") "

2.5 Malumotlar turi - malumotlar turi 8 xil bo'ladi ular " Raqam , BigInt , String , Mantiqiy (mantiqiy tur) , "Nul" qiymati , "Aniqlanmagan" qiymat , Ob'ektlar va belgilar , Operator turi . 
Ular haqida malumot {
Raqam - Raqam turi butun va suzuvchi nuqtali sonlarni ifodalaydi.
BigInt - (253-1) <<< shu sondan katta bo'lgan barcha sonlar BigInt deb ataladi .
String - JavaScript-dagi satr tirnoqlar bilan o'ralgan bo'lishi kerak.
Mantiqiy (mantiqiy tur) - Boolean turi faqat ikkita qiymatga ega: trueva false.
"Nul" qiymati - Bu shunchaki "hech narsa", "bo'sh" yoki "qiymat noma'lum" ni ifodalovchi maxsus qiymat.
"Aniqlanmagan" qiymat - Agar o'zgaruvchi e'lon qilingan, lekin tayinlanmagan bo'lsa, uning qiymati quyidagicha bo'ladi - undefined.
Ob'ektlar va belgilar - Olingan userob'ektni "ism" va "yosh" deb nomlangan ikkita imzolangan faylga ega kabinet sifatida tasavvur qilish mumkin.
Operator turi - Biz har xil turdagi qiymatlarni boshqacha qayta ishlashni yoki shunchaki tezkor tekshirishni xohlayotganimizda foydalidir.
}
