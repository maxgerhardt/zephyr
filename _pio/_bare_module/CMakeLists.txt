# Warning! Do not delete this auto-generated file.
file(GLOB module_srcs *.c* *.S)
add_library(_PIODUMMY INTERFACE)
zephyr_library()
zephyr_library_sources(${module_srcs})
