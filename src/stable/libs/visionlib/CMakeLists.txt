list_subdirectories( LIST_LIBS ${CMAKE_CURRENT_SOURCE_DIR} 1)

FOREACH (libs ${LIST_LIBS})
        ADD_SUBDIRECTORY (${libs})
ENDFOREACH()



