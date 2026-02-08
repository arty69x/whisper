# Whisper

## การทำงานที่ดี

1. ติดตั้ง dependencies
   - `npm install`
2. เริ่มพัฒนา
   - `npm run dev`
3. ตรวจสอบ asset ของ Blueprint (ถ้าจำเป็น)
   - `node blueprint-factory/output/image-to-ui-monorepo/verify-assets.js`
4. สร้าง build ใหม่ของ Blueprint
   - `node blueprint-factory/scripts/create_complete_repo.mjs`
