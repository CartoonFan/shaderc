use_relative_paths = True

vars = {
  'abseil_git':  'https://github.com/abseil',
  'google_git':  'https://github.com/google',
  'khronos_git': 'https://github.com/KhronosGroup',

  'abseil_revision': '1315c900e1ddbb08a23e06eeb9a06450052ccb5e',
  'effcee_revision': '8ce15c424e61a94ee27b5be0ec0ed036b158e6e3',
  'glslang_revision': '963588074b26326ff0426c8953c1235213309bdb',
  'googletest_revision': '90a41521142c978131f38c6da07b4eb96a9f1ff6',
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
