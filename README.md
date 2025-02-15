# Qryptum

## About The Project

Qryptum is a next-generation machine learning framework designed for efficiency and high-performance computation. Built on the cutting-edge Mojo programming language, Qryptum aims to redefine AI development by leveraging static graph compilation and low-level optimizations, achieving speeds comparable to or surpassing well-established frameworks.

Mojo, developed by Modular, is engineered to provide the ease of Python while delivering performance similar to Rust or C++. Qryptum capitalizes on this by integrating custom Tensor and TensorShape implementations, optimizing execution performance, and streamlining AI model training and inference.

While Qryptum is still in its early development phase, continuous improvements and upgrades are being made to push the boundaries of AI computation. Stay tuned for upcoming benchmarks and feature enhancements!

## Quick Start

To run Qryptum benchmarks, execute the following:

```sh
mojo -I . examples/housing.mojo
mojo -I . examples/sin_estimate.mojo
mojo -I . examples/mnist.mojo
```

For comparison, a PyTorch-based implementation can be run using:

```sh
pip install -r python-requirements.txt
python examples/housing.py
python examples/sin_estimate.py
python examples/mnist.py
```

## Roadmap

### v0.1.0 ✅
- Optimized matrix multiplication and convolution kernels
- Custom Tensor and TensorShape implementation
- Enhanced benchmarking and model execution performance
- Profiling tools and additional performance testing

### v0.2.0 (Work In Progress)
- Additional operators: Slice, (Un)Squeeze, Concat, Clip, Gather, Split, FMA, etc.
- Expanded layer support and activation functions
- Graph submodules & graph concatenation
- Computer vision benchmarks

### Long-Term Goals
- Advanced parallelization techniques
- GPU acceleration support
- Improved data loaders for training efficiency
- Automatic tuning and performance optimizations
- ONNX and MAX compatibility

## Blockchain & Token Integration
Qryptum is integrating blockchain technology to power AI computation. A dedicated Qryptum Token (QRYPT) will be introduced to facilitate seamless and decentralized access to machine learning resources. This token will be used directly for:

- Payment of compute power
- Accessing LLM (Large Language Model) resources
- Incentivizing contributions to the Qryptum ecosystem

⚠ **NO TOKEN HAS LAUNCHED YET!** Please be cautious of any unofficial token claims.

## Contributing
Qryptum is a community-driven project, and contributions are highly encouraged! Whether it's bug fixes, performance enhancements, or new feature proposals, your input helps improve the ecosystem.

### How to Contribute
1. Fork the project
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

Before submitting a PR, ensure that all unit tests pass using:

```sh
mojo run -I . test/test_ops.mojo
```

If introducing a significant feature, please include new test cases to validate its functionality.

## License
Distributed under the Apache 2.0 License with LLVM Exceptions. See `LICENSE` and the LLVM License for more information

