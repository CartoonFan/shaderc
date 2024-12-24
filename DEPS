use_relative_paths = True

vars = {
  'abseil_git':  'https://github.com/abseil',
  'google_git':  'https://github.com/google',
  'khronos_git': 'https://github.com/KhronosGroup',

  'abseil_revision': '1315c900e1ddbb08a23e06eeb9a06450052ccb5e',
  'effcee_revision': 'a0455557f48e617ed5fecb3143c4ad2dbd39cf40',
  'glslang_revision': '3a2834e7702651043ca9f35d022739e740563516',
  'googletest_revision': 'e54519b09463cec3aea77a1739e02c97ca766da5',
  're2_revision': '6dcd83d60f7944926bfd308cc13979fc53dd69ca',
  'spirv_headers_revision': '3f17b2af6784bfa2c5aa5dbb8e0e74a607dd8b3b',
  'spirv_tools_revision': 'becf97fdc95572165e941feadc1a3064e2b95c87',
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
