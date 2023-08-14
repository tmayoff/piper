piper_lib = library(
    'piper',
    'piper.cpp',
    dependencies: [piper_phenomize, espeak, fmt, onnxruntime, spdlog],
)
piper_dep = declare_dependency(
    include_directories: '.',
    dependencies: [piper_phenomize, espeak, fmt, onnxruntime, spdlog],
    link_with: piper_lib,
)

if not meson.is_subproject()
    executable('piper', 'main.cpp', dependencies: piper_dep)
endif
