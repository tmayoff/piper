piper_lib = library('piper', 'piper.cpp', dependencies: [piper_phenomize, espeak, fmt, onnxruntime])
piper_dep = declare_dependency(dependencies: [piper_phenomize, espeak, fmt, onnxruntime], link_with: piper_lib)

executable('piper', 'main.cpp', dependencies: piper_dep)
