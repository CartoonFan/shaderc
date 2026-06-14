use_relative_paths = True

vars = {
  'abseil_git':  'https://github.com/abseil',
  'google_git':  'https://github.com/google',
  'khronos_git': 'https://github.com/KhronosGroup',

  'abseil_revision': '630e92d5d51d73a1f60ddd7654980ca2eae91582',
  'effcee_revision': '910ed15722d5d05c9d71ecf36c1a22243cb79b02',
  'glslang_revision': '06c267049a53ee407739848e9fbd8e01f938e67e',
  'googletest_revision': '52eb8108c5bdec04579160ae17225d66034bd723',
  're2_revision': '927f5d53caf8111721e734cf24724686bb745f55',
  'spirv_headers_revision': '1e770e7de8373a8dd49f23416cf7ca4001d01040',
  'spirv_tools_revision': '605a0154c7743ed4239c0eb7f3c61f17ffde4fd0',
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
