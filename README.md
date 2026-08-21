# Alefba Deer v2 for Codex

یک پت سفارشی Codex با شخصیت گوزن آبی جادویی Alefba. این نسخه از نو ساخته شده و هر فریم انیمیشن مستقل، کامل و درون محدودهٔ خودش است.

![Alefba Deer v2 contact sheet](pets/alefba-deer-v2/contact-sheet.png)

## Contents

- `pets/alefba-deer-v2/spritesheet.webp` — spritesheet نهایی با قرارداد Codex v2
- `pets/alefba-deer-v2/pet.json` — مانیفست پت
- `pets/alefba-deer-v2/validation.json` — گزارش اعتبارسنجی ساختاری
- `pets/alefba-deer-v2/contact-sheet.png` — پیش‌نمایش همهٔ حرکت‌ها و جهت‌ها

## Install

پوشهٔ `pets/alefba-deer-v2` را در پوشهٔ pets مربوط به Codex کپی کنید:

```bash
mkdir -p ~/.codex/pets
cp -R pets/alefba-deer-v2 ~/.codex/pets/
```

سپس Codex را دوباره باز کنید و از فهرست pets، **Alefba Deer v2** را انتخاب کنید.

## Specification

- Sprite version: `2`
- Atlas size: `1536 × 2288`
- Cell size: `192 × 208`
- Layout: 8 columns × 11 rows
- Standard states: idle, running right/left, waving, jumping, failed, waiting, running, review
- Look directions: 16 clockwise directions

The included `validation.json` reports a successful v2 validation with transparent backgrounds and no unexpected populated cells.

## Reuse

برای استفاده در پروژه یا نصب دیگر، فقط دو فایل `pet.json` و `spritesheet.webp` لازم‌اند. فایل contact sheet و validation report برای مرور و کنترل کیفیت نگه داشته شده‌اند.
