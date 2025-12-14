<script setup>
import { computed, ref } from 'vue'
import dmmphoto from './Photo/DMM.jpg'
import fishmarketphoto from './Photo/FishMarket2.jpg'
import UOphoto from './Photo/UO.jpg'
import hotelphoto from './Photo/Hotel.jpg'
import longislandphoto from './Photo/LongIsland.jpg'
import porktamagophoto from './Photo/PorkTamago.jpg'
import shabuphoto from './Photo/Shabu.jpg'
import outletphoto from './Photo/Outlet.jpg'
import kushiyakiCanphoto from './Photo/KushiyakiCan.jpg'
import parkphoto from './Photo/Park.jpg'
import ATVphoto from './Photo/ATV.jpg'
import SanAphoto from './Photo/SanA.jpg'
import Round1photo from './Photo/Round1.jpg'
import breakfastphoto from './Photo/Breakfast.jpg'
import beautifulaquariumphoto from './Photo/BeautifulAquarium.jpg'
import USvillagephoto from './Photo/USVillage.jpg'
import HanasakiMarchephoto from './Photo/HanasakiMarche.jpg'
import nothingphoto from './Photo/Nothing.jpg'
import gatheringphoto from './Photo/Gathering.jpg'
import beefphoto from './Photo/Beef.jpg'
import kingvillagephoto from './Photo/KingVillage.jpg'
import holephoto from './Photo/Hole.jpg'
import gangalaphoto from './Photo/Gangala.jpg'
import donkiphoto from './Photo/Donki.jpg'
import saporrodrugphoto from './Photo/SaporroDrug.jpg'
import busphoto from './Photo/Bus.jpg'
import burgerphoto from './Photo/Burger.jpg'
import gelatophoto from './Photo/Gelato.jpg'
import calbeephoto from './Photo/Calbee.jpg'
import saltphoto from './Photo/Salt.jpg'
import Dessertphoto from './Photo/Dessert.jpg'
import PocoCafephoto from './Photo/PocoCafe.jpg'
import Ramenphoto from './Photo/Ramen.jpg'



const days = ref([
  {
    id: 1,
    title: 'Day 1 · ✈️ 抵達日',
    date: '2025-12-21',
    weatherUrl: 'https://www.data.jma.go.jp/multi/yoho/yoho_detail.html?code=471010&lang=cn_zt',
    items: [
      {
        id: 11,
        time: '15:50',
        title: '✈️ UO826 香港 → 那覇',
        image: UOphoto,
        busRouteNote: '航班 UO826 15:50–19:20',
        openingHours: null,
        remarks: '到達那覇機場，出關、搭車去酒店。',
        mapLink: 'https://www.google.com/maps/place/%E9%82%A3%E9%9C%B8%E6%A9%9F%E5%A0%B4%E5%9C%8B%E9%9A%9B%E7%B7%9A%E8%88%AA%E5%BB%88/@26.2091396,127.6484447,17z/data=!3m1!4b1!4m6!3m5!1s0x34e569c4911ff08d:0xe36f832c2a0a80de!8m2!3d26.2091348!4d127.6510196!16s%2Fg%2F11f66vvhqm?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
      },
      {
        id: 12,
        time: '21:00',
        title: '🏨 Naha Tokyu REI Hotel Check-in',
        image: hotelphoto,
        openingHours: null,
        busRouteNote: '🚇 單軌電車，15分鐘',
        remarks: '放低行李，附近隨便食晚餐',
        mapLink: 'https://www.google.com/maps/place/Naha+Tokyu+REI+Hotel/@26.2081627,127.6759971,17z/data=!3m1!5s0x34e5699f15fad57f:0x72618271fe093b83!4m10!3m9!1s0x34e5699f148045a3:0xf409aaf810c14b78!5m3!1s2025-12-18!4m1!1i2!8m2!3d26.2097786!4d127.6773562!16s%2Fg%2F1tgh9xds?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
      }
    ]
  },

  {
    id: 2,
    title: 'Day 2 · 🐠 DMM 水族館日',
    date: '2025-12-22',
    weatherUrl: 'https://www.data.jma.go.jp/multi/yoho/yoho_detail.html?code=471010&lang=cn_zt',
    items: [
      {
        id: 21,
        time: '11:00',
        title: '🍣 糸満魚市場',
        image: fishmarketphoto,
        openingHours: '10:00–19:00',
        busRouteNote: '🚌 89巴士 · 約50分鐘',
        remarks: '平靚正魚生。',
        mapLink: 'https://www.google.com/maps/place/%E7%B3%B8%E6%BB%BF%E9%AD%9A%E5%B8%82%E5%A0%B4/@26.1387399,127.6723107,13z/data=!4m6!3m5!1s0x34e567c221f4f19d:0x58162367592c3315!8m2!3d26.1380987!4d127.6613785!16s%2Fg%2F1td2k73b?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
      },
      {
        id: 22,
        time: '13:00',
        title: '🐠 DMM水族館',
        image: dmmphoto,
        openingHours: '09:00–19:00',
        busRouteNote: '🚌 TK02 · 約14分鐘',
        remarks: '互動型水族館 · 用 Okinawa FunPass。',
        mapLink: 'https://maps.app.goo.gl/ULehVR3a7QWQUyKQ8?g_st=ipc'
      },
      {
        id: 23,
        time: '17:00',
        title: '🌅 瀨長島 日落',
        image: longislandphoto,
        openingHours: null,
        busRouteNote: '🚌 TK02 · 約15分鐘',
        remarks: '影日落，大約17:40',
        mapLink: 'https://www.google.com/maps/place/%E7%80%A8%E9%95%B7%E5%B3%B6/@26.1876905,127.6414562,14.25z/data=!4m6!3m5!1s0x34e5681e893b714d:0xa5360835fe2d83b8!8m2!3d26.1766603!4d127.6404367!16s%2Fg%2F11bw5zqltd?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
      },
      {
        id: 24,
        time: '20:00',
        title: '💄 札幌藥妝 國際通店',
        image: saporrodrugphoto,
        openingHours: '11:00–22:00',
        busRouteNote: '🚌 TK02 + 🚇 Metro',
        remarks: '藥妝盡力掃\n來店不限金額消費並出示兌換券即享來店禮一份\n消費滿5000日圓，享85折 (10%免稅＋5% off)',
        mapLink: 'https://www.google.com/maps/place/%E6%9C%AD%E5%B9%8C%E8%97%A5%E5%A6%9D+%E6%B2%96%E7%B9%A9%E5%9C%8B%E9%9A%9B%E9%80%9A%E5%BA%97/@26.2119572,127.6797148,16z/data=!3m1!5s0x34e56977ca477bc1:0x37add69ad70a419b!4m6!3m5!1s0x34e56977cbab4267:0x9d76b47d13828856!8m2!3d26.214528!4d127.6824331!16s%2Fg%2F11c5sw4qxy?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
      },
      {
        id: 25,
        time: '20:30',
        title: '🛒 Donki 那覇壺川店',
        image: donkiphoto,
        openingHours: '08:00–03:00',
        busRouteNote: '🚶 步行約2分鐘',
        remarks: '連到酒店 ，適合最後掃貨。\n消費税前滿10000日幣，享85折 (10%免稅＋5% off)，消費税前滿30000日幣，享83折 (10%免稅＋7% off)',
        mapLink: 'https://www.google.com/maps/place/%E5%94%90%E5%90%89%E8%A8%B6%E5%BE%B7+%E9%82%A3%E9%9C%B8%E5%A3%BA%E5%B7%9D%E5%BA%97/@26.2119572,127.6797148,16z/data=!3m1!5s0x34e569a1d837fb8d:0x35ab80a3f176ef31!4m10!3m9!1s0x34e5695e41a68adf:0x1d991fdd5dcdadf1!5m3!1s2025-12-18!4m1!1i2!8m2!3d26.2081133!4d127.6778504!16s%2Fg%2F11h4g8dby_?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
      }
    ]
  },

  { id: 3,
     title: 'Day 3 · 🏰 沖繩世界文化王國日',
     date: '2025-12-23',
     weatherUrl: 'https://www.data.jma.go.jp/multi/yoho/yoho_detail.html?code=471010&lang=cn_zt', 
     items: [
  {
    id: 31,
    time: '10:00',
    title: '⛰️ Gangala 之谷',
    image: gangalaphoto,
    openingHours: '09:00-16:00',
    busRouteNote: '🚌 54巴士 (08:45)',
    remarks: '穿運動鞋\n洞內濕冷',
    mapLink: 'https://www.google.com/maps/place/Gangala%E4%B9%8B%E8%B0%B7/@26.1399316,127.746722,17.25z/data=!4m6!3m5!1s0x34e56f694e9fa999:0xad0c7c6998743d6!8m2!3d26.141889!4d127.7469057!16s%2Fg%2F11d_d2l1nd?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
  },
  {
    id: 32,
    time: '12:00',
    title: '🏰 沖繩世界文化王國',
    image: kingvillagephoto,
    openingHours: '09:30-17:30',
    busRouteNote: '',
    remarks: 'Okinawa FunPass\n玻璃體驗',
    mapLink: 'https://www.google.com/maps/place/%E6%B2%96%E7%B9%A9%E4%B8%96%E7%95%8C/@26.1399316,127.746722,17.25z/data=!4m6!3m5!1s0x34e56f6969c6afcd:0xfed80b6e91aa9dcb!8m2!3d26.1404807!4d127.7489447!16s%2Fg%2F11bwy_9ddh?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
  },
  {
    id: 33,
    time: '12:00',
    title: '🪨 玉泉洞',
    image: holephoto,
    openingHours: null,
    busRouteNote: '',
    remarks: 'Okinawa FunPass包埋\n有時間先去',
    mapLink: 'https://www.google.com/maps/place/%E7%8E%89%E6%B3%89%E6%B4%9E/@26.1403435,127.7487907,19z/data=!3m1!4b1!4m6!3m5!1s0x34e56985519f786b:0x5e9a8bdcd64306dd!8m2!3d26.1403423!4d127.7494344!16s%2Fg%2F121vxnxv?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
  },
  {
    id: 34,
    time: '19:00',
    title: '🥩 琉球之牛 那覇久茂地店',
    image: beefphoto,
    openingHours: '17:00-23:00',
    busRouteNote: '🚌 54巴士',
    remarks: '沖繩燒肉名店\nBooking number:N7APA7',
    mapLink: 'https://www.google.com/maps/place/%E7%84%BC%E8%82%89+%E7%90%89%E7%90%83%E3%81%AE%E7%89%9B+%E9%82%A3%E8%A6%87%E4%B9%85%E8%8C%82%E5%9C%B0/@26.2164689,127.6820774,17.17z/data=!4m6!3m5!1s0x34e569d4b50475dd:0xccda9cf6e2c8caaf!8m2!3d26.2156112!4d127.6818936!16s%2Fg%2F11xvx5lsxx?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
  }
]},
{ id: 4,
     title: 'Day 4 · 🐠 美麗海水族館日',
     date: '2025-12-24',
     weatherUrl: 'https://www.data.jma.go.jp/multi/yoho/yoho_detail.html?code=471010&lang=cn_zt', 
     items: [
  {
    id: 41,
    time: '08:30',
    title: '🧑‍🤝‍🧑 Klook團集合',
    image: gatheringphoto,
    openingHours: null,
    busRouteNote: '🚶 步行，10分鐘',
    remarks: '集合地點：那霸縣前廳前blue seal palette 久茂地店\n訂單編號：GXS708665',
    mapLink: 'https://www.google.com/maps/place/Blue+Seal+Palette%E4%B9%85%E8%8C%82%E5%9C%B0%E5%BA%97/@26.2135334,127.6780175,17.5z/data=!3m1!5s0x34e5699dcf5496af:0x579b3bcc4d2041e0!4m14!1m7!3m6!1s0x34e5699dbf5d4f01:0x68fc35666e138059!2zQmx1ZSBTZWFsIFBhbGV0dGXkuYXojILlnLDlupc!8m2!3d26.2135781!4d127.6795951!16s%2Fg%2F1hm2w88k6!3m5!1s0x34e5699dbf5d4f01:0x68fc35666e138059!8m2!3d26.2135781!4d127.6795951!16s%2Fg%2F1hm2w88k6?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
  },
  {
    id: 42,
    time: '09:45',
    title: '🌊 萬座毛',
    openingHours: null,
    image: nothingphoto,
    busRouteNote: '🚌 Klook',
    remarks: '真係乜都冇\n一定要防曬',
    mapLink: 'https://www.google.com/maps/place/%E8%90%AC%E5%BA%A7%E6%AF%9B/@26.4829677,127.8539811,13.75z/data=!4m6!3m5!1s0x34e503788741a7f9:0xdfec3d6fcce75918!8m2!3d26.5052353!4d127.8504781!16s%2Fg%2F1218dy2r?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
  },
  {
    id: 43,
    time: '11:40',
    title: '🍙 Hanasaki Marche商場',
    openingHours: null,
    image: HanasakiMarchephoto,
    busRouteNote: '🚌 Klook',
    remarks: 'Klook推介海景星巴克同埋豬肉蛋飯團',
    mapLink: 'https://www.google.com/maps/place/Hanasaki+Marche/@26.6821939,127.8809598,17z/data=!4m6!3m5!1s0x34e4fbd751e110df:0x30890e2a61ecd092!8m2!3d26.6821891!4d127.8835347!16s%2Fg%2F11g4cz6s4s?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
  },
  {
    id: 44,
    time: '12:50',
    title: '🐠 美麗海水族館',
    openingHours: null,
    image: beautifulaquariumphoto,
    busRouteNote: '🚌 Klook',
    remarks: 'Okinawa FunPass',
    mapLink: 'https://www.google.com/maps/place/%E6%B2%96%E7%B9%A9%E7%BE%8E%E9%BA%97%E6%B5%B7%E6%B0%B4%E6%97%8F%E9%A4%A8/@26.6923171,127.8852663,13.75z/data=!3m1!5s0x34e4fa331411ea83:0xa075f02c5f1d5747!4m6!3m5!1s0x34e4fa3152619e3d:0xea08a6700fdd9ffe!8m2!3d26.694338!4d127.8780131!16zL20vMDUxdjVi?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
  },
  {
    id: 45,
    time: '17:30',
    title: '🗽 美國村',
    openingHours: null,
    image: USvillagephoto,
    busRouteNote: '🚌 Klook',
    remarks: 'AI話聖誕燈飾超靚',
    mapLink: 'https://www.google.com/maps/place/%E7%BE%8E%E5%9C%8B%E6%9D%91/@26.3164723,127.7541142,18.75z/data=!4m6!3m5!1s0x34e5130508159acd:0x1bde7c8b1d9e8bcc!8m2!3d26.3158799!4d127.7540077!16s%2Fg%2F122qywtm?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
  }
]},
{ id: 5,
     title: 'Day 5 · 🕹️ 遊戲日',
     date: '2025-12-25',
     weatherUrl: 'https://www.data.jma.go.jp/multi/yoho/yoho_detail.html?code=471010&lang=cn_zt', 
     items: [
  {
    id: 51,
    time: '10:00',
    title: '🧇 甘味處 萬丸',
    image: breakfastphoto,
    openingHours: '07:00-15:00',
    busRouteNote: '🚶 步行',
    remarks: 'Chill住食個靚早餐',
    mapLink: 'https://www.google.com/maps/place/%E7%94%98%E5%91%B3%E8%99%95+%E8%90%AC%E4%B8%B8+%E9%82%A3%E9%9C%B8%E6%B3%89%E5%B4%8E%E5%BA%97/@26.2116803,127.6753946,16.75z/data=!4m6!3m5!1s0x34e5699e86721ddf:0x4f6452ba851b94bf!8m2!3d26.2125886!4d127.6782911!16s%2Fg%2F1hc7qn0y8?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
  },
  {
    id: 52,
    time: '12:30',
    title: '🕹️ Round 1',
    image: Round1photo,
    openingHours: '10:00-00:00',
    busRouteNote: '🚌 大量巴士40分鐘',
    remarks: '係放電嘅時間',
    mapLink: 'https://www.google.com/maps/place/Round+1+Stadium/@26.2665376,127.713224,13.75z/data=!3m1!5s0x34e56ca3bc981893:0x5dd6c7c9dccd52da!4m6!3m5!1s0x34e56ca3bc94fbf9:0xc33e30a1271d66a3!8m2!3d26.2758032!4d127.7310375!16s%2Fg%2F1tdpjvh1?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
  },
  {
    id: 53,
    time: '13:00',
    title: '🛒 San-A',
    image: SanAphoto,
    openingHours: '09:00-22:00',
    busRouteNote: '🚶 步行',
    remarks: '潛在Dinner地方',
    mapLink: 'https://www.google.com/maps/place/San-A+Ginowan+Convention+City/@26.2561041,127.7110903,14.5z/data=!3m1!5s0x34e56ca23189bbbf:0x6d366f48ee744400!4m6!3m5!1s0x34e56ca23198770f:0x1b99b132f2716eec!8m2!3d26.2748925!4d127.7298419!16s%2Fg%2F119pg4cb0?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
  }
]},
{ id: 6,
     title: 'Day 6 · 🏎️ 南城ATV日',
     date: '2025-12-26',
     weatherUrl: 'https://www.data.jma.go.jp/multi/yoho/yoho_detail.html?code=471010&lang=cn_zt', 
     items: [
  {
    id: 61,
    time: '11:00',
    title: '🏎️ 南城南條飯店ATV',
    image: ATVphoto,
    openingHours: null,
    busRouteNote: '🚌 339/39巴士 1小時 (0943)',
    remarks: '戶外活動，帶防曬\nPass through the hotel front gate and proceed to the rear to see the gymnasium',
    mapLink: 'https://www.google.com/maps/place/%E5%8D%97%E5%9F%8E%E5%8D%97%E6%A2%9D%E9%A3%AF%E5%BA%97/@26.1649762,127.7692752,19.29z/data=!3m1!5s0x34e56e542a9d18ab:0x93682f228e7b6ac5!4m10!3m9!1s0x34e56e56801ed593:0x66e940c2cfc6fe51!5m3!1s2025-12-18!4m1!1i2!8m2!3d26.1650646!4d127.7693818!16s%2Fg%2F11by_11k70?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
  },
  {
    id: 62,
    time: '13:00',
    title: '🌊 知念岬',
    image: parkphoto,
    openingHours: null,
    busRouteNote: '🚌 南城市內巴士',
    remarks: '聽 ~ 海哭的聲音',
    mapLink: 'https://www.google.com/maps/place/%E4%B9%85%E6%89%8B%E5%A0%85%E6%B5%B7%E5%B2%B8/@26.1688265,127.8257895,17z/data=!4m10!3m9!1s0x34e571099bb7db1d:0x5e2c718142afe9f3!5m3!1s2025-12-18!4m1!1i2!8m2!3d26.1711875!4d127.8300625!16s%2Fg%2F11j99gx13x?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
  },
  {
    id: 63,
    time: '19:00',
    title: '🍢 Kushiyaki Can',
    image: kushiyakiCanphoto,
    openingHours: '17:30-00:00',
    busRouteNote: '🚌 338巴士 (1635)',
    remarks: '平價串燒，推介',
    mapLink: 'https://www.google.com/maps/place/Kushiyaki+Can/@26.2130807,127.6794384,16.58z/data=!4m10!3m9!1s0x34e5690cd32bd3f3:0xd115dd9ad3bf2d7a!5m3!1s2025-12-18!4m1!1i2!8m2!3d26.2121349!4d127.6780053!16s%2Fg%2F11l71x4548?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
  }
]},
{ id: 7,
     title: 'Day 7 · 🛍️ 購物日',
     date: '2025-12-27',
     weatherUrl: 'https://www.data.jma.go.jp/multi/yoho/yoho_detail.html?code=471010&lang=cn_zt', 
     items: [
  {
    id: 71,
    time: '09:43',
    title: '🍣 糸満魚市場',
    image: fishmarketphoto,
    openingHours: '10:00–19:00',
    busRouteNote: '🚌 89巴士',
    remarks: '再戰魚生',
    mapLink: 'https://www.google.com/maps/place/%E7%B3%B8%E6%BB%BF%E9%AD%9A%E5%B8%82%E5%A0%B4/@26.1493374,127.6678675,14.83z/data=!4m10!3m9!1s0x34e567c221f4f19d:0x58162367592c3315!5m3!1s2025-12-18!4m1!1i2!8m2!3d26.1380987!4d127.6613785!16s%2Fg%2F1td2k73b?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
  },
  {
    id: 72,
    time: '11:00',
    title: '🛍️ 沖繩ASHIBINAA Outlet',
    image: outletphoto,
    openingHours: '10:00–20:00',
    busRouteNote: '🚌 TK02 · 約14分鐘',
    remarks: '🛒 最後血拼日，食埋blue seal雪糕',
    mapLink: 'https://www.google.com/maps/place/%E6%B2%96%E7%B9%A9+ASHIBINAA+Outlet/@26.1586798,127.6480783,14.83z/data=!4m10!3m9!1s0x34e5680b869eccf7:0xd51f50b361213e26!5m3!1s2025-12-18!4m1!1i2!8m2!3d26.1590569!4d127.6575776!16s%2Fg%2F1235dvb9?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
  },
  {
    id: 73,
    time: '19:00',
    title: '🐖 Shokusai Shubo Matsumoto',
    image: shabuphoto,
    openingHours: '17:00-22:00',
    busRouteNote: '🚌 38巴士',
    remarks: '豬肉shabu shabu收尾',
    mapLink: 'https://www.google.com/maps/place/Shokusai+Shubo+Matsumoto/@26.2145778,127.6807819,16.25z/data=!3m1!5s0x34e5699ce07d4d35:0x9f8f61827a3e658b!4m6!3m5!1s0x34e5699ce6bb12b5:0x98ad747f6dea2fb7!8m2!3d26.2169514!4d127.6783311!16s%2Fg%2F1t_wm305?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
  }
]},
{ id: 8,
     title: 'Day 8 · 🛫 回程日',
     date: '2025-12-28',
     weatherUrl: 'https://www.data.jma.go.jp/multi/yoho/yoho_detail.html?code=471010&lang=cn_zt', 
     items: [
  {
    id: 81,
    time: '10:00',
    title: '🛫 UO821 出發',
    image: UOphoto,
    openingHours: null,
    busRouteNote: '🚇 單軌電車，15分鐘',
    remarks: '航班 UO821，提前2小時到',
    mapLink: 'https://www.google.com/maps/place/%E9%82%A3%E9%9C%B8%E6%A9%9F%E5%A0%B4%E5%9C%8B%E9%9A%9B%E7%B7%9A%E8%88%AA%E5%BB%88/@26.2079676,127.659564,14.5z/data=!4m6!3m5!1s0x34e569c4911ff08d:0xe36f832c2a0a80de!8m2!3d26.2091348!4d127.6510196!16s%2Fg%2F11f66vvhqm?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
  },
  {
    id: 82,
    time: '11:55',
    title: '🍖 Pork Tamago',
    image: porktamagophoto,
    openingHours: '07:00–20:00',
    busRouteNote: '',
    remarks: '機場機場食唔駛排隊',
    mapLink: 'https://www.google.com/maps/place/%E7%8F%80%E5%A1%94%E7%91%AA+%E9%82%A3%E9%9C%B8%E6%A9%9F%E5%A0%B4%E5%9C%8B%E9%9A%9B%E7%B7%9A%E7%BE%8E%E9%A3%9F%E5%8D%80%E5%BA%97/@26.207187,127.6480565,17z/data=!3m1!5s0x34e569c53a121587:0x2621517f24c6c2ae!4m10!1m2!2m1!1zcG9yayB0YW1hZ28gb25pZ2lyaSDpgqPpnLjmqZ_loLQ!3m6!1s0x34e569437bf89123:0x7d3f2cafb8c7cfad!8m2!3d26.2078028!4d127.6504602!15sCiBwb3JrIHRhbWFnbyBvbmlnaXJpIOmCo-mcuOapn-WgtCIDiAEBWiQiInBvcmsgdGFtYWdvIG9uaWdpcmkg6YKjIOmcuCDmqZ_loLSSARRicmVha2Zhc3RfcmVzdGF1cmFudOABAA!16s%2Fg%2F11j8sjs5z3?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
  }
]},
{
  id: 9, // 確保唔同於 1–8
  title: '📎 附錄',
  date: '2025-12-XX',
  weatherUrl: 'https://www.kotsu-okinawa.org/index.html',
  items: [
    {
      id: 91,
      time: '01:00',
      title: '🚌 巴士網',
      image: busphoto, 
      openingHours: null,
      busRouteNote: '',
      remarks: '查巴士時間同路線用\n沖繩交通資訊網',
      mapLink: 'https://www.kotsu-okinawa.org/index.html'
    },
    {
      id: 92,
      time: '02:00',
      title: '🍔 Zootons',
      image: burgerphoto, 
      openingHours: '11:00-20:00 (二日就去到15:00)',
      busRouteNote: '',
      remarks: '百大burger名店\n前段國際通',
      mapLink: 'https://maps.app.goo.gl/ewmMwvG9zgAyjLxJ7?g_st=ic'
    },
    {
      id: 93,
      time: '02:00',
      title: '🍮 TRIPCAFEOKINAWA',
      image: Dessertphoto, 
      openingHours: '08:00-19:00',
      busRouteNote: '',
      remarks: '吸引甜品店\n中段國際通',
      mapLink: 'https://www.google.com/maps/place/%E8%88%92%E8%8A%99%E9%9B%B7/@26.2152072,127.6818956,17.5z/data=!4m6!3m5!1s0x34e5692a7d0c51cb:0x8f6c7eccb6ba2c44!8m2!3d26.2155976!4d127.6831369!16s%2Fg%2F11yjls_62d?entry=ttu&g_ep=EgoyMDI1MTIwOS4wIKXMDSoASAFQAw%3D%3D'
    },
    {
      id: 94,
      time: '02:00',
      title: '🍦 Fontana Gelato',
      image: gelatophoto, 
      openingHours: '10:30-21:30',
      busRouteNote: '',
      remarks: '好食gelato\n中段國際通',
      mapLink: 'https://www.google.com/maps/place/Fontana+Gelato/@26.2142335,127.6831002,16.75z/data=!3m1!5s0x34e5697a003b4967:0x374f2651008a8c84!4m6!3m5!1s0x34e5697b1d925555:0x904e35daaa7f454e!8m2!3d26.2156548!4d127.6866005!16s%2Fg%2F11cp7ls6lg?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
    },
    {
      id: 95,
      time: '03:00',
      title: '🍚 Poco Cafe Okinawa',
      image: PocoCafephoto, 
      openingHours: '09:30-22:00，星期四休息',
      busRouteNote: '',
      remarks: 'Taco飯+苦瓜餃子\n後段國際通',
      mapLink: 'https://www.google.com/maps/place/Poco+Cafe+Okinawa/@26.2157557,127.6841177,17z/data=!3m1!5s0x34e5697a03991b4b:0x4c228405b7a513b8!4m6!3m5!1s0x34e5697a0397e9f7:0xbaed73616f763668!8m2!3d26.2159526!4d127.6868218!16s%2Fg%2F11gdrdp7sh?entry=ttu&g_ep=EgoyMDI1MTIwOS4wIKXMDSoASAFQAw%3D%3D'
    },    
    {
      id: 96,
      time: '03:00',
      title: '🍟 Calbee+ 沖繩國際通店',
      image: calbeephoto, 
      openingHours: '10:00-21:00',
      busRouteNote: '',
      remarks: '手信選擇\n後段國際通',
      mapLink: 'https://www.google.com/maps/place/Calbee%2B+%E6%B2%96%E7%B9%A9%E5%9C%8B%E9%9A%9B%E9%80%9A%E5%BA%97/@26.2160323,127.6865337,18z/data=!4m6!3m5!1s0x34e5697a58b5678b:0x66e50e017932ccc1!8m2!3d26.2163637!4d127.689128!16s%2Fg%2F11b6rwsj54?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
    },
    {
      id: 97,
      time: '05:00',
      title: '🍟 塩の専門店 塩屋',
      image: saltphoto, 
      openingHours: '10:00-21:00',
      busRouteNote: '',
      remarks: '鹽味雪糕\n後段國際通',
      mapLink: 'https://www.google.com/maps/place/%E5%A1%A9%E3%81%AE%E5%B0%82%E9%96%80%E5%BA%97+%E5%A1%A9%E5%B1%8B+%E5%9B%BD%E9%9A%9B%E9%80%9A%E3%82%8A%E5%BA%97/@26.216778,127.6897328,17z/data=!4m6!3m5!1s0x34e569770beb5e01:0x93a07b9b4b570c8d!8m2!3d26.2166959!4d127.6897678!16s%2Fg%2F11bywdcwhn?entry=ttu&g_ep=EgoyMDI1MTIwMi4wIKXMDSoASAFQAw%3D%3D'
    },
    {
      id: 98,
      time: '05:00',
      title: '🍜 暖暮拉麵 那霸牧志店',
      image: Ramenphoto, 
      openingHours: '10:00-02:00',
      busRouteNote: '',
      remarks: '沖繩必食拉面\n後段國際通',
      mapLink: 'https://www.google.com/maps/place/%E6%9A%96%E6%9A%AE%E6%8B%89%E9%BA%B5+%E9%82%A3%E9%9C%B8%E7%89%A7%E5%BF%97%E5%BA%97/@26.2157557,127.6841177,17z/data=!4m6!3m5!1s0x34e5697bcfbeaaab:0x860befe404def6ef!8m2!3d26.2178669!4d127.6873312!16s%2Fg%2F1trpnjsm?entry=ttu&g_ep=EgoyMDI1MTIwOS4wIKXMDSoASAFQAw%3D%3D'
    }
    
    // 之後可以再慢慢加 92, 93... etc
  ]
}

])

const activeDayId = ref(2)
const activeDay = computed(() => days.value.find(d => d.id === activeDayId.value))

function setDay(id) {
  activeDayId.value = id
}

function openWeather(day) {
  if (!day?.weatherUrl) return
  window.open(day.weatherUrl, '_blank')
}

function openMap(link) {
  if (!link) return
  window.open(link, '_blank')
}
</script>

<template>
  <div class="min-h-screen bg-purple-50">
    <div class="max-w-md mx-auto px-4 py-4">
      <!-- Day tabs -->
      <div class="flex gap-2 mb-3 overflow-x-auto no-scrollbar">
        <button
          v-for="d in days"
          :key="d.id"
          @click="setDay(d.id)"
          class="px-3 py-1 text-xs rounded-full border"
          :class="d.id === activeDayId
            ? 'bg-white border-purple-400 text-purple-700 font-semibold'
            : 'bg-purple-100 border-purple-100 text-purple-500'"
        >
          {{ d.title }}
        </button>
      </div>

      <!-- Header -->
      <header v-if="activeDay" class="mb-3 text-left">
        <h1 class="text-xl font-bold text-purple-700">
          {{ activeDay.title }}
        </h1>
        <p class="text-xs text-purple-400 mt-0.5">
          {{ activeDay.date }}
        </p>
      </header>

      <!-- Weather card -->
      <section
        v-if="activeDay"
        class="mb-4 rounded-2xl bg-white border border-purple-100 px-4 py-3 flex items-center justify-between shadow-sm"
      >
        <div class="text-left">
          <p class="text-[11px] font-semibold text-purple-500 uppercase tracking-wide">
            今日天氣
          </p>
          <p class="text-xs text-slate-600 mt-1">
            日本氣象廳 · 那覇預報
          </p>
        </div>
        <button
          @click="openWeather(activeDay)"
          class="ml-3 px-3 py-2 rounded-xl text-xs font-semibold text-white bg-gradient-to-r from-sky-400 to-emerald-400 shadow-md hover:shadow-lg active:scale-95 transition"
        >
          ☁️ 打開
        </button>
      </section>

      <!-- Timeline + cards -->
      <main v-if="activeDay" class="relative flex">
        <!-- Left vertical line -->
        <div class="flex flex-col items-center">
          <div class="w-px bg-purple-200 h-full"></div>
        </div>

        <!-- Right content -->
        <div class="flex-1 ml-4 space-y-5 pb-6">
          <article
            v-for="item in activeDay.items"
            :key="item.id"
            class="relative flex items-stretch"
          >
            <!-- Dot + time -->
            <div class="absolute -left-6 top-4 flex flex-col items-center">
              <div class="w-3 h-3 rounded-full bg-white border-2 border-fuchsia-400 shadow"></div>
            </div>

            <div class="w-12 pr-2 pt-2 text-right flex-shrink-0">
              <p class="text-xs font-semibold text-fuchsia-600">
                {{ item.time }}
              </p>
            </div>

            <!-- Card -->
            <div
              class="flex-1 bg-white rounded-2xl shadow-md border border-purple-100 overflow-hidden text-left"
            >
              <!-- Title -->
              <div class="px-4 pt-3 pb-2">
                <h2 class="text-sm font-semibold text-slate-800 leading-snug">
                  {{ item.title }}
                </h2>
              </div>

              <!-- Image -->
              <div class="w-full h-40 bg-slate-200 overflow-hidden">
                <img :src="item.image" alt="" class="w-full h-full object-cover" />
              </div>

              <!-- Info -->
              <div class="px-4 py-3 space-y-2">
                

                <p
                  v-if="item.openingHours"
                  class="text-[11px] text-purple-500 font-medium"
                >  
                  ⏰ Opening hours：{{ item.openingHours }}
                </p>

                <p
                  v-if="item.busRouteNote"
                  class="inline-flex items-center px-2.5 py-1 rounded-full bg-sky-50 text-sky-700 border border-sky-100 text-[11px] font-medium"
                >
                  {{ item.busRouteNote }}
                </p>

                <p
                  v-if="item.remarks"
                  class="text-xs text-slate-600 bg-purple-50 rounded-xl px-3 py-2 border border-purple-100 whitespace-pre-line"
                >
                  💡 {{ item.remarks }}
                </p>

                <div class="flex justify-end pt-1">
                  <button
                    @click="openMap(item.mapLink)"
                    class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-xl text-xs font-semibold
                           bg-gradient-to-r from-fuchsia-400 to-sky-400 text-white shadow-sm hover:shadow-md active:scale-95 transition"
                  >
                    🗺️ Map
                  </button>
                </div>
              </div>
            </div>
          </article>
        </div>
      </main>
    </div>
  </div>
</template>

<style scoped>
.no-scrollbar::-webkit-scrollbar {
  display: none;
}
.no-scrollbar {
  -ms-overflow-style: none;
  scrollbar-width: none;
}
</style>