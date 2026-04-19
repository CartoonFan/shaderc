use_relative_paths = True

vars = {
  'abseil_git':  'https://github.com/abseil',
  'google_git':  'https://github.com/google',
  'khronos_git': 'https://github.com/KhronosGroup',

  'abseil_revision': '1315c900e1ddbb08a23e06eeb9a06450052ccb5e',
  'effcee_revision': 'ae38e040cbb7e83efa8bfbb4967e5b8c8c89b55a',
  'glslang_revision': '46a961a14ddf3032b7e05ce4dc7ef4068997cb61',
  'googletest_revision': 'd72f9c8aea6817cdf1ca0ac10887f328de7f3da2',
  're2_revision': '972a15cedd008d846f1a39b2e88ce48d7f166cbd',
  'spirv_headers_revision': 'ad9184e76a66b1001c29db9b0a3e87f646c64de0',
  'spirv_tools_revision': '5278681115c9099ca33183cbf91f3726ee962616',
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
