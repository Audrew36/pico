if (NOT PICO_NO_HARDWARE)
    add_subdirectory(hello_multicore)
    add_subdirectory(multicore_fifo_irqs)
    add_subdirectory(multicore_runner)
    add_subdirectory(multicore_runner_queue)
endif ()
