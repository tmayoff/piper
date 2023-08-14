project('piper-phonemize', 'cpp')

cpp = meson.get_compiler('cpp')

libpiper_phonemize_dep = declare_dependency(
    dependencies: cpp.find_library(
        'libpiper_phonemize',
        dirs: [meson.current_source_dir() / 'lib'],
    ),
    include_directories: 'include',
)
