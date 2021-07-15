
zephyr_include_directories(include)

add_subdirectory(subsys)

zephyr_library()
zephyr_library_sources(empty.c)
