# CattusMI4
对于Vivado 2024.1用户：2024破坏了ftdi_program的依赖和兼容性，请退回2023.2。参见：https://adaptivesupport.amd.com/s/question/0D54U00008mBMcvSAG/vivado-20241-break-programftdi-dependencies

FTDI-FT4232(主芯片) [Datasheet](https://ftdichip.com/wp-content/uploads/2020/08/DS_FT4232H.pdf)
- xilinx_downloader_ft4232.tcl : 在VivadoTcl中执行，将您的CattusMI4开发板编程为Xilinx下载器 （仅限**4232**型号），可以修改0123456为您自己的序列号。
- xilinx_downloader_ft2232.tcl : 在VivadoTcl中执行，将您的CattusMI4开发板编程为Xilinx下载器 （仅限**2223**型号），可以修改0123456为您自己的序列号。
- CattusMI2Sch_R2b.pdf ：修订版本2b的原理图
- CattusMI2Gbr_Masked.zip : pcb光绘 （已脱敏，严禁用于制造）
- CattusMI4_DC_Characteristics.xlsx : 破坏性分析所得直流工作参数
