---
layout: page
title: "ข่าว 1 :StackOverflow แนะนำกฎการเขียนคอมเมนต์โค้ด อย่าคอมเมนต์แทนการแก้โค้ดที่ไม่ดี"
permalink: /StackPverflow/
---

# **StackOverflow แนะนำกฎการเขียนคอมเมนต์โค้ด**

<p align="center">
<img src="https://www.blognone.com/sites/default/files/styles/thumbnail/public/topics-images/stack.png?itok=3jHmHQ7X" style="width:150px;height:150px;">
</p>

Ellen Spertus จาก StackOverflow แนะนำถึงการเขียนคอมเมนต์โค้ด 9 ข้อ เพื่อการเขียนโค้ดที่ดีขึ้น พร้อมกับเตือนว่าโค้ดที่มีคอมเมนต์แย่ๆ นั้นแย่กว่าโค้ดที่ไม่มีคอมเมนต์เลยเสียอีก โดยกฎ 9 ข้อได้แก่

1. **อย่าเขียนซ้ำกับในโค้ด**: หลายคนอาจจะเรียนมาว่ายิ่งคอมเมนต์โค้ดเยอะยิ่งดี สร้างนิสัยให้โปรแกรมเมอร์บางคนคอมเมนต์ระบุสิ่งที่เขียนในโค้ดอยู่แล้ว

2. **อย่าใช้คอมเมนต์เป็นข้ออ้างในการเขียนโค้ดแย่ๆ**: โค้ดที่อ่านยากหลายครั้งแก้ไขได้ด้วยการตั้งชื่อตัวแปรให้สื่อถึงการใช้งานตั้งแต่แรก เช่นบางคนชอบตั้งชื่อตัวแปรเป็นอักษรตัวเดียว

3. **ถ้าอธิบายโค้ดด้วยคอมเมนต์ไม่ได้ อาจจะแปลว่าโค้ดแย่**: บางครั้งคอมเมนต์ในโค้ดอาจจะบอกแค่ว่ามันยากเกินอธิบาย การที่โค้ดอธิบายไม่ได้เช่นนี้อาจจะแปลว่าเราควรปรับโค้ดใหม่ให้ตรงไปตรงมา

4. **อย่าปล่อยให้คอมเมนต์สร้างความสับสน**: คอมเมนต์บางอย่างไม่ได้เกี่ยวอะไรกับโค้ด ทำให้คนอ่านงงว่าคนคอมเมนต์จะบอกอะไร

5. **พยายามอธิบายส่วนที่คนไม่ชิน**: หากเห็นโค้ดที่คนอื่นมาอ่านแล้วน่าจะรู้สึกแปลก หรือโค้ดที่คนอาจจะรู้สึกว่าตัดทิ้งก็ได้ก็ควรเขียนคอมเมนต์ไว้ว่าโค้ดส่วนนั้นจำเป็นอย่างไร

6. **ใส่ที่มาของโค้ด**: การใส่ลิงก์ที่มาของโค้ดช่วยให้คนอ่านรู้ว่าโค้ดนี้พยายามแก้ปัญหาอะไร และบางทีโค้ดในที่มาก็มีการปรับปรุงไปแล้วก็อาจจะนำมาปรับปรุงในโครงการด้วย

7. **ใส่ลิงก์อ้างอิง**: บางครั้งเราอาจจะไม่ได้เอาโค้ดมาโดยตรง แต่อ้างอิงจากเอกสารมาตรฐาน การใส่ลิงก์ไว้ก็ช่วยให้คนอ่านรู้ว่าเราพยายามทำตามมาตรฐานใด และบางครั้งมาตรฐานก็มีการปรับปรุงเช่นกัน

8. **อ้างอิงถึงบั๊ก**: หลายครั้งโค้ดที่กำลังพัฒนาเกิดจากการแก้ไขบั๊กก่อนหน้า ควรใส่คอมเมนต์อธิบายว่าโค้ดส่วนนั้นแก้ไขบั๊กอย่างไร หรือบางทีก็อ้างอิงหมายเลขบั๊กเข้าไปเลย

9. **เตือนว่ายังอิมพลีเมนต์ไม่เสร็จ**: หลายโครงการมีฟีเจอร์ที่อิมพลีเมนต์ไว้ครึ่งๆ กลางๆ การใส่คอมเมนต์ TODO ค่อนข้างเป็นมาตรฐาน หรือให้ดีก็อ้างอิงถึง issue tracker ที่กำลังคุยกันถึงการแก้ไขโค้ดส่วนนั้นไว้เลย

คำแนะนำในการเขียนคอมเมนต์โค้ดนั้นมีหลากหลาย แต่แนวทางของ StackOverflow ก็นับว่าครอบคลุมกรณีส่วนใหญ่ โดยเฉพาะการใส่ที่มาในข้อ 6-8 ที่คำแนะนำบางที่ไม่ได้กล่าวถึงกัน

<p align="center">
<img src="https://www.blognone.com/sites/default/files/externals/48fa4f09d20571034b296799160834bc.png" style="width:700px;height:450px;">
</p>

คอมเมนต์ทุกบรรทัดโดยไม่จำเป็นทำให้โค้ดอ่านยากกว่าเดิม ตัวอย่างโดย [Professional_Marxman](https://www.reddit.com/r/ProgrammerHumor/comments/5dhdt6/my_teacher_told_me_i_needed_to_comment_every_line/da56d6m/)

### ที่มา [Blognone](https://www.blognone.com/node/126445)

---
