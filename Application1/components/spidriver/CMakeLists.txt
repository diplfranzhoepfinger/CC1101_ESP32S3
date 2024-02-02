idf_component_register(
                    SRCS "spi_master_lobo.c"
                    INCLUDE_DIRS "."
                    PRIV_REQUIRES esp_ringbuf driver heap
                    )

