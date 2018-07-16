
if (FIPS)
    add_subdirectory(1.0.2-fips)
else ()
    add_subdirectory(1.1.0)
endif ()

Message(STATUS "Using OpenSSL: ${OPENSSL_ROOT_DIR}")
Message(STATUS "OpenSSL include: ${OPENSSL_INCLUDE_DIR}")
Message(STATUS "OpenSSL libraries: ${OPENSSL_LIBRARIES}")
Message(STATUS "OpenSSL libcrypto: ${OPENSSL_CRYPTO_LIBRARY}")
Message(STATUS "OpenSSL FIPS LD: ${OPENSSL_FIPS_CC}")