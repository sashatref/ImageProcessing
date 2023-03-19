set(PROJECT_NAME ImageProcessing)

project(${PROJECT_NAME})

set(SOURCES
    image.h
    image.cpp
)

add_library(${PROJECT_NAME} ${SOURCES})

#target_link_libraries(${PROJECT_NAME}
#    PRIVATE
#    Qt5::Widgets
#)



