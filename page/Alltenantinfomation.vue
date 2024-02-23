<template>
    <Navbar/>
      <!-- หัวข้อ -->
      <div class="mt-5 ml-36">
          <span class="text-2xl font-bold">รายละเอียดและรายชื่อของผู้เช่า</span>
      </div>
      
      <!-- เมนูค้นหา -->
      <div class="bg-white ml-56 mr-56 mt-7">
        <div class='relative '>
            <input type="text" placeholder="Enter name" class="pl-10 pr-4 py-2 rounded-lg border border-gray-300 w-full">
            <div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none">
                <svg class="h-5 w-5 text-gray-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 10-14 0 7 7 0 0014 0z" />
                </svg>
            </div>
        </div>    
      </div>
  
      <!-- ห้อง -->
      <div class="ml-40">
          <p class="text-xl font-bold">ห้องทั้งหมด</p>
      </div>
      
      <!-- ข้อมูลผู้เช่าคนที่1 -->
      <div class="flex">
        <div class="h-full mx-auto flex rounded-sm">
            <div class="">
                <p class="bg-[#63C3FF] px-9 py-3 font-bold text-2xl">A101</p>
            </div>
  
            <div class="w-1/5 flex justify-center items-center">
                <img src="./public/nadeach.jpg" class="rounded-full w-[150px] h-[150px]"/>
            </div>
            
            <div class="flex justify-center items-center">
              <ul class="">
                <li class="fa fa-user"><b> ชื่อ</b> : ณเดชน์ คลูชิมิจ๊ะ</li>
                <li class="fa fa-phone"><b> เบอร์โทรศัพท์</b> : 099-9999999</li>
                <li class=""><b>เริ่มทำสัญญาเมื่อ</b> 14 มกราคม 2541</li>
              </ul>
            </div>
  
            <div class="flex justify-center items-center">
                <ul>
                    <li class="fa fa-user "><b> ชื่อเล่น</b>: น้องเดชน์</li>
                    <li class=""><b> อีเมล</b>: Nadacheiei@gimi.com</li>
                    <li class=""><b>เพศ</b>: ชาย</li>
                </ul>
            </div>
            
            <div class="button">
                <ul id="button3"> 
                    <li class="p-5 bg-green-400 "><a href="#"><b>สถานะ</b>: กำลังเช่า</a></li>
                </ul>
                <ul id="button1">
                    <li class="hover:bg-auto p-5 bg-blue-400"><a href="#" target="_blank"><b>แชทกับผู้เช่า</b></a></li>
                </ul>
                <ul id="button2">
                    <li class="hover:bg-auto p-5 bg-sky-300"><a href="localhost:3000/inde" target="_self"><b>รายละเอียดเพิ่มเติม...</b></a></li>
                </ul>
            </div>
          </div>
      </div>
     <!-- ---------------------- -->
     <br>
      <!-- ข้อมูลผู้เช่าคนที่2 -->
      <div class="bg-white h-[250px] flex ">
          <div class="container mx-auto h-full flex  bg-sky-100 ">
              <div class="roomnum1 bg-slate-900 float-left">
              <ul>
                  <li class="p-9"><b>A102</b></li>
              </ul>
          </div>
              <div class="w-1/3 flex flex-col justify-center items-center ">
                  <div id="pic1">
                      <img src="./public/user.jpg" class="rounded-full w-[150px] h-[150px]" />
                  </div>
                  
              </div>
          <div class="infomation1 ">
              <ul>
                  <li class="fa fa-user p-4"><b> ชื่อ</b> : พลตำรวจเอก ฟามรัก</li>
                  <li class="fa fa-phone p-4"><b> เบอร์โทรศัพท์</b> : 099-9999999</li>
                  <li class="p-4"><b>เริ่มทำสัญญาเมื่อ</b> 14 มกราคม 2541</li>
              </ul>
          </div>
  
           <div class="infomation1">
              <ul>
                  <li class="fa fa-user p-4"><b> ชื่อเล่น</b>: จุ้ก</li>
                  <li class="p-4"><b>อีเมล</b>: pkoekcheiei@gimi.com</li>
                  <li class="p-4"><b>เพศ</b>: ชาย</li>
              </ul>
          </div>
          <div class="button">
              <ul id="button3"> 
                  <li class="p-5 bg-orange-400 "><a href="#"><b>สถานะ</b>: ค้างเช่า</a></li>
              </ul>
              <ul id="button1">
                  <li class="hover:bg-auto p-5 bg-blue-400"><a href="#" target="_blank"><b>แชทกับผู้เช่า</b></a></li>
              </ul>
              <ul id="button2">
                  <li class="hover:bg-auto p-5 bg-sky-300"><a href="#" target="_blank"><b>รายละเอียดเพิ่มเติม...</b></a></li>
              </ul>
          </div>
           </div>
      </div>
  <!-- ----------------------------- -->
      <br>
      <!-- ผู้เช่าคนที่ 3 -->
      <div class="bg-white h-[250px] ">
          <div class="container mx-auto h-full flex  bg-sky-100 ">
              <div class="roomnum1 bg-slate-900 float-left">
              <ul>
                  <li class="p-9"><b>B101</b></li>
              </ul>
          </div>
              <div class="w-1/3 flex flex-col justify-center items-center ">
                  <div id="pic1">
                      <img src="./public/us33.jpg" class="rounded-full w-[150px] h-[150px]" />
                  </div>
                  
              </div>
          <div class="infomation1 ">
              <ul>
                  <li class="fa fa-user p-4"><b> ชื่อ</b> : เอเรน เยเกอร์</li>
                  <li class="fa fa-phone p-4"><b> เบอร์โทรศัพท์</b> : 099-9999999</li>
                  <li class="p-4"><b>เริ่มทำสัญญาเมื่อ</b> 8 ตุลาคม 2544</li>
              </ul>
          </div>
  
           <div class="infomation1">
              <ul>
                  <li class="fa fa-user p-4"><b> ชื่อเล่น</b>: เอเรน</li>
                  <li class="p-4"><b>อีเมล</b>: arenrakmikasanakub@gimi.com</li>
                  <li class="p-4"><b>เพศ</b>: ชาย</li>
              </ul>
          </div>
          <div class="button">
              <ul id="button3"> 
                  <li class="p-5 bg-green-400 "><a href="#"><b>สถานะ</b>: กำลังเช่า</a></li>
              </ul>
              <ul id="button1">
                  <li class="hover:bg-auto p-5 bg-blue-400"><a href="#" target="_blank"><b>แชทกับผู้เช่า</b></a></li>
              </ul>
              <ul id="button2">
                  <li class="hover:bg-auto p-5 bg-sky-300"><a href="#" target="_blank"><b>รายละเอียดเพิ่มเติม...</b></a></li>
              </ul>
          </div>
           </div>
      </div>
      <!-- ---------------------- -->
      <br>
      <!-- ผู้เช่าคนที่ 4 -->
      <div class="bg-white h-[250px] ">
          <div class="container mx-auto h-full flex  bg-sky-100 ">
              <div class="roomnum1 bg-slate-900 float-left">
              <ul>
                  <li class="p-9"><b>B102</b></li>
              </ul>
          </div>
              <div class="w-1/3 flex flex-col justify-center items-center ">
                  <div id="pic1">
                      <img src="./public/jan.jpg" class="rounded-full w-[150px] h-[150px]" />
                  </div>
                  
              </div>
          <div class="infomation1 ">
              <ul>
                  <li class="fa fa-user p-4"><b> ชื่อ</b> : เจน ดีจริงๆ</li>
                  <li class="fa fa-phone p-4"><b> เบอร์โทรศัพท์</b> : 099-9999999</li>
                  <li class="p-4"><b>เริ่มทำสัญญาเมื่อ</b> 5 กรกฎาคม 2465</li>
              </ul>
          </div>
  
           <div class="infomation1">
              <ul>
                  <li class="fa fa-user p-4"><b> ชื่อเล่น</b>: เจน</li>
                  <li class="p-4"><b>อีเมล</b>: haiterdaikubkao44@gimi.com</li>
                  <li class="p-4"><b>เพศ</b>: หญิง</li>
              </ul>
          </div>
          <div class="button">
              <ul id="button3"> 
                  <li class="p-5 bg-green-400 "><a href="#"><b>สถานะ</b>: กำลังเช่า</a></li>
              </ul>
              <ul id="button1">
                  <li class="hover:bg-auto p-5 bg-blue-400"><a href="#" target="_blank"><b>แชทกับผู้เช่า</b></a></li>
              </ul>
              <ul id="button2">
                  <li class="hover:bg-auto p-5 bg-sky-300"><a href="#" target="_blank"><b>รายละเอียดเพิ่มเติม...</b></a></li>
              </ul>
          </div>
           </div>
      </div>
      <!-- -------------- -->
      <br>
      <!-- ผู้เช่าคนที่ 5 -->
      <!-- <div class="bg-white h-[250px] ">
          <div class="container mx-auto h-full flex  bg-sky-100 ">
              <div class="roomnum1 bg-slate-900 float-left">
              <ul>
                  <li class="p-9"><b>B103</b></li>
              </ul>
          </div>
              <div class="w-1/3 flex flex-col justify-center items-center ">
                  <div id="pic1">
                      <img src="./public/user.jpg" class="rounded-full w-[150px] h-[150px]" />
                  </div>
                  
              </div>
          <div class="infomation1 ">
              <ul>
                  <li class="fa fa-user p-4"><b> ชื่อ</b> : ผู้ใช้ และ นามสกุล</li>
                  <li class="fa fa-phone p-4"><b> เบอร์โทรศัพท์</b> : 099-9999999</li>
                  <li class="p-4"><b>เริ่มทำสัญญาเมื่อ</b> วัน กรกฎาคม 2465</li>
              </ul>
          </div>
  
           <div class="infomation1">
              <ul>
                  <li class="fa fa-user p-4"><b> ชื่อเล่น</b>: ผูเ้ช่า</li>
                  <li class="p-4"><b>อีเมล</b>: aaaaaa@gimi.com</li>
                  <li class="p-4"><b>เพศ</b>: หญิง</li>
              </ul>
          </div>
          <div class="button">
              <ul id="button3"> </ul>
          </div>
        </div>
      </div> -->
  </template>
  
  <script>
  export default {
    name: 'app'
  }
  </script>
  <style>
    body{
      font-family: "Poppins",sans-serif;
    }
  </style>
  