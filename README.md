# TVM Codegen Notes



# Codegen Optimization

* DietCode, dynamic shape, loop partitioning and local padding optimization for CUDA [repo0](https://github.com/UofT-EcoSystem/DietCode/tree/main) [repo1](https://github.com/UofT-EcoSystem/DietCode) [source code](https://github.com/UofT-EcoSystem/tvm/tree/4a7edcf19382d93908f2226b226bb58f18d4e1fb#local-padding) [paper](https://assets.amazon.science/14/33/43345d8142d8936ec591f5600aa5/dietcode-automatic-optimization-for-dynamic-tensor-programs.pdf) [slides](https://mlsys.org/media/mlsys-2022/Slides/2175.pdf) [pre-RFC](https://discuss.tvm.apache.org/t/rfc-dietcode-an-auto-scheduler-for-dynamic-tensor-programs/12757) [doc](https://uoft-ecosystem.github.io/DietCode/index.html)


# CPU backend

* [Intel-LIBXSMM-integration](https://github.com/apache/tvm-rfcs/blob/main/rfcs/0046-Intel-LIBXSMM-integration.md)

* [ARM aarch64-backend-with-sve](https://github.com/apache/tvm-rfcs/blob/main/rfcs/0094-aarch64-backend-with-sve.md)

# Other techniques

* [Halide SVE support](https://github.com/halide/Halide/pull/6781)

