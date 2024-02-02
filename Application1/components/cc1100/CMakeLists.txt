idf_component_register(
                    SRCS "libcc1100.c"
                    INCLUDE_DIRS "."
                    PRIV_REQUIRES nvs_flash driver spidriver
                    )

