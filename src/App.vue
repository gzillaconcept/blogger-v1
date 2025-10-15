<script setup>
import { RouterLink, RouterView } from 'vue-router'
// import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <nav class="flex flex-row justify-between px-10 bg-black h-48px">
    <div>
      <ul class="font-semibold menu menu-horizontal px-1">
        <li><a>THE MAUVE</a></li>
      </ul>
    </div>
    <div>
      <ul class="menu menu-horizontal px-1">
        <li><a>ติดต่อเรา</a></li>
      </ul>
    </div>
  </nav>
  <div class="flex flex-col items-center bg-base-100 shadow-sm">
    <figure class="flex items-center">
      <img src="../src/assets/sd_68dcab71965b8.jpg" alt="Movie" />
    </figure>
    <div class="card-body">
      <h1 class="card-title text-4xl font-semibold">สารสกัดโปรตีนไหมซิริซิน</h1>
      <p class="text-lg font-medium">เผยความงามจากภายในสู่ภายนอก</p>

      <p>
        สารบำรุงผิวที่ซ่อนเร้นอยู่ในธรรมชาติมายาวนานกว่า 4,700 ปี เซริซินคือโปรตีนคุณภาพสูงจากใยไหม ประกอบด้วยกรดอะมิโน
        18 ชนิด ซึ่งมีคุณสมบัติใกล้เคียงกับกรดอะมิโนที่เป็นส่วนประกอบของร่างกายมนุษย์
        ช่วยเสริมสร้างและฟื้นฟูเซลล์ผิวอย่างน่าอัศจรรย์ ช่วยสร้างเซลล์ไฟโบรบลาสต์ ซึ่งมีหน้าที่สร้างคอลลาเจนโดยตรง
        และยังช่วยยับยั้งเอนไซม์ไทโรซิเนส ซึ่งเป็นสาเหตุของการเกิดเม็ดสีผิว ช่วยปรับสภาพผิวอย่างสมบูรณ์แบบ
        มีประสิทธิภาพในการซึมซาบอย่างล้ำลึก พร้อมมอบความชุ่มชื้นอย่างยาวนานถึง 300 เท่า ช่วยให้ผิวตึงกระชับ เรียบเนียน
        นุ่ม และมอบความกระจ่างใสและผิวอ่อนเยาว์อย่างเป็นธรรมชาติ
      <h1 class="text-lg font-medium">การประยุกต์ใช้ทางการแพทย์</h1>
      <p>
        โปรตีนไหมเซริซินมีคุณสมบัติที่ดีหลายประการ เช่น ลดการอักเสบ ต้านจุลชีพ ดูดซับและระบายความชื้นได้ดี
        เข้ากันได้ดีกับโปรตีนในร่างกายมนุษย์และสามารถกระตุ้นการเจริญเติบโตของเซลล์
        จึงถูกนำมาประยุกต์ใช้ในด้านวิศวกรรมเนื้อเยื่อทางการแพทย์ ระบบนำส่งยา สารออกฤทธิ์ หรือเพื่อรักษาโรค
        ใช้สำหรับทาแผลเพื่อช่วยรักษาความชุ่มชื้นในแผล ส่งเสริมกระบวนการสมานแผล
        กระตุ้นการสร้างคอลลาเจนเพื่อให้แผลหายเร็วขึ้น และกำจัดแบคทีเรีย</p>

      <h1 class="text-lg font-medium">อาหารและสุขภาพ</h1>

      <p>โปรตีนเซริซินจากไหม เมื่อนำมาใช้เป็นส่วนผสมอาหาร จะมีสารที่ควบคุมคอเลสเตอรอลในหลอดเลือด สลายแอลกอฮอล์ในร่างกาย
        ช่วยความจำ และกระตุ้นการทำงานของหัวใจ อาหารที่มีโปรตีนเซริซินเป็นส่วนประกอบ เช่น ไส้กรอก มีลักษณะนุ่มละมุน
        สีสดเหมือนเพิ่งทำใหม่ๆ ไอศกรีมจะทำให้ไม่ละลายง่ายและเนียน ส่วนเส้นก๋วยเตี๋ยวจะทำให้เหนียวนุ่ม</p>

      <h1 class="text-lg font-medium">สารสกัดผงโปรตีนไหมเซริซิน</h1>

      <p>สารสกัดผงโปรตีนไหมเซริซินได้จากรังไหมสีทองธรรมชาติ ใช้สำหรับเป็นส่วนผสมสำหรับการผลิตเครื่องสำอาง
        ผลิตภัณฑ์ดูแลผิว ผลิตภัณฑ์ทางการแพทย์ ทรีทเมนต์โดยตรง และสปา ฯลฯ
        ผลิตภัณฑ์สารสกัดโปรตีนไหมเซริซินของเรา ไม่ได้สกัดจากน้ำรังไหมต้มในอุตสาหกรรมทอผ้า
        กระบวนการผลิตของเราเป็นการสกัดแบบธรรมชาติด้วยการต้มรังไหมและสเปรย์ดรายให้เป็นผงปราศจากสารเคมี ไม่เป็นอันตราย
        ไม่มีส่วนผสมอื่นๆ ความเข้มข้นสูง และบริสุทธิ์ 100% เราเปิดรังไหมและนำดักแด้ออก
        เพื่อให้ดักแด้ไหมกลายเป็นผีเสื้อตามวงจรชีวิตของแมลง
      </p>

      <h1 class="text-lg font-medium">เราคือใคร</h1>

      <p>เรามุ่งมั่นที่จะจัดหาวัตถุดิบจากธรรมชาติสำหรับบริการความงาม คัดสรรวัตถุดิบคุณภาพในราคาที่เหมาะสม
        สร้างความพึงพอใจให้กับลูกค้า และมุ่งมั่นพัฒนางานวิจัยอย่างต่อเนื่อง เรามีฟาร์มไหมขนาดเล็กเป็นของตัวเอง
        ดำเนินการมากว่า 30 ปี กระบวนการผลิตด้วยมือทุกขั้นตอน การสกัดโปรตีนไหม
        เราได้ส่งวัตถุดิบไปยังห้องปฏิบัติการและโรงงานที่ได้มาตรฐานสากล

        เราดูแลแหล่งเพาะเลี้ยงดักแด้เพื่อให้ความอบอุ่น และเพื่อให้มันเติบโตเป็นผีเสื้อตามวงจรชีวิตของแมลง</p>
      </p>
    </div>
    <figure class="flex items-center">
      <img src="../src/assets/sd_68dccab3a2f7f.jpg" alt="Movie" />
    </figure>
  </div>
  <div class="flex flex-col items-center bg-gray-900 text-white p-6">
  <h2 class="text-4xl font-medium mb-4">Contact</h2>

  <form class="flex flex-col w-full max-w-md space-y-4">
    <div class="flex flex-col py-2">
      <label for="email" class="mb-1">อีเมล</label>
      <input
        id="email"
        type="email"
        placeholder="อีเมล"
        class="w-full px-2 py-2 rounded border border-gray-600 bg-gray-800 focus:outline-none focus:ring-2 focus:ring-blue-500"
      />
    </div>

    <div class="flex flex-col py-2">
      <label for="subject" class="mb-1">เรื่องที่ต้องการติดต่อ</label>
      <input
        id="subject"
        type="text"
        placeholder="เรื่อง"
        class="w-full px-2 py-2 rounded border border-gray-600 bg-gray-800 focus:outline-none focus:ring-2 focus:ring-blue-500"
      />
    </div>

    <div class="flex flex-col py-2">
      <label for="message" class="mb-1">ข้อความ</label>
      <textarea
        id="message"
        placeholder="ข้อความ"
        class="w-full h-24 px-2 py-2 rounded border border-gray-600 bg-gray-800 focus:outline-none focus:ring-2 focus:ring-blue-500"
      ></textarea>
    </div>
<div class="py-2">
  <button
      type="submit"
      class="w-full py-3 mt-2 bg-blue-600 rounded hover:bg-blue-700 transition"
    >
      ส่งข้อความ
    </button></div>
    
  </form>
</div>

  <footer class="flex flex-col items-center bg-black py-5">
    <h1 class="card-title text-2xl font-medium pb-2">The Mauve</h1>
    <p>

      1 หมู่ 7 ต.หนองแดง อ.แม่จริม จ.น่าน 55170</p>
    <p>เบอร์ติดต่อ : 093-4299624</p>


  </footer>
</template>
