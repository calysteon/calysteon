# CVE List
| CVE | Vendor | CWE | Reference | Writeup |
|---|---|---|---|---|
| **CVE-2026-28890** | Apple | **CWE-125** (Out-of-Bounds Read) | [126801](https://support.apple.com/en-us/126801) | - |
| **CVE-2026-28857** | Apple | **CWE-122** (Heap-based Buffer Overflow) | [126792](https://support.apple.com/en-us/126792), [126794](https://support.apple.com/en-us/126794), [126799](https://support.apple.com/en-us/126799), [126800](https://support.apple.com/en-us/126800) | - |
| **CVE-2026-28845** | Apple | **CWE-862** (Missing Authorization) | [126794](https://support.apple.com/en-us/126794) | - |
| **CVE-2026-27820** | Ruby | **CWE-122** (Heap-based Buffer Overflow) | [ruby-lang.org](https://www.ruby-lang.org/en/news/2026/03/05/buffer-overflow-zlib-cve-2026-27820/) | - |
| **CVE-2026-20652** | Apple | **CWE-191** (Integer Underflow) | [126354](https://support.apple.com/en-us/126354) | - |
| **CVE-2025-43505** | Apple | **CWE-787** (Out-of-Bounds Write / Heap Corruption) | [125641](https://support.apple.com/en-us/125641) | - |
| **CVE-2025-43504** | Apple | **CWE-121** (Stack-based Buffer Overflow) | [125641](https://support.apple.com/en-us/125641) | [True](https://objective-see.org/blog/blog_0x83.html) |
| **CVE-2025-43375** | Apple | **CWE-20** (Improper Input Validation) | [125117](https://support.apple.com/en-us/125117) | - |
| **CVE-2025-43370** | Apple | **CWE-20** (Improper Input Validation) | [125117](https://support.apple.com/en-us/125117) | - |
| **CVE-2025-43353** | Apple | **CWE-787** (Out-of-Bounds Write / Heap Corruption) | [125110](https://support.apple.com/en-us/125110), [125111](https://support.apple.com/en-us/125111), [125112](https://support.apple.com/en-us/125112) | [True](https://calysteon.github.io/cve/CVE-2025-43353.html) |
| **CVE-2025-43299** | Apple | **CWE-20** (Improper Input Validation) | [125109](https://support.apple.com/en-us/125109), [125110](https://support.apple.com/en-us/125110), [125111](https://support.apple.com/en-us/125111), [125112](https://support.apple.com/en-us/125112) | - |
| **CVE-2025-43295** | Apple | **CWE-20** (Improper Input Validation) | [125109](https://support.apple.com/en-us/125109), [125110](https://support.apple.com/en-us/125110), [125111](https://support.apple.com/en-us/125111), [125112](https://support.apple.com/en-us/125112) | - |
| **CVE-2025-53623** | Shopify | **CWE-78** (OS Command Injection) | - | - |
| **CVE-2025-43577** | Adobe | **CWE-416** (Use-After-Free) | - | - |
| **CVE-2024-13334** | WordPress | **CWE-79** (Reflected XSS) | - | - |
| **CVE-2024-10813** | WordPress | **CWE-200** (Information Exposure) | - | - |
| **CVE-2024-10792** | WordPress | **CWE-79** (Reflected XSS) | - | - |
| **CVE-2024-0848** | WordPress | **CWE-79** (Reflected XSS) | - | - |
| **CVE-2024-0847** | WordPress | **CWE-352** (CSRF) | - | - |
| **CVE-2024-1780** | WordPress | **CWE-79** (Reflected XSS) | - | - |
| **CVE-2024-1782** | WordPress | **CWE-79** (Reflected XSS) | - | - |
| **CVE-2024-0708** | WordPress | **CWE-200** (Information Exposure) | - | - |
| **CVE-2024-0859** | WordPress | **CWE-352** (CSRF) | - | - |

---

# Acknowledgments
| Vendor | Platform / Release | Component(s) | Reference |
|---|---|---|---|
| Apple | Xcode 26.2 | **otool** | [126801](https://support.apple.com/en-us/126801) |
| Apple | iOS / iPadOS 26.2 | **LLVM**, **WebKit** | [126792](https://support.apple.com/en-us/126792) |
| Apple | macOS Tahoe 26.2 | **Core Bluetooth**, **LaunchServices**, **LLVM**, **WebKit** | [126794](https://support.apple.com/en-us/126794) |
| Apple | macOS Tahoe 26.2 | **FileVault** | [125886](https://support.apple.com/en-us/125886) |
| Apple | tvOS 26.2 | **LLVM** | [126797](https://support.apple.com/en-us/126797) |
| Apple | watchOS 26.2 | **LLVM** | [126798](https://support.apple.com/en-us/126798) |
| Apple | visionOS 26.2 | **LLVM**, **WebKit** | [126799](https://support.apple.com/en-us/126799) |
| Apple | Safari 26.2 | **WebKit** | [126800](https://support.apple.com/en-us/126800) |
| Apple | iOS / iPadOS 26 | **darwinOS**, **libc**, **libpthread**, **libxml2** | [125108](https://support.apple.com/en-us/125108) |
| Apple | iOS / iPadOS 18.7 | **libpthread**, **libxml2** | [125109](https://support.apple.com/en-us/125109) |
| Apple | macOS Tahoe 26 | **AMD**, **Core Bluetooth**, **CoreMedia**, **darwinOS**, **libc**, **libedit**, **libpthread**, **libxml2** | [125110](https://support.apple.com/en-us/125110) |
| Apple | macOS Sequoia 15.7 | **libpthread**, **libxml2** | [125111](https://support.apple.com/en-us/125111) |
| Apple | macOS Sonoma 14.8 | **libpthread**, **libxml2** | [125112](https://support.apple.com/en-us/125112) |
| Apple | tvOS 26 | **darwinOS**, **libc**, **libpthread**, **libxml2** | [125114](https://support.apple.com/en-us/125114) |
| Apple | visionOS 26 | **darwinOS** | [125115](https://support.apple.com/en-us/125115) |
| Apple | watchOS 26 | **darwinOS**, **libc**, **libpthread**, **libxml2** | [125116](https://support.apple.com/en-us/125116) |
