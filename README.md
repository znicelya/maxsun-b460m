# maxsun-b460m

铭瑄挑战者B460M macOS12.6 EFI

> 电脑配置

    |硬件|型号|
    |---|---|
    |主板|铭瑄 挑战者 B460M|
    |CPU|qsrk(i5-10500 ES)|
    |核显|UHD 630|
    |wifi+蓝牙|AX210|
    |声卡|Realtek ALC662|
    |有线网卡|RTL 8111|


> 注意事项

- NVRAM -> 7C436110-AB2A-4BBB-A880-FE41995C9F82 -> boot-args -> alcid如果无法驱动声卡，可以换成1试试
- 如果有独显 需要去掉 NVRAM -> 7C436110-AB2A-4BBB-A880-FE41995C9F82 -> boot-args 中的 `-wegnoegpu` 并查阅对应显卡驱动方式

- wifi驱动只有在当前版本可用，如果后续升级需要替换对应版本的wifi驱动