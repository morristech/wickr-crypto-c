
if (FIPS)
    add_subdirectory(1.0.2-fips)
else ()
    add_subdirectory(1.1.0)
endif ()