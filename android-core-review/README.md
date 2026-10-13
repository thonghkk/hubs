# Android Core Components — Senior Engineer Review

> 📱 Lộ trình ôn tập toàn diện cho **Senior Android Developer** — 12 chủ đề từ OS internals đến System Services

---

## 🚀 Cách sử dụng

### Xem website (cách nhanh nhất)

Mở file `index.html` bằng trình duyệt:
- **macOS / Windows / Linux:** Click đôi vào `index.html`
- **VS Code:** Dùng extension Live Server → Click "Go Live"
- **Chrome CLI:** `open index.html` (macOS) hoặc `start index.html` (Windows)

> ✅ Không cần server, không cần internet — 100% offline, zero dependencies.

---

## 📁 Cấu trúc project

```
android-core-review/
├── index.html              # Website tương tác (toàn bộ CSS/JS inline)
├── README.md               # File này
└── knowledge/              # 12 file Markdown chi tiết (nguồn kiến thức)
    ├── cc1_process_application_zygote.md
    ├── cc2_main_thread_looper_handler.md
    ├── cc3_activity_lifecycle.md
    ├── cc4_fragment_lifecycle.md
    ├── cc5_intent_intent_filter.md
    ├── cc6_pending_intent.md
    ├── cc7_broadcast_receiver.md
    ├── cc8_service_foreground_service.md
    ├── cc9_workmanager.md
    ├── cc10_content_provider.md
    ├── cc11_binder_ipc.md
    └── cc12_activity_manager_system_services.md
```

---

## 📚 12 Chủ đề ôn tập

| # | Chủ đề | Core concepts |
|---|---|---|
| 1 | **Process, Application & Zygote** | fork COW, LMKD, oom_score_adj, cold start |
| 2 | **Main Thread, Looper, Handler** | epoll, MessageQueue, ANR, memory leak |
| 3 | **Activity Lifecycle** | config change vs process death, ViewModel, SavedStateHandle, launch modes |
| 4 | **Fragment Lifecycle** | 2 lifecycles, ViewBinding cleanup, FragmentManager, backstack |
| 5 | **Intent & Intent Filter** | resolution algorithm, Parcelable vs Serializable, 1MB Binder limit |
| 6 | **PendingIntent** | system token, FLAG_IMMUTABLE, Android 12+, security |
| 7 | **BroadcastReceiver** | static vs dynamic, API 26+ limits, goAsync(), exported |
| 8 | **Service & Foreground Service** | main thread!, AIDL, FGS types, restrictions Android 12+/14+ |
| 9 | **WorkManager** | guaranteed ≠ immediate, idempotency, chaining, Room internals |
| 10 | **ContentProvider & FileProvider** | Binder IPC, CursorWindow 2MB, FileProvider vs file:// |
| 11 | **Binder IPC** | 1-copy mmap, Proxy/Stub, thread pool, DeathRecipient |
| 12 | **ActivityManagerService** | System Server, AMS/ATMS, ActivityThread, Instrumentation |

---

## 🎯 Mục tiêu học tập

Với mỗi chủ đề, trả lời được 5 lớp câu hỏi:

1. **Concept** — Thành phần này là gì?
2. **Internal mechanism** — Android Framework vận hành nó như thế nào?
3. **Real-world use case** — Khi nào nên dùng trong production?
4. **Trade-off** — Khi nào không nên dùng và giải pháp thay thế?
5. **Senior insight** — Lifecycle, process death, IPC, security và performance?

---

## ✅ Checklist hoàn thành mỗi chủ đề

- [ ] Giải thích concept trong 2 phút không nhìn tài liệu
- [ ] Vẽ được luồng nội bộ ở mức process và thread
- [ ] Nêu ít nhất 2 production use case
- [ ] Nêu ít nhất 2 trường hợp không nên dùng
- [ ] Phân tích lifecycle và process death ảnh hưởng ra sao
- [ ] Phân tích security impact nếu component được export
- [ ] Trả lời ít nhất 5 câu follow-up không chuẩn bị trước

---

## 📊 Thống kê

- **12** chủ đề từ OS foundation → System Services
- **~6,000** dòng tài liệu Markdown chi tiết
- **80+** câu hỏi phỏng vấn Senior với gợi ý trả lời
- **100% offline** — không cần internet hay server

---

## 🤝 Chia sẻ

Copy toàn bộ folder `android-core-review/` và paste vào bất kỳ thiết bị nào. Mở `index.html` là dùng được ngay.

---

*Được tạo cho lộ trình Senior Android Engineer / Android Tech Lead*
