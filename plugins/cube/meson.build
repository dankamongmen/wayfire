animiate = shared_module('cube',
                         ['cube.cpp', 'cubemap.cpp', 'skydome.cpp', 'simple-background.cpp'],
                         include_directories: [wayfire_api_inc, wayfire_conf_inc],
                         dependencies: [wlroots, pixman, wfconfig],
                         install: true,
                         install_dir: join_paths(get_option('libdir'), 'wayfire'))
