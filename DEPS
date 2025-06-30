use_relative_paths = True

vars = {
  'abseil_git':  'https://github.com/abseil',
  'google_git':  'https://github.com/google',
  'khronos_git': 'https://github.com/KhronosGroup',

  'abseil_revision': '1315c900e1ddbb08a23e06eeb9a06450052ccb5e',
  'effcee_revision': '8ce15c424e61a94ee27b5be0ec0ed036b158e6e3',
  'glslang_revision': '8a85691a0740d390761a1008b4696f57facd02c4',
  'googletest_revision': 'c67de117379f4d1c889c7581a0a76aa0979c2083',
  're2_revision': '8ea5841693c6c0b837c6ed2189217e8f8d6fee9c',
  'spirv_headers_revision': '04b76709bf40a7ce8df3382060ef3620f19de566',
  'spirv_tools_revision': '40eb301f320e1d85ce3bc12798022149eae3eee3',
}

deps = {
  'third_party/abseil_cpp':
      Var('abseil_git') + '/abseil-cpp.git@' + Var('abseil_revision'),

  'third_party/effcee': Var('google_git') + '/effcee.git@' +
      Var('effcee_revision'),

  'third_party/googletest': Var('google_git') + '/googletest.git@' +
      Var('googletest_revision'),

  'third_party/glslang': Var('khronos_git') + '/glslang.git@' +
      Var('glslang_revision'),

  'third_party/re2': Var('google_git') + '/re2.git@' +
      Var('re2_revision'),

  'third_party/spirv-headers': Var('khronos_git') + '/SPIRV-Headers.git@' +
      Var('spirv_headers_revision'),

  'third_party/spirv-tools': Var('khronos_git') + '/SPIRV-Tools.git@' +
      Var('spirv_tools_revision'),
}
