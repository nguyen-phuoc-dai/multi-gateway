cmake_minimum_required(VERSION 3.16)

idf_component_register(SRCS "main.cpp"
                            "gw_eth.c"

                    INCLUDE_DIRS    "."
                                    "include"
                                    "../components/bsp/include"
                                    "../components/ethernet_init/"
)
