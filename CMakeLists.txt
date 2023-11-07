idf_component_register(SRCS "drv_net.c"
                    INCLUDE_DIRS "." 
                    REQUIRES "esp_netif"
                             "esp_event"
                                      )
                 

