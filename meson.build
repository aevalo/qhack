project('qhack', 'c', default_options: ['c_std=c11'])
sources = files([
  'dungeon.c',
  'error.c',
  'game.c',
  'misc.c',
  'monster.c',
  'player.c',
  'qhack.c',
  'sysdep.c'
])
cursesdep = dependency('ncurses')
executable('qhack', sources, dependencies: cursesdep)
