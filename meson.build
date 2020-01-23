project('libinireader', 'cpp',
    meson_version: '>= 0.50.0')

src = [
    'cpp/INIReader.cpp'
]

ini_lib = static_library('ini', src)
ini_dep = declare_dependency(link_with: [ini_lib])