add_subdirectory(spdlog)

file(GLOB SOURCES src/*.cpp)

add_library(log ${SOURCES})

target_link_libraries(log PRIVATE spdlog::spdlog)
target_include_directories(log PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)