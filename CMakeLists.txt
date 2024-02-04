
cmake_minimum_required( VERSION 3.5 )
project( asio )

set( SOURCE_DIR asio/include )
set( INCLUDE_DIRS ${SOURCE_DIR} )

add_library(${PROJECT_NAME} INTERFACE)

target_include_directories(${PROJECT_NAME} INTERFACE ${INCLUDE_DIRS}
)
