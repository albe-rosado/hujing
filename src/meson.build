sources = [
	'App.vala',
	'MainWindow.vala',
	'Flatpak.vala',
	'ProgressView.vala',
	'FlatpakProgressView.vala',
]

deps = [
	dependency('gio-2.0', version: '>= 2.48'),
	dependency('glib-2.0', version: '>= 2.48'),
	dependency('gtk+-3.0', version: '>= 3.18'),
	dependency('granite', version: '>=0.4.0.1'),
]

gnome = import('gnome')

executable(
	meson.project_name(),
	sources,
	vala_args: '--target-glib=2.48',
	dependencies: deps,
	install: true,
)
