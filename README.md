In this project, we have data of Urdu language. Our task is to first convert Urdu audio into urdu text, we will build this algorithm from scratch and train our model on label data. Our corpus contains 50 different Urdu words.
The Audio data contain of following 50 Urdu's words:

1.  abbu	ابو
2.  acha	اچھا
3.  ali	        علی
4.  ammi	امی
5.  camera	کیمرہ
6.  call	کال
7.  dikhao	دکھاؤ
8.  dial	ڈائل
9.  doo	        دَو
10. facebook	فیس بک
11. gallery	گیلری
12. ghar	گھر
13. google	گوگل
14. ha	        ہے
15. habib	حبیب
16. jana	جانا
17. ka	        کا
18. kr	       کر
19. khabrain	خبریں
20. khol	کھول
21. kro        کرو
22. le	       لے
23. location	لوکیشن
24. lock	لاک
25. live	لائیو
26. lo	       لو
27. Lahore	لاہور	
28. message	میسج
29. mila	مِلا
30. mujhay	مجھے
31. news	نیوز
32. number	نمبر
33. off		آف
34. on		آن
35. open	اوپن
36. photo	 فوٹو
37. phone	فون
38. school	سکول
39. university  یونیورسٹی
40. WhatsApp	واٹس ایپ
41. Zero	زیرو
42. One		ون
43. Two		ٹو
44. Three	تھری
45. Four	فور
46. Five	فائیو
47. Six		سِکس
48. Seven	سیون
49. Eight	اَیٹ
50. Nine	نائن

So, after enough training on these words, we give any sentence to our model using only these words, our model will generate the text against that audio.
e.g: Audio is: "علی سکول گیا ہے"
Then our model will generate the text : "علی سکول گیا ہے"
Then maybe later on we use an LLM to convert this urdu text into english text and then we maybe convert this english text into english audio.
