# Add Corrade as a subproject
add_subdirectory(corrade EXCLUDE_FROM_ALL)

# Add Magnum as a subproject, enable Sdl2Application
# set(WITH_SDL2APPLICATION ON CACHE BOOL "" FORCE)
# set(WITH_GLFWAPPLICATION OFF CACHE BOOL "" FORCE)
add_subdirectory(magnum EXCLUDE_FROM_ALL)