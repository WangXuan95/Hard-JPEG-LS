JPEG-LS encoder for FPGAs
===========================
基于**FPGA**的流式的**JPEG-LS**图象编码器

编码器代码全在 RTL/jls_encoder.sv 中。

目前仅支持深度为8bit的灰度图片，且图片宽度取值范围为[4,4095]，高度取值范围[1,65535]

请在 RTL/tb.sv 中指定待压缩的图片(.pgm)的完整路径，以及输出图片的(.jls)的完整路径，然后运行仿真。
