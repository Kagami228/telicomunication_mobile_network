project('mobile_network', 'cpp',
  version : '1.0',
  default_options : ['warning_level=3',
                     'cpp_std=c++14'])

exe = executable('mobile_network', 'main.cpp','Wrapper.cpp',
  install : true)
  
test('basic', exe)
