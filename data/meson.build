gnome = import('gnome')

squeekboard_resources = gnome.compile_resources(
   'squeekboard-resources',
   'squeekboard.gresources.xml',

   c_name: 'squeekboard',
)

desktopconf = configuration_data()
desktopconf.set('bindir', bindir)
