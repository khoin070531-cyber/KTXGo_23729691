NGUYEN MINH KHOI
MSSV: 23729691
URL clone HTTPS: https://github.com/nguyenminhkhoi/23729691_TH2.git
STAMP: #945697

# KTXGo Delivery - Project Báo Cáo Thực Hành TH2

## Thông Tin Cấu Hình MSSV

- **MSSV**: `23729691`
- **LAST_DIGIT**: `1`
- **STUDENT_SEED**: `691`
- **Mã Thi (Exam Stamp)**: `#945697` (Tính từ: `TH2|23729691|NGUYEN MINH KHOI`)
- **Package name**: `ktxgo-23729691`
- **Cart Persist key**: `ktxgo-cart-23729691`

---

## Bảng Biến Thể VARIANT (MSSV Cuối 1)

```
watermark: bottom
login: phone
tabs: Shop → Cart → Me
haptic: selection
ship: B
detail: card
```

- **Watermark**: Nằm phía DƯỚI màn hình.
- **Login**: Dùng ô SỐ ĐIỆN THOẠI.
- **Tab Navigation**: Cửa hàng (Shop) → Giỏ (Cart) → Tôi (Me).
- **Haptic Feedback**: Selection khi bấm nút thêm sản phẩm.
- **Phí Ship**: Công thức B (`9000 + Math.round(km * 1500) + 2000`).
- **Màn Chi Tiết**: Presentation `card` dạng Stack navigation.

---

## Hằng Số Tính Toán Động

- `DEBOUNCE_MS` = `400`
- `STALE_TIME_MS` = `21000`
- `PRICE_MULTIPLIER` = `20500`
- `BASE_SHIP_FEE` = `9000`
- `ROOM_LABEL` = `P.391`
- `BANNER_IMAGE_ID` = `291`

---

## Cấu Trúc Thư Mục Chuẩn Yêu Cầu

```
KTXGo_23729691/
├── README.md
├── App.tsx
├── package.json
├── babel.config.js
├── tsconfig.json
└── src/
    ├── constants/
    │   ├── student.ts
    │   └── theme.ts
    ├── hooks/
    │   ├── useDebouncedValue.ts
    │   └── useCampusLocation.ts
    ├── services/
    │   ├── apiClient.ts
    │   └── productApi.ts
    ├── stores/
    │   ├── authStore.ts
    │   └── cartStore.ts
    ├── navigation/
    │   ├── RootNavigator.tsx
    │   ├── AuthStack.tsx
    │   ├── MainTabs.tsx
    │   └── ShopStack.tsx
    ├── components/
    │   ├── ProductCard.tsx
    │   └── Watermark.tsx
    └── screens/
        ├── LoginScreen.tsx
        ├── HomeScreen.tsx
        ├── DetailScreen.tsx
        ├── CartScreen.tsx
        └── MeScreen.tsx
```

---

## Hướng Dẫn Chạy Project

```bash
# 1. Cài đặt các gói phụ thuộc
npm install

# 2. Chạy giao diện Web / Emulator
npm run web
```
