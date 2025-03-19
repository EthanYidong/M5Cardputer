set(COMPONENT_ADD_INCLUDEDIRS
    src
    )

file(GLOB SRCS
  src/*.*
  src/utility/*.*
  )

set(COMPONENT_SRCS ${SRCS})

set(COMPONENT_REQUIRES(M5Unified M5GFX))

register_component()
