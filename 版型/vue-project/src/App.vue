<template>
  <div class="flair flair--3"></div>
  <el-header>
    <el-avatar :icon="UserFilled" />
    <div class="hamburger-menu" @click="toggleMenu">
      <i :class="['hamburger-icon', { open: menuOpen }]"></i>
    </div>
    <div class="demo-type" :class="{ open: menuOpen }">
      <el-link :underline="false" href="#" @click.prevent="scrollToElement('a')">傳送門1</el-link>
      <el-link :underline="false" href="#" @click.prevent="scrollToElement('b')">傳送門2</el-link>
      <el-link :underline="false" href="#" @click.prevent="scrollToElement('c')">傳送門3</el-link>
    </div>
  </el-header>
  <el-container>
    <swiper :modules="[Navigation]" navigation class="mySwiper">
      <swiper-slide><img src="https://picsum.photos/1920/500/?random=1" /></swiper-slide>
      <swiper-slide><img src="https://picsum.photos/1920/500/?random=2" /></swiper-slide>
      <swiper-slide><img src="https://picsum.photos/1920/500/?random=3" /></swiper-slide>
      <swiper-slide><img src="https://picsum.photos/1920/500/?random=4" /></swiper-slide>
      <swiper-slide><img src="https://picsum.photos/1920/500/?random=5" /></swiper-slide>
      <swiper-slide><img src="https://picsum.photos/1920/500/?random=6" /></swiper-slide>
      <swiper-slide><img src="https://picsum.photos/1920/500/?random=7" /></swiper-slide>
      <swiper-slide><img src="https://picsum.photos/1920/500/?random=8" /></swiper-slide>
      <swiper-slide><img src="https://picsum.photos/1920/500/?random=9" /></swiper-slide>
    </swiper>
  </el-container>
  <p>
    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Id porro modi accusantium voluptates
    quam totam, necessitatibus quae quas molestiae dolorum doloribus doloremque vero minus sunt
    aliquam sed facere recusandae obcaecati quidem repellendus ratione voluptatibus fugiat. Quaerat
    nostrum delectus vel id sed eveniet similique voluptatibus aspernatur ad, in, quod laudantium
    maiores.Quaerat nostrum delectus vel id sed eveniet similique voluptatibus aspernatur ad, in,
    quod laudantium maiores.Quaerat nostrum delectus vel id sed eveniet similique voluptatibus
    aspernatur ad Lorem ipsum dolor sit, amet consectetur adipisicing elit. Id porro modi
    accusantium voluptates quam totam, necessitatibus quae quas molestiae dolorum doloribus
    doloremque vero minus sunt aliquam sed facere recusandae obcaecati quidem repellendus ratione
    voluptatibus fugiat. Quaerat nostrum delectus vel id sed eveniet similique voluptatibus
    aspernatur ad, in, quod laudantium maiores.Quaerat nostrum delectus vel id sed eveniet similique
    voluptatibus aspernatur ad, in, quod laudantium maiores.Quaerat nostrum delectus vel id sed
    eveniet similique voluptatibus aspernatur ad aspernatur ad, in, quod laudantium maiores.Quaerat
    nostrum delectus vel id sed eveniet similique voluptatibus aspernatur ad aspernatur ad, in, quod
    laudantium maiores.Quaerat nostrum delectus vel id sed eveniet similique voluptatibus aspernatur
    ad similique voluptatibus aspernatur adadadad.Lorem ipsum dolor sit, amet consectetur
    adipisicing elit. Id porro modi accusant ium voluptates quam totam, necessitatibus quae quas
    molestiae dolorum doloribus doloremque vero minus sunt aliquam sed facere recusandae obcaecati
    quidem repellendus ratione voluptatibus fugiat. Quaerat nostrum delectus vel id sed eveniet
    similique voluptatibus aspernatur ad, in, quod laudantium maiores.Quaerat nostrum delectus vel
    id sed eveniet similique voluptatibus aspernatur ad, in, quod laudantium maiores.Quaerat nostrum
    delectus vel id sed eveniet similique voluptatibus aspernatur ad Lorem ipsum dolor sit, amet
    consectetur adipisicing elit. Id porro modi accusantium voluptates quam totam, necessitatibus
    quae quas molestiae dolorum doloribus doloremque vero minus sunt aliquam sed facere recusandae
    obcaecati quidem repellendus ratione voluptatibus fugiat. Quaerat nostrum delectus vel id sed
    eveniet similique voluptatibus aspernatur ad, in, quod laudantium maiores.Quaerat nostrum
    delectus vel id sed eveniet similique voluptatibus aspernatur ad, in, quod laudantium
    maiores.Quaerat nostrum delectus vel id sed eveniet similique voluptatibus aspernatur ad
    aspernatur ad, in, quod laudantium maiores.Quaerat nostrum delectus vel id sed eveniet similique
    voluptatibus aspernatur ad aspernatur ad, in, quod laudantium maiores.Quaerat nostrum delectus
    vel id sed eveniet similique voluptatibus aspernatur ad similique voluptatibus aspernatur
    adadadad.Lorem ipsum dolor sit, amet consectetur adipisicing elit. Id porro modi accusant ium
    voluptates quam totam, necessitatibus quae quas molestiae dolorum doloribus doloremque vero
    minus sunt aliquam sed facere recusandae obcaecati quidem repellendus ratione voluptatibus
    fugiat. Quaerat nostrum delectus vel id sed eveniet similique voluptatibus aspernatur ad, in,
    quod laudantium maiores.Quaerat nostrum delectus vel id sed eveniet similique voluptatibus
    aspernatur ad, in, quod laudantium maiores.Quaerat nostrum delectus vel id sed eveniet similique
    voluptatibus aspernatur ad Lorem ipsum dolor sit, amet consectetur adipisicing elit. Id porro
    modi accusantium voluptates quam totam, necessitatibus quae quas molestiae dolorum doloribus
    doloremque vero minus sunt aliquam sed facere recusandae obcaecati quidem repellendus ratione
    voluptatibus fugiat. Quaerat nostrum delectus vel id sed eveniet similique voluptatibus
    aspernatur ad, in, quod laudantium maiores.Quaerat nostrum delectus vel id sed eveniet similique
    voluptatibus aspernatur ad, in, quod laudantium maiores.Quaerat nostrum delectus vel id sed
    eveniet similique voluptatibus aspernatur ad aspernatur ad, in, quod laudantium maiores.Quaerat
    nostrum delectus vel id sed eveniet similique voluptatibus aspernatur ad aspernatur ad, in, quod
    laudantium maiores.Quaerat nostrum delectus vel id sed eveniet similique voluptatibus aspernatur
    ad similique voluptatibus aspernatur adadadad.
  </p>
  <div class="flex flex-wrap gap-12">
    <el-card style="width: 100%; height: 330px" data-aos="zoom-out-down" id="a">
      <img src="https://picsum.photos/1920/300/?random=1" />
    </el-card>
    <el-card style="width: 100%; height: 330px" shadow="hover" data-aos="zoom-in-left" id="b">
      <img src="https://picsum.photos/1920/300/?random=2" />
    </el-card>
    <el-card style="width: 100%; height: 330px" shadow="never" data-aos="flip-left" id="c">
      <img src="https://picsum.photos/1920/300/?random=3" />
    </el-card>
  </div>
</template>

<script setup>
import { ref } from 'vue'
import { UserFilled } from '@element-plus/icons-vue'
import 'swiper/css'
import 'swiper/css/navigation'
import { Swiper, SwiperSlide } from 'swiper/vue'
import { Navigation } from 'swiper/modules'
import AOS from 'aos'
import 'aos/dist/aos.css'
import { gsap } from 'gsap'

// 初始化 AOS
AOS.init()

const menuOpen = ref(false)

function toggleMenu() {
  menuOpen.value = !menuOpen.value
}

function scrollToElement(id) {
  console.log(`Attempting to scroll to element with ID: ${id}`)
  const element = document.getElementById(id)
  if (element) {
    console.log('Element found:', element)
    element.scrollIntoView({ behavior: 'smooth' })
    menuOpen.value = false
  } else {
    console.error('Element not found')
  }
}

// 監聽鼠標移動事件，更新.flair 元素的位置
window.addEventListener('mousemove', (e) => {
  gsap.to('.flair', {
    x: e.clientX,
    y: e.clientY,
    duration: 0.6,
    ease: 'power3'
  })
})

// 設置初始狀態
gsap.set('.flair', { xPercent: -50, yPercent: -50 })
</script>

<style scoped>
header {
  margin: 30px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.el-link {
  margin: 0 50px 0 0;
  font-size: 30px;
}

.demo-type {
  display: flex;
  align-items: center;
}

.flex {
  display: flex;
}

.flex-wrap {
  flex-wrap: wrap;
}

.gap-12 {
  gap: 12px;
}

.flair {
  width: 100px;
  height: 100px;
  position: fixed;
  top: 0;
  left: 0;
  pointer-events: none;
  background: url(https://stickershop.line-scdn.net/stickershop/v1/product/3065/LINEStorePC/main.png?v=1);
  background-size: cover;
  mix-blend-mode: difference; /* 使元素與背景有對比 */
}

.hamburger-menu {
  display: none;
  cursor: pointer;
}

.hamburger-icon {
  width: 30px;
  height: 3px;
  background-color: black;
  position: relative;
  transition: all 0.3s;
}

.hamburger-icon::before,
.hamburger-icon::after {
  content: '';
  width: 30px;
  height: 3px;
  background-color: black;
  position: absolute;
  transition: all 0.3s;
}

.hamburger-icon::before {
  top: -10px;
}

.hamburger-icon::after {
  top: 10px;
}

.hamburger-icon.open {
  background-color: transparent;
}

.hamburger-icon.open::before {
  top: 0;
  transform: rotate(45deg);
}

.hamburger-icon.open::after {
  top: 0;
  transform: rotate(-45deg);
}

.demo-type {
  display: flex;
  align-items: center;
  transition:
    max-height 0.3s ease,
    transform 0.3s ease;
  overflow: hidden;
  position: absolute;
  right: 50px;
  top: 10px;
  white-space: nowrap;
}

.demo-type.open {
  max-height: 200px;
  transform: translateX(-110%); /* 调整展開距離 */
}

@media (max-width: 767px) {
  .demo-type {
    flex-direction: row;
    align-items: flex-start;
    max-height: 0;
    position: absolute;
    right: 10px;
    top: 10px;
  }

  header {
    margin: 10px;
  }

  .swiper-slide img {
    height: 200px;
  }

  .el-card {
    height: 200px;
  }

  p {
    font-size: 14px;
  }

  .hamburger-menu {
    display: block;
  }

  .demo-type {
    flex-direction: row;
    align-items: flex-start;
    max-height: 0;
    position: absolute;
    right: 10px;
    top: 10px;
  }

  .demo-type.open {
    max-height: 200px;
    transform: translateX(-10%); /* 调整展開距离 */
  }

  .el-link {
    margin: 0 5px;
  }
}

@media (min-width: 768px) and (max-width: 1023px) {
  .el-link {
    font-size: 20px;
    margin: 0 20px 0 0;
  }

  header {
    margin: 20px;
  }

  .swiper-slide img {
    height: 300px;
  }

  .el-card {
    height: 250px;
  }

  p {
    font-size: 16px;
  }
}

@media (min-width: 1024px) {
  .el-link {
    font-size: 30px;
    margin: 0 50px 0 0;
  }

  header {
    margin: 30px;
  }

  .swiper-slide img {
    height: 500px;
  }

  .el-card {
    height: 330px;
  }

  p {
    font-size: 18px;
  }
}
</style>
