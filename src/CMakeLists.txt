set(TARGET_NAME "rapid_template")

set(TARGET_SOURCES 
    ${CMAKE_CURRENT_SOURCE_DIR}/main.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/adc.cpp
)

add_executable(${TARGET_NAME} ${TARGET_SOURCES})

target_include_directories(${TARGET_NAME}
    PUBLIC
        ${PROJECT_SOURCE_DIR}/inc
    PRIVATE
        ""
)

target_link_libraries(${TARGET_NAME}
    PUBLIC
        ""
    PRIVATE
        ""
)

