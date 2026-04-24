📱 iOS App
│
├── 🎨 Presentation Layer（UI层）
│   ├── AppDelegate / SceneDelegate
│   ├── Router / Coordinator（页面跳转控制）
│   ├── View（UIKit / SwiftUI）
│   ├── ViewController / ViewModel
│   └── UI Components（通用组件）
│
├── 🧠 Business Layer（业务逻辑层）
│   ├── UseCase / Service
│   ├── Business Logic（登录、支付、推荐等）
│   └── State Management（Redux / MVVM / Observable）
│
├── 🌐 Network Layer（网络层）
│   ├── API Client（封装请求）
│   ├── Request Builder
│   ├── Response Parser（JSON → Model）
│   ├── Interceptor（Token、日志、埋点）
│   └── Retry / Timeout / Error Handling
│
├── 💾 Storage Layer（存储层）
│   ├── UserDefaults（轻量配置）
│   ├── Keychain（敏感信息）
│   ├── Database（CoreData / SQLite）
│   ├── FileManager（文件缓存）
│   └── Cache（内存 + 磁盘）
│
├── 🔐 Auth Layer（认证层）
│   ├── Login / Logout
│   ├── Token 管理（Access / Refresh）
│   ├── Session 管理
│   └── 权限控制（Role / Feature）
│
├── 📡 Analytics & APM（监控层）
│   ├── Event Tracking（点击/页面）
│   ├── Performance（启动时间、FPS）
│   ├── Crash（KSCrash / PLCrashReporter）
│   ├── Logs（本地 + 上报）
│   └── OpenTelemetry（Trace / Span）
│
├── 🔔 Push & Messaging（消息系统）
│   ├── APNs
│   ├── Firebase Cloud Messaging
│   ├── In-App Messaging
│   └── Notification Service Extension
│
├── 🧩 Feature Modules（业务模块）
│   ├── Home
│   ├── Feed
│   ├── Profile
│   ├── Settings
│   └── Payment / Order
│
├── ⚙️ Infrastructure（基础设施）
│   ├── Dependency Injection（DI）
│   ├── Config（环境配置 dev/staging/prod）
│   ├── Feature Flag / A-B Test
│   ├── Logging System
│   └── Error Reporting
│
├── 🔄 Async & Concurrency（并发）
│   ├── GCD / OperationQueue
│   ├── Swift Concurrency（async/await）
│   └── Combine / RxSwift
│
├── 🔗 Integration（集成层）
│   ├── Third-party SDK（支付/登录/广告）
│   ├── WebView（Hybrid）
│   └── DeepLink / Universal Link
│
├── 🧪 Testing（测试）
│   ├── Unit Test
│   ├── UI Test（XCUITest）
│   ├── Snapshot Test
│   └── Mock / Stub
│
├── 🚀 DevOps（工程化）
│   ├── CI/CD（GitHub Actions / Jenkins）
│   ├── Fastlane
│   ├── 自动打包 / 上传 TestFlight
│   └── Crash 符号表管理（dSYM）
│
└── 📦 Packaging（打包发布）
    ├── Build Configuration
    ├── Code Signing
    ├── App Store / Enterprise / AdHoc
    └── 灰度发布（Feature Flag / Remote Config）
