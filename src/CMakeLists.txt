SET(EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR}/bin)

ADD_EXECUTABLE(cjserver server.cpp)
TARGET_LINK_LIBRARIES(cjserver pthread)

INSTALL(TARGETS cjserver DESTINATION bin)
