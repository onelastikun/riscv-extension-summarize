# RISC-V Ratified Unprivileged ISA Extensions

Source: RISC-V International, _The RISC-V Instruction Set Manual_, release `riscv-isa-release-cc30642-2026-06-23`, Volume I: Unprivileged Architecture.

说明：以下条目以 RISC-V International 最新发布的 `riscv-isa-release-cc30642-2026-06-23` 中 Volume I 顶部 Preface 的 ratified ISA modules 表为准；每组内部按扩展缩写字母顺序排列。

## 独立 / 基础扩展

| 缩写 | 扩展全称 / 官方章节标题 | 主要作用 | URL |
|---|---|---|---|
| `D` | D Extension for Double-Precision Floating-Point | 提供 IEEE 754 双精度浮点运算。 | [6.2](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:d) |
| `E` | RV32E and RV64E Base Integer Instruction Sets | 提供面向小型实现的精简整数寄存器基础 ISA。 | [2.3](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#rv32e) |
| `F` | F Extension for Single-Precision Floating-Point | 提供 IEEE 754 单精度浮点运算。 | [6.1](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:f) |
| `I` | RV32I / RV64I Base Integer Instruction Sets | 提供 32 位和 64 位基础整数指令集。 | [2.1 RV32I](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#rv32), [2.2 RV64I](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#rv64) |
| `M` | M Extension for Integer Multiplication and Division | 提供整数乘法和除法指令。 | [4.5](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:m) |
| `Q` | Q Extension for Quad-Precision Floating-Point | 提供 IEEE 754 四精度浮点运算。 | [6.3](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:q) |
| `RVWMO` | RVWMO Memory Consistency Model | 定义 RISC-V 弱内存一致性模型。 | [3.1](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#memorymodel) |
| `Za128rs` | Za128rs Extension for Reservation-Set Size | 指定 LR/SC 保留集合大小能力。 | [5.3](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:za128rs) |
| `Za64rs` | Za64rs Extension for Reservation-Set Size | 指定较小粒度的 LR/SC 保留集合大小能力。 | [5.4](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:za64rs) |
| `Zaamo` | Zaamo Extension for Atomic Memory Operations | 提供 AMO 类原子内存操作。 | [5.6](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zaamo) |
| `Zabha` | Zabha Extension for Byte and Halfword Atomic Memory Operations | 提供字节和半字原子内存操作。 | [5.8](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zabha) |
| `Zacas` | Zacas Extension for Atomic Compare-and-Swap (CAS) Instructions | 提供原子比较并交换指令。 | [5.9](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zacas) |
| `Zalasr` | Zalasr Extension for Atomic Load-Acquire and Store-Release Instructions | 提供原子 acquire load 和 release store 指令。 | [5.7](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zalasr) |
| `Zalrsc` | Zalrsc Extension for Load-Reserved/Store-Conditional Instructions | 提供 LR/SC 原子序列指令。 | [5.2](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zalrsc) |
| `Zama16b` | Zama16b Extension for 16-byte Misaligned Atomicity | 定义 16 字节非对齐访问的原子性能力。 | [5.10](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zama16b) |
| `Zawrs` | Zawrs Extension for Wait-on-Reservation-Set instructions | 提供等待保留集合变化的低功耗同步指令。 | [5.5](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zawrs) |
| `Zba` | Zba Extension for Address Generation | 提供地址生成常用位操作和加法辅助指令。 | [8.1](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zba) |
| `Zbb` | Zbb Extension for Basic Bit Manipulation | 提供基础位计数、旋转、取反逻辑和字节操作。 | [8.2](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zbb) |
| `Zbc` | Zbc Extension for Carry-less Multiplication | 提供无进位乘法指令。 | [8.5](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zbc) |
| `Zbkb` | Zbkb Extension for Bit Manipulation for Cryptography | 提供密码算法常用的标量位操作指令。 | [8.6](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zbkb) |
| `Zbkc` | Zbkc Extension for Carry-less Multiplication for Cryptography | 提供密码算法所需的无进位乘法子集。 | [8.7](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zbkc) |
| `Zbkx` | Zbkx Extension for Crossbar Permutations | 提供交叉置换指令以支持查表型位/字节变换。 | [8.8](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zbkx) |
| `Zbs` | Zbs Extension for Single-Bit Manipulation | 提供单个位的设置、清除、反转和提取指令。 | [8.3](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zbs) |
| `Zca` | Zca Extension for Integer Compressed Instructions | 提供基础整数压缩指令。 | [7.1](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zca) |
| `Zcb` | Zcb Extension for Additional Compressed Instructions | 提供额外的压缩整数和位操作指令。 | [7.5](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zcb) |
| `Zcd` | Zcd Extension for Double-Precision Floating-Point Compressed Instructions | 提供双精度浮点加载/存储压缩指令。 | [7.3](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zcd) |
| `Zcf` | Zcf Extension for Single-Precision Floating-Point Compressed Instructions | 提供 RV32 单精度浮点加载/存储压缩指令。 | [7.2](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zcf) |
| `Zclsd` | Zclsd Extension for Compressed Load/Store Pair Instructions | 提供 RV32 压缩双字加载/存储对指令。 | [7.9](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zclsd) |
| `Zcmop` | Zcmop Extension for Compressed May-Be-Operations | 提供 16 位 MOP 预留兼容操作指令。 | [7.10](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zcmop) |
| `Zcmp` | Zcmp Extension for Compressed Prologues and Epilogues | 提供函数序言和尾声的压缩 PUSH/POP 指令。 | [7.7](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zcmp) |
| `Zcmt` | Zcmt Extension for Compressed Table Jumps | 提供压缩表跳转指令。 | [7.6](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zcmt) |
| `Zdinx` | Zdinx | 提供使用整数寄存器的双精度浮点指令。 | [6.8.2](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zdinx) |
| `Zfa` | Zfa Extension for Additional Floating-Point Instructions | 提供额外浮点加载常量、比较、转换和最值等指令。 | [6.6](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zfa) |
| `Zfbfmin` | Zfbfmin Extension for BF16 Conversions | 提供标量 BF16 与单精度浮点之间的最小转换支持。 | [6.7](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zfbfmin) |
| `Zfh` | Zfh Extension for Half-Precision Floating-Point | 提供 IEEE 754 半精度浮点运算。 | [6.4](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zfh) |
| `Zfhmin` | Zfhmin Extension for Half-Precision Floating-Point Conversions | 提供半精度浮点最小转换支持。 | [6.5](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zfhmin) |
| `Zfinx` | Zfinx, Zdinx, Zhinx, and Zhinxmin Extensions for Floating-Point in Integer Registers | 提供使用整数寄存器承载浮点操作数的单精度浮点指令。 | [6.8](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zfinx) |
| `Zhinx` | Zhinx | 提供使用整数寄存器的半精度浮点指令。 | [6.8.4](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#_zhinx) |
| `Zhinxmin` | Zhinxmin | 提供使用整数寄存器的半精度浮点最小转换支持。 | [6.8.5](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#_zhinxmin) |
| `Zic64b` | Zic64b Extension for 64-byte Cache Blocks | 声明缓存块大小为 64 字节的能力。 | [4.15](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zic64b) |
| `Zicbom` | Zicbom Extension for Cache-Block Management | 提供缓存块清理、刷新和失效管理操作。 | [4.20.5](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zicbom) |
| `Zicbop` | Zicbop Extension for Cache-Block Prefetch | 提供缓存块预取指令。 | [4.20.7](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zicbop) |
| `Zicboz` | Zicboz Extension for Cache-Block Zero | 提供缓存块清零指令。 | [4.20.6](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zicboz) |
| `Ziccamoa` | Ziccamoa Extension for Main Memory Atomics | 声明主存支持原子内存操作。 | [4.12](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:ziccamoa) |
| `Ziccamoc` | Ziccamoc Extension for Main Memory Compare-and-Swap | 声明主存支持比较并交换原子操作。 | [4.13](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:ziccamoc) |
| `Ziccid` | Ziccid Extension for Instruction/Data Coherence and Consistency | 定义指令和数据访问之间的主存一致性能力。 | [4.10](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#_ziccid_extension_for_instructiondata_coherence_and_consistency) |
| `Ziccif` | Ziccif Extension for Instruction-Fetch Atomicity | 定义取指访问的原子性能力。 | [4.9](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:ziccif) |
| `Zicclsm` | Zicclsm Extension for Main Memory Misaligned Accesses | 声明主存支持非对齐加载/存储访问。 | [4.14](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zicclsm) |
| `Ziccrse` | Ziccrse Extension for Main Memory Reservability | 声明主存支持 LR/SC 保留语义。 | [4.11](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:ziccrse) |
| `Zicfilp` | Zicfilp for Landing Pad | 提供控制流完整性中的 landing pad 支持。 | [4.17.1](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zicfilp) |
| `Zicfiss` | Shadow Stack (Zicfiss) | 提供控制流完整性中的影子栈支持。 | [4.17.2](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zicfiss) |
| `Zicntr` | Zicntr Extension for Base Counters and Timers | 提供基础计数器和定时器 CSR。 | [4.3](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zicntr) |
| `Zicond` | Zicond Extension for Integer Conditional Operations | 提供整数条件清零类操作。 | [4.7](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zicond) |
| `Zicsr` | Zicsr Extension for Control and Status Register (CSR) Instructions | 提供控制与状态寄存器读写指令。 | [4.2](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zicsr) |
| `Zifencei` | Zifencei Extension for Instruction-Fetch Fence | 提供指令取指同步屏障。 | [4.1](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zifencei) |
| `Zihintntl` | Zihintntl Extension for Non-Temporal Locality Hints | 提供非时间局部性访问提示。 | [4.18](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zihintntl) |
| `Zihintpause` | Zihintpause Extension for Pause Hint | 提供自旋等待中的暂停提示。 | [4.19](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zihintpause) |
| `Zihpm` | Zihpm Extension for Hardware Performance Counters | 提供硬件性能计数器访问能力。 | [4.4](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zihpm) |
| `Zilsd` | Zilsd Extension for Load/Store Pair Instructions | 提供整数加载/存储对指令。 | [4.8](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zilsd) |
| `Zimop` | Zimop Extension for May-Be-Operations | 提供可被未来扩展重定义的 MOP 指令空间。 | [4.16](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zimop) |
| `Zknd` | Zknd NIST Suite: AES Decryption | 提供 AES 解密相关标量指令。 | [11.1.2.1](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zknd) |
| `Zkne` | Zkne NIST Suite: AES Encryption | 提供 AES 加密相关标量指令。 | [11.1.2.2](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zkne) |
| `Zknh` | Zknh NIST Suite: Hash Function Instructions | 提供 SHA-2 哈希相关标量指令。 | [11.1.2.3](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zknh) |
| `Zkr` | Zkr Entropy Source Extension | 提供熵源 CSR 接口。 | [11.1.2.6](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zkr) |
| `Zksed` | Zksed ShangMi Suite: SM4 Block Cipher Instructions | 提供 SM4 分组密码相关标量指令。 | [11.1.2.4](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zksed) |
| `Zksh` | Zksh ShangMi Suite: SM3 Hash Function Instructions | 提供 SM3 哈希相关标量指令。 | [11.1.2.5](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zksh) |
| `Zkt` | Zkt Extension for Data-Independent Execution Latency | 定义数据无关执行延迟要求。 | [11.2](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zkt) |
| `Zmmul` | Zmmul Extension for Integer Multiplication | 提供仅乘法的整数乘法子集。 | [4.6](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zmmul) |
| `Ztso` | Ztso Extension for Total Store Ordering | 提供更强的总存储排序内存模型。 | [3.2](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:ztso) |
| `Zvbb` | Zvbb Vector Extension for Basic Bit Manipulation | 提供向量基础位操作指令。 | [9.12](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zvbb) |
| `Zvbc` | Zvbc Vector Extension for Carry-less Multiplication | 提供向量无进位乘法指令。 | [9.13](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zvbc) |
| `Zve32f` | Zve32f Vector Extension for Single-Precision Floating-Point | 提供嵌入式向量单精度浮点支持。 | [9.3](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zve32f) |
| `Zve32x` | Zve32x Vector Extension for 32-bit Integer | 提供嵌入式向量 8/16/32 位整数支持。 | [9.2](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zve32x) |
| `Zve64d` | Zve64d Vector Extension for Double-Precision Floating-Point | 提供嵌入式向量双精度浮点支持。 | [9.6](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zve64d) |
| `Zve64f` | Zve64f Vector Extension for 64-bit Integer and Single-Precision Floating-Point | 提供嵌入式向量 64 位整数和单精度浮点支持。 | [9.5](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zve64f) |
| `Zve64x` | Zve64x Vector Extension for 64-bit Integer | 提供嵌入式向量 64 位整数支持。 | [9.4](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zve64x) |
| `Zvfbfmin` | Zvfbfmin Vector Extension for BF16 Conversions | 提供向量 BF16 转换支持。 | [9.10](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zvfbfmin) |
| `Zvfbfwma` | Zvfbfwma Vector Extension for BF16 Widening Multiply-Accumulation | 提供向量 BF16 扩宽乘加支持。 | [9.11](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zvfbfwma) |
| `Zvfh` | Zvfh Vector Extension for Half-Precision Floating-Point | 提供向量半精度浮点运算支持。 | [9.9](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zvfh) |
| `Zvfhmin` | Zvfhmin Vector Extension for Half-Precision Floating-Point Conversions | 提供向量半精度浮点最小转换支持。 | [9.8](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zvfhmin) |
| `Zvkb` | Zvkb Vector Cryptography Bit-manipulation | 提供向量密码学常用位操作子集。 | [11.3.2.1](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zvkb) |
| `Zvkg` | Zvkg Vector GCM/GMAC | 提供向量 GCM/GMAC 运算支持。 | [11.3.2.2](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zvkg) |
| `Zvkned` | Zvkned NIST Suite: Vector AES Block Cipher | 提供向量 AES 分组密码指令。 | [11.3.2.3](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zvkned) |
| `Zvknha` | Zvknha and Zvknhb NIST Suite: Vector SHA-2 Secure Hash | 提供向量 SHA-2 安全哈希指令的 `Zvknha` 变体。 | [11.3.2.4](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zvknha) |
| `Zvknhb` | Zvknha and Zvknhb NIST Suite: Vector SHA-2 Secure Hash | 提供向量 SHA-2 安全哈希指令的 `Zvknhb` 变体。 | [11.3.2.4](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zvknha) |
| `Zvksed` | Zvksed ShangMi Suite: SM4 Block Cipher | 提供向量 SM4 分组密码指令。 | [11.3.2.5](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zvksed) |
| `Zvksh` | Zvksh ShangMi Suite: SM3 Secure Hash | 提供向量 SM3 安全哈希指令。 | [11.3.2.6](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zvksh) |
| `Zvkt` | Zvkt Vector Data-Independent Execution Latency | 定义向量指令的数据无关执行延迟要求。 | [11.3.2.13](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zvkt) |
| `Zvl*` | Zvl*: Minimum Vector Length Extensions | 定义最小向量长度能力族。 | [9.1.18.1](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#_zvl_minimum_vector_length_extensions) |

## 组合 / 包含关系扩展

| 缩写 | 扩展全称 / 官方章节标题 | 主要作用 | URL |
|---|---|---|---|
| `A` | A Extension for Atomic Instructions | 提供原子内存操作基础能力；包含 `Zalrsc`、`Zaamo`。 | [5.1](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:a) |
| `B` | B Bit Manipulation Extension for Application Processors | 面向应用处理器的位操作组合扩展；包含 `Zba`、`Zbb`、`Zbs`。 | [8.4](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:b) |
| `C` | C Extension for Compressed Instructions | 提供通用压缩指令以提升代码密度；主要依赖 `Zca`，并按条件包含 `Zcf`、`Zcd`。 | [7.4](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:c) |
| `V` | V Vector Extension for Application Processors | 提供面向应用处理器的通用向量计算能力；主要依赖 `Zvl128b`、`Zve64d`。 | [9.7](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:v) |
| `Zce` | Zce Extension for Enhanced Instruction Compression | 提供面向微控制器的增强压缩指令组合；包含 `Zca`、`Zcb`、`Zcmp`、`Zcmt`，条件包含 `Zcf`。 | [7.8](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zce) |
| `Zk` | Zk Standard scalar cryptography extension | 标量密码学组合扩展；包含 `Zkn`、`Zkr`、`Zkt`。 | [11.1.2.9](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zk) |
| `Zkn` | Zkn NIST Algorithm Suite | 标量 NIST 密码算法组合扩展；包含 `Zbkb`、`Zbkc`、`Zbkx`、`Zkne`、`Zknd`、`Zknh`。 | [11.1.2.7](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zkn) |
| `Zks` | Zks ShangMi Algorithm Suite | 标量商密算法组合扩展；包含 `Zbkb`、`Zbkc`、`Zbkx`、`Zksed`、`Zksh`。 | [11.1.2.8](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zks) |
| `Zvkn` | Zvkn NIST Algorithm Suite | 向量 NIST 密码算法组合扩展；包含 `Zvkned`、`Zvknhb`、`Zvkb`、`Zvkt`。 | [11.3.2.7](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zvkn) |
| `Zvknc` | Zvknc NIST Algorithm Suite with carry-less multiply | 向量 NIST 密码组合扩展并加入无进位乘法；包含 `Zvkn`、`Zvbc`。 | [11.3.2.8](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zvknc) |
| `Zvkng` | Zvkng NIST Algorithm Suite with GCM | 向量 NIST 密码组合扩展并加入 GCM；包含 `Zvkn`、`Zvkg`。 | [11.3.2.9](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zvkng) |
| `Zvks` | Zvks ShangMi Algorithm Suite | 向量商密算法组合扩展；包含 `Zvksed`、`Zvksh`、`Zvkb`、`Zvkt`。 | [11.3.2.10](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zvks) |
| `Zvksc` | Zvksc ShangMi Algorithm Suite with carry-less multiplication | 向量商密组合扩展并加入无进位乘法；包含 `Zvks`、`Zvbc`。 | [11.3.2.11](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zvksc) |
| `Zvksg` | Zvksg ShangMi Algorithm Suite with GCM | 向量商密组合扩展并加入 GCM；包含 `Zvks`、`Zvkg`。 | [11.3.2.12](https://github.com/riscv/riscv-isa-manual/releases/download/riscv-isa-release-cc30642-2026-06-23/riscv-spec.html#ext:zvksg) |
