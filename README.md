 # BPSK-QPSK-16QAM-64QAM调制解调

 ## 概述

 本仓库提供了BPSK（二进制相移键控）、QPSK（正交相移键控）、16QAM（16进制幅度调制）以及64QAM的调制与解调实现代码。特别地，这些实现完全避免了依赖MATLAB的内置函数，旨在为学习数字信号处理和通信原理的学生及爱好者提供一个清晰、简洁的自学工具。通过自行编写的代码，用户可以更深入地理解各种调制技术的核心概念与操作细节。

 #3 特点

 - **纯自定义代码**：所有调制解调算法均非基于MATLAb自带库函数，便于学习每一行背后的数学逻辑。
 - **教育友好**：适合于教学和自我学习，帮助用户直观了解不同调制方式的特性。
 - **模块化设计**：代码结构清晰，方便理解和修改，易于集成到更复杂的通信系统仿真中。
 - **应用场景广泛**：适用于简单的通信系统原型开发、学术研究辅助或教育演示等。

 ## 使用指南

 1. **环境要求**：需要MATLAB环境来运行这些脚本。
 2. **启动步骤**：
    - 下载本仓库中的全部文件。
       - 打开MATLAB，定位到下载的文件夹。
          - 运行对应的调制或解调函数（例如，从最基础的`bpskModem.m`开始）。
          3. **示例用法**：每种调制方式通常会有相应的调制(`modulation`)和解调(`demodulation`)函数，用户可以通过调用这些函数，并传入适当的参数来生成并检测信号。
          4. **调试与学习**：建议在运行代码的同时，仔细阅读每部分代码注释，理解数据流的处理过程和变换逻辑。

          ## 注意事项

          - 在使用本仓库的代码时，请确保你具备基本的数字信号处理知识。
          - 为了最大化学习效果，建议尝试修改参数或增加噪声模型，观察对信号质量的影响。
          - 请注意，由于是自定义实现，虽然尽力保证准确性，但在极端情况下可能不完全符合工业标准实现。

          通过这个仓库的学习与实践，希望用户能更好地掌握现代通信系统中不可或缺的调制与解调技术。开始你的探索之旅吧！

          ## 下载链接
          [BPSK-QPSK-16QAM-64QAM调制解调](https://pan.quark.cn/s/05bbc820fe80) 

          (备用: [备用下载](https://pan.baidu.com/s/1KsxccN_W4Riw35yW8CTyFw?pwd=1234))
