project('yield_options', 'c')

subproject('sub')

assert(get_option('super_alone') == 'one', 'Unshared option has wrong value in superproject.')
assert(get_option('super_shared') == 'two', 'Unshared option has wrong value in superproject..')
