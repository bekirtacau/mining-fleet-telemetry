add_executable(
    fleet_simulator
    main.cpp
)

target_compile_options(
    fleet_simulator
    PRIVATE
        -Wall
        -Wextra
        -Wpedantic
)
