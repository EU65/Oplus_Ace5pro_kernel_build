# Oplus_Ace5pro_kernel_build

所有构建工作流都会在编译前应用 `patches/` 中的 CVE-2026-43499
rtmutex 修复；安全补丁应用失败时构建会立即停止。
