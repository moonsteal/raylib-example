project('myproject', 'c',
  version : '1.0.0',
  license: 'MIT'
)

raylib_proj = subproject('raylib')
raylib_dep = raylib_proj.get_variable('raylib_dep')

executable('example', 'main.c',
  dependencies: [raylib_dep]
)
