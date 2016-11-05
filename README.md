#ใบงานที่ 5
##เรื่อง การใช้งานคำสั่ง Console.WriteLine()
##วัตถุประสงค์
1). เพื่อให้นักศึกษาบอกวิธีการใช้คำสั่งแสดงผลบน Text Mode ในภาษา C# ได้
2). เพื่อให้นักศึกษาสามารถปรับแต่งคำสั่งแสดงผลทางหน้าจอตามต้องการได้

##ขั้นเตรียมการทดลอง
1). สร้าง Project ตั้งชื่อเป็น Lab5 เพื่อทดลองการใช้งานคำสั่ง Console.WriteLine()
ลำดับขั้นการทดลอง
(หมายเหตุ ในรูปประกอบที่มี namespace เป็น Lab4 รบกวนแก้เป็น Lab5 ด้วยครับ)
2). ทดลองเรื่องจำนวนของอาร์กิวเมนต์ในคำสั่ง Console.WriteLine()

 2.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic1.png)

  2.2). รันโปรแกรม และบันทึกผลที่ได้
 <br> ขึ้นข้อความ This is text 1. 2 และ 3 คนละบรรทัด
<hr>
<hr>
<hr>
<hr>
 2.3). แก้โปรแกรมตามรูปด้านล่างนี้
 
  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic2.png)

 2.4). รันโปรแกรม และบันทึกผลที่ได้
 <br>ขึ้นข้อความ 3 and 6




###คำถาม 5.1 เครื่องหมาย { }  ในคำสั่ง Console.WriteLine() มีลักษณะการใช้งานอย่างไร
<br>เป็นการเรียกใช้ตัวอักษรที่อยู่หลัง , โดยตัวและจะเป็นตำแหน่ง 0 และถัดไปคือ 1
<hr>
<hr>
<hr>
<hr>
###คำถาม 5.2  ถ้ามีการใช้ตัวเลขใน { } ที่กระโดด เช่น {0} {2} {3} จะใช้งานได้หรือไม่ อย่างไร จงอธิบาย
<hr><br> ใช้งานได้ถ้ามีตัวอักษรอยุ่ในตัวแหน่งที่ 0 2 และ 3
<hr>
<hr>
<hr>
<hr>
 
 2.5). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic3.png)

 2.6). รันโปรแกรม และบันทึกผลที่ได้
<br>ขึ้นข้อความ 6,3 and 6 
<hr>
<hr>
<hr>
<hr>

3). ทดลองเรื่องการกำหนดความกว้างของอาร์กิวเมนต์

  3.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic4.png)

  3.2). รันโปรแกรม และบันทึกผลที่ได้
<hr><br><img src="https://github.com/Atcharee248/LAB-05/blob/master/img/lab5_1.JPG?raw=true">
<hr>
<hr>
<hr>
<hr>

###คำถาม 5.3 การกำหนดความกว้างของอาร์กิวเมนต์ด้วยเครื่องหมาย { , }  ในคำสั่ง Console.WriteLine() มีรูปแบบการใช้งานอย่างไร
<hr><br> ตัวเลขตำแหน่ง หลัง เช่น {0,5} จะเป็นการแสดงตัวอักษรที่ตำแหน่งที่ 5
<hr>
<hr>
<hr>
<hr>


4). ทดลองเรื่องการกำหนดรูปแบบของอาร์กิวเมนต์
  4.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic5.png)

  4.2). รันโปรแกรม และบันทึกผลที่ได้
<hr><br><img src="https://github.com/Atcharee248/LAB-05/blob/master/img/lab5_2.JPG?raw=true">
<hr>
<hr>
<hr>
<hr>

5). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของอาร์กิวเมนต์
  5.1). แก้โปรแกรมตามรูปด้านล่างนี้
 
 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic6.png)

  5.2). รันโปรแกรม และบันทึกผลที่ได้
<BR> <IMG src="https://github.com/Atcharee248/LAB-05/blob/master/img/lab5_3.JPG?raw=true">
6). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของทศนิยมของอาร์กิวเมนต์
  6.1). แก้โปรแกรมตามรูปด้านล่างนี้

 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic7.png)

  6.2). รันโปรแกรม และบันทึกผลที่ได้
  <br> <img src="https://github.com/Atcharee248/LAB-05/blob/master/img/lab5_4.JPG?raw=true">

## แบบฝึกหัด จงระบุ output ของบรรทัดคำสั่งต่อไปนี้

```csharp
1.  string name = "Hello";
    Console.WriteLine(String.Format("{0} there. I said {0}! {0}???", name));
2.    Console.WriteLine("{2:d} {0:d} {1:d}", 1, 2, 3);
3.    Console.WriteLine("Hello " + "World");
4.    Console.WriteLine("Here comes a slash \\");
5.    Console.WriteLine("|{0, 10}|", 999);
6.    Console.WriteLine("|{0,-10}|", 000);
7.    Console.WriteLine("The value: {0}.", 500);
8.    Console.WriteLine("The value: {0:C}.", 500);
9.    Console.WriteLine("{0,-10:F4}", 12.3456789);
10.   Console.WriteLine("{0,-10:C}", 12.3456789);
11.   Console.WriteLine("{0,-10:E3}", 12.3456789);
12.   Console.WriteLine("{0,-10:x}", 65535);
13.   Console.WriteLine("{0,-10:X}", 65535);
14.   int i; 
      Console.WriteLine("Value\tSquared\tCubed"); 
      for(i = 1; i < 10; i++) 
          Console.WriteLine("{0}\t{1}\t{2}", i, i*i, i*i*i); 
15.    Console.WriteLine("{0:#.###}.", 1234.56789);
```
1 <IMG src="https://github.com/Atcharee248/LAB-05/blob/master/img/51.JPG?raw=true"><br>
2 มีข้อความขึ้นว่า 3 1 2 <br>
3 ข้อความว่า Hello World<br>
4 ข้อความว่า Here comes a slash \
<br>5 <IMG src="https://github.com/Atcharee248/LAB-05/blob/master/img/51.JPG?raw=true"><br>
6 <IMG src="https://github.com/Atcharee248/LAB-05/blob/master/img/56.JPG?raw=true"><br>
7 ข้อความ The value: 500<br>
8  ข้อความ The value: ?500<br>
9 ข้อความ 12.3457<br>
10 ข้อความ ?12.35<br>
11 ข้อความ 1.235E+001<br>
12 ข้อความ ffff<br>
13 ข้อความ FFFF<br>
14 <IMG src="https://github.com/Atcharee248/LAB-05/blob/master/img/514.JPG?raw=true"><br>
15 1234.568.
