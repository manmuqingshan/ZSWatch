if(CONFIG_APPLICATIONS_USE_CHRONOS)
    FILE(GLOB app_sources *.c)
    target_sources(app PRIVATE ${app_sources})
    add_subdirectory(assets)
    add_subdirectory(screens)
endif()