
file(GLOB SRCS *.cu)

set(CU_SOURCES ${CU_SOURCES} ${SRCS})
set(CU_SOURCES ${CU_SOURCES} PARENT_SCOPE)
