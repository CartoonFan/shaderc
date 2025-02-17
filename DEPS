use_relative_paths = True

vars = {
  'abseil_git':  'https://github.com/abseil',
  'google_git':  'https://github.com/google',
  'khronos_git': 'https://github.com/KhronosGroup',

  'abseil_revision': '1315c900e1ddbb08a23e06eeb9a06450052ccb5e',
  'effcee_revision': '12241cbc30f20730b656db7fd5a3fa36cd420843',
  'glslang_revision': 'ef5207f9f8cce5097568efb15d3297d8b5d13014',
  'googletest_revision': 'c00fd25b71a17e645e4567fcb465c3fa532827d2',
  're2_revision': '4a8cee3dd3c3d81b6fe8b867811e193d5819df07',
  'spirv_headers_revision': 'e7294a8ebed84f8c5bd3686c68dbe12a4e65b644',
  'spirv_tools_revision': '3364b982713a0440d1d342dd5eec65b122a61b71',
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
