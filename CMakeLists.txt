idf_component_register(
 SRCS "turcutils.c"
 INCLUDE_DIRS "." "${CMAKE_CURRENT_BINARY_DIR}"
 PRIV_REQUIRES
   "base_nodemcu"
   "lua"
   "platform"
)

extmod_declare_module(TURCUTILS)
