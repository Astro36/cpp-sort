project(
  'sort',
  'cpp',
  default_options : ['warning_level=3', 'cpp_std=c++20'],
  license : 'MIT',
  meson_version: '>=0.55.0',
  version : '0.1'
)

subdir('include')

sort_lib = library('sort', include_directories : sort_inc)
sort_dep = declare_dependency(include_directories : sort_inc, link_with : sort_lib)

subdir('benchmarks')
subdir('tests')

