use_relative_paths = True

vars = {
  'abseil_git':  'https://github.com/abseil',
  'google_git':  'https://github.com/google',
  'khronos_git': 'https://github.com/KhronosGroup',

  'abseil_revision': '1315c900e1ddbb08a23e06eeb9a06450052ccb5e',
  'effcee_revision': '514b52ec61609744d7e587d93a7ef9b60407ab45',
  'glslang_revision': '19246e3fbc095586e0e325b378ea351aababeb7c',
  'googletest_revision': '1b96fa13f549387b7549cc89e1a785cf143a1a50',
  're2_revision': 'e7aec5985072c1dbe735add802653ef4b36c231a',
  'spirv_headers_revision': '6146b3d9ad4fcc5fb512209d348e97ce03749169',
  'spirv_tools_revision': '8c1e6ca9b896a5a82ea39973a2f677f515f1f45d',
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
