#------------------------------------------------------------------------------
# klib
#------------------------------------------------------------------------------

set (headers khash.h)

# lib
add_library(klib INTERFACE ${headers})
target_include_directories(klib PUBLIC .)
