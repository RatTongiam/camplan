# Prima Motion Capture Volume Planner

A single-file web app for planning optical motion-capture camera placement: capture volume, camera coverage, marker visibility by pixel size, predicted 3D error and residual, and anchor-marker suggestions for OptiTrack Motive Continuous Calibration.

Live version: https://camplan.primamotion.tech  
Source: https://github.com/RatTongiam/camplan

## Status and disclaimer

This tool supports preliminary assessment and planning only. Results come from a geometric model and from camera specifications collected from publicly available sources, which may be incomplete or inaccurate. Occlusion, reflections, lighting, mounting and calibration quality are not modelled. See the disclaimer inside the app.

## Run locally

Open `index.html` in a modern browser. No build step and no server are needed.

## License

Copyright (C) 2026 Prima Motion Co., Ltd. Originally developed by Prima Motion Co., Ltd.

The code is open source under the GNU Affero General Public License, version 3 (`LICENSE.txt`), with additional terms under section 7 (`ADDITIONAL-TERMS.txt`):

- keep the copyright and attribution notices;
- mark modified versions as modified and give them a different name;
- the names "Prima Motion" and "PRIMA" and the Prima Motion logo are **not** licensed (`TRADEMARKS.txt`).

If you make a modified version available to users over a network, the AGPL requires you to offer them its source code.

OptiTrack, Qualisys, Vicon and their product names are trademarks of their respective owners. This project is not affiliated with or endorsed by them.

## Contributing

See `CONTRIBUTING.md`. Corrections to camera specifications are especially welcome; please cite a public source.

---

# Prima Motion Capture Volume Planner (ภาษาไทย)

เว็บแอปไฟล์เดียวสำหรับวางแผนตำแหน่งกล้อง optical motion capture: ประเมิน capture volume จำนวนกล้องที่มองเห็น การมองเห็น marker ตามขนาด pixel ค่า error 3D และ residual ที่คาดการณ์ และแนะนำตำแหน่ง anchor marker สำหรับ Continuous Calibration ใน OptiTrack Motive

ใช้งานออนไลน์: https://camplan.primamotion.tech  
ซอร์สโค้ด: https://github.com/RatTongiam/camplan

## ข้อจำกัด

เครื่องมือนี้ใช้ช่วยประเมินและวางแผนเบื้องต้นเท่านั้น ข้อมูลกล้องรวบรวมจากเอกสารที่เผยแพร่ต่อสาธารณะ ซึ่งอาจไม่ครบถ้วนหรือคลาดเคลื่อน และยังไม่ได้จำลองการบดบัง แสงสะท้อน สภาพแสง การยึดกล้อง และคุณภาพการ calibrate โปรดอ่านข้อจำกัดความรับผิดชอบในแอป

## การใช้งานในเครื่อง

เปิดไฟล์ `index.html` ด้วยเบราว์เซอร์ ไม่ต้องติดตั้งหรือมีเซิร์ฟเวอร์

## License

Copyright (C) 2026 บริษัท พริมา โมชั่น จำกัด

ซอร์สโค้ดเปิดภายใต้ GNU AGPL-3.0 (`LICENSE.txt`) พร้อมเงื่อนไขเพิ่มเติมตามมาตรา 7 (`ADDITIONAL-TERMS.txt`):

- ต้องคงข้อความลิขสิทธิ์และข้อความระบุผู้สร้าง
- ฉบับที่ดัดแปลงต้องระบุว่าดัดแปลงและใช้ชื่ออื่น
- ชื่อ "Prima Motion" "PRIMA" และโลโก้ **ไม่รวม** อยู่ใน license (`TRADEMARKS.txt`)

ผู้ที่นำฉบับดัดแปลงไปเปิดให้ผู้อื่นใช้ผ่านเครือข่าย ต้องเปิดซอร์สโค้ดให้ผู้ใช้เหล่านั้นตาม AGPL

## ร่วมพัฒนา

ดู `CONTRIBUTING.md` ยินดีรับการแก้ไขข้อมูลสเปกกล้อง โปรดแนบแหล่งอ้างอิงที่เปิดเผยต่อสาธารณะ
