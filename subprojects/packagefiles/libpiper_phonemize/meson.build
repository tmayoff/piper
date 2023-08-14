project('piper-phonemize', 'cpp')

cpp = meson.get_compiler('cpp')

libpiper_phonemize_dep = declare_dependency(
    dependencies: cpp.find_library(
        'libpiper_phonemize',
        dirs: [meson.current_source_dir() / 'lib'],
    ),
    include_directories: 'include',
)

libespeak_ng_dep = declare_dependency(
    dependencies: cpp.find_library(
        'libespeak-ng',
        dirs: [meson.current_source_dir() / 'lib'],
    ),
    include_directories: 'include',
)

libonnxruntime_dep = declare_dependency(
    dependencies: cpp.find_library(
        'libonnxruntime',
        dirs: [meson.current_source_dir() / 'lib'],
    ),
    include_directories: 'include',
)
