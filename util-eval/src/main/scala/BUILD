scala_library(
  provides = scala_artifact(
    org = 'com.twitter',
    name = 'util-eval',
    repo = artifactory,
  ),
  dependencies=[
    '3rdparty/jvm/org/scala-lang:scala-compiler',
    'util/util-core/src/main/scala',
    '//:scala-reflect',
  ],
  fatal_warnings=True,
  sources=rglobs('*.scala'),
)
