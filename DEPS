use_relative_paths = True

vars = {
  'abseil_git':  'https://github.com/abseil',
  'google_git':  'https://github.com/google',
  'khronos_git': 'https://github.com/KhronosGroup',

  'abseil_revision': '1315c900e1ddbb08a23e06eeb9a06450052ccb5e',
  'effcee_revision': '874b47102c57a8979c0f154cf8e0eab53c0a0502',
  'glslang_revision': '04801966f69257d02eed2d5fcf8083916a76ad5f',
  'googletest_revision': '155b337c938a2953e5675f9dc18c99f05f4c85d0',
  're2_revision': 'c84a140c93352cdabbfb547c531be34515b12228',
  'spirv_headers_revision': '7c2f5333e9c662620581361dffc327a99800bb52',
  'spirv_tools_revision': 'a871fc43e29038d96109a64a64219eacefdf0634',
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
