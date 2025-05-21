---
title: 'Home'
date: 2023-10-24
type: landing

design:
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: "โครงการหมูหลุม"
      text: "โครงการเกษตรยั่งยืนที่ใช้แนวทางการเลี้ยงหมูโดยไม่พึ่งพาสารเคมี ด้วยหลักการธรรมชาติและการจัดการอินทรีย์"
      primary_action:
        text: เริ่มต้นเรียนรู้
        url: /about/
      secondary_action:
        text: ติดต่อโครงการ
        url: /contact/
      announcement:
        text: "แนะนำโครงการหมูหลุมเพื่อความยั่งยืน"
        link:
          text: "อ่านเพิ่มเติม"
          url: "/blog/"
    design:
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
        margin: [0, 0, 0, 0]
      css_class: "bg-white"
      background:
        color: "white"
        image:
          filename: "pigfarm.png"  # Save your image in `assets/media/`
          filters:
            brightness: 0.85

  - block: stats
    content:
      items:
        - statistic: "1,500+"
          description: |
            เกษตรกรที่เข้าร่วม  
            โครงการหมูหลุม
        - statistic: "30+"
          description: |
            จังหวัดที่มีการขยาย  
            โครงการหมูหลุม
        - statistic: "100%"
          description: |
            ลดการใช้สารเคมี  
            และเพิ่มสุขภาพสัตว์
    design:
      css_class: "bg-[#f8fdf8]"
      spacing:
        padding: ["2rem", "0", "2rem", "0"]

  - block: features
    id: features
    content:
      title: จุดเด่นของโครงการ
      text: การเลี้ยงหมูหลุมคือแนวทางใหม่ที่ช่วยลดต้นทุน เพิ่มสุขภาพสัตว์ และส่งเสริมระบบนิเวศในฟาร์มให้ยั่งยืน
      items:
        - name: ลดกลิ่นและแมลง
          icon: sun
          description: ระบบฟาร์มหมูหลุมช่วยลดกลิ่นและแมลงรบกวนโดยไม่ต้องใช้สารเคมี
        - name: เพิ่มคุณภาพชีวิตสัตว์
          icon: heart
          description: หมูมีสุขภาพดีขึ้นและเคลื่อนไหวอย่างอิสระในหลุมที่มีวัสดุรองพื้นธรรมชาติ
        - name: ผลผลิตปลอดภัย
          icon: shield-check
          description: ผลิตภัณฑ์จากฟาร์มหมูหลุมปลอดภัยสำหรับผู้บริโภค
        - name: ลดต้นทุนการผลิต
          icon: chart-bar
          description: ลดต้นทุนอาหารและการดูแลสุขภาพสัตว์ด้วยแนวทางธรรมชาติ
        - name: ฟาร์มเชิงนิเวศ
          description: ส่งเสริมการใช้วัสดุเหลือใช้และหมุนเวียนทรัพยากรในฟาร์ม
        - name: การเรียนรู้ร่วมกัน
          icon: academic-cap
          description: ส่งเสริมเครือข่ายเกษตรกร แลกเปลี่ยนความรู้ และสร้างชุมชนเข้มแข็ง

  - block: cta-card
    content:
      title: "เข้าร่วมเครือข่ายเกษตรกรหมูหลุมวันนี้"
      text: ไม่ว่าคุณจะเป็นเกษตรกรมือใหม่หรือผู้เชี่ยวชาญ โครงการหมูหลุมเปิดโอกาสให้ทุกคนเรียนรู้และเติบโตไปด้วยกัน
      button:
        text: สมัครเข้าร่วมโครงการ
        url: /join/
    design:
      card:
        css_class: "bg-[#245e3c] text-white"
        css_style: "border-radius: 0.75rem; box-shadow: 0px 5px 15px rgba(0,0,0,0.1);"
---
