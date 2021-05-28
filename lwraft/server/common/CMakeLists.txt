set(This libsrvcommon)

set(SOURCES
    candidates.c
)

add_library(${This} STATIC ${SOURCES} ${HEADERS})

target_include_directories(${This} PUBLIC 
    ${PROJECT_SOURCE_DIR}/include/public
    ${PROJECT_SOURCE_DIR}/include
    ${PROJECT_SOURCE_DIR}/thirdparty/openldap_2018_0ba50a1d0/include
)