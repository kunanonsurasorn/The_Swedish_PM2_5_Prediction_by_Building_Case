# **โปรเจคการทำนายเกิด PM2.5 โดยใช้ชุดข้อมูลการปล่อยก๊าซจากอาคารในประเทศสวีเดนระหว่างปี 1990 ถึง 2023**

## 1.วัตถุประสงค์ 

    1.1 เพื่อทำนายการเกิด PM 2.5 จากชุดข้อมูลการเกิด PM 2.5 ในปี 1990 ถึงปี 2023
 
    1.2 เพื่อหาโมเดลที่เหมาะสมทำนายการเกิด PM 2.5

## 2.ชุดข้อมูล

    2.1 ชุดข้อมูลที่ใช้มาจากหน่วยงานสถิติของประเทศสวีเดน (Statistics Sweden) 
 
    2.2 เว็บไซต์ของหน่วยงานสถิติสวีเดน : https://www.scb.se/en/

## 3.ภาษาที่ใช้ในการเขียนโปรแกรม

    ภาษาที่ใช้ในการเขียนโปรแกรมคือ Python

## 4.Python Libraries ที่ใช้ในการทำโปรเจค

    4.1 Pandas
 
    4.2 Matplotlib
 
    4.3 Seaborn
 
    4.4 Sklearn

 ## 5.ผลลัพท์
 ### 5.1 โมเดลก่อนการปรับปรุง
 
       5.1.1 โมเดลที่เหมาะสมสำหรับการทำนายการเกิด PM 2.5 เป็น Lineare Regression
   
       5.1.2 Mean Absolute Error = 15.573148409443574
   
       5.1.3 Mean Squared Error = 929.0789690193789
   
       5.1.4 Root Mean Squared Error = 30.480796725469283
   
       5.1.5 R2 Score = 0.9999088287823679
   
 ### 5.2 โมเดลหลังการปรับปรุง
 
       5.2.1 โมเดลที่เหมาะสมสำหรับการทำนายการเกิด PM 2.5 เป็น Lineare Regression
   
       5.2.2 Mean Absolute Error = 4.6454289955159656
   
       5.2.3 Mean Squared Error = 101.28140742769907
   
       5.2.4 Root Mean Squared Error = 10.063866425370474
   
       5.2.5 R2 Score = 0.9999900611793544
   
