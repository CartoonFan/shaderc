use_relative_paths = True

vars = {
  'abseil_git':  'https://github.com/abseil',
  'google_git':  'https://github.com/google',
  'khronos_git': 'https://github.com/KhronosGroup',

  'abseil_revision': '1315c900e1ddbb08a23e06eeb9a06450052ccb5e',
  'effcee_revision': '2c97e5689ed8d7ab6ae5820f884f03a601ae124b',
  'glslang_revision': '7c4d91e7819a1d27213aa3499953d54ae1a00e8f',
  'googletest_revision': 'ff233bdd4cac0a0bf6e5cd45bda3406814cb2796',
  're2_revision': '6dcd83d60f7944926bfd308cc13979fc53dd69ca',
  'spirv_headers_revision': 'f013f08e4455bcc1f0eed8e3dd5e2009682656d9',
  'spirv_tools_revision': 'b64a423b44f448df5464978173e28be12069b73c',
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
