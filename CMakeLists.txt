cmake_minimum_required( VERSION 3.7.1 )

project( jmsd_natibase_libs )


include( ${JMSD_CMAKE_SETTINGS_PATH}/verbosity/project-group-header.cmake )


add_subdirectory( jmsd_nb_components_lib )


include( ${JMSD_CMAKE_SETTINGS_PATH}/verbosity/project-group-footer.cmake )
