# xo-flatstring/example/ex1/CMakeLists.txt

set(SELF_EXE xo_flatstring_ex1)
set(SELF_SRCS ex1.cpp)

add_executable(${SELF_EXE} ${SELF_SRCS})
xo_include_options2(${SELF_EXE})

# ----------------------------------------------------------------
# dependencies..

xo_self_headeronly_dependency(${SELF_EXE} xo_flatstring)
#xo_dependency(${SELF_EXE} reflect)

# end CMakeLists.txt
