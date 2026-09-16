# 🗺️ SƠ ĐỒ CHIẾN LƯỢC & TIẾN TRÌNH GIẢNG DẠY (TEACHING FLOW & ROADMAP)
**Chủ đề**: Khám Phá Trí Tuệ Nhân Tạo (AI) Dành Cho Học Sinh Tiểu Học  
**Dành cho**: Giáo viên đứng lớp | **Thời lượng tổng**: 60 phút

---

## 📊 1. SƠ ĐỒ TIẾN TRÌNH TỔNG QUAN (OVERALL MERMAID FLOW)

```mermaid
flowchart TD
    classDef prep fill:#e1f5fe,stroke:#0288d1,stroke-width:2px;
    classDef teach fill:#e8f5e9,stroke:#388e3c,stroke-width:2px;
    classDef safe fill:#fff3e0,stroke:#f57c00,stroke-width:2px;
    classDef eval fill:#f3e5f5,stroke:#7b1fa2,stroke-width:2px;

    subgraph PHASE1 ["GIAI ĐOẠN 1: CHUẨN BỊ (Trước giờ học 15 phút)"]
        P1["📄 In Phiếu bài tập A4\n(04_Phieu_Hoat_Dong_Hoc_Sinh.md)"]:::prep
        P2["🖥️ Mở Slide bài giảng\n(03_Slide_Noi_Dung_Goc.md)"]:::prep
        P3["🌐 Test Link Web AI:\nQuickDraw & ChatGPT"]:::prep
        P4["🛡️ Phương án B: Clip/Tranh vẽ sẵn\n(Nếu mất Wi-Fi)"]:::prep
        P1 --> P2 --> P3 --> P4
    end

    subgraph PHASE2 ["GIAI ĐOẠN 2: THỰC THI BÀI DẠY (60 Phút trên bục giảng)"]
        direction TB
        T1["00 - 10 min: KHỞI ĐỘNG (WARM-UP)\n• Game 'Con Người vs Máy Tính'\n• Điệu nhảy Ăng-ten Robot"]:::teach
        T2["10 - 25 min: KHÁM PHÁ (DISCOVERY)\n• Trò chơi nhập vai 'Dạy Robot Chó/Mèo'\n• Hiểu về Dữ liệu (Data)"]:::teach
        T3["25 - 45 min: TRẢI NGHIỆM (HANDS-ON)\n• Bé vẽ - AI đoán (QuickDraw)\n• Cùng AI sáng tác truyện cổ tích"]:::teach
        T4["45 - 55 min: THẢO LUẬN AN TOÀN (SAFETY)\n• 3 Quy tắc vàng bảo vệ thông tin\n• Kỹ thuật 'AI cũng có lúc sai'"]:::safe
        T5["55 - 60 min: TỔNG KẾT (WRAP-UP)\n• Đọc thơ đồng dao AI\n• Cấp Huy hiệu Nhà Khai Phá AI Nhí"]:::eval
        
        T1 --> T2 --> T3 --> T4 --> T5
    end

    subgraph PHASE3 ["GIAI ĐOẠN 3: ĐÁNH GIÁ (Sau giờ học)"]
        E1["✏️ Thu phiếu làm bài tập & tô màu của học sinh"]:::eval
        E2["🌟 Tuyên dương & Đánh giá nhận thức an toàn"]:::eval
        E1 --> E2
    end

    PHASE1 ==> PHASE2
    PHASE2 ==> PHASE3
```

---

## ⏱️ 2. BẢNG TIẾN TRÌNH CHI TIẾT THEO PHÚT (TIMELINE ROADMAP)

```
┌──────────┬─────────────────────────────┬─────────────────────────────────┬──────────────────────────────┐
│  Thời gian│ Tên hoạt động               │ Hành động của Giáo viên         │ Hành động của Học sinh       │
├──────────┼─────────────────────────────┼─────────────────────────────────┼──────────────────────────────┤
│ 00 - 05' │ 🚀 Đón lớp & Khởi động     │ Nêu luật chơi "Con Người vs AI" │ Hô to đáp án & tương tác     │
│ 05 - 10' │ 💃 Điệu nhảy Ăng-ten Robot  │ Hướng dẫn động tác tay          │ Đứng lên làm theo nhịp điệu  │
│ 10 - 18' │ 🐾 Game "Dạy Robot"        │ Đóng vai Người dạy Data Trainer │ 1 bạn nhập vai Robot AI      │
│ 18 - 25' │ 🧠 Giải thích Dữ liệu (Data)│ Dùng sơ đồ "Thức ăn của AI"     │ Quan sát & trả lời câu hỏi   │
│ 25 - 35' │ 🎨 Bé vẽ - AI đoán          │ Mở QuickDraw trên máy chiếu     │ 2-3 em lên bảng vẽ trực tiếp │
│ 35 - 45' │ 📖 Sáng tác truyện với AI   │ Gõ câu chuyện từ ý tưởng lớp    │ Đóng góp nhân vật kỳ diệu    │
│ 45 - 52' │ 🛡️ 3 Quy tắc vàng an toàn   │ Đưa tình huống thực tế          │ Thảo luận & phản biện        │
│ 52 - 55' │ ❌ Kỹ thuật AI đoán sai     │ Cố tình cho AI trả lời sai      │ Cười & phát hiện lỗi của AI  │
│ 55 - 58' │ 📜 Đọc thơ đồng dao AI      │ Bắt nhịp bài thơ 4 câu          │ Đọc đồng thanh cả lớp        │
│ 58 - 60' │ 🏅 Trao huy hiệu & Dặn dò   │ Trao huy hiệu giấy & phát phiếu │ Nhận quà & làm phiếu bài tập │
└──────────┴─────────────────────────────┴─────────────────────────────────┴──────────────────────────────┘
```

---

## 📋 3. CHECKLIST KIỂM TRA TRƯỚC VÀ SAU TIẾT HỌC

### 🔴 CHECKLIST TRƯỚC GIỜ HỌC (Trước 15 phút):
- [ ] Dã in đủ **Phiếu hoạt động** cho 100% học sinh trong lớp.
- [ ] Đã test đường truyền mạng Wi-Fi và mở sẵn tab web: `quickdraw.withgoogle.com` và `chatgpt.com`.
- [ ] Đã chiếu thử **Slide 1** lên màn hình máy chiếu xem hình ảnh và chữ có rõ nét không.
- [ ] Chuẩn bị sẵn 1 bộ tranh in giấy (Chó, Mèo, Quả táo) làm phương án dự phòng khi mất kết nối mạng.

### 🟢 CHECKLIST TRONG GIỜ HỌC:
- [ ] Học sinh hào hứng tham gia trò chơi khởi động.
- [ ] 100% học sinh nắm được từ khóa: **Dữ liệu (Data)** và **3 Quy tắc an toàn**.
- [ ] Không có thời gian "chết" khi giáo viên thao tác máy tính.

### 🟡 CHECKLIST SAU GIỜ HỌC:
- [ ] Thu lại phiếu bài tập để đánh giá mức độ hiểu bài của từng em.
- [ ] Nhận xét tiết học và khen thưởng cả lớp.

---

## 🛡️ 4. KỊCH BẢN XỬ LÝ SỰ CỐ TRÊN BỤC GIẢNG (RISK MANAGEMENT)

| Sự cố phát sinh | Nguyên nhân | Kịch bản xử lý của Giáo viên |
| :--- | :--- | :--- |
| **Mất Wi-Fi / Mạng quá chậm** | Nghẽn mạng trường học | Chuyển ngay sang **Phương án B**: Giơ bức ảnh vẽ sẵn ra và đóng vai "Giáo viên là cỗ máy AI", đố học sinh đoán. |
| **AI trả lời ra từ ngữ khó hiểu** | ChatGPT dùng từ người lớn | Giáo viên đọc lướt nhanh và **dịch lại theo ngôn ngữ tiểu học** cho cả lớp nghe. |
| **Học sinh ồn ào khi chơi game** | Các em quá hào hứng | Hô khẩu lệnh phản xạ: *Giáo viên hô "Robot đâu?" ➡️ Học sinh khoanh tay hô "Robot đây!"* để ổn định trật tự. |
