use_relative_paths = True

vars = {
  'abseil_git':  'https://github.com/abseil',
  'google_git':  'https://github.com/google',
  'khronos_git': 'https://github.com/KhronosGroup',

  'abseil_revision': '1315c900e1ddbb08a23e06eeb9a06450052ccb5e',
  'effcee_revision': '2c97e5689ed8d7ab6ae5820f884f03a601ae124b',
  'glslang_revision': 'a0995c49ebcaca2c6d3b03efbabf74f3843decdb',
  'googletest_revision': '35d0c365609296fa4730d62057c487e3cfa030ff',
  're2_revision': '4a8cee3dd3c3d81b6fe8b867811e193d5819df07',
  'spirv_headers_revision': '36d5e2ddaa54c70d2f29081510c66f4fc98e5e53',
  'spirv_tools_revision': '7c58952fa8ab2fff009cb6710fad34bd1ce7dff3',
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
