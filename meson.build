project('libinireader', 'cpp',
    meson_version: '>= 0.50.0')

inc = include_directories([
    'cpp'
])

src = [
    'cpp/INIReader.cpp'
]

ini_lib = static_library('ini', src)
ini_dep = declare_dependency(include_directories: [inc], link_with: [ini_lib])