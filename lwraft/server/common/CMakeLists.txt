set(This libsrvcommon)

set(SOURCES
    candidates.c
)

add_library(${This} STATIC ${SOURCES} ${HEADERS})