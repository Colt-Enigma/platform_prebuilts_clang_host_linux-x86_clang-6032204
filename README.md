Add in your device tree to compile with clang 10.0.1
----------------------------------------------------
	TARGET_KERNEL_CLANG_COMPILE := true
	TARGET_KERNEL_CLANG_VERSION := 10.0.1
	CROSS_COMPILE := $(PWD)/prebuilts/clang/host/linux-x86/clang-6032204

