# แก๊งแมว · Bad Gang

[คลิปท่าต่อสู้ของทั้งสามตัว](./Cat-Crew-Combat.mp4) · [ภาพสมาชิก](./Cat-Crew.jpg) · [ชุดสลับของลูกสมุน](./Cat-Crew-Outfits.jpg)

| สมาชิก | ต้นฉบับ Blender | GLB สำหรับเกม | ชุดสลับ |
| --- | --- | --- | --- |
| เฮียนิล · หัวหน้า | [Blender](../hia-nin/Hia-Nin.blend) | [GLB](../hia-nin/Hia-Nin.glb) | ชุดหัวหน้าพัดจันทร์ |
| พริกจี๊ด · แมวสามสี | [Blender](../prik-jeed/Prik-Jeed.blend) | [GLB](../prik-jeed/Prik-Jeed.glb) | [ชุดส่งของสีมินต์](../prik-jeed/Prik-Jeed-Mint-Courier.glb) |
| ถังทอง · แมวส้ม | [Blender](../thang-thong/Thang-Thong.blend) | [GLB](../thang-thong/Thang-Thong.glb) | [ชุดงานวัดสีม่วง](../thang-thong/Thang-Thong-Plum-Festival.glb) |

| ท่า | เฮียนิล | พริกจี๊ด | ถังทอง |
| --- | --- | --- | --- |
| ยืนพัก | `SilkIdle` | `SparkIdle` | `RumbleIdle` |
| เตรียมสู้ | `FanGuard` | `SpringGuard` | `DrumGuard` |
| โจมตี 1 | `CrescentFan` ปาดพัดเสี้ยวจันทร์ | `RibbonFlip` ตีลังกาพาริบบิ้นหมุน | `DrumRoll` รัวกลองสลับซ้ายขวา |
| โจมตี 2 | `VelvetSweep` หมุนตัวกวาดพัด | `CometKick` กระโดดถีบ | `SumoStomp` ยกเข่ากระทืบพื้น |
| โจมตี 3 | `BellFeint` ยกพัดล่อแล้วเปลี่ยนระดับ | `TwinHop` กระโดดสองจังหวะ | `DrumCrash` กระโดดทุบกลอง |
| หลบหรือป้องกัน | `SideGlide` | `RibbonDodge` | `TuckGuard` |
| โดนโจมตี | `SilkRecoil` | `SpringRecoil` | `BassRecoil` |

สำหรับลูกสมุน เลือกโครงกระดูกใน Blender แล้วตั้ง **Object Properties → Custom Properties → Outfit** เป็น 0 สำหรับชุดเดิม หรือ 1 สำหรับชุดสลับ ในเกมเลือกใช้ GLB ของชุดที่ต้องการได้เลย แต่ละชุดของตัวเดียวกันใช้โครงกระดูกและแอนิเมชันชุดเดียวกัน
