
set(PROJECT_NAME example)

project(${PROJECT_NAME})

set(SOURCES
    main.cpp
)

add_library(${PROJECT_NAME} ${SOURCES})

target_link_libraries(${PROJECT_NAME}
    PRIVATE
    ImageProcessing
)
