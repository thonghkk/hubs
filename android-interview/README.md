# 📱 Sổ Ôn Phỏng Vấn Android — Java · Kotlin · Framework

> Hệ thống 72 câu hỏi phỏng vấn thực chiến cho Android Developer, phân chia theo 12 tầng kiến thức (L0–L9), tích hợp lộ trình ôn 3 tuần, gắn cờ điểm yếu 🔴, tần suất hỏi 🔁, chế độ bấm giờ 60s và bảng truy vết feedback thực tế.

---

## 🚀 Cách sử dụng

Mở trực tiếp file `index.html` bằng trình duyệt web:
- **macOS / Windows / Linux:** Bấm đúp vào `index.html` hoặc chạy lệnh `open index.html` (macOS).
- **Trực tiếp từ Knowledge Hub:** Truy cập `../index.html` và chọn thẻ **"Sổ ôn phỏng vấn Android"**.

> ✅ 100% Offline, Zero Dependencies, tự động lưu tiến độ vào LocalStorage.

---

## 📁 Cấu trúc thư mục

```text
android-interview/
├── index.html        # Ứng dụng SPA hoàn chỉnh (HTML + CSS + JS inline + Data)
└── README.md         # Tài liệu hướng dẫn sử dụng
```

---

## 📚 12 Tầng Kiến Thức (L0 – L9)

| Mã | Tầng | Số câu | Trọng tâm |
|:---:|---|:---:|---|
| **L0** | Giới thiệu & Kinh nghiệm | 3 | Template giới thiệu tiếng Anh ~60s, khung 5 ý mô tả dự án, khung STAR kể bug |
| **L1** | Quy trình phát triển phần mềm | 6 | Waterfall, V-Model, Agile/Scrum, Scrum Master, Artifacts |
| **L2** | Yêu cầu & Kiến trúc hệ thống | 3 | NFR, HLD vs LLD (câu hỏi tình huống), Client-Server vs P2P |
| **L3** | Thiết kế chi tiết: SOLID, Design Pattern, UML | 10 | 🔴 Singleton thread-safe, 🔴 Builder, 🔴 Adapter, Observer, Class/Sequence Diagram |
| **L4** | Ngôn ngữ & OOP (Java/Kotlin) | 11 | 🔴 Abstract vs Interface, Đa hình, Kotlin vs Java, Coroutine scopes, Exception |
| **L4b**| Cấu trúc dữ liệu & Thuật toán | 9 | Array vs Collection, HashMap/Hashtable, Binary Search, DFS/BFS, Quick/Merge Sort |
| **L5** | Concurrency (Đa luồng) | 7 | 🔴 Thread Pool / ExecutorService, Deadlock, Shared variables, Reactive programming |
| **L5** | Memory & Runtime | 3 | GC roots & ART GC, WeakReference, Memory leak & công cụ xử lý |
| **L6** | Android Framework & Platform | 6 | 🔴 Kiến trúc nền tảng 5 tầng, Service lifecycle, Runtime/Special Permission, Binder IPC, AIDL, JNI |
| **L7** | Data layer & Persistence | 4 | Lưu trữ dữ liệu Android, Room database, Serializable vs Parcelable, AAR vs JAR |
| **L8** | Testing | 5 | Unit test, C0/C1/C2 coverage, Mock vs Stub vs Fake vs Spy, Testing frameworks |
| **L9** | Debug, Log & Tools | 5 | Quy trình debug & Tools, Log levels, Cơ chế logd/buffer, ADB commands, Buffer size |

---

## 🎯 3 Chế Độ Chính Trong Ứng Dụng

1. **📖 Chế độ Học (Learn):**
   - 3 cột độc lập: Điều hướng tầng → Danh sách câu hỏi → Nội dung chi tiết.
   - Bộ lọc thông minh: Toàn bộ, Cần ôn (🔴), Hỏi nhiều (🔁), Chấm điểm 0 / 1 / 2 / 3.
   - Chế độ tự kiểm tra (Flashcard) kèm đồng hồ bấm giờ 60s để luyện phản xạ nói to.
   - Tự chấm điểm theo 4 mức độ: *Không biết (0)*, *Mơ hồ (1)*, *Ấp úng (2)*, *Thành thạo (3)*.

2. **📊 Chế độ Tiến độ (Progress):**
   - Theo dõi tiến độ mục tiêu đạt mức "Thành thạo" (Điểm 3).
   - Lộ trình 3 tuần chi tiết:
     - **Tuần 1:** Các câu từng hụt và kỹ năng thiết kế (L2, L3, L4.2, L5.1).
     - **Tuần 2:** Android Framework, concurrency, memory (L6, L7, L5.2–L5.10).
     - **Tuần 3:** Ngôn ngữ, CTDL, testing, debug, quy trình, giới thiệu (L0, L1, L4, L4b, L8, L9).
   - Sao lưu (Export) và Nhập lại (Import) dữ liệu tiến độ dạng JSON.

3. **🔍 Chế độ Truy vết (Trace):**
   - Bảng đối chiếu chéo giữa từng dòng ghi chú từ các buổi phỏng vấn thực tế với câu hỏi cụ thể trong bộ đề, đảm bảo không bỏ sót bất kỳ kiến thức nào.

---

## ⌨️ Phím tắt tiện lợi

- <kbd>/</kbd>: Nhảy nhanh vào ô tìm kiếm.
- <kbd>J</kbd> / <kbd>K</kbd>: Di chuyển tới câu tiếp theo / câu trước đó.
- <kbd>Space</kbd>: Lật mở / che đáp án trong chế độ tự kiểm tra.
- <kbd>0</kbd> – <kbd>3</kbd>: Chấm điểm nhanh cho câu đang học.
- <kbd>1</kbd> – <kbd>3</kbd> (trong trang Tiến độ): Chuyển nhanh giữa các tab Học / Tiến độ / Truy vết.
