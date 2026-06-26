[Download](https://github.com/zepiam/Fav-Wallpaper-Ex/releases/tag/latest)
> **Note EN:** Download .zip and extract to your PC.
> **Note TH:** เข้าไปโหลดไฟล์ .zip นำไปแตกในคอมของคุณ

# Fav Wallpaper Ex

Fav Wallpaper Ex is a Windows desktop application built with C# that makes managing your wallpapers simple and hassle-free.

### The Problem
Have you ever found the perfect image for your wallpaper, only to realize it’s portrait-oriented? When you set it as your wallpaper, Windows just centers the image, often cutting off the best parts. Trying to crop it yourself, save it, and end up with dozens of separate files for different screen sizes is just a pain.

### The Solution
Fav Wallpaper Ex solves this by detecting your monitor's resolution. It gives you a cropping frame that matches your screen's aspect ratio, allowing you to crop exactly what you want directly within the app.

---

### Key Features

* **Single Wallpaper:** Easily set a specific image for a specific monitor.
* **Wallpaper Pool:** Select a collection of images to rotate on your desktop. You can set the rotation interval to whatever you like.
* **Span Wallpaper:** Use one large image across multiple monitors. The app calculates the combined resolution of your setup and lets you crop across all screens at once. (Best for monitors arranged in a simple horizontal or vertical line).
* **Schedule Wallpaper:** Organize wallpapers by time. You can create different sets for different times of the day, with custom rotation settings for each.

> **Note:** If no specific images are set for a monitor or a specific time, the system will fall back to your "Single Wallpaper" settings.

---

### More Useful Features

1. **Quick Access & Favorites:** Pin your favorite image folders for fast access. You can "star" any image while cropping to save it to your `Favourites` folder, so you don't have to hunt for it again.
2. **Pause in Fullscreen:** If you're playing a game or watching a video in fullscreen, the app automatically pauses wallpaper rotation to prevent any lag or stuttering during the transition animation.
3. **Smart Eco Mode:** When you aren't using the app, it enters a low-RAM usage mode (Disabled by default).
4. **Startup with Windows:** You can set the app to launch automatically when you turn on your PC (Disabled by default).
5. **Smart Thumbnail Generation:** The app automatically generates thumbnails for your gallery. If something goes wrong, you can simply trigger a re-scan from the Main Dashboard or Settings.
6. **Lightweight Background Process:** The app is designed to be efficient, clearing unused RAM while running in the background.

---

### Important Notes

* **Caching:** The app creates a cache folder at `C:/Users/YourPC/AppData/Local/FavWallpaperCache` to store settings, thumbnails, and your active cropped wallpapers. When you change your wallpaper, the old cropped file is automatically deleted to keep things tidy.

---

### Troubleshooting (Rare Cases)

1. **Monitor Glitches:** If you frequently swap GPU ports, Windows might get confused with Monitor IDs. If the app acts up, go to **System Monitor Management** and check for "Ghost Monitors." If you see any, select them and click **Uninstall**. Restart your PC, and it will be back to normal.
2. **Startup Issues:** If you move the app's folder after its first run, "Startup with Windows" might stop working. Just toggle the setting OFF and ON again in the Settings menu to refresh the path.
3. **Display Issues:** If thumbnails don't load or an overlay gets stuck, try restarting the app and clicking **Generate** in the Dashboard or Settings.

---

### Support the Project

If you find this tool useful, feel free to support its development!

[Buy Me a Coffee](https://buymeacoffee.com/men9ch)

---

# Fav Wallpaper Ex

Fav Wallpaper Ex เป็นโปรแกรมช่วยจัดการ Wallpaper บนระบบปฏิบัติการ Windows ที่พัฒนาด้วยภาษา C# เพื่อให้การจัดการและตั้งค่ารูปหน้าจอของคุณเป็นเรื่องง่ายและสะดวกสบายที่สุด

### ปัญหาที่คุณอาจเคยเจอ
เคยไหม? เจอรูปถ่ายหรือภาพอาร์ตที่สวยมากๆ จนอยากเอามาตั้งเป็น Wallpaper แต่ภาพนั้นดันเป็นแนวตั้ง พอสั่ง Set as Wallpaper บน Windows ภาพกลับถูกขยายและตัดตรงกลางจอ ทำให้ไม่แสดงจุดเด่นของภาพที่คุณต้องการครอป จะเอาภาพไปเข้าโปรแกรมอื่นเพื่อตัดรูปแยกไว้ก็ยุ่งยาก แถมยังทำให้มีไฟล์ภาพเดียวกันหลายขนาดเต็มเครื่องไปหมด

### วิธีแก้ปัญหา
โปรแกรมนี้ถูกสร้างขึ้นมาเพื่อแก้ปัญหานี้โดยเฉพาะ! ระบบสามารถตรวจจับความละเอียดหน้าจอ (Resolution) ของคุณได้โดยอัตโนมัติ และจะแสดงกรอบสี่เหลี่ยมที่มีสัดส่วน (Ratio) ตรงกับหน้าจอของคุณเป๊ะๆ ช่วยให้คุณเลือกครอปตำแหน่งภาพที่ต้องการ และนำไปตั้งเป็น Wallpaper ได้ทันทีจากในโปรแกรม

---

### โหมดการทำงานหลัก

* **Single Wallpaper:** ตั้งค่ารูปแบบภาพเดี่ยว โดยสามารถเลือกเจาะจงได้ว่าต้องการให้รูปไหนไปแสดงที่หน้าจอไหน
* **Wallpaper Pool:** ทำงานคล้ายกับโหมดภาพเดี่ยว แต่คุณสามารถเลือกรูปภาพเก็บไว้ได้ทีละหลายๆ รูป เพื่อให้ระบบสลับเปลี่ยนภาพ (Rotate) บนหน้าจอให้โดยอัตโนมัติ และกำหนดเวลาในการสลับรูปได้ตามใจชอบ
* **Span Wallpaper:** ใช้ภาพเพียงภาพเดียวเชื่อมต่อยาวทะลุทุกหน้าจอ โดยระบบครอปจะนำหน้าจอทั้งหมดที่มีมารวมความละเอียดกัน แล้วแสดงกรอบครอปตามความกว้างรวมของทุกจอให้ทันที (แนะนำให้ใช้กับหน้าจอที่วางเรียงกันในแนวตั้งหรือแนวนอนเป็นเส้นตรงเท่านั้น)
* **Schedule Wallpaper:** จัดชุดรูปภาพตามช่วงเวลา โดยคุณสามารถเลือกรูปภาพจำนวนมากใส่ไว้ในแต่ละช่วงเวลาของวัน พร้อมทั้งตั้งค่ารูปแบบการสลับภาพและเวลาในการเปลี่ยนภาพได้อย่างอิสระในทุกๆ ช่วงเวลา

> 💡 **ข้อควรรู้:** ในโหมด Pool และ Schedule หากหน้าจอใดหรือช่วงเวลาใดไม่ได้มีการตั้งรูปภาพเอาไว้ ระบบจะดึงภาพที่ตั้งไว้ในโหมด **Single Wallpaper** มาแสดงแทนโดยอัตโนมัติ

---

### ฟีเจอร์เพิ่มเติมที่น่าสนใจ

1. **Quick Access & Favorites:** สามารถปักหมุด (Pin) โฟลเดอร์รูปภาพโปรดให้แสดงบน Quick Access ในหน้า Gallery ได้ทันที นอกจากนี้ยังสามารถกดปุ่มดาว (Star) ในหน้าครอปรูปภาพเพื่อบันทึกเข้า `Favourites` เอาไว้เรียกใช้ภายหลังได้ง่ายๆ โดยไม่ต้องไปนั่งหาไฟล์รูปใหม่อีกรอบ
2. **Pause in Fullscreen:** เมื่อคุณเปิดวิดีโอหรือเล่นเกมแบบเต็มจอ (Fullscreen) ระบบจะหยุดสลับรูปภาพชั่วคราว เพื่อป้องกันไม่ให้ Fade Animation ตอนเปลี่ยนวอลเปเปอร์ไปรบกวนทรัพยากรเครื่อง ทำให้คอมพิวเตอร์ไม่หน่วงหรือกระตุกขณะที่คุณเล่นเกมหรือดูวิดีโอ
3. **Smart Eco Mode:** ระบบประหยัดแรมอัจฉริยะ เมื่อโปรแกรมหลุดจากการโฟกัส (ไม่ได้เปิดหน้าต่างโปรแกรมทิ้งไว้) ระบบจะเข้าสู่โหมดประหยัด RAM ทันที (ฟีเจอร์นี้ปิดไว้เป็นค่าเริ่มต้น)
4. **Startup with Windows:** รองรับการเปิดโปรแกรมอัตโนมัติพร้อมเปิดเครื่องคอมพิวเตอร์ โดยสามารถเข้าไปเปิดใช้งานได้ที่เมนู Setting (ฟีเจอร์นี้ปิดไว้เป็นค่าเริ่มต้น)
5. **Regenerate Thumbnail:** ระบบสร้างรูปตัวอย่าง (Thumbnail) สำหรับแสดงในโปรแกรมโดยอัตโนมัติ หากมีรูปไหนสร้างไม่สำเร็จ คุณสามารถกดสั่ง Generate ใหม่ได้เองที่ Main Dashboard หรือใน Setting
6. **Lightweight Background Process:** เมื่อไม่ได้โฟกัสโปรแกรม โปรแกรมจะทำการคืนพื้นที่ RAM ที่ไม่ได้ใช้ออกทันที และเปลี่ยนไปทำงานเงียบๆ อยู่เบื้องหลัง (Background) โดยใช้ RAM ให้น้อยที่สุดเพื่อไม่ให้รบกวนการทำงานอื่น

---

### สิ่งที่ควรทราบ

* **Cache Folder:** โปรแกรมจะสร้างโฟลเดอร์สำหรับเก็บ Cache ไว้ที่ `C:/Users/YourPC/AppData/Local/FavWallpaperCache` เพื่อบันทึกค่าการตั้งค่าและฐานข้อมูลทั้งหมดของโปรแกรมไว้ในนี้
* **การจัดการไฟล์ครอป:** ทุกครั้งที่คุณครอปภาพ โปรแกรมจะนำภาพที่ครอปเสร็จแล้วไปเซฟไว้ใน Cache Folder และเมื่อใดที่คุณเปลี่ยนรูปใหม่ ระบบจะลบภาพครอปเก่าใน Cache ออกทันทีในทุกโหมดการตั้งค่าเพื่อประหยัดพื้นที่
* **Thumbnail Cache:** ระบบจะทำการเขียน Cache ของรูป Thumbnail ทั้งหมดลงใน Cache Folder เช่นกัน

---

### ปัญหาที่อาจพบ (Rare Case)

1. **ปัญหา Monitor ID สับสน:** หากคุณมีการสลับช่องเสียบสายจอบนการ์ดจอ (GPU port) บ่อยๆ อาจทำให้ Windows สับสน Monitor ID หรือเกิด ID ซ้ำกันจนโปรแกรมแสดงผลผิดปกติ หากเจอกรณีนี้ ให้เข้าไปที่เมนู **System Monitor Management** ในส่วนของ **Ghost Monitor** หากพบจอค้างอยู่ให้เลือกและกด **Uninstall** ระบบจะไปลบ Registry Monitor ใน Device Manager ให้ จากนั้นเมื่อ Restart PC กลับมา โปรแกรมจะใช้งานได้ตามปกติ
2. **ปัญหา Startup ไม่ทำงาน:** หากคุณย้ายตำแหน่งโฟลเดอร์ที่ตั้งของโปรแกรมหลังจากเปิดใช้งานไปแล้วครั้งหนึ่ง อาจทำให้ระบบ Startup พร้อม Windows ไม่ทำงาน แก้ไขได้โดยการเข้าไปกด ปิด (OFF) และ เปิด (ON) ส่วน Startup with Windows ใน Setting อีกครั้งเพื่อให้ระบบจดจำตำแหน่งใหม่
3. **ปัญหาการแสดงผลค้าง:** หากระบบ Generate ภาพไม่สำเร็จแล้วโปรแกรมแสดงผลผิดปกติ เช่น หน้า Overlay ค้าง หรือภาพใน Gallery ไม่ยอมแสดง แนะนำให้ปิดโปรแกรมแล้วเปิดใหม่ จากนั้นกดสั่ง Generate ผ่าน Main Dashboard หรือใน Setting ให้เสร็จสิ้น โปรแกรมจะกลับมาแสดงผลปกติ

---

### Donate / สนับสนุนนักพัฒนา

หากโปรแกรมนี้ช่วยให้คุณจัดการวอลเปเปอร์ได้สะดวกขึ้น และอยากสนับสนุนการพัฒนาโปรแกรม สามารถโดเนทเลี้ยงกาแฟผมได้ที่ลิงก์ด้านล่างนี้เลยครับ! 🙏

[ดูข้อมูล Donate ผ่านช่องทางคนไทย](https://men9ch.com/support/)
