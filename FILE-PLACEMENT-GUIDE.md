# 📁 File Placement Guide

## Video Setup

### Homepage Hero Video
**File:** `65 - XMAS+CNY Campaign.mp4`
**Location:** Copy to `assets/videos/` folder
**Rename to:** `campaign-video.mp4`

**Steps:**
1. Find your file: `65 - XMAS+CNY Campaign.mp4`
2. Copy it to: `MKT/assets/videos/`
3. Rename it to: `campaign-video.mp4`

The video will automatically play as the homepage background!

---

## Card Type Images Setup

### 8 Card Type Images
**Location:** Place in `assets/images/card-types/` folder

**Required Images & Naming:**

| Your File | Rename To | Card Type |
|-----------|-----------|-----------|
| Image 1 | `gift-card.png` | 禮品卡 |
| Image 2 | `loyalty-card.png` | 集點卡 |
| Image 3 | `subscription-card.png` | 訂閱 |
| Image 4 | `reward-card.png` | 獎勵卡 |
| Image 5 | `coupon-card.png` | 優惠券 |
| Image 6 | `membership-card.png` | 會員卡 |
| Image 7 | `discount-card.png` | 折扣卡 |
| Image 8 | `cashback-card.png` | 回贈卡 |

**Steps:**
1. Locate your 8 card images (numbered 1-8)
2. Copy them to: `MKT/assets/images/card-types/`
3. Rename them according to the table above
4. Supported formats: PNG, JPG, JPEG, GIF, WEBP

**Note:** If your files have different extensions (like .jpg), update the extension in the table above to match.

---

## Quick PowerShell Commands

### Copy video file:
```powershell
# Replace 'SOURCE_PATH' with your video's location
Copy-Item "SOURCE_PATH\65 - XMAS+CNY Campaign.mp4" "C:\Users\OneManArmy\Documents\MKT\assets\videos\campaign-video.mp4"
```

### Copy and rename images (example):
```powershell
# Replace 'SOURCE_PATH' with your images' location
Copy-Item "SOURCE_PATH\1.png" "C:\Users\OneManArmy\Documents\MKT\assets\images\card-types\gift-card.png"
Copy-Item "SOURCE_PATH\2.png" "C:\Users\OneManArmy\Documents\MKT\assets\images\card-types\loyalty-card.png"
Copy-Item "SOURCE_PATH\3.png" "C:\Users\OneManArmy\Documents\MKT\assets\images\card-types\subscription-card.png"
Copy-Item "SOURCE_PATH\4.png" "C:\Users\OneManArmy\Documents\MKT\assets\images\card-types\reward-card.png"
Copy-Item "SOURCE_PATH\5.png" "C:\Users\OneManArmy\Documents\MKT\assets\images\card-types\coupon-card.png"
Copy-Item "SOURCE_PATH\6.png" "C:\Users\OneManArmy\Documents\MKT\assets\images\card-types\membership-card.png"
Copy-Item "SOURCE_PATH\7.png" "C:\Users\OneManArmy\Documents\MKT\assets\images\card-types\discount-card.png"
Copy-Item "SOURCE_PATH\8.png" "C:\Users\OneManArmy\Documents\MKT\assets\images\card-types\cashback-card.png"
```

---

## After Placing Files

Refresh your browser to see:
- ✅ Video playing on homepage banner
- ✅ 8 card type images displayed on the membership card page

If images don't show, check:
1. File names match exactly (case-sensitive)
2. Files are in the correct folders
3. File extensions are correct (.png, .jpg, etc.)
