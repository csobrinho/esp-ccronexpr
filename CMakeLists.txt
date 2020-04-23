set(COMPONENT_ADD_INCLUDEDIRS ".")
set(COMPONENT_SRCS "ccronexpr.c")

register_component()

target_compile_definitions(${COMPONENT_TARGET} PUBLIC -D CRON_USE_LOCAL_TIME)
